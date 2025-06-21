	CODING FOR login.html

 <!DOCTYPE html>
  <html>
  <head>
  <title>Login Form</title>
  <link rel="stylesheet" type="text/css" href="login1.css">
  </head>
  <body>
  <a href="index.html">BACK TO HOME</a>
  <h2>maadi thottam sachu</h2><br>
  <div class="login">
      <form id="login" method="get" action="login.php">
  <label><b>User Name
  </b>
  </label>
  <input type="text" name="Uname" id="Uname" placeholder="Username">
  <br><br>
   <label><b>Password
      </b>
      </label>
  <input type="Password" name="Pass" id="Pass" placeholder="Password">
 <br><br>
     <input type="button" name="log" id="log" value="Log In Here">
 <br><br>
     <input type="checkbox" id="check">
     <span>Remember me</span>
      <br><br>
      Forgot <a href="#">Password</a>
    </form>
</div>
<h1>&#169 maadi thottam sachu 2024</h1>
</body>
</html>


 Coding for index.html

    <!DOCTYPE html>
<html>
    <head>
<title>maadi thootam sachu</title>
<meta charset="utf-8" />
<meta name="viewpoint" content="width=device-width,initial-scal=1.0">
<meta http-equip="X-UA-compatible" content="ie=edge">
<link rel="stylesheet" href="style.css" media="screen" type="text/css" />
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>
<script type="text/javascript" src="js/jquery.store.js"></script>
<script type="text/javascript" src="js/main.js"></script>
<script type="text/javascript"
src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>

</head>

<body>

<section id="nav-bar">
<nav class="navbar navbar-expand-lg navbar-light">
<h1>maadi thottam sachu</h1>
<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
<span class="navbar-toggler-icon"></span>
</button>
<div class="collapse navbar-collapse" id="navbarNav">
<ul class="navbar-nav ml-auto">

<li class="nav-item">
<a style="color:black;" class="nav-link" href="#new-arrivals">Products</a>
</li>
<li class="nav-item">
<a style="color:black;" class="nav-link" href="cart.html">Cart</a>

</li>


<li class="nav-item">
<a style="color:black;" class="nav-link" href="#about">About Us</a>
</li>

<li class="nav-item">
<a style="color:black;" class="nav-link" href="#services">Our Services</a>
</li>

<li class="nav-item">
<a style="color:black;" class="nav-link" href="#contact">Contact</a>
</li>

<li class="nav-item">
<a style="color:black;" class="nav-link" href="./login.html">Login/Sign Up</a>
</li>

</ul>
</div>
</nav>
<div class="slider">
<div id="carouselExampleInterval" class="carousel slide" data-ride="carousel">
<div class="carousel-inner">
<div class="carousel-item active" data-interval="10000">
<img src="C:\Users\akile\Downloads\Farmaholics.io-main\Farmaholics.io-main\images\pic.jpg" class="d-block w-100" alt="..."style="width: 100px;height:300px;">
</div>
<div class="carousel-item" data-interval="2000">
<img src="C:\Users\akile\Downloads\Farmaholics.io-main\Farmaholics.io-main\images\image4.jpg" class="d-block w-100" alt="..." style="width: 100px;height:300px;">
</div>
<div class="carousel-item">
<img src="C:\Users\akile\Downloads\Farmaholics.io-main\Farmaholics.io-main\images\image5.jpg" class="d-block w-100" alt="..."style="width: 100px;height:300px;">
</div>
<div class="carousel-item">
<img src="https://i.postimg.cc/qR3cPXV8/featuredimage4.jpg" class="d-block w-100" alt="..."style="width: 100px;height:300px;">
</div>
<div class="carousel-item">
<img src="https://i.postimg.cc/PqczVVcX/featuredimage5.jpg" class="d-block w-100" alt="..."style="width:100px;height:300px;">
</div>
</div>
<a class="carousel-control-prev" href="#carouselExampleInterval" role="button" data-slide="prev">
<span class="carousel-control-prev-icon" aria-hidden="true"></span>
<span class="sr-only">Previous</span>
</a>
<a class="carousel-control-next" href="#carouselExampleInterval" role="button" data-slide="next">
<span class="carousel-control-next-icon" aria-hidden="true"></span>
<span class="sr-only">Next</span>
</a>
</div>
</div>
<!------Featured Categories----->
<section class="featured-categories">
<div class="container">
<div class="row">
<div class="col-md-3">
<img src="https://i.postimg.cc/7ZZWpcB0/featured.png">
</div>
<div class="col-md-3">
<img src="https://i.postimg.cc/Kj50WrB0/featured1.png">
</div>
<div class="col-md-3">
<img src="images/seeds all type.webp">
</div>
<div class="col-md-3">
<img src="https://i.postimg.cc/RCG1j02p/featured3.png">
</div>
</div>
</div>
</section>
<section class="new-arrivals" id="new-arrivals">
<div id="site">
<div class="container">
<div class="title-box">
<h2>New Arrivals</h2>
</div>
<div class="row">
<div class="col-md-3">
<div class="product-top">
<img src="C:\Users\akile\Downloads\Farmaholics.io-main\Farmaholics.io-main\images\image1.jpg">
<div class="overlay-right">
<button type="button" class="btn btn-secondary" title="Quick Shop">
<i class="fa fa-eye"></i>
</button>

