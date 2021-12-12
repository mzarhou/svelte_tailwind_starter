<script lang="ts">
	import "../styles/tailwind-output.css"
</script>

<div class="text-center mt-40">
	Here we go
</div>
<div class="text-center mt-40">
	Here we go
</div>
<div class="text-center mt-40">
	Here we go
</div>
<div class="text-center mt-40">
	Here we go
</div>

<style>
	div {
		display: inline-block;
		position: relative;
		padding: 30px;
		border: 1px blue solid;
	}
	div::after {
		--size: 10px;
		content: "";
		width: var(--size);
		height: var(--size);
		border-radius: 50%;
		background-color: red;
		position: absolute;
		left: 0;
		top: 0;
	}
	div::before {

	}
</style>
