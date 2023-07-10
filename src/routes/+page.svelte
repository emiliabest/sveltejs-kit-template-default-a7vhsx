<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>

<div class="ai">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSV9XMgmlORig6Gj8KrdqA00D3jqmyB8xluXQ&usqp=CAU">

</div>

<h3>
AI
</h3>

	<h1>
		Welcome<br />To Your New and Timely<br />CloudSafe App
	</h1>

	<h2>Subscribe to the Newsletter</h2>

<button onclick="myFunction()">Click Me</button>

<script>
function myFunction() {
  alert("You are now subscribed for notifications about new updates! To opt out, see Updates tab.");
}
</script>

</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