<button type="button" class="btn btn-secondary" title="Add to Wishlist">
<i class="fa fa-heart-o"></i>
</button>

<button type="button" class="btn btn-secondary" title="Add to Cart">
<i class="fa fa-shopping-cart"></i>
</button>
</div>
</div>


<div class="product-bottom text-center">

<h3>tomato seeds</h3>
<div class="product-description" data-name="Grapes seeds" data-price="250">

<p class="product-price">&#8377; 30</p>
<form class="add-to-cart" action="cart.html">
<div>
<label for="qty-2">Quantity</label>
<input type="text" name="qty-2" id="qty-2" class="qty" value="1" />
</div>
<p><input type="submit" value="Add to cart" class="btn" /></p>
</form>

</div>
</div>
</div>

<div class="col-md-3">
<div class="product-top">
<img src="images/cauliflower seeds.jpeg">
<div class="overlay-right">
<button type="button" class="btn btn-secondary" title="Quick Shop">
<i class="fa fa-eye"></i>
</button>

<button type="button" class="btn btn-secondary" title="Add to Wishlist">
<i class="fa fa-heart-o"></i>
</button>
<button type="button" class="btn btn-secondary" title="Add to Cart">
<i class="fa fa-shopping-cart"></i>
</button>
</div>
</div>


<div class="product-bottom text-center">

<h3>Cauliflower seeds</h3>
<div class="product-description" data-name="Cauliflower seeeds" data-price="100">

<p class="product-price">&#8377; 30</p>
<form class="add-to-cart" action="cart.html">
<div>
<label for="qty-2">Quantity</label>
<input type="text" name="qty-2" id="qty-2" class="qty" value="1" />
</div>
<p><input type="submit" value="Add to cart" class="btn" /></p>
</form>

</div>
</div>
</div>
     <div class="col-md-3">
<div class="product-top">
<img src="C:\Users\akile\Downloads\Farmaholics.io-main\Farmaholics.io-main\images\img2.jpg">
<div class="overlay-right">
<button type="button" class="btn btn-secondary" title="Quick Shop">
<i class="fa fa-eye"></i>
</button>

<button type="button" class="btn btn-secondary" title="Add to Wishlist">
<i class="fa fa-heart-o"></i>
</button>

<button type="button" class="btn btn-secondary" title="Add to Cart">
<i class="fa fa-shopping-cart"></i>
</button>
</div>
</div>


<div class="product-bottom text-center">

<h3>Yellow tomato seed</h3>
<div class="product-description" data-name="Apple seeds" data-price="250">

<p class="product-price">&#8377; 30</p>
<form class="add-to-cart" action="cart.html">
<div>
<label for="qty-2">Quantity</label>
<input type="text" name="qty-2" id="qty-2" class="qty" value="1" />
</div>
<p><input type="submit" value="Add to cart" class="btn" /></p>
</form>

</div>
</div>
</div>
<div class="col-md-3">
<div class="product-top">
<img src="C:\Users\akile\Downloads\Farmaholics.io-main\Farmaholics.io-main\images\img3.jpg">
<div class="overlay-right">
<button type="button" class="btn btn-secondary" title="Quick Shop">
<i class="fa fa-eye"></i>
</button>

<button type="button" class="btn btn-secondary" title="Add to Wishlist">
<i class="fa fa-heart-o"></i>
</button>

<button type="button" class="btn btn-secondary" title="Add to Cart">
<i class="fa fa-shopping-cart"></i>
</button>
</div>
</div>


