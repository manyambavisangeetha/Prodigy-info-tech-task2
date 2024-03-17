
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Stopwatch</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <h1 class="heading">
      <a href="index.html">Stopwatch</a>
    </h1>
    <div class="container">
      <div class="timer-display">
        00 : 00 : 00 : 000
      </div>
      <div class="buttons">
        <button id="start-timer">Start</button>
        <button id="pause-timer">Pause</button>
        <button id="reset-timer">Reset</button>
        <button id="lap-timer" class="timer-button">Lap</button>
      </div>
    </div>
    <h2 class="lap-list lap-label">Laps</h2>
    <ul class="lap-list" id="lap-list"></ul>
    <script src="./index.js"></script>
  </body>
</html>
