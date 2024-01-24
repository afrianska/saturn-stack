<script>
  import "../app.css";
</script>

<div class="container z-0">
	<slot/>
</div>

<style lang="postcss">
	.container {
		@apply relative max-w-full h-screen bg-sky-100 flex items-center;
	}
</style>