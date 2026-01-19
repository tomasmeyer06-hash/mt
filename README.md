<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>¿Me perdonas clara ? 💖</title>
  <style>
    body {
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      font-family: 'Arial', sans-serif;
      text-align: center;
      height: 100vh;
      margin: 0;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .card {
      background: white;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.2);
      width: 300px;
    }

    h1 {
      color: #ff4d6d;
    }

    #mensaje {
      margin: 20px 0;
      font-size: 18px;
      min-height: 60px;
    }

    button {
      background: #ff4d6d;
      color: white;
      border: none;
      padding: 15px 25px;
      font-size: 16px;
      border-radius: 30px;
      cursor: pointer;
      transition: transform 0.2s, background 0.2s;
    }

    button:hover {
      background: #e63950;
      transform: scale(1.05);
    }
  </style>
</head>
<body>

<div class="card">
  <h1>¿Me perdonas clara ? 🥺💖</h1>
  <p id="mensaje">Toca el botón...</p>
  <button onclick="mostrarFrase()">Perdóname 💕</button>
</div>

<script>
  const frases = [
    "Lo siento mucho, clara 😔",
    "Prometo hacerlo mejor 💕",
    "No quiero pelear contigo nena< 🥺",
    "Eres lo mejor que me pasó 💖",
    "Mi mundo es mejor contigo 🌍❤️",
    "Te amo más de lo que puedo explicar 😘",
    "¿Me das otra oportunidad? 🙏💞",
    "Sin ti todo es más triste 😢",
    "Prometo sacarte una sonrisa hoy 😊",
    "Perdóname, corazón 💓"
  ];

  function mostrarFrase() {
    const random = Math.floor(Math.random() * frases.length);
    document.getElementById("mensaje").textContent = frases[random];
  }
</script>

</body>
</html>
