<template>
	<div>
		<layout page_title="Sign up">
			<div class="flex justify-center">
				<div class="w-3/5">
					<form>
						<div class="flex mb-2">
							<label class="w-2/5 py-2">Username</label>
							<input type="text" class="w-3/5 border rounded-lg px-4 py-2">
						</div>
						<div class="flex mb-2">
							<label class="w-2/5 py-2">Password</label>
							<input type="text" class="w-3/5 border rounded-lg px-4 py-2">
						</div>
						<div class="flex mb-2">
							<label class="w-2/5 py-2">Password confirmation</label>
							<input type="text" class="w-3/5 border rounded-lg px-4 py-2">
						</div>

						<div class="flex justify-end">
							<button class="bg-yellow-400 px-4 py-2 text-white font-bold rounded-lg hover:shadow-lg">Sign up</button>
						</div>
					</form>
				</div>
			</div>
		</layout>
	</div>
</template>

<script>
	import Layout from '../Shared/Layout.vue';

	export default {
		name: "Signup",
		components: {
			Layout
		}
	}
</script>