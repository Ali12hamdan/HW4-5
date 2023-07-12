<script>
	let activeTab = 'skills';

	// function openTab(tab) {
	//   activeTab = tab;
	// }
</script>

<div id="about">
	<div class="container">
		<div class="row">
			<div class="about-col-1">
				<!-- <img src="images/photo_2.jpg"> -->
				<div id="titlebar" />
				<div id="datebar" />
				<!-- <img id="jokeimage" alt="alt" /> -->
			</div>
			<div class="about-col-2">
				<h1 class="sub-title">About Me</h1>
				<p>
					I'm 22 and interested in data science and robotics.<br />
					I also participated in WRO(World Robot Olympiad )<br />
					and ARC(Annual Robotic Competition) I'm also interested in <br />front-end development and
					I like going to gym.
				</p>

				<!-- <div class="tab-titles">
            <p
              class="tab-links"
              class:active-link={activeTab === 'skills'}
              on:click={() => openTab('skills')}
            >
              Skills
            </p>
            <p
              class="tab-links"
              class:active-link={activeTab === 'experience'}
              on:click={() => openTab('experience')}
            >
              Experience
            </p>
            <p
              class="tab-links"
              class:active-link={activeTab === 'education'}
              on:click={() => openTab('education')}
            >
              Education
            </p>
          </div> -->
				<div class="tab-contents" class:active-tab={activeTab === 'skills'} id="skills">
					<ul>
						<li>
							<span>Robotics</span>
							<br />
							Lego Mindstorm & Arduino
						</li>
						<li>
							<span>Web Scraping</span>
							<br />
							Extracting data Using Python
						</li>
						<li>
							<span>Data Structure</span>
							<br />
							C++, Python
						</li>
						<li>
							<span>Team Work</span>
							<br />
							Participating in Multiple Competitions and Organizing IT Events
						</li>
					</ul>
				</div>

				<div class="tab-contents" class:active-tab={activeTab === 'experience'} id="experience">
					<ul>
						<li>
							<span>WRO</span>
							<br />
							2018-2021 national participant
						</li>
						<li>
							<span>ARC</span>
							<br />
							Golden medal in regional competition held in Lebanon
						</li>
						<li>
							<span>Robotic Tutor</span>
							<br />
							2019-2022 Certified Lego & Arduino Tutor at SCS
						</li>
						<li>
							<span>Competitive Programming Tutor</span>
							<br />
							2021-2022 Programming Tutor at SCS
						</li>
					</ul>
				</div>

				<div class="tab-contents" class:active-tab={activeTab === 'education'} id="education">
					<ul>
						<li>
							<span>Innopolis University</span>
							<br />
							1st year bachelor
						</li>
					</ul>
				</div>
			</div>
		</div>
	</div>
</div>

<style>
	* {
		margin: 0;
		padding: 0;
		font-family: 'Poppins', sans-serif;
		box-sizing: border-box;
	}

	/* #header {
		width: 100%;
		height: 100vh;
		background-image: url(images/IMG_60631.jpg);
		background-size: cover;
		background-position: center;
	} */

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

	/* nav {
		display: flex;
		flex-wrap: wrap;
		justify-content: space-between;
		align-items: center;
	} */

	nav ul li {
		display: inline-block;
		list-style: none;
		margin: 0px 20px;
		color: black;
	}

	/* nav ul li a {
		text-decoration: none;
		color: rgb(243, 240, 240);
		font-weight: bold;
		font-size: 25px;
		position: relative;
	} */

	/* nav ul li a::after {
		content: '';
		width: 0;
		height: 2px;
		background: #ff004f;
		position: absolute;
		left: 0;
		bottom: -6px;
		transition: 0.5s;
	} */

	/* nav ul li a:hover::after {
		width: 100%;
	} */

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
