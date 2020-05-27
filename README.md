# sample-shopping-cart
<!DOCTYPE html>
<html lang="en">
<head>
<link rel="stylesheet" href=style.css>
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
<link tel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js></script>

<title>Online grocery</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: Arial, Helvetica, sans-serif;
}
</style>
</head>
<body>

<h1>Store</h1>
<p>A website created by me.</p>

<div class="top navbar">
<div class="search box">
<input typetype="text"class="form-control">
<span class="input-group-text"><i class="fa fa-search" aria-hidden="true"></i></span>
</div>
</div>
<div class="menu">
<ul>
<li><a href="#"><i class="fa fa-shopping-basket" aria-hidden="true"></i>cart</a></li>
<li><a href="#">Sign up</a></li>
<li><a href="#">Log in</a></li>
</ul>
</div>
<section class="header">
<div class="side menu">
<ul>
<li>Shampoo<i class="fa fa-angle-right" aria-hidden="true"></i>
<ul>
<li>Arnica shampoo</li>
<li>Dove shampoo</li>
<li>Sunsilk shampoo</li>
</ul>
</li>
<li>Dry fruit<i class="fa fa-angle-right" aria-hidden="true"></i> 
<ul>
<li>Cashewnuts</li>
<li>Almonds</li>
<li>Peanuts</li>
</ul>
</li>
<li>Baby products<i class="fa fa-angle-right" aria-hidden="true"></i>
<ul>
<li>Baby oil</li>
<li>Baby shop</li>
<li>Baby shampoo</li>
</ul>
</li>
<li>Food items<i class="fa fa-angle-right" aria-hidden="true"></i>
<ul>
<li>Sugar</li>
<li>Flour</li>
<li>Salt</li>
</ul>
</li>
</div>
<div class="slider">
<div id="slider" class="carousel slide carousel-fade" data-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="..." class="d-block w-100" alt="Basket">
    </div>
    <div class="carousel-item">
      <img src="..." class="d-block w-100" alt="Shampoo">
    </div>
    <div class="carousel-item">
      <img src="..." class="d-block w-100" alt="Dry fruit">
</div>
  </div>
    <ol class="carousel-indicators">
    <li data-target="#slider" data-slide-to="0" class="active"></li>
    <li data-target="#slider" data-slide-to="1"></li>
    <li data-target="#slider" data-slide-to="2"></li>
  </ol>
</div>
</div>
</section>

<script>
   function open-menu() 
    {document.getElementById=("side-menu").style.display="block";
     document.getElementById=("menu- btn").style.display="none";
     document.getElementById=("close-btn").style.display="block";
}
function close-menu() 
    {document.getElementById=("side-menu").style.display="none";
     document.getElementById=("menu- btn").style.display="block";
     document.getElementById=("close-btn").style.display="none";
}
</script>

<div class="cart">
  <img src="jeans3.jpg" alt="Denim Jeans" style="width:100%">
  <h1>Tailored Jeans</h1>
  <p class="price">$19.99</p>
  <p>Some text about the jeans..</p>
  <p><button>Add to Cart</button></p>
</div>
</body>
</html>









