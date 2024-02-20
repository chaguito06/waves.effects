<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Música Relajante</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="container">
    <h1>Escucha Música Relajante</h1>
    <audio id="audioPlayer" controls>
        <source src="tu_musica_relajante.mp3" type="audio/mp3">
        Tu navegador no soporta el elemento de audio.
    </audio>
    <div class="timer">
        <label for="timerInput">Establecer temporizador (minutos):</label>
        <input type="number" id="timerInput" min="1" placeholder="Ejemplo: 15">
        <button onclick="startTimer()">Iniciar Temporizador</button>
    </div>
</div>
<script src="script.js"></script>
</body>
</html>
