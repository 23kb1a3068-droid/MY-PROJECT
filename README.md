<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript Linked Example</title>
</head>
<body>
    <h1>JavaScript Linked to HTML</h1>
    <p id="demo">This text will be changed by JavaScript.</p>
    <button onclick="changeText()">Click Me!</button>

    <!-- Linking the external JavaScript file with defer to ensure it loads after HTML -->
    <script defer src="script.js"></script>
</body>
</html>
