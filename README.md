<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Declaring function</title>
    <style>
        body {
            background-color: lightgrey;
        }
        .out {
            color: red;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h2> Function with user-name </h2>
    <p id="demo1" class="out"></p>
    <script>
        let greet=function() {
            return "Hello students. How are you?!!";
        }
        document.getElementById("demo1").innerText = greet();
    </script>
    
</body>
</html>
