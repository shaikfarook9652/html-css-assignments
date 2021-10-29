# html-css-assignments
hi my name is shaik mahammad farook this is my module 2 assigment repositary
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Mod 2 assignment</title>
	<style>
	*{
		box-sizing: border-box;
		margin: 0;
		padding: 0;
	}
	body{
		margin: 0;
		padding: 0;
	}
	section{
		clear: right;
	}
	h1 {
		margin-bottom: 30px;
		text-align: center;
	}
	#container{
		position: relative;
	}
	#p1{
		float: right;
		background-color: red;
		width: 90px;
	}
	#p2{
		float: right;
		background-color: yellow;
		width: 90px;
	}
	#p3{
		float: right;
		background-color: lightsalmon;
		width: 90px;
	}
	#chicken{
		background-color:grey;
		margin: 20px;
		position: relative;
	}
	#beef{
		background-color: wheat;
		margin: 20px;
		position: relative;
	}
	#sushi{
		background-color: lightblue;
		margin: 20px;
		position: relative;
	}
	/********** Large devices only **********/
	@media (min-width: 992px) {
  	#chicken {
   		width: 33%;
   		
  	}
  	#beef{
    	width: 33%;
    	
  	}
  	#sushi{
  		width: 33%;
  		
  	}
	}


/********** Medium devices only **********/
	@media (min-width: 768px) and (max-width: 991px) {
  	#chicken {
    	width: 50%;
  	}
  	#beef{
    	width: 50%;
  	}
  	#sushi {
    	width: 100%;
 	 }


</style>
</head>
<body>
	<h1>Story</h1>
	<div id="container">
	 	<div id="chicken">
	 		<p id="p1">chicken</p>
	 		<section>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</section>
	 	</div>
	  	<div id="beef">
	  		<p id="p2">beef</p>
	  		<section>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.
</section>
	  	</div>
	  	<div id="sushi">
	  		<p id="p3">sushi</p>
	  		<section>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</section>
	  		shaik mahammad farook
	  	</div>
	</div>
</body>
</html>
