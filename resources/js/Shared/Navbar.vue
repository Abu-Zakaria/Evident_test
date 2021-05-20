<template>
	<div class="bg-green-400 py-4 px-10 shadow-md w-full flex">
		<!-- this section will be shown at left side -->
		<div class="flex justify-start w-1/2">
			<inertia-link class="text-2xl" href="/">Home</inertia-link>
		</div>

		<!-- this section will be shown at right side -->
		<div class="flex justify-end w-1/2">
			<inertia-link class="py-2 px-4 bg-pink-600 mr-2 font-bold text-white rounded-lg hover:shadow-md" href="/login">Login</inertia-link>
			<inertia-link class="py-2 px-4 bg-yellow-400 font-bold text-white rounded-lg hover:shadow-md" href="/signup">Signup</inertia-link>
		</div>
	</div>
</template>

<script>
	export default {
		name: "Navbar"
	}
</script>