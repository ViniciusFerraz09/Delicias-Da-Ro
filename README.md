<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Delícias da Rô</title>
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --rosa-claro: #f8c6d8;
      --rosa-escuro: #e883a7;
      --bege: #fff3e0;
      --marrom: #4e2c2c;
      --dourado: #d4af37;
      --fonte-destaque: 'Pacifico', cursive;
      --fonte-principal: 'Open Sans', sans-serif;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: var(--fonte-principal);
      background-color: var(--bege);
      color: var(--marrom);
    }

    header {
      background-color: var(--rosa-claro);
      padding: 2rem 1rem;
      text-align: center;
    }

    header img {
      max-width: 150px;
      border-radius: 50%;
    }

    header h1 {
      font-family: var(--fonte-destaque);
      font-size: 2.5rem;
      color: var(--marrom);
      margin-top: 0.5rem;
    }

    nav {
      background-color: var(--rosa-escuro);
      padding: 1rem;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: 600;
    }

    .section {
      padding: 2rem 1rem;
    }

    .destaques, .cardapio {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 2rem;
    }

    .produto {
      background-color: white;
      border-radius: 1rem;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      max-width: 280px;
      text-align: center;
      padding: 1rem;
    }

    .produto img {
      max-width: 100%;
      border-radius: 1rem;
    }

    .produto h3 {
      margin-top: 1rem;
      font-size: 1.2rem;
      color: var(--marrom);
    }

    .produto p {
      margin-top: 0.5rem;
      font-size: 0.95rem;
      color: #444;
    }

    footer {
      background-color: var(--rosa-escuro);
      color: white;
      text-align: center;
      padding: 2rem 1rem;
    }

    footer a {
      color: white;
      text-decoration: none;
    }

    .sobre {
      max-width: 800px;
      margin: 0 auto;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <img src="/mnt/data/file-45X52RNjbAEoUpjUY2QAw1" alt="Logo Delícias da Rô">
    <h1>Delícias da Rô</h1>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#cardapio">Cardápio</a>
    <a href="#sobre">Sobre Nós</a>
    <a href="#contato">Contato</a>
  </nav>

  <section class="section destaques" id="home">
    <div class="produto">
      <img src="https://via.placeholder.com/300x200?text=Bolo+Decorado" alt="Bolo Decorado">
      <h3>Bolo Decorado</h3>
      <p>Delicioso bolo personalizado para sua ocasião especial.</p>
    </div>
    <div class="produto">
      <img src="https://via.placeholder.com/300x200?text=Cupcake+Colorido" alt="Cupcake">
      <h3>Cupcakes</h3>
      <p>Coloridos, fofinhos e irresistíveis!</p>
    </div>
    <div class="produto">
      <img src="https://via.placeholder.com/300x200?text=Doces+Finos" alt="Doces Finos">
      <h3>Doces Finos</h3>
      <p>Elegância e sabor em cada mordida.</p>
    </div>
  </section>

  <section class="section" id="cardapio">
    <h2 style="text-align:center; margin-bottom: 2rem; font-family: var(--fonte-destaque); font-size: 2rem;">Nosso Cardápio</h2>
    <div class="cardapio">
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Bolo+de+Chocolate" alt="Bolo de Chocolate">
        <h3>Bolo de Chocolate</h3>
        <p>Com cobertura de brigadeiro. Opções veganas disponíveis.</p>
      </div>
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Mini+Salgados" alt="Mini Salgados">
        <h3>Mini Salgados</h3>
        <p>Coxinhas, quibes e muito mais. Ideais para festas!</p>
      </div>
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Brigadeiros+Gourmet" alt="Brigadeiros Gourmet">
        <h3>Brigadeiros Gourmet</h3>
        <p>Sabores variados, com ingredientes selecionados.</p>
      </div>
    </div>
  </section>

  <section class="section" id="sobre">
    <div class="sobre">
      <h2 style="font-family: var(--fonte-destaque); font-size: 2rem; margin-bottom: 1rem;">Sobre Nós</h2>
      <p>
        A Delícias da Rô nasceu do amor pela confeitaria artesanal. Com receitas de família e muito carinho, criamos doces e salgados que encantam pela beleza e sabor. Cada pedido é feito com dedicação para tornar seu momento ainda mais especial.
      </p>
      <p style="margin-top: 1rem;">
        Venha nos conhecer e provar essas delícias feitas com amor!
      </p>
    </div>
  </section>

  <footer id="contato">
    <p>Siga no Instagram: <a href="https://instagram.com/deliciasdaro.rn" target="_blank">@deliciasdaro.rn</a></p>
    <p>Contato via WhatsApp: <a href="https://wa.me/5511985314398" target="_blank">(11) 98531-4398</a></p>
  </footer>
</body>
</html>
