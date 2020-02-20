<html>
  <head>
    <title> Tetris!</title>
    <style>
      body {
        background: #202028;
        color: #fff;
        font-family: sans-serif;
        font-size: 2em;
        text-align: center;
      }
      canvas {
        border: solid .2em #fff;
        height: 90vh;
      }
    </style>
  </head>
  <body>
    <span> Score: <div id="score"></div> Controls: Q/W to spin</span>
    <canvas id="tetris" width="240" height="400"></canvas>
    <script src="tetris.js"></script>
  </body>
</html>