<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Stock Navigation</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f7fb;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .container {
      text-align: center;
    }

    h1 {
      margin-bottom: 30px;
      color: #333;
    }

    .btn {
      display: block;
      width: 250px;
      margin: 15px auto;
      padding: 15px;
      font-size: 18px;
      font-weight: bold;
      color: white;
      background: #4CAF50;
      border: none;
      border-radius: 12px;
      cursor: pointer;
      transition: 0.3s;
      text-decoration: none;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }

    .btn:hover {
      background: #388e3c;
      transform: scale(1.05);
    }

    .btn-secondary {
      background: #2196F3;
    }

    .btn-secondary:hover {
      background: #1565c0;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Select Stock Report</h1>
    <a href="https://ireshdudde.github.io/21SepColdStorage/" target="_blank" class="btn">Cold Storage Balance Stock</a>
    <a href="https://ireshdudde.github.io/21Sep-GodownStock/" target="_blank" class="btn btn-secondary">Godown Stock Details</a>
  </div>
</body>
</html>
