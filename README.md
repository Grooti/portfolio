<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Siddhant Kumr|Portfolio</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    
    <link href="https://fonts.googleapis.com/css?family=Poppins:100,200,300,400,500,600,700,800,900" rel="stylesheet">

    <link rel="stylesheet" href="css/open-iconic-bootstrap.min.css">
    <link rel="stylesheet" href="css/animate.css">
    
    <link rel="stylesheet" href="css/owl.carousel.min.css">
    <link rel="stylesheet" href="css/owl.theme.default.min.css">
    <link rel="stylesheet" href="css/magnific-popup.css">

    <link rel="stylesheet" href="css/aos.css">

    <link rel="stylesheet" href="css/ionicons.min.css">
    
    <link rel="stylesheet" href="css/flaticon.css">
    <link rel="stylesheet" href="css/icomoon.css">
    <link rel="stylesheet" href="css/style.css">


  </head>
  <body data-spy="scroll" data-target=".site-navbar-target" data-offset="300">
	  
	  
    <nav class="navbar navbar-expand-lg navbar-dark ftco_navbar ftco-navbar-light site-navbar-target" id="ftco-navbar">
	    <div class="container">
	      <a class="navbar-brand" href="index.html">Portfolio</a>
	      <button class="navbar-toggler js-fh5co-nav-toggle fh5co-nav-toggle" type="button" data-toggle="collapse" data-target="#ftco-nav" aria-controls="ftco-nav" aria-expanded="false" aria-label="Toggle navigation">
	        <span class="oi oi-menu"></span> Menu
	      </button>

	      <div class="collapse navbar-collapse" id="ftco-nav">
	        <ul class="navbar-nav nav ml-auto">
	          <li class="nav-item"><a href="#home-section" class="nav-link"><span>Home</span></a></li>
	          <li class="nav-item"><a href="#about-section" class="nav-link"><span>About</span></a></li>
	          <li class="nav-item"><a href="#resume-section" class="nav-link"><span>Resume</span></a></li>
	          <li class="nav-item"><a href="#project-section" class="nav-link"><span>Projects</span></a></li>
	          <li class="nav-item"><a href="#contact-section" class="nav-link"><span>Contact</span></a></li>
	        </ul>
	      </div>
	    </div>
	  </nav>
	  <section id="home-section" class="hero">
		  <div class="home-slider  owl-carousel">
	       <div class="slider-item ">
	      	<div class="overlay"></div>
	         <div class="container">
	          <div class="row d-md-flex no-gutters slider-text align-items-end justify-content-end" data-scrollax-parent="true">
	          	<div class="one-third js-fullheight order-md-last img" style="background-image:url(images/about.png);">
	          	 <div class="overlay"></div>
	          	</div>
		          <div class="one-forth d-flex  align-items-center ftco-animate" data-scrollax=" properties: { translateY: '70%' }">
		          	<div class="text">
		          		<span class="subheading">Hello!</span>
			            <h1 class="mb-4 mt-3">I'm <span>Siddhant Kumar</span></h1>

						<!-- Element to contain animated typing -->
						<span id="typing-animation"></span>

						<script>

						// Initialize the typing animation
						const typingAnimationElement = document.getElementById('typing-animation');

						// Create an array of typing text
						const typingTexts = [
						'Engineer  ',
						'Web Developer  ',
						'Photographer   ',
						];

						// Create a function to display the typing animation for a given text
						function playTypingAnimation(text) {
						// Loop through each character and add it to the element
						for (let i = 0; i < text.length; i++) {
							setTimeout(() => {
							typingAnimationElement.textContent += text[i];
							}, i * 200); // Increase the delay to slow down the typing animation
						}

						// Once the animation is complete, reset the text and start over
						setTimeout(() => {
							typingAnimationElement.textContent = '';
							playTypingAnimation(typingTexts[(typingTexts.indexOf(text) + 1) % typingTexts.length]);
						}, text.length * 200);
						}

						// Start the typing animation loop
						playTypingAnimation(typingTexts[0]);

						</script>

						<br>
						<br>
			            <h2>A Beginner WebDev</h2>
						<!-- <h2 class="d-flex" style="margin-bottom: 0">With over 5 years of experience</h2> -->
						<!-- <br> -->
			            <p><a href="https://www.youtube.com/@ingeniousladka911" class="btn btn-primary py-3 px-4">YouTube</a> 
							<a href="https://github.com/Grooti" class="btn btn-white btn-outline-white py-3 px-4">My works</a></p>
		            </div>
		          </div>
	        	</div>
	        </div>
	      </div>
		</div>
    </section>



    <section class="ftco-about img ftco-section ftco-no-pb" id="about-section">
    	<div class="container">
			<div class="row">
				<div class="row d-flex align-items-stretch">
				<!-- <div class="row d-flex"> -->
					<div class="col-md-6 col-lg-5 d-flex">
						<div class="img-about img d-flex align-items-stretch">
							<div class="overlay">
								<div class="row">
									<div class="col-sm-6 col-md-5">
									  <div class="about-img">
										<img src="images/simple.png" class="img-fluid rounded b-shadow-a" alt="">
									  </div>
									</div>
									<!-- Details next to profile image -->
									<div class="col-sm-6 col-md-7">
									  <div class="about-info">
										<p><span class="title-s">Name: </span> <span>Siddhant Kumar</span></p>
										<p><span class="title-s">Job Role: </span> <span>Beginner WebDev</span></p>
										<p><span class="title-s">Experience: </span> <span>3 Months</span></p>
										<p><span class="title-s">Address: </span> <span>Bihar, India</span></p>
									  </div>
									</div>
								  </div>

								<div class="skill-mf">
									<p class="title-s">Skills</p>
									<span>SQL</span> <span class="pull-right">95%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 95%;" aria-valuenow="95" aria-valuemin="0"
											aria-valuemax="100"></div>
									</div>
									
									<span>HTML, CSS, JAVA</span> <span class="pull-right">85%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 85%" aria-valuenow="85" aria-valuemin="0"
											aria-valuemax="100"></div>
									</div>
									
									<span>C, C++, JAVA</span> <span class="pull-right">90%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 90%" aria-valuenow="90" aria-valuemin="0"
											aria-valuemax="100"></div>
									</div>
									
									<span>Photogyapher, Cinematographer</span> <span class="pull-right">85%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 85%" aria-valuenow="85" aria-valuemin="0"
											aria-valuemax="100"></div>
									</div>
									
									<span>Content Writer</span> <span class="pull-right">80%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 80%" aria-valuenow="80" aria-valuemin="0"
											aria-valuemax="100"></div>
									</div>
								</div>
							</div>
						</div>
					</div>
					
					<div class="col-md-6 col-lg-7 pl-lg-5 pb-5">
						<div class="row justify-content-start pb-3">
							<div class="col-md-12 heading-section ftco-animate">
								
								<h1 class="big">About</h1>
								<h2 class="mb-4">About Me</h2>
								
								<p>I am a beginner Wev Developer. Learning the basic to advance in the field of web development.</p>
								<ul class="about-info mt-4 px-md-0 px-2">
									<li class="d-flex"><span>Profile:</span> <span>Web Developer</span></li>
									<li class="d-flex"><span>Domain:</span> <span>Retail, Ecommerce, &amp; Digital Marketing</span></li>
									<li class="d-flex"><span>Education:</span> <span>Bachelor of Engineering</span></li>
									<li class="d-flex"><span>Language:</span> <span>English, Hindi</span></li>
									<li class="d-flex"><span>Other Skills:</span> <span>Cloud Computing, Excel, Git, Google Analytics &amp; SEO</span></li>
									<li class="d-flex"><span>Interest:</span> <span>Web Development, Travel Photography, Cinematography</span></li>
									
								</ul>
							</div>
						</div>


						<div class="counter-wrap ftco-animate d-flex mt-md-3">
							<div class="text">
								<p class="mb-4">
									<span class="number" data-number="3">0</span> <span>+</span>
									<span>&nbsp; Projects completed</span>
								</p>
								<p><a href="https://www.linkedin.com/in/siddhant-kumar-0400b3229/" class="btn btn-primary py-3 px-3">LinkedIn</a></p>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
    </section>



	
    <section class="ftco-section ftco-no-pb" id="resume-section">
    	<div class="container">
    		<div class="row justify-content-center pb-5">
          <div class="col-md-10 heading-section text-center ftco-animate">
          	<h1 class="big big-2">Resume</h1>
            <h2 class="mb-4">Resume</h2>
            <p>Completed Diploma and forward-looking
				graduate from the University of Sant Longowal
				Institute of Engineering and Technology in
				Computer Science. Trained in WebDev, C++,
				Java, C programming, as well as making and
				updating design documents, photography and
				cinematography etc. Completed a 4-week
				training at Ansh Infotech, Ludhiana, Punjab.</p>
          </div>
        </div>

		<div class="row">
			<h1 class="big-4">Experience</h1>
			<div class="underline"></div>
		</div>
		<br>
		
		<div class="row">
				<div class="col-md-6">
					<div class="resume-wrap ftco-animate">
						<span class="date">2024-Present</span>
						<h2>Front End Web Developer</h2>
						<span class="position">Beginner</span>
						<p class="mt-4">W e b D e v e l o p e r I n t e r n 
							<ul>
								<li>HTML,CSS,JS</li>
								<li>Django Framework (Basic)</li>
								<li>Database Management System</li>
									
							</ul>
						</p>
					</div>

				</div>

				<div class="col-md-6">
					<div class="resume-wrap ftco-animate">
						<span class="date">2020-2023 June</span>
						<h2>Diploma in computer science</h2>
						<span class="position">SLIET</span>
						<p class="mt-4">Sant Longowal Institute of Engineering and Technology 
							<ul>
								<li></li>
								<li></li>
								<li></li>
							</ul>
						</p>
					</div>

				</div>
			</div>

		<br>
		<br>

		<div class="row">
			<h1 class="big-4">Education</h1>
			<div class="underline"></div>
		</div>
		<br>
		
			<div class="row">
    			<div class="col-md-6">
    				<div class="resume-wrap ftco-animate">
    					<span class="date">2023-Pursuing</span>
    					<h2>Bachelor of Engineering</h2>
    					<span class="position">Sant Longowal Institute of Engineering and Technology </span>
    					<p class="mt-4">Grade: First class distinction.</p>
    				</div>
    			</div>

    			<div class="col-md-6">
    				<div class="resume-wrap ftco-animate">
    					<span class="date">2019-2020</span>
    					<h2>Metriculation</h2>
    					<span class="position">Public Central School</span>
    					<p class="mt-4">Grade: First class distinction.(80%)</p>
    				</div>
				</div>
    		</div>

    		<div class="row justify-content-center mt-5">
    			<div class="col-md-6 text-center ftco-animate">
    				<p><a href="https://drive.google.com/file/d/1bt1VqUt013zX6xKx9ca3ua5I695IKseM/view?usp=sharing" class="btn btn-primary py-4 px-5">Download Resume</a></p>
    			</div>
    		</div>
    	</div>
    </section>

   

    <section class="ftco-section" id="project-section">
      <div class="container">
        <div class="row justify-content-center mb-5 pb-5">
          <div class="col-md-7 heading-section text-center ftco-animate">
            <h1 class="big big-2">Projects</h1>
            <h2 class="mb-4">Projects</h2>
            <p>Below are the sample Data Analytics projects on SQL, Python, Power BI & ML.</p>
          </div>
        </div>
        <div class="row d-flex">
          <div class="col-md-4 d-flex ftco-animate">
          	<div class="blog-entry justify-content-end">
              <a href="#" class="block-20 zoom-effect" style="background-image: url('https://picsum.photos/200/300');">
              </a>
              <div class="text mt-3 float-right d-block">

                <h3 class="heading"><a href="#">Project 1</a></h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae, quaerat? Voluptatibus quis harum ea dolorem quasi quas voluptatem eos reiciendis nam fugiat maxime, assumenda aperiam voluptates molestiae facere officiis fugit!</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 d-flex ftco-animate">
          	<div class="blog-entry justify-content-end">
              <a href="#" class="block-20 zoom-effect" style="background-image: url('https://picsum.photos/200/300');">
              </a>
              <div class="text mt-3 float-right d-block">

                <h3 class="heading"><a href="#">Project 2</a></h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quo voluptatibus, dolorum repudiandae neque, vitae cumque eius necessitatibus perspiciatis temporibus repellendus exercitationem velit, soluta maiores modi fugiat! Hic qui ullam sunt.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 d-flex ftco-animate">
          	<div class="blog-entry">
              <a href="#" class="block-20 zoom-effect" style="background-image: url('https://picsum.photos/200/300');">
              </a>
              <div class="text mt-3 float-right d-block">

                <h3 class="heading"><a href="#">Project 3</a></h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit, sed quam? Sequi voluptate perspiciatis consequatur omnis dignissimos, minus earum fugit ut sapiente nihil temporibus neque eum! Optio amet possimus accusamus.</p>
              </div>
            </div>
          </div>
        </div>
	<br>
		<!-- added justify-content-center to center align the last two projects -->
		<div class="row d-flex justify-content-center">  
			<div class="col-md-4 d-flex ftco-animate">
				<div class="blog-entry justify-content-end">
				<a href="#" class="block-20 zoom-effect" style="background-image: url('https://picsum.photos/200/300');">
				</a>
				<div class="text mt-3 float-right d-block">
  
				  <h3 class="heading"><a href="#">Project 4</a></h3>
				  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta harum quia vero fuga saepe! Veniam sequi ex eligendi. Reprehenderit assumenda sint eos, ratione veritatis dolorem similique quia modi ut consectetur.</p>
				</div>
			  </div>
			</div>
			<div class="col-md-4 d-flex ftco-animate">
				<div class="blog-entry justify-content-end">
				<a href="#" class="block-20 zoom-effect" style="background-image: url('https://picsum.photos/200/300');">
				</a>
				<div class="text mt-3 float-right d-block">
  
				  <h3 class="heading"><a href="#">Project 5</a></h3>
				  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime fugiat cupiditate aperiam odit sint autem recusandae atque tempore ipsa, ratione provident saepe. Quibusdam, excepturi perferendis reprehenderit nesciunt porro atque magnam?</p>
				</div>
			  </div>
			</div>
		 </div>
	  </div>
    </section>

	<section class="ftco-section ftco-no-pt ftco-no-pb ftco-counter img" id="section-counter">
      <div class="container">
		<div class="row d-md-flex align-items-center">
          <div class="col-md d-flex justify-content-center counter-wrap ftco-animate">
            <div class="block-18">
              <div class="text">
                <strong class="number" data-number="2">0</strong>
                <span>Achievements</span>
              </div>
            </div>
          </div>
          <div class="col-md d-flex justify-content-center counter-wrap ftco-animate">
            <div class="block-18">
              <div class="text">
                <strong class="number" data-number="3">0</strong>
                <span>Projects</span>
              </div>
            </div>
          </div>
          <div class="col-md d-flex justify-content-center counter-wrap ftco-animate">
            <div class="block-18">
              <div class="text">
                <strong class="number" data-number="10">0</strong>
                <span>Mentored Students</span>
              </div>
            </div>
          </div>
          <div class="col-md d-flex justify-content-center counter-wrap ftco-animate">
            <div class="block-18">
              <div class="text">
                <strong class="number" data-number="50">0</strong>
                <span>Cups of coffee</span>
              </div>
            </div>
          </div>
        </div>
      </div>
	
	  <div class="ftco-section ftco-hireme img margin-top" style="background-image: url(images/about.png)">
			<!-- <div class="container"> -->
				<div class="row justify-content-center">
					<div class="col-md-7 ftco-animate text-center">
						<h2>More projects on<span style="color: black;"> Github  </span> </h2>
						<div class="heading"> <h4>I am being happy with Web development.</h4>
						<br>
						<p><a href="https://github.com/Grooti" class="btn btn-primary py-3 px-5">GitHub</a></p>
						</div>
					</div>
				</div>
			<!-- </div> -->
		</div>
	</section>



    <section class="ftco-section contact-section ftco-no-pb" id="contact-section">
      <div class="container">
      	<div class="row justify-content-center mb-5 pb-3">
          <div class="col-md-7 heading-section text-center ftco-animate">
            <h1 class="big big-2">Contact</h1>
            <h2 class="mb-4">Contact Me</h2>
            <p>Below are the details to reach out to me!</p>
          </div>
        </div>

        <div class="row d-flex contact-info mb-5">
          <div class="col-md-6 col-lg-3 d-flex ftco-animate">
          	<div class="align-self-stretch box p-4 text-center">
          		<div class="icon d-flex align-items-center justify-content-center">
          			<span class="icon-map-signs"></span>
          		</div>
          		<h3 class="mb-4">Address</h3>
	            <p>Bihar, India</p>
	          </div>
          </div>
          <div class="col-md-6 col-lg-3 d-flex ftco-animate">
          	<div class="align-self-stretch box p-4 text-center">
          		<div class="icon d-flex align-items-center justify-content-center">
          			<span class="icon-phone2"></span>
          		</div>
          		<h3 class="mb-4">Contact Number</h3>
	            <p><a href="tel://0101010101">+91 7492973921</a></p>
	          </div>
          </div>
          <div class="col-md-6 col-lg-3 d-flex ftco-animate">
          	<div class="align-self-stretch box p-4 text-center">
          		<div class="icon d-flex align-items-center justify-content-center">
          			<span class="icon-paper-plane"></span>
          		</div>
          		<h3 class="mb-4">Email Address</h3>
	            <p><a href="mailto:info@yoursite.com">siddhantgrooti@gmail.com</a></p>
	          </div>
          </div>
          <div class="col-md-6 col-lg-3 d-flex ftco-animate">
          	<div class="align-self-stretch box p-4 text-center">
          		<div class="icon d-flex align-items-center justify-content-center">
          			<span class="icon-globe"></span>
          		</div>
          		<h3 class="mb-4">Download Resume</h3>
	            <p><a href="https://drive.google.com/file/d/1bt1VqUt013zX6xKx9ca3ua5I695IKseM/view?usp=sharing">Download</a></p>
	          </div>
          </div>

		  <div class="container">
			<br>
			<br>
			<div class="row justify-content-center">
				<div class="col-md-7 ftco-animate text-center">
					<h2>Have a<span> Question?  </span> <a href="https://forms.gle/XLHRHsn7Tk3m2PVL7" class="btn btn-primary py-3 px-5">Click Here</a> </h2>
				</div>
			</div>
				<br>
					<ul class="ftco-footer-social list-unstyled d-flex justify-content-center align-items-center mb-0">
					  <li class="ftco-animate normal-txt">Find me on  </li>
					  <li class="ftco-animate"><a href="https://www.youtube.com/@ingeniousladka911"><span class="icon-youtube"></span></a></li>
					  <li class="ftco-animate"><a href="https://www.linkedin.com/in/siddhant-kumar-0400b3229/"><span class="icon-linkedin"></span></a></li>
				      <li class="ftco-animate"><a href="https://www.instagram.com/grootisid/#"><span class="icon-instagram"></span></a></li>
					</ul>
				<br>
		   </div>
   </div>
 </section>


 
	
    <footer class="ftco-footer ftco-section">
		<div class="container">
		  <div class="row">
			<div class="col-md-12 text-center">
  
			  <p><!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
	Copyright &copy;<script>document.write(new Date().getFullYear());</script> All rights reserved | To the developer <i class="icon-heart color-danger" aria-hidden="true"></i> by <a href="https://colorlib.com" target="_blank">Siddhant</a>
	<!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. --></p>
			</div>
		  </div>
		</div>
	  </footer>


  <!-- loader -->
  <div id="ftco-loader" class="show fullscreen"><svg class="circular" width="48px" height="48px"><circle class="path-bg" cx="24" cy="24" r="22" fill="none" stroke-width="4" stroke="#eeeeee"/><circle class="path" cx="24" cy="24" r="22" fill="none" stroke-width="4" stroke-miterlimit="10" stroke="#F96D00"/></svg></div>


  <script src="js/jquery.min.js"></script>
  <script src="js/jquery-migrate-3.0.1.min.js"></script>
  <script src="js/popper.min.js"></script>
  <script src="js/bootstrap.min.js"></script>
  <script src="js/jquery.easing.1.3.js"></script>
  <script src="js/jquery.waypoints.min.js"></script>
  <script src="js/jquery.stellar.min.js"></script>
  <script src="js/owl.carousel.min.js"></script>
  <script src="js/jquery.magnific-popup.min.js"></script>
  <script src="js/aos.js"></script>
  <script src="js/jquery.animateNumber.min.js"></script>
  <script src="js/scrollax.min.js"></script>
  
  <script src="js/main.js"></script>
    
  </body>
</html>
