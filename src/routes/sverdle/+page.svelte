<script>
	import welcome from '$lib/images/burger.png';
	import book from '$lib/images/book.png';
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

	<h1>My Projects:</h1>
    <div class="content2">
    <h3>Free Books Discord Bot
	</h3>
 <p>I wanted to learn discord.py, so I created a discord bot that accepts the command $book bookname and will return a PDF of that book.
	 <a href="https://github.com/isaacfonner/Book-PDF-Discord-Bot"> View Github.</a>
	 <a href="https://discord.com/oauth2/authorize?client_id=1223805559510274088&permissions=824633838592&scope=bot"> Add to server.</a>
	</p>	</div>
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


}
   .bottom {
	font-size: 20px;
   }
   .book {
	margin-left: 8px;
   }
   .content2 {
	text-align: top;
	vertical-align: top;
	margin: 5px;
   }

</style>
