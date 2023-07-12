<script>
	//   import logo from './images/name_logo.PNG';

	//   export let scrollBehavior = "smooth";
</script>

<div id="header">
	<div class="container">
		<nav>
			<!-- <img src="{logo}" class="logo" alt="Logo" /> -->
			<ul>
				<li><a href="/">Home</a></li>
				<li><a href="/about">About</a></li>
			</ul>
		</nav>
	</div>
</div>

<!-- about -->

<style>
	* {
		margin: 0;
		padding: 0;
		font-family: 'Poppins', sans-serif;
		box-sizing: border-box;
	}

	/* html {
    scroll-behavior: {scrollBehavior};
  } */

	/* body {
		background: #f9f8fa;
	} */

	#header {
		width: 100%;
		height: 10vh;
		background-image: url(images/IMG_60631.jpg);
		background-size: cover;
		background-position: center;
	}

	/* img {
		mix-blend-mode: multiply;
		margin-left: -50px;
		margin-top: 20px;
		width: 30%;
		height: 5%;
	} */

	.container {
		max-width: 1170px;
		margin: auto;
		padding: 10px 10;
	}

	nav {
		display: flex;
		flex-wrap: wrap;
		justify-content: space-between;
		align-items: center;
	}

	nav ul li {
		display: inline-block;
		list-style: none;
		margin: 0px 20px;
	}

	nav ul li a {
		text-decoration: none;
		color: rgb(243, 240, 240);
		font-weight: bold;
		font-size: 25px;
		position: relative;
	}

	nav ul li a::after {
		content: '';
		width: 0;
		height: 2px;
		background: #ff004f;
		position: absolute;
		left: 0;
		bottom: -6px;
		transition: 0.5s;
	}

	nav ul li a:hover::after {
		width: 100%;
	}

	/* .header-text {
		margin-top: 1%;
		font-size: 30px;
	} */

	/* .header-text h1 {
		font-size: 50px;
		margin-bottom: 20px;
	} */

	/* .header-text h1 span {
		color: #590de6;
	} */
</style>
