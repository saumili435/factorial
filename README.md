# factorial
html>
body>

h2>Factorial/h2>

p id="demo">/p>
script>
function myFunction(var a)
if(a==1)
{
	return 1;
}
else
{
	return(a*myFunction(--a));
}
function main(var n)
if(n>0)
document.getElementById("demo").innerHTML="The Factorial is :" + "main (n)";
/script>

/body>
/html>

