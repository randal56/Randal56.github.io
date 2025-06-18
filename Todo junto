<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mi Proyecto Web</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    header {
      background-color: #4CAF50;
      color: white;
      padding: 20px;
    }
    nav {
      margin: 20px;
    }
    button {
      margin: 8px;
      padding: 10px 20px;
      font-size: 16px;
      background-color: #2196F3;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }
    button:hover {
      background-color: #0b7dda;
    }
    .contenido {
      display: none;
      background-color: white;
      margin: 20px auto;
      padding: 20px;
      border-radius: 10px;
      max-width: 850px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    iframe, img {
      max-width: 100%;
    }
  </style>
</head>
<body>

<header>
  <h1>Mi Proyecto Integrado</h1>
</header>

<nav>
  <button onclick="mostrarContenido('codigo1')">Código 1</button>
  <button onclick="mostrarContenido('codigo2')">Código 2</button>
  <button onclick="mostrarContenido('codigo3')">Código 3</button>
  <button onclick="mostrarContenido('codigo4')">Código 4</button>
  <button onclick="location.reload()">🔄 Refrescar</button>
</nav>

<div id="codigo1" class="contenido">
  <h2>Integral Definida</h2>
  <p>Explicación sobre cómo resolver una integral definida paso a paso.</p>
  <iframe src="https://vt.tiktok.com/ZSkgB3m7M/" width="360" height="640"></iframe>
</div>

<div id="codigo2" class="contenido">
  <h2>Identidad Mexicana según Samuel Ramos</h2>
  <p>Reflexión sobre la identidad del mexicano. Haz clic abajo para ver el video.</p>
  <a href="https://vt.tiktok.com/ZSkgM8U8o/" target="_blank">Ver video en TikTok</a>
</div>

<div id="codigo3" class="contenido">
  <h2>Derecho</h2>
  <img src="/storage/emulated/0/Pictures/WhatsApp/IMG-20250617-WA0005(1).jpg" alt="Imagen 1">
  <img src="/storage/emulated/0/Pictures/WhatsApp/IMG-20250617-WA0004(1).jpg" alt="Imagen 2"><br><br>
  <a href="Triptico.html">Mapa Conceptual</a> |
  <a href="cuadro.html">Cuadro Comparativo</a> |
  <a href="ingles.html">Inglés</a> |
  <a href="index_2.html">Index</a>
</div>

<div id="codigo4" class="contenido">
  <h2>Juego Interactivo: Neoliberalismo</h2>
  <p>Actividad sobre neoliberalismo: juega y aprende.</p>
  <iframe allowfullscreen width="795" height="690" frameborder="0" src="https://es.educaplay.com/juego/24309729-busqueda_de_palabras_neoliberalismo.html"></iframe>
</div>

<script>
  function mostrarContenido(id) {
    let bloques = document.getElementsByClassName('contenido');
    for (let i = 0; i < bloques.length; i++) {
      bloques[i].style.display = 'none';
    }
    document.getElementById(id).style.display = 'block';
  }
</script>

</body>
</html>
