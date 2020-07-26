<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Chick Shop</title>
<link rel="stylesheet" href="C:/Users/Public/Documents/css/style.css">
<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
<link href="https://fonts.googleapis.com/css?family=Oxygen:400,300,700" rel="stylesheet" type="text/css">
<a href="style.css"></a>
<style>
body {
	font-size: 16px;
	color: #fff;
	background-color: black;
	font-family: 'Oxygen', sans-serif;
}
#header-nav {
	background-color: purple;
	border-radius: 0;
	border: 0;
}
.navbar-header h1{
	font-weight: bolder;
	color: blue;
	text-shadow: 0px 2px 2px black;
	margin-bottom: 30px;
	position: relative;
}
h2 {
	color: yellow;
	width: auto;
	height: auto;
	overflow: hidden;
	text-shadow: 0px 3px 3px blue;
	position: relative;
}
#nav-list a{
	color: yellow;
	text-align: center;
}
#nav-list a:hover {
	background: black;
}
#nav-list a span{
	font-size: 1.8em;
}
#collapsable-nav a{/*Collapsed nav menu text*/
	font-size: 1.2em;
}
.navbar-collapse.in{
	overflow-y: auto;
}
.collapse.in{
	display: block;
}
#collapsable-nav a span{/*Collapsed nav menu glyph*/
	font-size: 1em;
	margin-right: 5px;
}
.navbar-header
.button.navbar-toggle, .navbar-header .icon-bar{
	border:1px solid yellow;
}
.navbar-header button.navbar-toggle
:hover,.navbar-header .icon-bar:hover {
	background:black;
}
.container {
	margin: auto;
	margin-bottom: 25px;
}
.chicken {
	text-align: center;
}
.Beef {
	text-align: center;
}
.Sushi {
	text-align: center;
}
.chick {
	background-color: grey;
	border: 2px solid yellow;
	overflow: scroll;
	height: 150px;
}
.bee {
	background-color: grey;
	border: 2px solid yellow;
	overflow: scroll;
	height: 150px;
}
.shush {
	background-color: grey;
	border: 2px solid yellow;
	overflow: scroll;
	height: 150px;
}
</style>
</head>
<body>
<header>
	<nav id="header-nav" class="navbar navbar-default">
		<div class="container">
			<div class="navbar-header">
				<h1>Food,LLC</h1>
				<button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#collapsable-nav">
					<span class="sr-only">Toggle navigation</span>
					<span class="icon-bar"></span>
					<span class="icon-bar"></span>
					<span class="icon-bar"></span>
				</button>
			</div>
			<div class="navbar-collapse collapse in" id="collapsable-nav">
				<ul id="nav-list" class="nav navbar-navbar-right">
					<li>
						<a href="#chicken">
							<span class="glyphicon glyphicon-cutlery"></span>
							<br class="hidden-xs">Chicken</a>
					</li>
					<li>
						<a href="#Beef">
							<span class="glyphicon glyphicon-cutlery"></span>
							<br class="hidden-xs">Beef</a>
					</li>
					<li>
						<a href="#Sushi">
							<span class="glyphicon glyphicon-cutlery"></span>
							<br class="hidden-xs">Sushi</a>
					</li>
				</ul><!-- #nav-list -->
			</div>
		</div>
	</nav>
</header>
<div>
	<h2 class="text-center">OUR MENU</h2>
</div>
<div class="container row">
	<div class="col-lg-12 col-md-12 col-sm-12 chick">
		<h3 class="chicken">Chicken</h3>
		<p>But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born and I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. No one rejects, dislikes, or avoids pleasure itself, because it is pleasure, but because those who do not know how to pursue pleasure rationally encounter consequences that are extremely painful. Nor again is there anyone who loves or pursues or desires to obtain pain of itself, because it is pain, but because occasionally circumstances occur in which toil and pain can procure him some great pleasure. To take a trivial example, which of us ever undertakes laborious physical exercise, except to obtain some advantage from it? But who has any right to find fault with a man who chooses to enjoy a pleasure that has no annoying consequences, or one who avoids a pain that produces no resultant pleasure?</p>
	</div>
	<div class="col-lg-6 col-md-6 col-sm-6 bee">
		<h3 class="Beef">Beef</h3>
		<p>But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born and I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. No one rejects, dislikes, or avoids pleasure itself, because it is pleasure, but because those who do not know how to pursue pleasure rationally encounter consequences that are extremely painful. Nor again is there anyone who loves or pursues or desires to obtain pain of itself, because it is pain, but because occasionally circumstances occur in which toil and pain can procure him some great pleasure. To take a trivial example, which of us ever undertakes laborious physical exercise, except to obtain some advantage from it? But who has any right to find fault with a man who chooses to enjoy a pleasure that has no annoying consequences, or one who avoids a pain that produces no resultant pleasure?</p>
	</div>
	<div class="col-lg-6 col-md-6 col-sm-6 shush">
		<h3 class="Sushi">Sushi</h3>
		<p>But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born and I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. No one rejects, dislikes, or avoids pleasure itself, because it is pleasure, but because those who do not know how to pursue pleasure rationally encounter consequences that are extremely painful. Nor again is there anyone who loves or pursues or desires to obtain pain of itself, because it is pain, but because occasionally circumstances occur in which toil and pain can procure him some great pleasure. To take a trivial example, which of us ever undertakes laborious physical exercise, except to obtain some advantage from it? But who has any right to find fault with a man who chooses to enjoy a pleasure that has no annoying consequences, or one who avoids a pain that produces no resultant pleasure?</p>
	</div>
</div>
<script src="https://code.jquery.com/jquery-2.1.4.js" integrity="sha256-siFczlgw4jULnUICcdm9gjQPZkw/YPDqhQ9+nAOScE4=" crossorigin="anonymous"></script>

<script src="<script src="https://code.jquery.com/jquery-2.1.4.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script src="js/script.js"></script>  
</body>
</html>
