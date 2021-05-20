<!doctype html>

<html lang="en">

<head>

  <meta charset="utf-8">
  <title>YENNIE - Portfolio with grid and modern simplicity style</title>
  <meta name="description" content="YENNIE - Portfolio with grid and modern simplicity style">
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="icon" type="image/png" href="img/chibi.png" />

  <!--Style-->

  <link rel="stylesheet" href="css/reset.css">
  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="css/style-responsive.css">

  <link rel="stylesheet" href="css/font-awesome.min.css">

  <!--[if lt IE 9]>
  <script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
  <![endif]-->

</head>

<body>

  <!--Preloader-->

  <div class="preloader" id="preloader">
    <div class="item">
      <div class="spinner">
      </div>
    </div>
  </div>

  <div class="opacity-nav">
    <div class="menu-index" id="buttons" style="z-index:999999">
      <i class="fa fa-close"></i>
    </div>

    <ul class="menu-fullscreen">
      <li><a class="" href="index.html">Home</a></li>
      <li><a href="projects.html">Projects</a></li>
      <li><a href="about.html">About me</a></li>
      <li><a href="https://yennnie.wixsite.com/yennie">Blog</a></li>
    </ul>
  </div>          

  <!--Header-->
  <header class="boxed" id="header-white">

    <div id="fullscreen">
        <div class="logo" id="full"><a href="index.html">Y E N N I E.</a></div>

      <div class="menu-index" id="button">
        <i class="fa fa-bars"></i>
      </div>
    </div>

    <div class="header-margin">

      <div class="logo"><a class="" href="index.html">Y E N N I E.</a></div>
      <ul class="header-nav">
        <li><a class="" href="projects.html">Projects</a></li>
        <li><a class="" href="about.html">About me</a></li>
	<li><a href="https://yennnie.wixsite.com/yennie">Blog</a></li>
      </ul>

      <ul class="social-icon">
        <div class="social-index">
          <li><a href="https://www.linkedin.com/in/yennnie/"><i class="fa fa-linkedin"></i></a></li>
          <li><a href="https://www.xing.com/profile/Yen_Nguyen59/cv"><i class="fa fa-xing"></i></a></li>
          <li><a href="https://www.instagram.com/yenn.nie/?hl=en"><i class="fa fa-instagram"></i></a></li>
        </div>
      </ul>
    </div>
  </header>

  <div class="clear"></div>

  <!--Content-->

  <div class="content" id="ajax-content">


    <div class="text-intro landing-text" id="site-type">

      <h1>My creative and simplicity modern</h1>
      <h1 class="typewrite"><span>Portfolio</span></h1>
      <p><br>
        Hello, I'm Yennie, A <i>Product Designer </i> and <i>Researcher </i> specializing in <i>UX/UI Design and Visual
          Design</i>. <br>
        I focus on creating experience that are functional and visual compelling. <br>Please check my portfolio. All
        project is clean and simplicity modern style.</p>

    </div>


    <!--Portfolio grid-->

    <ul class="portfolio-grid" id="portfolio-sidebar">


      <li class="grid-item" data-jkit="[show:delay=3000;speed=500;animation=fade]">
        <img src="img/portfolio/pi1.gif">
        <a href="single-gdss.html">
          <div class="grid-hover">
            <h1>GDSS</h1>
            <p>Web-Base system | UI/UX | Product</p>
          </div>
        </a>
      </li>

      <li class="grid-item" data-jkit="[show:delay=3000;speed=500;animation=fade]">
        <img src="img/portfolio/5.jpg">
        <a href="single-jpex.html">
          <div class="grid-hover">
            <h1>JapanEx</h1>
            <p>Web | UI/UX | Front-end</p>
          </div>
        </a>
      </li>

      <li class="grid-item" data-jkit="[show:delay=3000;speed=500;animation=fade]">
        <img src="img/portfolio/2.jpg">
        <a href="single-vlis.html">
          <div class="grid-hover">
            <h1>VietLIS</h1>
            <p>Web-based system | UI/UX| Product</p>
          </div>
        </a>
      </li>

      <li class="grid-item" data-jkit="[show:delay=3000;speed=500;animation=fade]">
        <img src="img/portfolio/3.jpg">
        <a href="single-wood.html">
          <div class="grid-hover">
            <h1>Balance-Tsumiki</h1>
            <p> Ecommerce Website| UI/UX</p>
          </div>
        </a>
      </li>

      <li class="grid-item" data-jkit="[show:delay=3000;speed=500;animation=fade]">
        <img src="img/portfolio/4.jpg">
        <a href="index.html">
          <div class="grid-hover">
            <h1>Qsensei Log </h1>
            <p>Log Management System | UI | Protected </p>
          </div>
        </a>
      </li>

      <li class="grid-item" data-jkit="[show:delay=3000;speed=500;animation=fade]">
        <img src="img/portfolio/6.jpg">
        <a href="single-visual.html">
          <div class="grid-hover">
            <h1>Visual Design</h1>
            <p>Branding | Graphical Design</p>
          </div>
        </a>
      </li>

    </ul>

  </div>


  <!--Home Sidebar-->

  <div id="ajax-sidebar">

    <div class="home-sidebar" style="position:fixed;" id="hero">

      <div class="parallax-option" data-jkit="[parallax:strength=0.8;axis=both]">

        <div class="parallax parallax1"><img src="img/round-2.png"></div>

      </div>

      <div class="parallax-option" data-jkit="[parallax:strength=0.3;axis=both]">

        <div class="parallax parallax1"><img src="img/round.png"></div>

      </div>

    </div>

  </div>


  <!--Footer-->

  <footer id="footer-box">

    <div class="footer-margin">

      <div class="copyright" id="footer-left">© Copyright 2020 - YENNIE. All Rights Reserved.</div>

    </div>


  </footer>


  <!--Scripts-->

  <script src="js/jquery.min.js"></script>
  <script src="js/jquery.easing.min.js"></script>
  <script src="js/modernizr.custom.42534.js" type="text/javascript"></script>
  <script src="js/jquery.waitforimages.js" type="text/javascript"></script>
  <script src="js/typed.js" type="text/javascript"></script>
  <script src="js/masonry.pkgd.min.js" type="text/javascript"></script>
  <script src="js/imagesloaded.pkgd.min.js" type="text/javascript"></script>
  <script src="js/jquery.jkit.1.2.16.min.js"></script>



  <script src="js/script.js" type="text/javascript"></script>
	<script>
    $('#button, #buttons').on('click', function() {
      $( ".opacity-nav" ).fadeToggle( "slow", "linear" );
    // Animation complete.
    });
  </script>

</body>

</html>
