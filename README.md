<html lang="en-us">
	<head>
		ryan happens to be very silly
	</head>
 	<body>
		<canvas id="stage" width="600" height="600"></canvas>
		<script type="text/javascript">
			window.onload = document.getElementById("game")	
		</script>
		  <div id="1">1</div>
		<script type="text/javascript">
		var game = document.getElementById ("1") ;
		var game = 0 ;
		var onClick = function( e ) {
 		   console.log('game was ', game);
		    game = 1 ;
		    console.log('Now game = ' , game);
		}
		game.onclick = onClick ;
		</script>
		  <div id="2">2</div>
		<script type="text/javascript">
		var game = document.getElementById ("2") ;
		var game = 0 ;
		var onClick = function( e ) {
 		   console.log('game was ', game);
		    game = 2 ;
		    console.log('Now game = ' , game);
		}
		game.onclick = onClick ;
		</script>
  		  <div id="3">3</div>
		<script type="text/javascript">
		var game = document.getElementById ("3") ;
		var game = 0 ;
		var onClick = function( e ) {
 		   console.log('game was ', game);
		    game = 3 ;
		    console.log('Now game = ' , game);
		}

		game.onclick = onClick ;
		</script>
  	</body>
