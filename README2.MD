<div><br class="Apple-interchange-newline"><!DOCTYPE html>
<html lang="es">
    <style>
        body {
    background-color: wheat; 
}
    </style>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Calculadora</title>
  <style>
    body { display: flex; justify-content: center; align-items: center; height: 40vh; margin: 0; }
    .container { text-align: center; }
    .container input { width: 70px; }

  </style>
</head>
<body>
  <div class="contenedor">
    <h1>Calculadora</h1>
    <input id="numero1" type="number" value="3">
    <span>+</span>
    <input id="numero2" type="number" value="4"><br>
    <button onclick="document.getElementById('resultado').innerText = 'El resultado es: ' + (parseFloat(numero1.value) + parseFloat(numero2.value));">Calcular</button><br>
    <p id="resultado"></p><div id="miRecuadro">
    
    
    </div>

  </div>
</body>
</html></div>
    