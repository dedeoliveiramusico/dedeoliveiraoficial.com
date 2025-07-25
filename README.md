<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dedé Oliveira - Site Oficial</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #1b1b1b;
      color: #e0e0e0;
    }

    header {
      background: linear-gradient(to right, #ffd700, #c0c0c0);
      padding: 1rem;
      text-align: center;
      color: #1b1b1b;
    }

    nav {
      background-color: #2e2e2e;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
      flex-wrap: wrap;
    }

    nav a {
      color: #ffd700;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #c0c0c0;
    }

    section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }

    .video-container {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    iframe {
      width: 100%;
      height: 315px;
      border: none;
    }

    footer {
      background-color: #2e2e2e;
      text-align: center;
      padding: 1rem;
      color: #aaa;
    }

    .redes a {
      display: inline-block;
      margin: 0.5rem;
      color: #ffd700;
      font-weight: bold;
    }

    @media (max-width: 600px) {
      nav {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Dedé Oliveira</h1>
    <p>Músico Autêntico • Romântico • Criador de Vídeos</p>
  </header>

  <nav>
    <a href="#inicio">Início</a>
    <a href="#videos">Vídeos</a>
    <a href="#biografia">Biografia</a>
    <a href="#redes">Redes Sociais</a>
  </nav>

  <section id="inicio">
    <h2>Bem-vindo ao meu mundo musical</h2>
    <p>Sou Dedé Oliveira, cantor autêntico com mais de 30 anos de história na música romântica. Aqui você encontra meus vídeos, biografia, links e tudo que representa a minha jornada musical. Viva a emoção comigo!</p>
  </section>

  <section id="videos">
    <h2>Últimos Vídeos</h2>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/wCJiud26q8M" allowfullscreen></iframe>
    </div>
  </section>

  <section id="biografia">
    <h2>Minha História</h2>
    <p>Com mais de 30 anos de estrada como cantor, Dedé Oliveira enfrentou altos e baixos. Após uma pausa, em 2020 ele recomeçou do zero como criador de vídeos na internet. Com seu estilo apaixonado, inspirado em Frankito Lopes, alcançou mais de 500 mil seguidores no Facebook e hoje espalha amor e saudade com suas canções românticas e vídeos autênticos.</p>
  </section>

  <section id="redes">
    <h2>Redes Sociais</h2>
    <div class="redes">
      <a href="https://youtube.com/@dedepoplovedeol20" target="_blank">YouTube</a><br/>
      <a href="https://www.facebook.com/share/19MtWA8RM7/" target="_blank">Facebook</a><br/>
      <a href="https://www.instagram.com/dede_oliveira_oficial" target="_blank">Instagram</a>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Dedé Oliveira. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
