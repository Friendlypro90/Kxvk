<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Botón centrado y grande</title>
  <style>
    /* Centrar todo el contenido vertical y horizontalmente */
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh; /* altura completa de la ventana */
      margin: 0;
      background-color: #black;
    }

    /* Estilo para el botón */
    button {
      padding: 20px 40px;
      font-size: 24px;
      cursor: pointer;
      border: none;
      border-radius: 10px;
      background-color: #red;
      color: yellow;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>
  <button id="btn" onclick="playAudio()">puchale aca</button>

  <audio id="audio">
    <source src="sonido.mp3" type="audio/mpeg" />
    Tu navegador no soporta audio.
  </audio>

  <script>
    function playAudio() {
      var audio = document.getElementById('audio');
      audio.play();
      document.getElementById('btn').disabled = true;
    }
  </script>
</body>
</html>
