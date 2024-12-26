<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Somando Numeros</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Somando Valores</h1>

    

    
    <div id="carlos">Resultado</div>

    <input type="number" name="Numeros" id="Numeros">+

    <input type="number" name="Numeros1" id="Numeros1">

    <input type="button" value="Somar" onclick="somar()" > 

  
    <script src="script.js"></script>
</body>
</html>


function somar() {
    var a = document.getElementById("Numeros");  
    var b = document.getElementById("Numeros1");  
    var c = document.getElementById("carlos");  

    var n1 = Number(a.value);  
    var n2 = Number(b.value);  

    var b = n1 + n2;  

    c.innerHTML = "A soma entre " + n1 + " e " + n2 + " é: <strong>" + b + "</strong>";

}

