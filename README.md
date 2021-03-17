<!DOCTYPE html>
<html>
    <head>
        <title>Weather forecast</title>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/css/bootstrap.min.css" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap" rel="stylesheet">
        <link href = "styles.css" rel = "stylesheet">
    </head>
    <body>
        <h1>Weather forecasting</h1>
            <div class = "jumbotron text-center">
                <span>Enter city name: </span><input type = "text" id = "city" autocomplete = "off"><br><br>
                <button class = "btn-primary" onclick = "getWeather()">Get Weather</button>
            </div>
            <div id = "result"></div>
            <table id = "table">
                <tr>
                    <td>
                        <canvas id = "myChart" width = "400" height = "400"></canvas>
                    </td>
                </tr>
            </table>
            <div id = "time"></div>
            <div class = "end">
                <p class = "foo">Source: https://openweathermap.org</p>
            </div>
    </body>
    <script src = "weather.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js@2.9.4/dist/Chart.min.js"></script>
</html>
