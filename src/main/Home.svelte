<script>
	let usuario = "Webmaster";
	function handleSubmit() {
    console.log("success");
  }
</script>

<div class="columns">
	<div class="column">
		<h1 class="title">Hello {usuario}!</h1>
		<h1 class="subtitle">First Day isn't easy</h1>
	</div>
	<div class="column">
		<input type="text" class="text" bind:value={usuario}>
		<button class="button is-info">
			Bulma?
		</button>
	</div>
</div>
