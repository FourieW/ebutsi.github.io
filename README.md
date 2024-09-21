<!DOCTYPE html>
<html>
<head>
<title>Ebutsi Trading</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif;}
body, html {
  height: 100%;
  color: #777;
  line-height: 1.8;
}
ul { color: #4CBB17; }
.text-wrapper {    color: black; }

#myNavbar{
    overflow: hidden;
    
}


/* Create a Parallax Effect */
.bgimg-1, .bgimg-2, .bgimg-3 {
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/* First image (Logo. Full height) */
.bgimg-1 {
  background-image: url('https://images.unsplash.com/photo-1622375836858-bb6f2d1938a0?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTJ8fGpvaGFubmVzYnVyZ3xlbnwwfHwwfHx8MA%3D%3D&w=1000&q=80');
  min-height: 100%;
}

/* Second image (Portfolio) */
.bgimg-2 {
  background-image: url("/w3images/parallax2.jpg");
  min-height: 400px;
}

/* Third image (Contact) */
.bgimg-3 {
  background-image: url("/w3images/parallax3.jpg");
  min-height: 400px;
}

.w3-wide {letter-spacing: 10px;}
.w3-hover-opacity {cursor: pointer;}

/* Turn off parallax scrolling for tablets and phones */
@media only screen and (max-device-width: 1600px) {
  .bgimg-1, .bgimg-2, .bgimg-3 {
    background-attachment: scroll;
    min-height: 400px;
  }
}







#navbar {
  width: 100%;
  background-color: 	#606060;
  overflow: auto;
}

/* Navbar links */
#navbar a {
  float: left;
  text-align: center;
  padding: 10px;
  color: white;
  text-decoration: none;
  font-size: 14px;
}

/* Navbar links on mouse-over */
#navbar a:hover {
  background-color: #000;
}

/* Current/active navbar link */
.active {
  background-color: #04AA6D;
}

/* Add responsiveness - will automatically display the navbar vertically instead of horizontally on screens less than 500 pixels */
@media screen and (max-width: 500px) {
  .navbar a {
    float: none;
    display: block;
  }
}



</style>
</head>
<body>

<!-- Navbar (sit on top) -->
<!-- <div class="w3-top">
  <div class="w3-bar" id="myNavbar">
    <a class="w3-bar-item w3-button w3-hover-black w3-hide-medium w3-hide-large w3-right" href="javascript:void(0);" onclick="toggleFunction()" title="Toggle Navigation Menu">
      <i class="fa fa-bars"></i>
    </a>
    <a href="#home" class="w3-bar-item w3-dark-gray w3-button w3-hover-green">HOME</a>
    <a href="#about" class="w3-bar-item w3-dark-gray w3-button w3-hide-small w3-hover-green"><i class="fa fa-user"></i> ABOUT</a>
    <a href="#portfolio" class="w3-bar-item w3-dark-gray  w3-button w3-hide-small w3-hover-green"><i class="fa fa-briefcase"></i> OFFER </a>
    <a href="#contact" class="w3-bar-item w3-dark-gray w3-button w3-hide-small w3-hover-green"><i class="fa fa-envelope"></i> CONTACT</a>
  </div>
  -->
  <div class="w3-top">
  <div id="navbar">
    <a href="#home" class="w3-bar-item w3-dark-gray w3-button w3-hover-green"><i class="fa fa-home"></i>&nbsp;&nbsp;HOME</a>
    <a href="#about" class="w3-bar-item w3-dark-gray w3-button w3-hide-small w3-hover-green"><i class="fa fa-user"></i>&nbsp;&nbsp;ABOUT</a>
    <a href="#offer" class="w3-bar-item w3-dark-gray  w3-button w3-hide-small w3-hover-green"><i class="fa fa-briefcase"></i>&nbsp;&nbsp;OFFER </a>
    <a href="#contact" class="w3-bar-item w3-dark-gray w3-button w3-hide-small w3-hover-green"><i class="fa fa-envelope"></i>&nbsp;&nbsp;CONTACT</a>



    <a href="#" class="w3-bar-item w3-button w3-green w3-right">Ebutsi Logo</a>


    
  </div>
  </div>

  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-bar-block w3-green w3-hide w3-hide-large w3-hide-medium">
    <a href="#about" class="w3-bar-item w3-button" onclick="toggleFunction()">ABOUT</a>
    <a href="#offer" class="w3-bar-item w3-button" onclick="toggleFunction()">OFFER</a>
    <a href="#contact" class="w3-bar-item w3-button" onclick="toggleFunction()">CONTACT</a>
  </div>
