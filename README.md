<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Audio Dictionary</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Audio Dictionary</h1>
    <input type="file" id="jsonFile" accept=".json">
    <button id="loadWords">Load Words</button>
    <div id="wordContainer"></div>
    <button id="startRecording">Start Recording</button>
    <button id="stopRecording" disabled>Stop Recording</button>
    <ul id="wordList"></ul>

    <script src="script.js"></script>
<style>
    .body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin: 0;
    padding: 20px;
}

.wordContainer {
    margin-top: 20px;
}

.wordList {
    list-style-type: none;
    padding: 0;
}

.li {
    margin: 10px 0;
}
</style>
    
    
</body>
</html>
