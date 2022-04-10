<!DOCTYPE html>
<html lang="en">
<head>
<title>mii</title>
<meta charset="utf-8">
<meta name="viewport" content="width-device-width initial-scale=1">
<link rel="stylesheet" href="bootstrap.css">
<Link rel="stylesheet" href="stylemii.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.6.3/css/all.css">  
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js">
  <style>
    ul
{
	list-style: none;
	
	text-decoration:NONE;
	float:left;

}
li{
	float:left;
	width:200px;
	padding:30px 0px 0px 20px;
	font-size:30px;
}
#ee
 a 
 {
	 color:white;
	 text-decoration:NONE;
	 
 }
 #aa
 {
	 padding:20px 0px 0px 50px;
	 background-color:#e4c02c;
 }
 #dropdownMenuLink
 a{
	 font-size:20px; 
	 background-color: #333;
	 margin:30px 0px 0px 60px;
 }
 .dropdown-menu
 ul
 {
	 text-decoration:NONE;
	list-style: none; 
	float:left;
 }
 .dropdown-item
 li
 {
	font-size:30px; 
	float:left;
 }
 .dropdown-item
 a 
 {
	 color:black;
	 text-decoration:NONE;
	 
 }
 
 .button {
  background-color: #4CAF50; 
  border: none;
  color: white;
  padding: 10px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
  background-color: red; 
  color: black; 
  border: 2px solid #f44336;
   background: red;
  animation: mymove 5s infinite;
}
@keyframes mymove
 {
  from {background-color: red;}
  to {background-color: blue;}
}
}

.button:hover {
  background-color: #f44336;
  color: white;
}

#iq
{
	background-image:url(about_img.jpg);
	
	height:500px;
}
.footer {
    padding: 24px 0;
    background: red;
    color: #ffffff;
    bottom: 0px !important;
    width: 100% !important;
}
.container {
    width: 100%;
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
}
.footer ul {
    
    list-style: none;
	text-decoration:NONE;
}
.footer ul li 
{
    display: inline-block;
	
	font-size:30px;
 margin: 0 16px;
} 
.footer
a 
 {
	 color:white;
	 text-decoration:NONE;
	 
 }
 .footer
 i
 {
	 font-size:40px;
	 padding-left:35px;
 }
    </STYLE>
  </script>
</head>
<body>
<div class="container-fluid">
<div class="row" style="height:100px;background-color:red;">
<div class="col-sm-3">
<img src="th.jpg" style="width:200px;height:100px;"></img>
</div>
<div class="col-sm-9" id="ee" >
<ul>
<li> <a href="Home.html">Home </a> </li>
<li> <a href="About.html">About </a> </li>
<li> <a href="Contacts.html">Contacts </a> </li>
<li> <a href="opportunity.html">Opportunities </a> </li>
</ul>
<div class="dropdown">
<a href="signin.html"  class="btn btn-secondary dropdown-toggle" id="dropdownMenuLink" data-bs-toggle="dropdown" aria-expanded="false">
    Login 
  </a>
  <ul class="dropdown-menu" aria-labelledby="dropdownMenuLink">
    <li><a class="dropdown-item" href="signin.html">Sign In</a></li>
    <li><a class="dropdown-item" href="signup.html">Sign Up</a></li>
  </ul>
</div>
</div>
</div>
<div class="row">
<div class="col-sm-6" >
<div id="demo" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="1491.jpg" alt="Los Angeles" class="d-block" style="width:100%;height:420px;">
      <div class="carousel-caption">
        <h3>Los Angeles</h3>
        <p>We had such a great time in LA!</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="fatty.jpg" alt="Chicago" class="d-block" style="width:100%">
      <div class="carousel-caption">
        <h3>Chicago</h3>
        <p>Thank you, Chicago!</p>
      </div> 
    </div>
    <div class="carousel-item">
      <img src="aa.jpg" alt="New York" class="d-block" style="width:100%">
      <div class="carousel-caption">
        <h3>New York</h3>
        <p>We love the Big Apple!</p>
      </div>  
    </div>
  </div>
 
  <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>
