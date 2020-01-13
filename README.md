<!DOCTYPE html>
<html>
<head>
	<title>Navbars</title>
</head>

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
	<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.9.0/css/all.css" integrity="sha384-i1LQnF23gykqWXg6jxC2ZbCbUMxyw5gLZY6UiUS98LYV5unm8GWmfkIS6jqJfb4E" crossorigin="anonymous">
	<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Allerta+Stencil">
<style type="text/css">
.one{
margin-left: 1rem;
}
#two{

	text-align: center;
	font-family: "Allerta Stencil", Sans-serif;
	letter-spacing: 7px;
	background-image: url(https://images.unsplash.com/photo-1536566482680-fca31930a0bd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=334&q=80);
	}
	#three{
text-align: center;
font-family: 'Share Tech Mono', monospace;
    font-size: 25px;
        background-color: lightsteelblue;
        color: black;

	}
	#four{
height: 350px;

	}
	#five{
margin-bottom: 3rem;
	}
	#six{
text-align: center;

	}

</style>

<body>
	<div class="container">

<nav class="navbar navbar-expand-sm navbar-light bg-light">
	<a href="" class="navbar-brand"><i class="fas fa-hiking"></i><span class="one">  MOUNTAIN  </span></a>
	<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navOne" aria-controls="navOne" aria-label="Toggle navigation" aira-expand="false" >
		<span class="navbar-toggler-icon"></span>
		
	</button>
	<div class="container">
<div class="collapse navbar-collapse" id="#navOne">
	<ul class="navbar-nav">
		<li><a href="" class="nav-item nav-link active">Home</a></li>
		<li><a href=""class="nav-item nav-link">Services</a></li>
		<li><a href=""class="nav-item nav-link">About</a></li>
	</ul>
	</div>
	<ul class="navbar-nav navbar-right">
	<div class="collapse navbar-collapse" id="#navOne">
	
		<li><a href="" class="nav-item nav-link active">Login</a></li>
		<li><a href=""class="nav-item nav-link active">Signup</a></li>
	</div>
		<li><a href="#" class="nav-item nav-link dropdown dropdown-toggle" role="button" id="dropIT" data-toggle="dropdown" aria-haspopup="true" aria-expand="true"><span id="six"> DropMe</span></a>
		<div class="dropdown">
		<div class="dropdown-menu" ariaLabelledBy="dropIT"> 
		 <a class="dropdown-item" href="">History</a> 
		<a class="dropdown-item" href="">Article</a>
		<a class="dropdown-item" href="">Note</a>
		</div>
	</div>	
	</li>
</ul>
</div>
</nav>
</div>

<div class="jumbotron display-4" id="two">
	<p>Into Thin Air</p>
	<h6>Explore - Everest</h6>
</div>
<div class="container">

<div class="row">

	<div class="col-lg-3  col-md-6 ">
	<div class="card" id="five"> 
		<div class="car-head">
			<a href="https://en.wikipedia.org/wiki/Mountain" target="blank"> <p id="three"><i class="fas fa-globe-africa"></i>Rainer</p></a>
			<div class="card-body"id="four">
				<p>Training starts the very first day and continues throughout each program. We choose to teach many skills up on the mountain rather than at the base prior to the climb. We feel this provides more realistic training conditions so you start out better prepared on summit day.

</p>
			</div>
		</div>
	</div>
</div>
	<div class="col-lg-3 col-md-6 ">
	<div class="card"  id="five">
		<div class="car-head" >
			<a href="https://en.wikipedia.org/wiki/Mountain" target="blank"><p id="three"><i class="fas fa-globe-africa"></i>Alps</p>
	</a>		<div class="card-body"id="four">
				<p>The Alps are the highest and most extensive mountain range system that lies entirely in Europe, separating Southern from Central and Western Europe and stretching approximately 1,200 kilometres across eight.
				</p>
			</div>
		</div>
	</div>
</div>


	<div class="col-lg-3 col-md-6 ">
	<div class="card" id="five">
		<div class="car-head">
			<a href="https://en.wikipedia.org/wiki/Mountain" target="blank"> <p id="three"><i class="fas fa-globe-africa"></i>Albert</p></a>
			<div class="card-body"id="four" >
				<p>Albert Mountain is a mountain in North Carolina's Nantahala Range of the Appalachian Mountains. The Appalachian Trail goes along its summit, which is around 5,200 feet high. A fire tower offers views of the Blue Ridge and the Little Tennessee River valley</p>
			</div>
		</div>
	</div>
</div>


	<div class="col-lg-3 col-md-6 ">
	<div class="card" id="five">
		<div class="car-head">
			<a href="https://en.wikipedia.org/wiki/Mountain" target="blank"> <p id="three"><i class="fas fa-globe-africa"></i>Alaska</p></a>
			<div class="card-body"id="four">
				<p>Alaska is a U.S. state in the northwest extremity of the United States West Coast, just across the Bering Strait from Asia. The Canadian province of British Columbia and territory of Yukon border the state to the east and southeast</p>
			</div>
		</div>
	</div>
</div>
</div>
</div>
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
</body>
</html>
