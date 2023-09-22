<html lang="en-us">
	<head>
		ryan happens to be very silly
	</head>
 	<body>
		  <div id="1">1</div>
		<script type="text/javascript">
		var game = document.getElementById ("game") ;

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
		var game = document.getElementById ("game") ;

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
		var game = document.getElementById ("game") ;

		var game = 0 ;
		var onClick = function( e ) {
 		   console.log('game was ', game);
		    game = 3 ;
		    console.log('Now game = ' , game);
		}

		game.onclick = onClick ;
		</script>
  	</body>
