<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Preparing Download...</title>
  <style>
    body {
      background-color: black;
      color: gold;
      text-align: center;
      font-family: sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .loader {
      border: 6px solid #333;
      border-top: 6px solid gold;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      animation: spin 1s linear infinite;
      margin-bottom: 20px;
    }
    @keyframes spin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }
  </style>
</head>
<body>
  <div class="loader"></div>
  <h2>Preparing your download...</h2>
  <p>If it doesn’t start automatically, <a href="https://gofile.io/d/v9ThCj" style="color: gold;">click here</a>.</p>

  <script>
    setTimeout(function() {
      window.open("https://gofile.io/d/v9ThCj", "_blank");
    }, 2000); // 2 seconds delay before opening
  </script>
</body>
</html>