<div class="product-bottom text-center">
<h3>red corn seeds</h3>

<div class="product-description" data-name="Strawberry seeds" data-price="300">

<p class="product-price">&#8377; 30</p>
<form class="add-to-cart" action="cart.html">
<div>
<label for="qty-2">Quantity</label>
<input type="text" name="qty-2" id="qty-2" class="qty" value="1" />
</div>
<p><input type="submit" value="Add to cart" class="btn" /></p>
</form>

</div>
</div>
</div>

</div>
<!------About Section------->
<section id="about">
<div class="container">
<div class="row">
<div class="col-md-6">
<h2>About Us</h2>
<div class="about-content">
Welcome to maadi thottam sachu website we are providing a quality seeds 
and we have every type of vegetables seeds and evry type of organic manure for plant 
so kindly see all the etails in the seeds and place your order


</div>
<button type="button" class="btn btn-primary">Read More>>

</button>

</div>
<div class="col-md-6 skills-bar">
<p>Delivery Rate</p>
<div class="progress">
<div class="progress-bar" style="width:85%;">85%</div>
</div>

<p>Customer Growth</p>
<div class="progress">
<div class="progress-bar" style="width:75%;">75%</div>
</div>

<p>Happy Employee</p>
<div class="progress">
<div class="progress-bar" style="width:90%;">90%</div>
</div>

</div>
</div>

</div>

<!------Services Section------->
<section id="services">

<div class="container">
<h1>Our Services</h1>
<div class="row services">
<div class="col-md-4 text-center">
<div class="icon">
<i class="fa fa-phone"></i>
</div>
<h3> 24/7 Support</h3>
<p>on order related queries</p>
</div>

<div class="col-md-4 text-center">
<div class="icon">
<i class="fa fa-shopping-cart"></i>
</div>
<h3> Return within 30 days</h3>
<p>of receiving your order</p>
</div>

<div class="col-md-4 text-center">
<div class="icon">
<i class="fa fa-truck"></i>
</div>
<h3>Get free delivery</h3>
<p>on orders above </p>
</div>
</div>
</div>

</section>

<!------COntact------------>
<section id="contact">

<div class="container">
<h1>Get In Touch</h1>
<div class="row">
<div class="col-md-6">
<form class="contact-form">
<div class="form-group">
<input type="text" class="form-control" placeholder="Your Name..">
</div>
<div class="form-group">
<input type="number" class="form-control" placeholder="Phone no.">
</div>
<div class="form-group">
<input type="email" class="form-control" placeholder="Email..">
</div>
<div class="form-group">
<textarea class="form-control" rows="4" placeholder="Message.."></textarea>
</div>
<button type="submit" class="btn btn-primary">Submit</button>
</form>
</div>
<div class="col-md-6 contact-info">
<div class="follow"><b><i class="fa fa-map-marker"></i> </b>mangadu,chennai,
</div>
<div class="follow"><b><i class="fa fa-mobile"></i> </b>(+91)9498349307</div>
<div class="follow"><b><i class="fa fa-envelope"></i> </b>maadithottam@gmail.com</div>
<div class="follow"><label><b>Get Social </b></label>
<a href="https://www.facebook.com/" target="_blank"><i class="fa fa-facebook"></i></a>
<a href="http://www.youtube.com/@MaadithottamSachu" target="_blank"><i
class="fa fa-youtube-play"></i></a>
<a href="https://twitter.com/login/" target="_blank"><i class="fa fa-twitter"></i></a>
<a href="https://myaccount.google.com/" target="_blank"><i
class="fa fa-google-plus"></i></a>
</div>
</div>
</div>
</div>
</section>
<footer id="site-info">
Copyright &copy; maadi thottam sachu 2023 <br>
</footer>
</body>
</html>


Code for cart.html

