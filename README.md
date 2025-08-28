<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>IntegraChain</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f5f5f5;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #ff6600;
      color: #fff;
      padding: 20px 40px;
      text-align: center;
    }

    header h1 {
      margin-bottom: 10px;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .hero {
      text-align: center;
    }

    .hero h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      color: #ff6600;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 40px;
    }

    .card {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      text-align: center;
    }

    footer {
      background: #222;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    footer a {
      color: #ff6600;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <header>
    <h1>IntegraChain</h1>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#servicos">Serviços</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <section class="hero" id="sobre">
    <h2>Conectando Tecnologia e Integração</h2>
    <p>Nossa missão é integrar soluções digitais para transformar negócios com inovação e eficiência.</p>
  </section>

  <section id="servicos">
    <h2 style="text-align:center;">Nossos Serviços</h2>
    <div class="features">
      <div class="card">
        <h3>Integração de Sistemas</h3>
        <p>Conectamos plataformas e processos para maior produtividade.</p>
      </div>
      <div class="card">
        <h3>Tecnologia Escalável</h3>
        <p>Soluções robustas que crescem junto com o seu negócio.</p>
      </div>
      <div class="card">
        <h3>Consultoria Estratégica</h3>
        <p>Orientação especializada para acelerar sua transformação digital.</p>
      </div>
    </div>
  </section>

  <section id="contato">
    <h2 style="text-align:center;">Entre em Contato</h2>
    <p style="text-align:center;">Envie um e-mail para <a href="mailto:contato@integrac-hain.com">contato@integrachain.com</a></p>
  </section>

  <footer>
    <p>&copy; 2025 IntegraChain | Desenvolvido para GitHub Pages</p>
  </footer>

</body>
</html>
