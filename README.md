<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Zika Scripts - Loja de Scripts FiveM</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }
    body {
      background-color: #0d0d0d;
      color: #fff;
      line-height: 1.6;
    }
    header {
      background-color: #1a1a1a;
      padding: 20px 40px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      box-shadow: 0 2px 10px rgba(0,0,0,0.6);
    }
    header img {
      height: 60px;
    }
    nav a {
      color: #fff;
      margin-left: 30px;
      text-decoration: none;
      font-weight: 600;
      position: relative;
    }
    nav a::after {
      content: "";
      position: absolute;
      bottom: -5px;
      left: 0;
      width: 0;
      height: 2px;
      background-color: #ff0000;
      transition: 0.3s ease;
    }
    nav a:hover::after {
      width: 100%;
    }
    .hero {
      text-align: center;
      padding: 100px 20px;
      background: linear-gradient(to right, #ff0000, #cc0000);
    }
    .hero h1 {
      font-size: 4em;
      font-weight: bold;
      margin-bottom: 15px;
    }
    .hero p {
      font-size: 1.4em;
      max-width: 700px;
      margin: 0 auto;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 30px;
      padding: 60px 40px;
      background-color: #121212;
    }
    .product {
      background-color: #1e1e1e;
      border: 1px solid #2a2a2a;
      border-radius: 15px;
      padding: 25px;
      text-align: center;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .product:hover {
      transform: translateY(-5px);
      box-shadow: 0 0 15px rgba(255, 0, 0, 0.3);
    }
    .product h2 {
      font-size: 1.6em;
      margin-bottom: 10px;
      color: #ff4444;
    }
    .product p {
      font-size: 1em;
      margin-bottom: 20px;
      color: #ccc;
    }
    .product button {
      background: #ff0000;
      color: white;
      border: none;
      padding: 12px 25px;
      font-size: 1em;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    .product button:hover {
      background: #cc0000;
    }
    .auth-section, .admin-section, .dashboard-section {
      padding: 60px 40px;
      background-color: #1b1b1b;
    }
    .auth-section h2, .admin-section h2, .dashboard-section h2 {
      font-size: 2em;
      margin-bottom: 20px;
      color: #ff4444;
    }
    .auth-form, .admin-form {
      max-width: 400px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    .auth-form input, .admin-form input {
      padding: 12px;
      border: none;
      border-radius: 5px;
      background: #2a2a2a;
      color: white;
    }
    .auth-form button, .admin-form button {
      background: #ff0000;
      border: none;
      color: white;
      padding: 12px;
      border-radius: 5px;
      cursor: pointer;
    }
    .auth-form button:hover, .admin-form button:hover {
      background: #cc0000;
    }
    .dashboard {
      max-width: 1000px;
      margin: 0 auto;
      background: #232323;
      padding: 30px;
      border-radius: 12px;
    }
    .dashboard h3 {
      font-size: 1.4em;
      color: #fff;
      margin-top: 20px;
    }
    .dashboard ul {
      margin-top: 10px;
      list-style: none;
    }
    .dashboard li {
      padding: 10px;
      border-bottom: 1px solid #333;
      color: #ccc;
    }
    footer {
      text-align: center;
      padding: 40px;
      background-color: #1a1a1a;
      font-size: 0.95em;
      border-top: 1px solid #333;
      color: #aaa;
    }
    .logo-container {
      display: flex;
      align-items: center;
    }
    .logo-container img {
      height: 60px;
      margin-right: 15px;
    }
    .logo-container span {
      font-size: 1.5em;
      font-weight: 700;
      color: #ff0000;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo-container">
      <img src="A_logo_for_\"Zika_Scripts\"_is_presented_in_this_hig.png" alt="Zika Scripts Logo">
      <span>Zika Scripts</span>
    </div>
    <nav>
      <a href="#">Início</a>
      <a href="#produtos">Scripts</a>
      <a href="#login">Login</a>
      <a href="#admin">Admin</a>
      <a href="#dashboard">Dashboard</a>
    </nav>
  </header>  <section class="hero">
    <h1>Scripts de Alta Qualidade para FiveM</h1>
    <p>Automatize seu servidor com sistemas profissionais, entregas instantâneas e suporte dedicado. Confie na Zika Scripts!</p>
  </section>  <section class="products" id="produtos">
    <div class="product">
      <h2>Painel de Caminhoneiro</h2>
      <p>Gerencie entregas com pagamento automático, waypoint e spawn de caminhão. Totalmente otimizado.</p>
      <button>Comprar Agora</button>
    </div>
    <div class="product">
      <h2>Concessionária 3D</h2>
      <p>Visual moderno com preview 3D dos veículos, banco de dados integrado e sistema de leilão in-game.</p>
      <button>Comprar Agora</button>
    </div>
    <div class="product">
      <h2>Desmanche de Veículos</h2>
      <p>Desmonte peça por peça, transporte para estoque e receba recompensa por cada parte.</p>
      <button>Comprar Agora</button>
    </div>
  </section>  <section class="auth-section" id="login">
    <h2>Login / Registro</h2>
    <form class="auth-form">
      <input type="text" placeholder="Usuário ou Email" required />
      <input type="password" placeholder="Senha" required />
      <button type="submit">Entrar</button>
      <button type="button">Criar Conta</button>
    </form>
  </section>  <section class="admin-section" id="admin">
    <h2>Painel do Administrador</h2>
    <form class="admin-form">
      <input type="text" placeholder="Nome do Script" required />
      <input type="text" placeholder="Descrição" required />
      <input type="number" placeholder="Preço em R$" required />
      <button type="submit">Adicionar Script</button>
    </form>
  </section>  <section class="dashboard-section" id="dashboard">
    <h2>Dashboard do Cliente</h2>
    <div class="dashboard">
      <h3>Histórico de Compras</h3>
      <ul>
        <li>Concessionária 3D - R$ 75,00 - 10/04/2025</li>
        <li>Painel Caminhoneiro - R$ 50,00 - 08/04/2025</li>
      </ul>
      <h3>Licenças Ativas</h3>
      <ul>
        <li>Concessionária 3D - Ativo</li>
        <li>Painel Caminhoneiro - Ativo</li>
      </ul>
    </div>
  </section>  <footer>
    <p>© 2025 Zika Scripts. Todos os direitos reservados. | Desenvolvido com profissionalismo para servidores de sucesso.</p>
  </footer>
</body>
</html>
