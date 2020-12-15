//fibonacci.html

<!DOCTYPE HTML>
<?xml version="1.0" encoding="UTF-8"?>
<html>
<head>
<title> fibonacci.html </title>
</head>
<body style="background-color:rgb(128, 126, 0)"> <!-- it is advised to not use inline styling -->
<h3 style="text-align:center; color:rgba(255, 255, 255, 0.479)"> Fibonacci Sequence </h3>
<script type="text/javascript">

var limit = prompt("Enter the limit 'n' to generate the fibonacci sequence :", " ");
var f1=0;
var f2=1;

document.write("The limit entered to generate the fibonacci sequence is: ",limit, "<br/>");
document.write("The fibonacci sequence : ");
document.write("",f1," ");
document.write("",f2," ");
 
var i,f3;
for(i=1; i<limit; i++)
{
	 f3=f1+f2;
	 document.write("",f3," ");
	 f1=f2;
	 f2=f3;
}

</script>
</body>
</html>
