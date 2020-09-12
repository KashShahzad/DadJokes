<template>
	<header class="header">
		<h1 class="title">DAD Jokes</h1>
		<ul>
			<li>
				<nuxt-link to="/">
					Home
				</nuxt-link>
			</li>
			<li>
				<nuxt-link to="/Jokes">
					Jokes
				</nuxt-link>
			</li>
			<li>
				<nuxt-link to="/About">
					About
				</nuxt-link>
			</li>
		</ul>
	</header>
</template>

<script>
	export default {
		name: 'AppHeader',
	}
</script>

<style>
	.header {
		display: flex;
		justify-content: space-between;
		align-items: center;
		margin-bottom: 1rem;
		padding-bottom: 1rem;
		border-bottom: 1px dotted rgb(224, 212, 212);
	}

	.header .title {
		font-size: 3rem;
		color: rgb(117, 117, 190);
	}
	.header ul {
		display: flex;
	}
	.header a {
		display: inline-block;
		background: rgb(102, 98, 98);
		color: white;
		padding: 0.3rem 1rem;
		margin-right: 0.5rem;
	}
</style>