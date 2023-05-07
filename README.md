<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Converter Celsius to Fahrenheit" />
    <meta name="keywords" content="converter, calculator, celsius, fahrenheit" />
    <meta name="author" content="Piotr Maliga" />
    <title>Temperature Converter</title>
    <main>Temperature Converter</main>

    <link href="style.css" rel="stylesheet">

    <link rel="preconcert" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">


    <script src="script.js" defer></script>
</head>

<body background="temp.jpg">
    
    <header>
        <label for="converter">Conversion of <span class="C">°C</span> to <span class="F">°F</span></label>
    </header>

    <div>
        <input type="text" id="converter" placeholder="°C">
    </div>

    <p class="result"></p>

    <div id="buttons">
        <button class="convertButton">Convert</button>
        <button class="resetButton">Reset</button>
        <button class="changeButton">Change</button>
    </div>
</body>

</html>
