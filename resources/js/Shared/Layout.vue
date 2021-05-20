<template>
	<div>
		<navbar></navbar>

		<div class="flex justify-center">
			<!-- page card -->
			<div class="w-6/12 mt-4 border border-grey-400 rounded-md shadow-md">
				<!-- card title -->
				<p class="p-2 bg-gray-100 w-full text-2xl">{{ page_title }}</p>
				<!-- end card title -->

				<!-- card body -->
				<div class="p-2">
					<!-- this is where the page content will be rendered -->
					<slot />
				</div>
				<!-- end card body -->
			</div>
		</div>
	</div>
</template>

<script>
	import Navbar from './Navbar.vue';

	export default {
		name: "Layout",
		props: ['page_title'],
		components: {
			Navbar
		}
	}
</script>