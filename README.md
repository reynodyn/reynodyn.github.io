<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Reynodyn</title>
<style>
body {
  margin: 0;
  font-family: sans-serif;
}

.about {
  font-size: 18px;
}
.topnav {
  overflow: hidden;
  position: relative;
    top: 0;
    left: 30%;
    transform: none;
}

.topnav a {
  float: left;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  background-color: white; 
    transition-duration: 0.4s;
  color: #595959; 
  }

.topnav a:hover {
  background-color:#f2f2f2;
  color: #000000;
  border-radius:80px;
}
.topnav a.active{
  color:#0077B4; ;
}
.topnav a.active:hover {
  background-color: #e6f6ff;
  color: #005580;
}
.card {
   background-color: white;
   padding: 120px  90px;
   margin-top: 20px;
}

.card2 {
   background-color: #f2f2f2;
   padding: 120px  90px;
   margin-top: 20px;
}
.subhead {
  color: #0077B4;
  font-size: 50px;
  padding: 30px 16px;
}

.button {
  background-color: #04AA6D; 
  border: none;
  color: white;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
 }
.button1 {
  background-color: transparent; 
  color: #0077B4; 
  border: 1px solid #0077B4;
  border-radius:80px;
}

.button1:hover {
  background-color: #e6f6ff;
  color: #005580;
  border: 2px solid #e6f6ff;
  border: 1px solid #0077B4;
}

.split {
  height: 100%;
  width: 50%;
  position: fixed;
  z-index: 1;
  top: 0;
  overflow-x: hidden;
  padding-top: 20px;
}

.left {
  left: 0;
  background-color: #111;
}

.right {
  right: 0;
  background-color: red;
}

footer {
  text-align: center;
  padding: 3px;
  background-color: #343a40;
  color: white;
}
.topnav .icon {
  display: none;
  background-color: #f2f2f2;
}

.flex-container {
  display: flex;
  flex-direction: row;
  font-size: 15px;
  
}

.flex-item-left {
  background-color: #f1f1f1;
  padding: 5%;
  flex: 50%;
}

.flex-item-right {
  padding: 5%;
  flex: 50%;
}
.map{
  width: 100%;
  height: 70%;

}
@media only screen and (max-width: 700px) {
 .map { 
     width: 100%;
     height: 30%;
  }
}


@media only screen and (max-width: 700px) {
  /* For mobile phones: */
  .body, .topnav, .card, .card2, .footer, .subhead, .flex-container{
    width: 70%;
   flex-direction: column;
  }

}

@media screen and (max-width: 700px) {
  .topnav a:not(:first-child) {display: none;}
  .topnav a.icon {
    float: right;
    display: block;
  }
}

@media screen and (max-width: 700px) {
  .topnav.responsive {position: relative;}
  .topnav.responsive .icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }
}

</style>
</head>
<body>

<div class="topnav" id="myTopnav">
  <a href="https://reynodyn.github.io" class="active">Home</a>
  <a href="#home">Services</a>
  <a href="#news">About us</a>
  <a href="#about">Work</a>
  <a href="#about">Insights</a>
  <a href="#contact">Contact</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()" >Re</a>
</div>
<script>
function myFunction() {
  var x = document.getElementById("myTopnav");
  if (x.className === "topnav") {
    x.className += " responsive";
  } else {
    x.className = "topnav";
  }
}
</script>

<div class="card">
<h1>Ideal for founders, product managers, and innovators who want to design, and brand their products for business growth</h1>
<button class="button button1">Learn more</button>
</div>

<div class="card">
<div class="subhead">Service built for you</div>
<div class="flex-container">
  <div class="flex-item-left">

Marketing
<ul style="line-height:180%">
<li>Organic search</li>
<li>E-commerce marketing services</li>
<li>Paid social media advertising</li>
<li>Global affiliate marketing</li>
</ul>


</div>
  <div class="flex-item-right">
Designing
<ul style="line-height:180%">
<li>Graphic Designing</li>
<li>Product designing</li>

<li>Strategy and planning</li>
<li>Print on demand - T-Shirt, mug Printing</li>
</ul>
</div>

</div>

<p>
<button class="button button1">See more</button>
</p>

</div>


<div class="card">
<div class="subhead"> Who we are</div>
<p class="about" style="line-height:180%">
We are built to change future. We serves as a strategic partner for businesses, specializing in promoting products or services to target audiences effectively. 
We conduct comprehensive market research to understand consumer behavior, trends, and competitors. 
Using this data, we develop tailored marketing strategies that may include digital campaigns, social media management, 
content creation, SEO optimization, and advertising.
</p>
<button class="button button1">About us</button>
</div>	
<div class="card2">
<div class="subhead"> Work</div>
<div class="flex-container">
  <div class="flex-item-left">
<img src="C:\Users\Thomas\Downloads\Thought of the day.jpg" alt="Thought" style="width:100%;height:100%;">
<p>Marketing</p>
</div>
  <div class="flex-item-right">
<img src="C:\Users\Thomas\Downloads\image.png" alt="horse" style="width:100%;height:70%;">
<p>Designing</p>

</div>

</div>
<p>
<button class="button button1">See more</button>
</p>
</div>

<div class="card">
<div class="subhead"> Blog</div>
<div class="flex-container">
  <div class="flex-item-left">

Technology
<ul style="line-height:180%">
<li>Organic search</li>

</ul>
<a href="#home" title="See more on technology">See more</a>

</div>
  <div class="flex-item-right">
Health
<ul style="line-height:180%">
<li>Graphic Designing</li>

</ul>
<a href="#home" title="See more on health">See more</a>
</div>
  <div class="flex-item-left">
Energy
<ul style="line-height:180%">
<li>Graphic Designing</li>

</ul>
<a href="#home" title="See more on energy">See more</a>
</div>
  <div class="flex-item-right">
Sustainable earth
<ul style="line-height:180%">
<li>Graphic Designing</li>

</ul>
<a href="#home" title="See more on sustainable earth">See more</a>
</div>

</div>
<p>
<button class="button button1">See more</button>
</p>
</div>
<div class="card">

<h1>Trusted by companies around the globe</h1>
<div class="flex-container">
  <div class="flex-item-left">
United States
</div>
<div class="flex-item-right">
Europe
</div>
 <div class="flex-item-left">
India
</div>
<div class="flex-item-right">
Australia
</div>

</div>

<img class="map" src="C:\Users\Thomas\Downloads\map.png" alt="map">
</div>
<div class="card2">
<h2><q>Either you run the day or the day runs you</q></h2><br />
Jim Rohn
</div>
<footer>
  <p>For help mail to
  <a href="mailto:reynodyn@gmail.com">reynodyn@gmail.com</a></p>
  <p>&copy; 2024 Reynodyn. All Rights Reserved.</p>
</footer>

</body>
</html>
