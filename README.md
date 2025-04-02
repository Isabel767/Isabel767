<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ISABEL FEBRONIO</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fdf6f0;
      color: #444;
    }
    header {
      background-color: #f9d5d3;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      color: #8e6e6e;
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      color: #b07c7c;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .gallery img {
      width: 100%;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }
    input, textarea {
      padding: 1rem;
      border: 1px solid #ddd;
      border-radius: 8px;
      font-size: 1rem;
    }
    button {
      background-color: #f7b6b2;
      border: none;
      padding: 1rem;
      font-size: 1rem;
      border-radius: 8px;
      color: white;
      cursor: pointer;
    }
    button:hover {
      background-color: #e49e9b;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background-color: #f2e9e4;
      color: #7b6c63;
      margin-top: 2rem;
    }
    .social-links a {
      margin: 0 10px;
      color: #b07c7c;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>ISABEL FEBRONIO</h1>
    <p>Ilustrações com personalidade suave</p>
  </header>

  <section>
    <h2>Sobre Mim</h2>
    <p>Sou Isabel Febronio, uma artista apaixonada por dar vida a emoções suaves e cores delicadas. Minhas ilustrações transitam entre o lúdico e o poético, com foco em tons pastéis e traços leves. Aqui compartilho meu trabalho e abro espaço para novas conexões criativas.</p>
  </section>

  <section>
    <h2>Portfólio</h2>
    <div class="gallery">
      <img src="ilustracao1.jpg" alt="Ilustração 1">
      <img src="ilustracao2.jpg" alt="Ilustração 2">
      <img src="ilustracao3.jpg" alt="Ilustração 3">
    </div>
  </section>

  <section>
    <h2>Comissões</h2>
    <p>Estou disponível para comissões personalizadas! Se você deseja uma ilustração única feita com carinho e estilo próprio, entre em contato. Faço artes para presentes, livros, redes sociais e projetos especiais.</p>
    <ul>
      <li>Retratos personalizados</li>
      <li>Cenas poéticas e conceituais</li>
      <li>Arte digital para marcas ou projetos</li>
    </ul>
  </section>

  <section>
    <h2>Contato</h2>
    <form action="mailto:isabel@email.com" method="POST" enctype="text/plain">
      <input type="text" name="nome" placeholder="Seu nome" required>
      <input type="email" name="email" placeholder="Seu e-mail" required>
      <textarea name="mensagem" rows="5" placeholder
