<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Waves Effects</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="container">
    <h1>Escucha Música Relajante</h1>
    <audio id="audioPlayer" controls>
        <source src=""simply-meditation-series-11hz-alpha-binaural-waves-for-relaxed-focus-8028.mp3 type="audio/mp3">
        Tu navegador no soporta el elemento de audio.
    </audio>
    <div class="timer">
        <label for="timerInput">Establecer temporizador (minutos):</label>
        <input type="number" id="timerInput" min="30" placeholder="Ejemplo: 15">
        <button onclick="startTimer()">Iniciar Temporizador</button>
    </div>
</div>
<script src="script.js"></script>
</body>
</html>
