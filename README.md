<!DOCTYPE html>
<html>
<head>
<title>Silk & Spice Road</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Amatic+SC">
<style>
body, html {height: 100%}
body,h1,h2,h3,h4,h5,h6 {font-family: Helvetica}
.menu {display: none}
.bgimg {
  background-repeat: no-repeat;
  background-size: cover;
  background-image: url("https://i.pinimg.com/originals/3e/e9/be/3ee9bef9dddea6852057292323bb95a0.jpg");
  min-height: 90%;
}
</style>
</head>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top w3-hide-small">
  <div class="w3-bar w3-xlarge w3-black" id="myNavbar">
    <a href="#" class="w3-bar-item w3-button">Home</a>
    <a href="#menu" class="w3-bar-item w3-button">Menu</a>
    <a href="#about" class="w3-bar-item w3-button">About</a>
    <a href="#contact" class="w3-bar-item w3-button">Contact</a>
  </div>
</div>
  
<!-- Header with image -->
<header class="bgimg w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-bottomleft w3-padding">
    <span class="w3-tag w3-xlarge">Open from 10am to 8pm</span>
  </div>
  <div class="w3-display-middle w3-center">
    <span class="w3-text-white w3-hide-small w3-black" style="font-size:100px">Flavors<br>Across Oceans</span>
    <span class="w3-text-white w3-hide-large w3-hide-medium" style="font-size:60px"><b>Flavors<br>Across Oceans</b></span>
    <p><a href="#menu" class="w3-button w3-xxlarge w3-black">Let me see the menu</a></p>
  </div>
</header>

<!-- Menu Container -->
<div class="w3-container w3-black w3-padding-64 w3-xxlarge" id="menu">
  <div class="w3-content">
  
    <h1 class="w3-center w3-jumbo" style="margin-bottom:64px">The Menu</h1>
    <div class="w3-row w3-center w3-border w3-border-dark-grey">
      <a href="javascript:void(0)" onclick="openMenu(event, 'Main Menu');" id="myLink">
        <div class="w3-col s4 tablink w3-padding-large w3-hover-red">Main Menu</div>
      </a>
      <a href="javascript:void(0)" onclick="openMenu(event, 'Side Menu');">
        <div class="w3-col s4 tablink w3-padding-large w3-hover-red">Side Menu</div>
      </a>
      <a href="javascript:void(0)" onclick="openMenu(event, 'Beverages');">
        <div class="w3-col s4 tablink w3-padding-large w3-hover-red">Beverages</div>
    </div>

    <div id="Main Menu" class="w3-container menu w3-padding-32 w3-white">
      <h1><b>Rasta Pho</b> <span class="w3-right w3-tag w3-dark-grey w3-round">$12.50</span></h1>
      <p class="w3-text-grey">chicken thighs, jamaican jerk seasoning, chicken broth miso paste noodles soft boiled egg scallion</p>
      <hr>
   
      <h1><b>Coconut Chicken Shiro</b> <span class="w3-right w3-tag w3-dark-grey w3-round">$15.50</span></h1>
      <p class="w3-text-grey">chicken strips coconut curry powder shiro powder injera</p>
      <hr>
      
      <h1><b>Chicken</b> <span class="w3-right w3-tag w3-dark-grey w3-round">$12.00</span></h1>
      <p class="w3-text-grey">goofy sauce, mozzarella, chicken, onions</p>
      <hr>

      <h1><b>Traditional Goofy Pizza</b> <span class="w3-right w3-tag w3-dark-grey w3-round">$12.50</span></h1>
      <p class="w3-text-grey">goofy sauce, goofy cheese, , mystery meat, fresh basil</p>
      <hr>

      <h1><b>Meat Town</b> <span class="w3-tag w3-red w3-round">Hot!</span><span class="w3-right w3-tag w3-dark-grey w3-round">$20.00</span></h1>
      <p class="w3-text-grey">goofy sauce, goofy cheese, lamb chops, hot sliced chicken, beef, chicken</p>
      <hr>

      <h1><b>Octupus Special</b> <span class="w3-tag w3-grey w3-round">New</span><span class="w3-right w3-tag w3-dark-grey w3-round">$21.50</span></h1>
      <p class="w3-text-grey">Fresh tomatoes, mozzarella, turkey peperoni, olives, fresh arugula</p>
    </div>

    <div id="Side Menu" class="w3-container menu w3-padding-32 w3-white">
      <h1><b>Custom Shaped Pizza</b> <span class="w3-tag w3-grey w3-round">Popular</span> <span class="w3-right w3-tag w3-dark-grey w3-round">$25.00</span></h1>
      <p class="w3-text-grey">Goofy sauce, Mozzarella, Parmesan, Ground beef</p>
      <hr>
    </div>


    <div id="Beverages" class="w3-container menu w3-padding-32 w3-white">
      <h1><b>Today's Soup</b> <span class="w3-tag w3-grey w3-round">Seasonal</span><span class="w3-right w3-tag w3-dark-grey w3-round">$5.50</span></h1>
      <p class="w3-text-grey">Ask the waiter</p>
      <hr>
   
      <h1><b>Bruschetta</b> <span class="w3-right w3-tag w3-dark-grey w3-round">$8.50</span></h1>
      <p class="w3-text-grey">Bread with pesto, tomatoes, onion, garlic</p>
      <hr>
      
      <h1><b>Garlic bread</b> <span class="w3-right w3-tag w3-dark-grey w3-round">$9.50</span></h1>
      <p class="w3-text-grey">Grilled ciabatta, garlic butter, onions</p>
      <hr>
      
      <h1><b>Tomozzarella</b> <span class="w3-right w3-tag w3-dark-grey w3-round">$10.50</span></h1>
      <p class="w3-text-grey">Tomatoes and mozzarella</p>
    </div><br>

  </div>
