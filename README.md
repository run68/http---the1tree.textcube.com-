<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
		<style>
			#two {
				background-color: red;
				display: none;
				width: 100px;
				height: 100px;
			}
			#one {
				background-color: #000;
				display: block;
				width: 100px;
				height: 100px;
			}
		</style>
	<title>Document</title>
</head>
<body>
  <div id="two"></div>
  <div id="one"></div>
  <p>아놔 </p>
  <button id="hide">hide</button>
  <button id="show">show</button>
<script>
	$(document).ready(function() {
		$("#hide").click(function() {
			$("p").hide();
		});
		$("#show").click(function() {
			$("p").show();
		});
	});
</script>
</body>
</html>