</div>
</div>
<div class="col-sm-3" id="aa" > <h2>
AT ur doorsteps!!! 
</h2> 
<i class="far fa-smile" style="font-size:50px;padding:10px 0px 10px 130px;"> </i>
<p style="font-size:20px;"> We serve food at your
 door step. </p> 
 <h4 style="margin-left:30px;"> 
The Right Food,</br> The Right Quantity,</br>
 The Right Quality,</br>At Right Place , </br>  At Right Time ! </br> </h4> </p>
</div>
<div class="col-sm-3" >
<h2 style="padding:20px 0px 0px 50px;"> <center>Staff </center></h2>
<p> Our staff is 100% vaccinated .</br>
We take care of ur cleanliness.</p>
<center> <img src="vaccine.jpg" style="width:200px;height:200px;"></img></center>
</div>
</div>
<div class="row" style="background-color:red;height:20px;">
</div>
<div class="row">
<div class="col-sm-1" style="background-color:red;"> </div>
<div class="col-sm-2"  > <center> <h2> Chinese </H2>  <center>
 <img src="chini.jpg" style="width:200px;height:200px;"> </img>
<button class="button"> <a href="chinese.html">Orders Now! </a></button>
</img>
</div>
<div class="col-sm-2" >  <center> <H2> South Indian</h2>  <center> 
<img src="dosa.jpg" style="width:200px;height:200px;"> </img>
<button class="button "> Orders Now! </button>
</div>
<div class="col-sm-2" >  <center> <h2> Mocktails </h2>  <center>
<img src="mock.jpg" style="width:200px;height:200px;"> </img>
 <button class="button"> Orders Now! </button>
</div>
<div class="col-sm-2" >  <center> <h2> Indian </h2>  <center>
<img src="indian.jpg" style="width:200px;height:200px;"> </img>
<button class="button"> Orders Now! </button>
 </div>
 <div class="col-sm-2" >  <center> <h2> Italian </h2>  <center>
<img src="italian.jpg" style="width:200px;height:200px;"> </img>
<button class="button "> Orders Now! </button>
</div>
<div class="col-sm-1" style="background-color:red;"> </div>
</div>
<div class="row" style="background-color:#eaee45;height:300px;">
<div class="col-sm-3"  >
<h3 style="padding:10px 0px 0px 40px;">No Minimum Order </h3>
<center><img src="order.jpg" style="width:150px;height:150px;" /> </center>

<p style="padding:10px 0px 0px 20px;">Order in for yourself or for the group,</br> with no restrictions on order value. </p>
</div>
<div class="col-sm-3" >
<h3 style="padding:10px 0px 0px 20px;">Live Order Tracking </h3>
<center><img src="Live.jpg" style="width:150px;height:150px;" /> </center>

<p style="padding:10px 0px 0px 20px;">Know where your order is at all times,</br> from the restaurant to your doorstep.</p>
</div><div class="col-sm-3" >
<h3 style="padding:10px 0px 0px 20px;">Lightning-Fast Delivery </h3>
<center><img src="dfe.jpg" style="width:150px;height:150px;" /> </center>

 <p style="padding:10px 0px 0px 20px;">Experience Swiggy's superfast delivery</br> for food delivered fresh & on time.</p>

</div>

<div class="col-sm-3" > 
  <h3 style="padding:10px 0px 0px 20px;"> Your feedback helps us</br> <center>to improve our </br>services.</center></h3>
  </br>
  </br>
  <center><button class="btn btn-primary" type="button" data-bs-toggle="offcanvas" >
    Give Feedback
  </button> </center>
</div>
</div>

<div class="footer">
<div class="col-sm-12" id="foot">
<div class="container" style="text-align: center!important;" > 
<ul>
<li> <a href="Home.html">Home </a> </li>
<li> <a href="About.html">About </a> </li>
<li> <a href="Orders.html">Orders </a> </li>
<li> <a href="Contacts.html">Contacts </a> </li>
<li> <a href="opportunity.html">Opportunities </a> </li>
</ul> 
</br>
<i class="fab fa-linkedin-in"></i>
<i class="fab fa-facebook-square"></i>
<i class="fab fa-instagram"></i>
<i class="fab fa-twitter"></i> </br>
 <p style="padding-top:10px;">@swiggy </p>

</div>
</div>
</div>
</div>
</body>
</html>