</div>

<!-- About Container -->
<div class="w3-container w3-padding-64 w3-red w3-xlarge" id="about">
  <div class="w3-content">
    <h1 class="w3-center w3-jumbo" style="margin-bottom:64px">About</h1>
    <p>The Pizza Restaurant was founded by coach Wells and Mr. Italiano in Seattle, Washington during world war 2. This business was originally founded to feed people with limited ingrediants because of war subsidies and the recent great depression. The location can be found at the bottom of this page..</p>
    <p><strong>The Chef?</strong> Mr. Italiano himself<img src="https://www.foodserviceequipmentjournal.com/2022/03/Aflonso-Marseglia.jpg" style="width:150px" class="w3-circle w3-right" alt="Chef"></p>
    <p>We are proud of our interiors.</p>
    <img src="https://dynamic-media-cdn.tripadvisor.com/media/photo-o/08/d3/af/0d/la-pizza-cresci.jpg?w=600&h=400&s=1" style="width:100%" class="w3-margin-top w3-margin-bottom" alt="Restaurant">
    <h1><b>Opening Hours</b></h1>
    
    <div class="w3-row">
      <div class="w3-col s6">
        <p>Mon & Tue CLOSED</p>
        <p>Wednesday 10.00 - 24.00</p>
        <p>Thursday 10:00 - 24:00</p>
      </div>
      <div class="w3-col s6">
        <p>Friday 10:00 - 12:00</p>
        <p>Saturday 10:00 - 23:00</p>
        <p>Sunday Closed</p>
      </div>
    </div>
    
  </div>
</div>

<!-- Contact -->
<div class="w3-container w3-padding-64 w3-black w3-xlarge"id="contact">
  <div class="w3-content">
    <h1 class="w3-center w3-jumbo" style="margin-bottom:64px">Contact</h1>
    <p>Find us at 400 23rd Ave, Seattle, WA 98122 at garfield or call us at 123-456-7890</p>
    <p><span class="w3-tag">FYI!</span> We offer full-service catering for any event, large or small. We understand your needs and we will cater the food to satisfy the biggerst criteria of them all, the goofiness.</p>
    <p class="w3-xxlarge"><strong>Reserve</strong> a table, ask for today's special or just send us a message:</p>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="number" placeholder="How many people" required name="People"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="datetime-local" placeholder="Date and time" required name="date" value="2025-1-1T20:00"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Message \ Special requirements" required name="Message"></p>
      <p><button class="w3-button w3-light-grey w3-block" type="submit">SEND MESSAGE</button></p>
    </form>
  </div>
</div>
<script>
// Tabbed Menu
function openMenu(evt, menuName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("menu");
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
     tablinks[i].className = tablinks[i].className.replace(" w3-red", "");
  }
  document.getElementById(menuName).style.display = "block";
  evt.currentTarget.firstElementChild.className += " w3-red";
}
document.getElementById("myLink").click();
</script>

</body>
</html>

