<script lang="ts">
	let imgSrc = 'https://avatars.githubusercontent.com/u/46527178?v=4';

	import FaInstagram from 'svelte-icons/fa/FaInstagram.svelte';
	import FaTwitter from 'svelte-icons/fa/FaTwitter.svelte';
	import FaTelegram from 'svelte-icons/fa/FaTelegram.svelte';
	import FaGithub from 'svelte-icons/fa/FaGithub.svelte';
	import FaSteam from 'svelte-icons/fa/FaSteam.svelte';
	import FaLaptopCode from 'svelte-icons/fa/FaLaptopCode.svelte';
</script>

<header />

<main class="container main">
	<!-- About Section -->
	<section class="about-section center">
		<img src={imgSrc} alt="Me" class="photo" />

		<hgroup>
			<h2>
				<strong>Zeeshan Ahmad</strong>
			</h2>
			<h2>
				<strong>// @itexpert120 //</strong>
			</h2>
		</hgroup>

		<p>"And if you gaze long enough into an abyss, the abyss will gaze back into you."</p>
		<cite>- Friedrich Nietzsche</cite>
	</section>

	<!-- Contact Section -->
	<section class="contact-section">
		<div class="flex-container">
			<a href="https://www.instagram.com/itexpert120" class="icon zoom">
				<FaInstagram />
			</a>
			<a href="https://www.twitter.com/itexpert120" class="icon zoom">
				<FaTwitter />
			</a>
			<a href="https://t.me/itexpert120" class="icon zoom">
				<FaTelegram />
			</a>
			<a href="https://www.github.com/itexpert120" class="icon zoom">
				<FaGithub />
			</a>
			<a href="https://steamcommunity.com/id/CreepyBoy09/" class="icon zoom">
				<FaSteam />
			</a>
			<a href="https://forum.xda-developers.com/m/itexpert-120.9032595/" class="icon zoom">
				<FaLaptopCode />
			</a>
		</div>
	</section>
</main>
