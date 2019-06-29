<script>
	import MyComponent from './MyComponent.svelte';
	let name = 'world';
	let src = `favicon.png`;
</script>

<style>
	p {
		color: red;
		font-family: 'Comic Sans MS';
		font-size: 2em;
	}
</style>

<h1>Hello {name}!</h1>
<img {src} alt="Svelte Icon" >
<p>This is a paragraph.</p>
<MyComponent />