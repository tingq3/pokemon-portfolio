<script>
	export let title;
	export let image;
	export let description;
	export let theme = "light";
	export let flip = false;
</script>

<div class={`hobby-container ${theme} ${flip ? 'flip' : ''}`}>
	<img src={image} alt={title} class="hobby-image" />

	<div class="hobby-content">
		<h3>{title}</h3>
		<hr />
		<p>{description}</p>
	</div>
</div>
