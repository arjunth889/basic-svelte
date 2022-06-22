<script>
	import Navbar from "./components/Navbar/Navbar.svelte";
	import Home from "./components/Pages/Home.svelte"
	import About from "./components/Pages/About.svelte"
	import Contact from "./components/Pages/Contact.svelte"
	import Courses from "./components/Pages/Courses.svelte"
</script>

<main>

	<Navbar/>
	<Home/>
	<Courses/>
	<About/>
	<Contact/>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>