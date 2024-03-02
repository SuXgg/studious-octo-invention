<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>WikiBrum - Página de Vehículos</title>
<style>
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    overflow: hidden;
  }

  .image {
    animation: slide 5s infinite alternate;
    transition: filter 0.5s ease;
  }

  .image:hover {
    filter: blur(3px);
  }

  .info {
    position: absolute;
    background: rgba(255, 255, 255, 0.8);
    padding: 10px;
    border-radius: 5px;
    display: none;
  }

  .image:hover + .info {
    display: block;
  }

  .logo {
    position: fixed;
    top: 10px;
    left: 10px;
    width: 100px;
    height: auto;
  }
</style>
</head>
<body>

<img class="logo" src="mustang_logo.png" alt="Logo Mustang">

<div class="container">
  <div>
    <img class="image" src="imagen1.jpg" alt="Vehículo 1" width="300">
    <div class="info">Información del vehículo 1</div>
  </div>
  <div>
    <img class="image" src="imagen2.jpg" alt="Vehículo 2" width="300">
    <div class="info">Información del vehículo 2</div>
  </div>
  <div>
    <img class="image" src="imagen3.jpg" alt="Vehículo 3" width="300">
    <div class="info">Información del vehículo 3</div>
  </div>
</div>

</body>
</html>
