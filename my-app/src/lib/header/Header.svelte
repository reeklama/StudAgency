<script>
	import { page } from '$app/stores';
	import logo from './svelte-logo.svg';
</script>


<main>
<div class="head1 shrift">
	<a href="/"><img class="logo" src="src/lib/logo3.png"  alt="СдАм"></a>
</div>
<div class="head2 shrift2">

	<div class="marg1 box"><a  href="/order">Заказать работу</a><a class="marg_a" href="/vacancy">Стать автором</a></div>
	<div class="marg2 box1">
		<section>По любым <br> вопросам</section>
		<section class="ww">:</section>
		<section class="marg_b" > sdamvse24@mail.ru <br> +7-913-196-85-52</section>
	</div>

</div>
</main>

<style>

	.ww{
		font-size: 40px;
		padding-left: 5px;
	}


	.box{

		width:200px; /* or whatever width you want. */
		height: 20px;
		max-width:250px; /* or whatever width you want. */
		display: inline-block;
	}

	.logo{
		margin-top: -10px;
		width: 198px;
		height: 76px;
		outline-width: 2px;
		outline-color: white;
	}

	main{
		background-image: image('src/lib/fon.jpg');

	}


	a{
		font-size: 20px;
		font-family: sans-serif;
		letter-spacing: -1px;
		font-style: italic;
		text-align: center;
		color: white;
		text-decoration: none;
	}

	.head1{
		height: 60px;
		padding-top: 0;
		width: 100%;
		background-color: #a42828;
	}

	.shrift{
		font-size: 48px;
		font-family: sans-serif;
		letter-spacing: -5px;
		font-style: italic;
		font-weight: bold;
		text-align: center;
		color: white;
	}

	.shrift2{
		font-size: 20px;
		font-family: sans-serif;
		letter-spacing: -1px;
		font-style: italic;
		text-align: center;
		color: white;
	}

	.head2{
		height: 60px;
		padding: 0;
		margin-top: 0;
		width: 100%;
		display: flex;
		justify-content: space-between;
		color: white;
		background-color: #252525;

	}

	.marg1{
		padding-left: 200px;
		padding-top: 6px;
		display: flex;
	}

	.marg2{
		padding-right: 200px;
		padding-top: 6px;
		display: flex;
	}


	.marg_a{
		padding-left: 200px;
	}
	.marg_b{
		padding-left: 50px;

	}



	header {
		display: flex;
		justify-content: space-between;
	}

	.corner {
		width: 3em;
		height: 3em;
	}

	.corner a {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 100%;
		height: 100%;
	}

	.corner img {
		width: 2em;
		height: 2em;
		object-fit: contain;
	}

	nav {
		display: flex;
		justify-content: center;
		--background: rgba(255, 255, 255, 0.7);
	}

	svg {
		width: 2em;
		height: 3em;
		display: block;
	}

	path {
		fill: var(--background);
	}

	ul {
		position: relative;
		padding: 0;
		margin: 0;
		height: 3em;
		display: flex;
		justify-content: center;
		align-items: center;
		list-style: none;
		background: var(--background);
		background-size: contain;
	}

	li {
		position: relative;
		height: 100%;
	}

	li.active::before {
		--size: 6px;
		content: '';
		width: 0;
		height: 0;
		position: absolute;
		top: 0;
		left: calc(50% - var(--size));
		border: var(--size) solid transparent;
		border-top: var(--size) solid var(--accent-color);
	}

	nav a {
		display: flex;
		height: 100%;
		align-items: center;
		padding: 0 1em;
		color: var(--heading-color);
		font-weight: 700;
		font-size: 0.8rem;
		text-transform: uppercase;
		letter-spacing: 0.1em;
		text-decoration: none;
		transition: color 0.2s linear;
	}

	a:hover {
		color: var(--accent-color);
	}
</style>
