<script>
	//

	import Contact from '$lib/contact.svelte';
	import Decriptions from '$lib/decriptions.svelte';
	import Card from '$lib/cards.svelte';
	import Foot from '$lib/foot.svelte';
	import Footer from '$lib/footer.svelte';
	import Nav from '$lib/nav.svelte';
	let title = 'Kakamega | Environmental Educational Program (KEEP) ';
</script>

<script:header>
	<title>{title}</title>
</script:header>

<main>
	<div class="wrapper  w-full min-h-screen">
		<div class="bg-[url('../Kag/fast.jpg')] bg-cover bg-no-repeat h-[90vh] w-full ">
			<div class="container mx-auto">
				<Nav />
			</div>
			<div class="container mx-auto">
				<Decriptions />
			</div>
		</div>
		<div class="w-full   ">
			<div class="mx-[18rem] ">
				<Card />
			</div>
		</div>

		<div class="bg-green-700 w-full">
			<div class="mx-[18rem]">
				<Contact />
			</div>
		</div>
		<div class="bg-green-900 pt-8">
			<div class="   ">
				<div class="mx-[18rem] ">
					<Footer />
				</div>
			</div>
			<div class="w-full bg-green-700 py-4">
				<div class="text-lg text-white mx-[18rem]  ">
					<Foot />
				</div>
			</div>
		</div>
	</div>
</main>
