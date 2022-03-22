<script>
	const grace = {
    title: 'Grace Hopper',
    img: 'https://upload.wikimedia.org/wikipedia/commons/5/55/Grace_Hopper.jpg',
    subTitle: 'Coolaste kodaren i marinen',
    content: 'Grace Hopper var en amerikansk dator-pionjär och sjöofficer (flottiljamiral). Hon var bland annat med och utvecklade Harvard Mark I och skapade den första kompilatorn. Hon populariserade användningen av programmeringsspråk som var oberoende av maskinen, något som ledde till utvecklingen av COBOL, ett högnivå programmeringsspråk som fortfarande används idag.'
}

let skrick = "";
let versaltMedelande = skrick.toUpperCase();
function upperCase(){
	
}

</script>

<main>

	<h1>{grace.title}</h1>
	<img src={grace.img} alt="Grace Hopper">
	<h2 class="subtitle">{grace.subTitle}</h2>

	<section>
		{grace.content}
	</section>

	<section>
		<input type="text" bind:value={skrick}>
		<button on:click={versaltMedelande}>Klick här!</button>
		<h1>{versaltMedelande}</h1>
	</section>


</main>

<style>
</style>