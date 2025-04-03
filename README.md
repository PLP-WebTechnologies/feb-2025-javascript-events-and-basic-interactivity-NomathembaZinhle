# feb-2025-avasjcript-events-and-basic-interactivity
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript Events and Interactivity</title>
    <style>
        #message {
            color: blue;
        }
        #toggleButton {
            background-color: lightblue;
            padding: 10px;
            border: none;
            cursor: pointer;
        }
        #toggleButton:hover {
            background-color: lightcoral;
        }
    </style>
</head>
<body>

<h1>Interactive JavaScript Page</h1>

<!-- Button to toggle text change -->
<button id="toggleButton">Click to Change Text</button>

<p id="message">Original Text</p>

<!-- Form to check for empty field -->
<form id="myForm">
    <label for="username">Username:</label>
    <input type="text" id="username" name="username">
    <button type="submit">Submit</button>
</form>

<script src="script.js"></script>
</body>
</html>
