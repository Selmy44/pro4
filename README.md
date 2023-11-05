# pro4
This project4
<!DOCTYPE html>
<html>
<head>
    <title>Music Platform</title>
    <style>
        /* Inline CSS for demonstration purposes. It's recommended to use external CSS for a real project. */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .music-player {
            text-align: center;
            padding: 20px;
        }
        audio {
            width: 100%;
            max-width: 400px;
            margin: 0 auto;
            display: block;
        }
        .control-buttons {
            margin-top: 20px;
        }
        button {
            font-size: 16px;
            padding: 10px 20px;
            background-color: #007BFF;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>My Music Platform</h1>
        <div class="music-player">
            <audio controls>
                <source src="your-audio-file.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
            <div class="control-buttons">
                <button onclick="playAudio()">Play</button>
                <button onclick="pauseAudio()">Pause</button>
            </div>
        </div>
    </div>

    <script>
        // JavaScript for controlling the audio element
        const audioElement = document.querySelector('audio');

        function playAudio() {
            audioElement.play();
        }

        function pauseAudio() {
            audioElement.pause();
        }
    </script>
</body>
</html>
