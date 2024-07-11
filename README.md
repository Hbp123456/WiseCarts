<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Senior Shopping Assistant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Senior Shopping Assistant</h1>
    <div class="container">
        <button id="startRecording">Start Recording</button>
        <button id="stopRecording" disabled>Stop Recording</button>
    </div>
    <audio id="audioElement" controls style="display: none;"></audio>
    <button id="uploadButton" disabled>Upload Audio</button>

    <script src="script.js"></script>
    <script src="https://smtpjs.com/v3/smtp.js"></script>
</body>
</html>

