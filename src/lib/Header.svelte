<script>
	const nav = [
		{ name: 'Home', href: '#hero', color: 'blue' },
		{ name: 'Experience', href: '#experience', color: 'orange' },
		{ name: 'Hobbies', href: '#hobbies', color: 'purple' }
	];
</script>

<header class="site-header">
	<nav class="main-nav">
        <img src="/images/pokemon-logo.png" alt="Logo" class="site-logo" />
		{#each nav as item}
			<a href={item.href} class="nav-link {item.color}">
				<span>{item.name}</span>
				<div class="underline"></div>
			</a>
		{/each}
	</nav>
</header>
