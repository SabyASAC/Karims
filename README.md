<html>
<title>Karims</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
body, html {
  height: 100%;
  font-family: "Calibri", sans-serif;
}

.bgimg {
  background-position: center;
  background-size: cover;
 
  min-height: 75%;
}

.menu {
  display: none;
}
</style>
<body>

<!-- Links (sit on top) -->
<div class="w3-top">
  <div class="w3-row w3-padding w3-black">
    <div class="w3-col s3">
      <a href="#" class="w3-button w3-block w3-grey">HOME</a>
    </div>
    <div class="w3-col s3">
      <a href="#about" class="w3-button w3-block w3-grey">ABOUT</a>
    </div>
    <div class="w3-col s3">
      <a href="#menu" class="w3-button w3-block w3-grey">MENU</a>
    </div>
    <div class="w3-col s3">
      <a href="#where" class="w3-button w3-block w3-grey">WHERE</a>
    </div>
  </div>
</div>

<!-- Header with image -->
<header class="bgimg w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-bottomleft w3-center w3-padding-large w3-hide-small">
    <span class="w3-tag">Open from 8 am to 11 pm </span>
  </div>
  <div class="w3-display-middle w3-center">
    <span class="w3-text-white" style="font-size:90px">Karim's</span>
  </div>
  <div class="w3-display-bottomright w3-center w3-padding-large">
    <span class="w3-text-grey"></span>
  </div>
</header>

<!-- Add a background color and large text to the whole page -->
<div class="w3-sand w3-grayscale w3-large">

<!-- About Container -->
<div class="w3-container" id="about">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-64"><span class="w3-tag w3-wide">About Karims: </span></h5>
    <p> Karim's Hotel or Karim's is a historic restaurant located near Jama Masjid, Gali Kababian, Old Delhi, Delhi, India. Established in 1913, the restaurant has been described as "synonymous with this area" and "arguably the city's most famous culinary destination".  </p>
    
    <div class="w3-panel w3-leftbar w3-light-grey">
      
      <p>Current Owner:Zaeem Uddin </p>
    </div>
   
    <p><strong>Opening hours:</strong>10 am to 8 pm </p>
    <p><strong>Address :</strong> Vikas Marg, Sagar Complex, New Rajdhani Enclave, Preet Vihar, New Delhi</p>
  </div>
</div>

<!-- Menu Container -->
<div class="w3-container" id="menu">
  <div class="w3-content" style="max-width:700px">
 
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">THE MENU</span></h5>
  
    <div class="w3-row w3-center w3-card w3-padding">
      <a href="javascript:void(0)" onclick="openMenu(event, 'Rice And Pulao');" id="myLink">
        <div class="w3-col s6 tablink">Rice And Pulao</div>
      </a>
      <a href="javascript:void(0)" onclick="openMenu(event, 'Shan-e-Tandoor');">
        <div class="w3-col s6 tablink">Shan-e-Tandoor</div>
      </a>
    </div>

    <div id="Rice And Pulao" class="w3-container menu w3-padding-48 w3-card">
      <h5>Veg Pulao     </h5>
      
      <h5>Veg Biriyani  </h5>
      
      <h5>Chicken Biryani </h5>
      
      <h5>Mutton Biryani</h5>

      <h5>Chicken Tikka Biryani </h5>
      
    </div>

    <div id="Shan-e-Tandoor" class="w3-container menu w3-padding-48 w3-card">
      <h5>Tandoori Bakra</h5>
      
    
      <h5>Tandoori Naan </h5>
      
    
      <h5>Tandoori Chicken</h5>
      
    
      <h5>Akbari Chicken TND</h5>
      
    </div>  
    
  </div>
</div>
</body>
</html>
<!-- Contact/Area Container -->
<div class="w3-container" id="where" style="padding-bottom:32px;">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">WHERE TO FIND US</span></h5>
    <p>Find us at the above mentioned address </p>
 
    
    <p><strong>Reserve</strong> a table, ask for today's special or just send us a message:</p>
      Send your responses <a href="https://forms.gle/1kMhg7TFfXXP7ret8">here!</a>
<!-- End page content -->
</div>
