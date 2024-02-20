<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Waves Effects</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="container">
    <h1>Waves Effects</h1>
    <audio id="audioPlayer" controls>
        <source src=<source src="simply-meditation-series-11hz-alpha-binaural-waves-for-relaxed-focus-8028.mp3" type="audio/mp3">
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

/* style.css */
body, html {
    height: 100%;
    margin: 0;
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #f3f4f6;
}

.container {
    text-align: center;
}

.timer {
    margin-top: 20px;
}


// script.js
function startTimer() {
    var minutes = document.getElementById('timerInput').value;
    var duration = minutes * 60 * 1000; // Convertir minutos a milisegundos
    setTimeout(function() {
        document.getElementById('audioPlayer').pause(); // Pausar la música
        alert("Tiempo terminado");
    }, duration);
    document.getElementById('audioPlayer').play(); // Iniciar la reproducción de música
}
