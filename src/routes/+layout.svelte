<script lang="ts">
	import '../app.postcss';
</script>

<img src="/logo.png" alt="Logo" style="max-width: 150px" />
<slot />

<style>
	img {
		position: absolute;
		top: 20px;
		left: 20px;
	}
</style>
