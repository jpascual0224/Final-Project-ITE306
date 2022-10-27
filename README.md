# Final-Project-ITE306
#Title: Ichiraku Restaurant
#Programmers:
#1. Baldedara Lanz
#2. Pascual Jeferson
#3. Baptista Bren
#4. Villanueva Amiel
#5. Wadia Elymilyn
#6. Sevilla Alyssa

<!DOCTYPE html>
<html>
<head>
<title>Ichiraku Ramen</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<style>
body,h1,h5 {font-family: "Raleway", sans-serif}
body, html {height: 100%}
.bgimg {
  background-image: url('Ichiraku.jpg');
  min-height: 100%;
  background-position: center;
  background-size: 260px 260px;
  background-repeat: no-repeat;
  background-color: black;
}
</style>
</head>
<body>

<div class="bgimg w3-display-container w3-text-white">
  <div class="w3-display-middle w3-jumbo">
  </div>
  <div class="w3-display-topleft w3-container w3-xlarge">
    <p><button onclick="document.getElementById('menu').style.display='block'" class="w3-button w3-black">menu</button></p>
    <p><button onclick="document.getElementById('contact').style.display='block'" class="w3-button w3-black">contact</button></p>
  </div>
  <div class="w3-display-bottomleft w3-container">
    <p class="w3-xlarge">monday - friday 8:00am-8:00pm | saturday 3:00pm-5:00pm</p>
    <p class="w3-large">Cabanatuan, Nueva Ecija</p>
    <p>powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank">Ichiraku</a></p>
  </div>
</div>

<!-- Menu Modal -->
<div id="menu" class="w3-modal">
  <div class="w3-modal-content w3-animate-zoom">
    <div class="w3-container w3-black w3-display-container">
      <span onclick="document.getElementById('menu').style.display='none'" class="w3-button w3-display-topright w3-large">x</span>
      <h1>Starters</h1>
    </div>
    <div class="w3-container">
      <h5>Tomato Soup <b>₱160</b></h5>
      <h5>Chicken Salad <b>₱120</b></h5>
      <h5>Bread and Butter <b>₱50</b></h5>
    </div>
    <div class="w3-container w3-black">
      <h1>Main Courses</h1>
    </div>
    <div class="w3-container">
      <h5>Sapporo Miso Ramen <b>₱235.32</b></h5>
      <h5>Hakata Ramen <b>₱256</b></h5>
      <h5>Okinawa Soba <b>₱220</b></h5>
      <h5>Kagoshima Ramen <b>₱135</b></h5>
      <h5>Ganja Ramen <b>₱200</b></h5>
    </div>
    <div class="w3-container w3-black">
      <h1>Desserts</h1>
    </div>
    <div class="w3-container">
      <h5>Fruit Salad <b>₱100</b></h5>
      <h5>Ice cream <b>₱100</b></h5>
      <h5>Chocolate Cake <b>₱200</b></h5>
      <h5>Cheese <b>₱150</b></h5>
    </div>
  </div>
</div>

<!-- Contact Modal -->
<div id="contact" class="w3-modal">
  <div class="w3-modal-content w3-animate-zoom">
    <div class="w3-container w3-black">
      <span onclick="document.getElementById('contact').style.display='none'" class="w3-button w3-display-topright w3-large">x</span>
      <h1>Contact</h1>
    </div>
    <div class="w3-container">
      <p>Reserve a table, ask for today's special or just send us a message:</p>
      <form action="/action_page.php" target="_blank">
        <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Name" required name="Name"></p>
        <p><input class="w3-input w3-padding-16 w3-border" type="number" placeholder="How many people" required name="People"></p>
        <p><input class="w3-input w3-padding-16 w3-border" type="datetime-local" placeholder="Date and time" required name="date" value="2020-11-16T20:00"></p>
        <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Message \ Special requirements" required name="Message"></p>
        <p><button class="w3-button" type="submit">SEND MESSAGE</button></p>
      </form>
    </div>
  </div>
</div>
