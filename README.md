<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Frontend Page</title>
    <style>
        /* Basic CSS styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: white;
            padding: 1em;
            text-align: center;
        }

        main {
            padding: 2em;
        }

        button {
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 4px;
        }

        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Basic Frontend</h1>
    </header>

    <main>
        <p>This is a simple HTML page with some CSS styling and JavaScript functionality.</p>
        <button onclick="showMessage()">Click Me</button>
        <p id="message"></p>
    </main>

    <script>
        // Basic JavaScript functionality
        function showMessage() {
            document.getElementById("message").textContent = "Hello! You clicked the button.";
        }
    </script>

</body>
</html>
