<script>
	let name = "willymar";
	let age = 23;
	function incrementAge() {
		age += 1
	}

</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>Hello {name}! the age is {age}</h1>
<button on:click="{incrementAge}">Tambah</button>