<!DOCTYPE html>
<html>
<head>
<title>Your Shopping Cart</title>
<meta charset="utf-8" />
<link rel="stylesheet" href="style.css" media="screen" type="text/css" />
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>
<script type="text/javascript" src="js/jquery.store.js"></script>
<script type="text/javascript"
src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>
</head>
<body id="cart-page">
<div id="site" class="cartcontent">
<header id="masthead">
</header>
<div id="content">
<h1>Your Shopping Cart</h1>
<form id="shopping-cart" action="cart.html" >
<table class="shopping-cart">
<thead>
<tr>
<th scope="col">Item</th>
<th scope="col">Qty</th>
<th scope="col" colspan="2">Price</th>
</tr>
</thead>
<tbody>
</tbody>
</table>
<p id="sub-total">
<strong>Sub Total</strong>: <span id="stotal"></span>
</p>
<ul id="shopping-cart-actions">
<li>
<input type="submit" name="update" id="update-cart" class="btn" value="Update Cart" />
</li>
<li>
<input type="submit" name="delete" id="empty-cart" class="btn" value="Empty Cart" />
</li>
<li>
<a href="index.html" class="btn">Continue Shopping</a>
</li>
<li>
<a href="checkout.html" class="btn">Go To Checkout</a>
</li>
</ul>
</form>
</div>
</div>
<footer id="site-info">
Copyright &copy; maadi thootam sachu 2024 <br> Made with &#10084;&#65039; By akash b
</footer>
</body>
</html>  
5.4 Coding for checkout.html

<!DOCTYPE html>
<html>
<head>
<title>Checkout</title>
<meta charset="utf-8" />
<link rel="stylesheet" href="style.css" media="screen" type="text/css" />
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>
<script type="text/javascript" src="js/jquery.store.js"></script>
<script type="text/javascript" src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>
</head>
<body id="checkout-page">
<div id="site">
<header id="masthead">
</header>
<div id="content">
<h1>Checkout</h1>
<table id="checkout-cart" class="shopping-cart">
<thead>
<tr>
<th scope="col">Item</th>
<th scope="col">Qty</th>
<th scope="col">Price</th>
</tr>
</thead>
<tbody>
</tbody>
</table>
 <div id="pricing">
<p id="shipping">
<strong>Shipping</strong>: <span id="sshipping"></span>
</p>
<p id="sub-total">
<strong>Total</strong>: <span id="stotal"></span>
</p>
 </div>
 <form action="order.html" id="checkout-order-form">
<h2>Your Details</h2>
<fieldset id="fieldset-billing">
<legend>Billing</legend>
<div>
<label for="name">Name</label>
<input type="text" name="name" id="name" data-type="string" data-message="This field cannot be empty" />
</div>
<div>
<label for="email">Email</label>
<input type="text" name="email" id="email" data-type="string" data-message="Not a valid email address" />
</div>
<div>
<label for="city">City</label>
<input type="text" name="city" id="city" data-type="string" data-message="This field cannot be empty" />
</div>
<div>
<label for="address">Address</label>
<input type="text" name="address" id="address" data-type="string" data-message="This field cannot be empty" />
</div>
<div>
<label for="zip">ZIP Code</label>
<input type="text" name="zip" id="zip" data-type="string" data-message="This field cannot be empty" />
</div>
<div>
<label for="country">Country</label>
<select name="country" id="country" data-type="string" data-message="This field cannot be empty">
<option value="">Select</option>
<option value="De">Denmark</option>
<option value="IN">India</option>
</select>
</div>
</fieldset>
<div id="shipping-same">Same as Billing <input type="checkbox" id="same-as-billing" value=""/></div>
<fieldset id="fieldset-shipping">
<legend>Shipping</legend>
<div>
<label for="sname">Name</label>
<input type="text" name="sname" id="sname" data-type="string" data-message="This field cannot be empty" />
</div>
<div>
<label for="semail">Email</label>
<input type="text" name="semail" id="semail" data-type="expression" data-message="Not a valid email address" />
</div>
<div>
<label for="scity">City</label>
<input type="text" name="scity" id="scity" data-type="string" data-message="This field cannot be empty" />
</div>
<div>
<label for="saddress">Address</label>
<input type="text" name="saddress" id="saddress" data-type="string" data-message="This field cannot be empty" />
</div>
<div>
<label for="szip">ZIP Code</label>
<input type="text" name="szip" id="szip" data-type="string" data-message="This field cannot be empty" />
</div>
<div>
<label for="scountry">Country</label>
<select name="scountry" id="scountry" data-type="string" data-message="This field cannot be empty">
<option value="">Select</option>
<option value="De">Denmark</option>
<option value="IN">India</option>
</select>
</div>
</fieldset>
<p><input type="submit" id="submit-order" value="Submit" class="btn" /></p>
</form>
</div>
</div>
<footer id="site-info">
Copyright &copy; maadithottam sachu 2024 <br> Made with &#10084;&#65039; By akash.b azar.N
</footer>
</body>
