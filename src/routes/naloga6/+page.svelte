<script lang="ts">
	// Napiši funkcijo, ki bo filtrirala seznam objektov tipa Oseba ({ ime: string; starost: number }) in izpisala samo osebe starejše od 18 let
	type Oseba = { ime: string; starost: number };

	function filtrirajOdrasle(ljudje: Oseba[]) {}

	const osebe: Oseba[] = [
		{ ime: 'Ana', starost: 16 },
		{ ime: 'Marko', starost: 20 },
		{ ime: 'Luka', starost: 25 },
		{ ime: 'Eva', starost: 14 }
	];

	console.log(filtrirajOdrasle(osebe));
	// Pričakovani rezultat: [{ ime: "Marko", starost: 20 }, { ime: "Luka", starost: 25 }]
</script>

<code>
	<pre>// Napiši funkcijo, ki bo filtrirala seznam objektov tipa Oseba ( ime: string; starost: number ) in izpisala samo osebe starejše od 18 let</pre>
</code>
<hr />
<p class="text-xl">Za testiranje odpri konzolo.</p>
