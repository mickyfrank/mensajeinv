<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invitación</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0e68c;
            margin: 0;
            font-family: Arial, sans-serif;
            text-align: center;
            overflow: hidden;
            flex-direction: column;
        }
        .container, .final-message, .intro {
            display: none;
            flex-direction: column;
            align-items: center;
            z-index: 1;
            padding: 10px;
            max-width: 90vw;
        }
        .message {
            font-size: 4vw;
            margin-bottom: 5vh;
            word-wrap: break-word;
        }
        .image-container img {
            width: 50vw;
            max-width: 1200px;
            margin-bottom: 5vh;
        }
        .button, .choice-button {
            padding: 2vh 5vw;
            font-size: 4vw;
            background-color: #ffeb3b;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin: 2vh;
            z-index: 1;
        }
        .fireworks {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('fireworks.gif') no-repeat center center;
            background-size: cover;
            z-index: 2;
        }
        .final-message {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            font-size: 6vw;
            z-index: 3;
            padding: 20px;
            box-sizing: border-box;
        }
        .doubts-button {
            padding: 2vh 5vw;
            font-size: 4vw;
            background-color: #ffeb3b;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 3vh;
        }
        .intro {
            display: flex;
            font-size: 4vw; /* Ajuste del tamaño de la fuente */
            animation: fadeInOut 5s ease-in-out;
            position: absolute;
            top: 10%;
            width: 100%;
        }
        @keyframes fadeInOut {
            0%, 100% { opacity: 0; }
            50% { opacity: 1; }
        }
    </style>
</head>
<body>

    <!-- Música de fondo -->
    <audio id="backgroundMusic" loop>
        <source src="musica.mp3" type="audio/mp3">
        Tu navegador no soporta el elemento de audio.
    </audio>

    <!-- Mensaje de introducción -->
    <div class="intro" id="introMessage">
        Hola, tengo algo especial para decirte...
    </div>

    <!-- Botón para iniciar la invitación -->
    <button class="button" id="startButton">Toca la pantalla Yohis, Leona...</button>

    <!-- Contenedor de invitación -->
    <div class="container" id="invitationContainer">
        <div class="message">¿Quieres salir conmigo este domingo 18 de agosto 2024?</div>
        <div class="image-container">
            <img src="girasol.jpg" alt="Girasol">
        </div>
        <button class="choice-button" id="yesButton" onclick="showFireworksAndConfetti()">Sí :)</button>
        <button class="choice-button" id="noButton" onclick="disableNoButton()">No :(</button>
    </div>

    <!-- Efecto de fuegos artificiales -->
    <div class="fireworks" id="fireworks"></div>

    <!-- Mensaje final -->
    <div class="final-message" id="finalMessage">
        <div>Gracias por existir, Escucha :3</div>
        <button class="doubts-button" onclick="resetToInitial()">¿DUDAS?</button>
    </div>

    <!-- Script de Confetti -->
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.5.1/dist/confetti.browser.min.js"></script>

    <script>
        // Mostrar la invitación después de 3 segundos del mensaje de introducción
        document.getElementById('startButton').addEventListener('click', function() {
            var music = document.getElementById('backgroundMusic');
            music.play().catch(function(error) {
                console.log("El usuario debe interactuar primero para que se reproduzca el audio.");
            });

            document.getElementById('introMessage').style.display = 'flex';
            setTimeout(function() {
                document.getElementById('introMessage').style.display = 'none';
                document.getElementById('invitationContainer').style.display = 'flex';
                document.getElementById('startButton').style.display = 'none';
            }, 1000); // Duración del mensaje de introducción
        });

        function showFireworksAndConfetti() {
            document.getElementById('fireworks').style.display = 'block';
            document.getElementById('noButton').disabled = true;
            document.getElementById('noButton').style.opacity = '0.5';

            // Lanzar confeti
            confetti({
                particleCount: 200,
                spread: 160,
                origin: { y: 0.6 },
            });

            setTimeout(showFinalMessage, 5000);
        }

        function showFinalMessage() {
            document.getElementById('fireworks').style.display = 'none';
            document.getElementById('finalMessage').style.display = 'flex';
        }

        function resetToInitial() {
            document.getElementById('finalMessage').style.display = 'none';
            document.getElementById('invitationContainer').style.display = 'flex';
            document.getElementById('noButton').disabled = false;
            document.getElementById('noButton').style.opacity = '1';

            // Reiniciar la música
            let music = document.getElementById('backgroundMusic');
            music.pause();
            music.currentTime = 0;
            music.play();
        }

        function disableNoButton() {
            alert("NO, NO ES UNA OPCION, QUE TU PUEDAS ELEGIR :)");
            document.getElementById('noButton').disabled = true;
            document.getElementById('noButton').style.opacity = '0.5';
        }
    </script>

</body>
</html>