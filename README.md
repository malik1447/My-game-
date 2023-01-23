<!DOCTYPE html>

<html>

<head>

  <meta charset="UTF-8">

  <meta name="viewport" content="width=device-width, initial-scale=1">

	<title>Snake Game</title>

	<link rel="stylesheet" href="style.css">

</head>

<body>

	<div id="game-container">

		<canvas id="gc" class="game-canvas" width="400" height="400"></canvas>

	</div>

	<div class="keys">

	  <a class="up arr" onclick="Snake.action('up')">

	    <i class="chevron up"></i></a>

	  <br />

	  <a class="left arr" onclick="Snake.action('left')">

	    <i class="chevron left"></i></a>

	  <a class="down arr" onclick="Snake.action('down')">

	    <i class="chevron down"></i></a>

	  <a class="right arr" onclick="Snake.action('right')">

	    <i class="chevron right"></i></a>

	</div>

	<script type="text/javascript" src="game.js"></script>

</body>

</html>