</div>

<!-- First Parallax Image with Logo Text 
<div class="bgimg-1 w3-display-container w3-opacity-min" id="home" style="background-color: #4CBB17">
  <div class="w3-display-middle" style="green-space:nowrap">
    <span class="w3-center w3-padding-large w3-black w3-xxlarge w3-wide w3-animate-opacity"> EBUTSI TRADING</span>
  </div>
</div>-->

<div class="bgimg-1 w3-display-container w3-opacity-min" id="home">
  <div class="w3-display-middle" style="white-space:nowrap;">
    <span class="w3-center w3-padding-large w3-xxlarge w3-wide w3-animate-opacity" style="background-color: #4CBB17; color: black;">EBUTSI TRADING</span>
  </div>
</div>



<!-- Container (About Section) -->
<div class="w3-content w3-container w3-padding-64" id="about">
  <h3 class="w3-center w3-xxlarge">ABOUT US</h3>
  <p class="w3-center"><em>Strategic Business Outsourcing</em></p>
  <br>
  <p>We strive to optimize and help other companies thrive by allowing them to focus on their core business, whilst taking care of all you human resources and labour related headaches!</p>
  <p>Our highly effective team of business specialists and service providers work with best practices and state-of-the-art solutions.
  </p>
  <br>
  <br>
  <div class="w3-row">
    <div class="w3-col m6 w3-center w3-padding-large">
      <p><b><i class="fa fa-vcard-o w3-margin-right"></i>Ebutsi RSA is a registered member of: </b></p><br>
    </div>

    <!-- Hide this text on small devices -->
    <div class="w3-col m6 w3-show-small w3-padding-large">
        <ul>
            <li><span class="text-wrapper">Workmen’s Compensation Act Reg. <span></li>
            <li><span class="text-wrapper">Unemployment Act Reg.<span></li>    
            <li><span class="text-wrapper">Income Tax<span></li>
            <li><span class="text-wrapper">Value Added Tax<span></li>
            <li><span class="text-wrapper">SDL<span></li>
          </ul>
    </div>
    <br>
    <br>
    <div class="w3-col m6 w3-center w3-padding-large">
        <p><b><i class="fa fa-vcard-o w3-margin-right"></i>Ebutsi RSA is a registered member of the following councils: </b></p><br>
      </div>
  
      <!-- Hide this text on small devices -->
      <div class="w3-col m6 w3-show-small w3-padding-large">
          <ul>
                <li><span class="text-wrapper">National Bargaining Council – Road Freight Industry <span></li>
                <li><span class="text-wrapper">Furniture Bargaining Council – JHB & KZN<span></li>    
                <li><span class="text-wrapper">Cleaning Provident Fund<span></li>
                <li><span class="text-wrapper">Metal  & Engineering Industries Bargaining Council<span></li>
            </ul>
      </div>
  </div>


 <!--<p class="w3-large w3-center w3-padding-16">Im really good at:</p>
  <p class="w3-wide"><i class="fa fa-camera"></i>Photography</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:90%">90%</div>
  </div>
  <p class="w3-wide"><i class="fa fa-laptop"></i>Web Design</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:85%">85%</div>
  </div>
  <p class="w3-wide"><i class="fa fa-photo"></i>Photoshop</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:75%">75%</div>
  </div>-->

</div>


<!--
<div class="w3-row w3-center w3-dark-grey w3-padding-16">
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">14+</span><br>
    Partners
  </div>
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">55+</span><br>
    Projects Done
  </div>
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">89+</span><br>
    Happy Clients
  </div>
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">150+</span><br>
    Meetings
  </div>
</div> -->

<!-- Second Parallax Image with Portfolio Text -->
<!--<div class="bgimg-2 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
    <span class="w3-xxlarge w3-text-white w3-wide">PORTFOLIO</span>
  </div>
</div>-->

