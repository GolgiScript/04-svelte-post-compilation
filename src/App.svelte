<script>
	let toggle = false;
</script>

<main>
	<div>
		Value: {toggle ? 'On' : 'Off'}
	</div>
	<button on:click={() => {toggle = !toggle}}>
		Toggle!
	</button>
</main>
