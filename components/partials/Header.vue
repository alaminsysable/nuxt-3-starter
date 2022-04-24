<template>
	<header class="border-b border-gray-200">
		<div class="container">
			<div class="flex justify-between items-center py-4">
				<nuxt-link to="/" class="text-3xl font-bold text-gray-700 uppercase">Logo</nuxt-link>
				<nav>
					<ul class="flex items-center gap-4">
						<li>
							<nuxt-link to="/" class="text-base font-normal text-gray-700">Home</nuxt-link>
						</li>
						<li>
							<nuxt-link to="/about" class="text-base font-normal text-gray-700">About</nuxt-link>
						</li>
					</ul>
				</nav>
			</div>
		</div>
	</header>
</template>

<script>
export default {}
</script>

<style></style>
