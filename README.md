<!DOCTYPE html>
<html>
<head>
	<title>Addition</title>
</head>
<script type="text/javascript">
	function add(){
		var x;
		var y;
		x=Number(document.getElementById("first").value);
		y=Number(document.getElementById("second").value);
		z=x + y;
		document.getElementById("answer").value=z;
	}


</script>
<body>
	<input id="first"><br>
	<input id="second"><br>
	<button onclick="add()">OK</button><br>
	<input id="answer">

</body>
</html>