<!-- Container (Portfolio Section) -->
<div class="w3-content w3-container w3-padding-64" id="offer">
  <h3 class="w3-center">What We Offer</h3>
  <p class="w3-center"><em>Here are some of our services that we offer.<br> Click on the images to make them bigger</em></p><br>

  <!-- Responsive Grid. Four columns on tablets, laptops and desktops. Will stack on mobile devices/small screens (100% width) -->
  <div class="w3-row-padding w3-center">
    <div class="w3-col m3">
      <img src="/w3images/p1.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="The mist over the mountains">
    </div>

    <div class="w3-col m3">
      <img src="/w3images/p2.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Coffee beans">
    </div>

    <div class="w3-col m3">
      <img src="/w3images/p3.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Bear closeup">
    </div>

    <div class="w3-col m3">
      <img src="/w3images/p4.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Quiet ocean">
    </div>
  </div>

  <div class="w3-row-padding w3-center w3-section">
    <div class="w3-col m3">
      <img src="/w3images/p5.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="The mist">
    </div>

    <div class="w3-col m3">
      <img src="/w3images/p6.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="My beloved typewriter">
    </div>

    <div class="w3-col m3">
      <img src="/w3images/p7.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Empty ghost train">
    </div>

    <div class="w3-col m3">
      <img src="/w3images/p8.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Sailing">
    </div>
    <button class="w3-button w3-padding-large w3-light-grey" style="margin-top:64px">LOAD MORE</button>
  </div>
</div>

<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-button w3-large w3-black w3-display-topright" title="Close Modal Image"><i class="fa fa-remove"></i></span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" class="w3-image">
    <p id="caption" class="w3-opacity w3-large"></p>
  </div>
</div>

<!-- Third Parallax Image with Portfolio Text -->
<!--<div class="bgimg-3 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
     <span class="w3-xxlarge w3-text-white w3-wide">CONTACT</span>
  </div>
</div>-->

<!-- Container (Contact Section) -->
<div class="w3-content w3-container w3-padding-64" id="contact">
  <h3 class="w3-center">WHERE WE WORK</h3>
  <p class="w3-center"><em>110 Asquith Rd,</em></p>
  <p class="w3-center"><em>Eveleigh,</em></p>
  <p class="w3-center"><em>Boksburg,</em></p>
  <p class="w3-center"><em>1459</em></p>

  <div class="w3-content w3-container w3-padding-64">
    <!--<div class="w3-col m4 w3-container">
      <img src="https://www.andbeyond.com/wp-content/uploads/sites/5/Johannesburg-Skyline.jpg" class="w3-image w3-round" style="width:100%">
    </div>-->
    <div class="w3-center ">
      <div class="w3-large w3-margin-bottom">
        <i class="fa fa-map-marker fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Johannesburg, RSA<br>
        <i class="fa fa-phone fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Phone: 011 892 0431/0231<br>
        <i class="fa fa-envelope fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Email: mitchell@ebutsi.co.za<br>
      </div>
      <!--<p>Swing by for a cup of <i class="fa fa-coffee"></i>, or leave me a note:</p>
      <form action="/action_page.php" target="_blank">
        <div class="w3-row-padding" style="margin:0 -16px 8px -16px">
          <div class="w3-half">
            <input class="w3-input w3-border" type="text" placeholder="Name" required name="Name">
          </div>
          <div class="w3-half">
            <input class="w3-input w3-border" type="text" placeholder="Email" required name="Email">
          </div>
        </div>
        <input class="w3-input w3-border" type="text" placeholder="Message" required name="Message">
        <button class="w3-button w3-black w3-right w3-section" type="submit">
          <i class="fa fa-paper-plane"></i> SEND MESSAGE
        </button>
      </form> -->
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64 w3-opacity w3-hover-opacity-off">
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <div class="w3-xlarge w3-section">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
  </div>
  <p>Created by <a href="www.linkedin.com/in/werner-fourie-078a0a1a5" title="Werner se creation" target="www.linkedin.com/in/werner-fourie-078a0a1a5" class="w3-hover-text-green">Werner</a></p>
</footer>
 
<script>
// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}

// Change style of navbar on scroll
window.onscroll = function() {myFunction()};
function myFunction() {
    var navbar = document.getElementById("myNavbar");
    if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
        navbar.className = "w3-bar" + " w3-card" + " w3-animate-top" + " w3-white";
    } else {
        navbar.className = navbar.className.replace(" w3-card w3-animate-top w3-white", "");
    }
}

// Used to toggle the menu on small screens when clicking on the menu button
function toggleFunction() {
    var x = document.getElementById("navDemo");
    if (x.className.indexOf("w3-show") == -1) {
        x.className += " w3-show";
    } else {
        x.className = x.className.replace(" w3-show", "");
    }
}
</script>

</body>
</html>

