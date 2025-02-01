<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>¿Quieres ser mi novia?</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to bottom right, #ff9a9e, #fad0c4);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      color: #333;
      text-align: center;
    }
    .container {
      background: rgba(255, 255, 255, 0.8);
      padding: 40px;
      border-radius: 15px;
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }
    .buttons {
      margin-top: 20px;
    }
    .button {
      background: #ff6f61;
      border: none;
      color: white;
      padding: 10px 20px;
      margin: 10px;
      font-size: 1rem;
      border-radius: 25px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .button:hover {
      background: #ff4b4b;
    }
    .button.no:hover {
      background: #999;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>¿Quieres ser mi novia?</h1>
    <div class="buttons">
      <button class="button yes" onclick="alert('¡Sabía que dirías que sí! 💖')">Sí</button>
      <button class="button no" onclick="alert('No hay problema, lo intenté. 😊')">No</button>
    </div>
  </div>
</body>
</html>
