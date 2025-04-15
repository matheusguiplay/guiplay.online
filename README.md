<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Guiplay Online</title>
  <style>
    body {
      margin: 0;
      font-family: sans-serif;
      background-color: #0e0e0e;
      color: #f3e5f5;
    }

    header {
      background-color: #6a1b9a;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      color: #e1bee7;
    }

    nav {
      background-color: #4a148c;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px 0;
    }

    nav a {
      color: #f3e5f5;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #ce93d8;
    }

    .section {
      padding: 40px 20px;
      text-align: center;
    }

    .product-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }

    .product {
      background-color: #2a2a2a;
      padding: 20px;
      border-radius: 10px;
      width: 250px;
      color: white;
    }

    .product img {
      width: 100%;
      border-radius: 10px;
    }

    footer {
      background-color: #6a1b9a;
      text-align: center;
      padding: 15px;
      color: #e1bee7;
    }
  </style>
</head>
<body>
  <header>
    <h1>Guiplay Online</h1>
  </header>

  <nav>
    <a href="#loja">Loja</a>
    <a href="#sobre">Sobre</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="loja" class="section">
    <h2>Produtos em Destaque</h2>
    <div class="product-list">
      <div class="product">
        <img src="https://via.placeholder.com/250x150?text=Naruto" alt="Action Figure Naruto">
        <h3>Naruto Uzumaki</h3>
        <p>Action Figure do Naruto em modo Sábio. Altura: 18cm.</p>
        <a href="#" style="color:#ce93d8;">Ver mais</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/250x150?text=Goku" alt="Action Figure Goku">
        <h3>Goku Super Saiyajin</h3>
        <p>Action Figure de Goku em Super Saiyajin 3. Altura: 20cm.</p>
        <a href="#" style="color:#ce93d8;">Ver mais</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/250x150?text=Spider-Man" alt="Action Figure Homem-Aranha">
        <h3>Homem-Aranha</h3>
        <p>Action Figure do Spider-Man com base articulada. Altura: 17cm.</p>
        <a href="#" style="color:#ce93d8;">Ver mais</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/250x150?text=Batman" alt="Action Figure Batman">
        <h3>Batman Dark Knight</h3>
        <p>Action Figure do Batman com capa de tecido. Altura: 19cm.</p>
        <a href="#" style="color:#ce93d8;">Ver mais</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/250x150?text=Luffy" alt="Action Figure Luffy">
        <h3>Monkey D. Luffy</h3>
        <p>Action Figure do Luffy com chapéu de palha. Altura: 18cm.</p>
        <a href="#" style="color:#ce93d8;">Ver mais</a>
      </div>
    </div>
  </section>

  <section id="sobre" class="section">
    <h2>Sobre Nós</h2>
    <p>Guiplay Online é uma loja dedicada a oferecer produtos incríveis para o seu dia a dia geek e gamer!</p>
  </section>

  <section id="contato" class="section">
    <h2>Contato</h2>
    <p>Entre em contato pelo e-mail: <a href="mailto:contato@guiplay.online" style="color:#ce93d8;">contato@guiplay.online</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Guiplay Online. Todos os direitos reservados.</p>
  </footer>
</body>
</html>
