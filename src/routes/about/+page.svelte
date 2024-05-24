<script>
	import welcome from '$lib/images/burger.png';
	import discord from '$lib/images/discord.png';
	import youtube from '$lib/images/youtube.png';
	import github from '$lib/images/github.png';
	import paypal from '$lib/images/paypal.png';
	import itch from '$lib/images/itch.png';
	import gmail from '$lib/images/gmail.png';
	import sv from '$lib/images/svelte.png';
	import bash from '$lib/images/bash.webp';
	import html from '$lib/images/html-5.png';
	import css from '$lib/images/css.png';
	import js from '$lib/images/js.png';
	import discordpy from '$lib/images/discordpy.png';
	import python from '$lib/images/python.png';
	import tailwind from '$lib/images/tailwind.png';
    import welcome_fallback from '$lib/images/burger.png';
</script>
<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
	<section>
		<h1>
			<span class="welcome">
				<picture>
					<source srcset={welcome} type="image/webp" />
					<img height="500px" src={welcome_fallback} alt="Welcome" />
				</picture>
			</span>
	
		</h1>
	
	</section>
<div class="content">
	<h1>My Socials:</h1>

<section class="socials">
<a href="https://discord.com/users/877943739824365588">
	<source srcset={discord} type="image/webp" />
	<img src="{discord}" alt="Girl in a jacket" width="50" height="50"> 
</a>
<a href="https://youtube.com/@Charmunk3d">
	<source srcset={youtube} type="image/webp" />
	<img src="{youtube}" alt="Girl in a jacket" width="50" height="50"> 
</a>
<a href="https://github.com/isaacfonner">
	<source srcset={github} type="image/webp" />
	<img src="{github}" alt="Girl in a jacket" width="50" height="50"> 
</a>
<a href="https://paypal.me/Charmunk3d">
	<source srcset={paypal} type="image/webp" />
	<img src="{paypal}" alt="Girl in a jacket" width="50" height="50"> 
</a>
<a href="https://isaacfonner.itch.io/">
	<source srcset={itch} type="image/webp" />
	<img src="{itch}" alt="Girl in a jacket" width="50" height="50"> 
</a>
<a href="javascript:alert('isaac@isaacfonner.com')">
	<source srcset={gmail} type="image/webp" />
	<img src="{gmail}" alt="Girl in a jacket" width="50" height="50"> 
</a>


</section>
<section class="socials">
	<h1>My Known Technologies:</h1>

	<a href="/about">
		<source srcset={sv} type="image/webp" />
		<img src="{sv}" alt="Girl in a jacket" width="40" height="50"> 
	</a>
	<a class="bash" href="/about">
		<source srcset={bash} type="image/webp" />
		<img src="{bash}" alt="Girl in a jacket" width="45" height="45"> 
	</a>
	<a href="/about">
		<source srcset={html} type="image/webp" />
		<img src="{html}" alt="Girl in a jacket" width="50" height="50"> 
	</a>
	<a href="/about">
		<source srcset={css} type="image/webp" />
		<img src="{css}" alt="Girl in a jacket" width="50" height="50"> 
	</a>
	
	<a href="/about">
		<source srcset={js} type="image/webp" />
		<img src="{js}" alt="Girl in a jacket" width="50" height="50"> 
	</a>
	<a href="/about">
		<source srcset={discordpy} type="image/webp" />
		<img src="{discordpy}" alt="Girl in a jacket" width="50" height="50"> 
	</a>
	<a href="/about">
		<source srcset={python} type="image/webp" />
		<img src="{python}" alt="Girl in a jacket" width="50" height="50"> 
	</a>
	<a href="/about">
		<source srcset={tailwind} type="image/webp" />
		<img src="{tailwind}" alt="Girl in a jacket" width="50" height="50"> 
	</a>
</section>

	<p>
		
	</p>
</div>
</div>
<style>

		.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0px;
		left: 0px;
		display: block;
		z-index: -1;
	}

	h1 {
  font-family: "Roboto", sans-serif;
  font-weight: 100;
  font-style: normal;
  color: black;

	}
	p {
  font-family: "Roboto", sans-serif;
  font-style: normal;
  outline-width: 5px;
outline-color: black;;
	}	pre {
  font-size: 13px;
  color: black;
  text-align: left;
	}

	.hello {
  font-family: "Roboto", sans-serif;
  font-weight: 200;
  font-style: normal;
  color: black;
  font-size: 25px;

	}
	.content {
    background-color: rgba(255, 255, 255, 0.8);
    border-radius: 15px; /* Adjust the value as needed */
	text-align: center;
	padding: 10px;

}
   .bottom {
	font-size: 20px;
   }
   a {
	padding: 5px;
   }

   .bash {
   }

</style>
