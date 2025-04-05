# Hello
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Моя первая страница</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 40px;
      background-color: #f0f0f0;
    }

    h1 {
      color: #333;
    }

    button {
      padding: 10px 20px;
      font-size: 16px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    button:hover {
      background-color: #45a049;
    }

    #output {
      margin-top: 20px;
      font-size: 18px;
      color: #555;
    }
  </style>
</head>
<body>

  <h1>Привет, Саша!</h1>
  <p>Нажми на кнопку ниже:</p>
  <button onclick="showMessage()">Кликни меня</button>

  <p id="output"></p>

  <script>
    function showMessage() {
      document.getElementById('output').innerText = 'Жопа!)';
    }
  </script>

</body>
</html>
