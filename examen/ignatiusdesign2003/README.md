examen

para este examen me basare en la entrga de la solemne 2, donde mejorare aspectos del java script en los que elementos como la barra para ingresar caracteres y que cuando se haga click pase algo y nos redirija a otra ventana nueva, dejo aqui su codigo:

<!DOCTYPE html>
<html>
<head>
<script>
function confirmInput() {
  fname = document.forms[0].fname.value;
  alert("Hello " + fname + "! You will now be redirected to www.w3Schools.com");
}
</script>
</head>
<body>

<form onsubmit="confirmInput()" action="https://www.w3schools.com/">
  Enter your name: <input id="fname" type="text" size="20">
  <input type="submit">
</form>

</body>
</html>

