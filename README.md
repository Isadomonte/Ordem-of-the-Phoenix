# Ordem-of-the-Phoenix
Plataforma de estudos para os alunos do 7 ano do zona oeste 2025
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Order of the Phoenix</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #121212;
      color: #f1f1f1;
    }

    header {
      background-color: #1f1f1f;
      padding: 1rem;
      text-align: center;
      font-size: 1.5rem;
      font-weight: bold;
    }

    nav {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      background-color: #272727;
      padding: 0.5rem;
    }

    nav a {
      color: #f1f1f1;
      text-decoration: none;
      margin: 0.5rem;
      padding: 0.5rem 1rem;
      border-radius: 10px;
      background-color: #333;
    }

    nav a:hover {
      background-color: #555;
    }

    main {
      padding: 1rem;
    }

    section {
      margin-bottom: 2rem;
    }

    h2 {
      border-bottom: 1px solid #444;
      padding-bottom: 0.5rem;
    }

    .resumo, .mapa-mental, .forum {
      background-color: #1e1e1e;
      padding: 1rem;
      border-radius: 10px;
      margin-bottom: 1rem;
    }

    input, textarea {
      width: 100%;
      padding: 0.5rem;
      margin-top: 0.5rem;
      border-radius: 5px;
      border: none;
    }

    button {
      margin-top: 0.5rem;
      padding: 0.5rem 1rem;
      border: none;
      border-radius: 5px;
      background-color: #4caf50;
      color: white;
      cursor: pointer;
    }

    button:hover {
      background-color: #45a049;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: #1f1f1f;
      color: #888;
    }
  </style>
</head>
<body>
  <header>Order of the Phoenix</header>

  <nav>
    <a href="#forum">Fórum</a>
    <a href="#resumos">Resumos</a>
    <a href="#mapas">Mapas Mentais</a>
    <a href="#upload">Enviar Arquivo</a>
  </nav>

  <main>
    <section id="forum">
      <h2>Fórum de Dúvidas</h2>
      <div class="forum">
        <textarea placeholder="Digite sua dúvida..."></textarea>
        <button>Postar Dúvida</button>
      </div>
    </section>

    <section id="resumos">
      <h2>Resumos</h2>
      <div class="resumo">
        <textarea placeholder="Escreva um resumo aqui..."></textarea>
        <button>Salvar Resumo</button>
      </div>
    </section>

    <section id="mapas">
      <h2>Mapas Mentais</h2>
      <div class="mapa-mental">
        <textarea placeholder="Descreva seu mapa mental..."></textarea>
        <button>Postar Mapa Mental</button>
      </div>
    </section>

    <section id="upload">
      <h2>Enviar Imagem ou PDF</h2>
      <input type="file" accept="image/*,.pdf" />
      <button>Enviar Arquivo</button>
    </section>
  </main>

  <footer>
    Feito com carinho por Isa
  </footer>
</body>
</html>
