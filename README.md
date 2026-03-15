<!DOCTYPE html>
<html>
<head>
<title>Local Service App</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<h1>Welcome to Our App</h1>
<p>Van Booking / Local Services</p>
</header>

<section class="icons">

<div class="icon">🚚<p>Transport</p></div>
<div class="icon">👨‍🌾<p>Farmer</p></div>
<div class="icon">🧑‍🔧<p>Worker</p></div>
<div class="icon">🏠<p>Local Help</p></div>

</section>

<h2>Buy / Services</h2>

<section class="cards">

<div class="card">
<img src="https://via.placeholder.com/150">
<p>Service 1</p>
</div>

<div class="card">
<img src="https://via.placeholder.com/150">
<p>Service 2</p>
</div>

<div class="card">
<img src="https://via.placeholder.com/150">
<p>Service 3</p>
</div>

</section>

<footer>
<p>Local Area Services</p>
</footer>

</body>
</html><!DOCTYPE html>
<html>
<head>
<title>Local Service Website</title>
</head>

<body>

<h1>Welcome to My Website</h1>
<p>This is my first local service booking website.</p>

</body>
</html>
body{
font-family: Arial;
text-align:center;
margin:0;
}

header{
background:#2c7be5;
color:white;
padding:20px;
}

.icons{
display:flex;
justify-content:center;
gap:20px;
margin:20px;
}

.icon{
background:#eee;
padding:10px;
border-radius:50%;
width:80px;
height:80px;
}

.cards{
display:flex;
justify-content:center;
gap:20px;
}

.card{
border:1px solid #ccc;
padding:10px;
width:150px;
}

footer{
margin-top:30px;
padding:10px;
background:#eee;
}
