# Fitness-app
# index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First App</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Welcome to My First App</h1>
    <p>This is my first web app created using GitHub!</p>
    <button id="clickButton">Click Me</button>

    <script src="script.js"></script>
</body>
</html>

# style.css
body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

h1 {
    color: #333;
}

button {
    padding: 10px 20px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}

# script.js
document.getElementById("clickButton").addEventListener("click", function() {
    alert("You clicked the button!");
});
