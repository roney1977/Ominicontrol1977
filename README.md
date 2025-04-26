<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Imagen Bailando</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #f0f0f0;
    }

    .bailarina {
      width: 300px;
      animation: bailar 2s infinite ease-in-out;
    }

    @keyframes bailar {
      0% { transform: rotate(0deg) translateY(0); }
      25% { transform: rotate(5deg) translateY(-10px); }
      50% { transform: rotate(0deg) translateY(0); }
      75% { transform: rotate(-5deg) translateY(-10px); }
      100% { transform: rotate(0deg) translateY(0); }
    }
  </style>
</head>
<body>
  <img src="tu-imagen.png" alt="Bailarina" class="bailarina">
</body>
</html>
