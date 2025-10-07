# Josane-sampaio
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Espaço de Beleza Josane Sampaio</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background-color: #fff;
      color: #333;
      line-height: 1.6;
    }
    header {
      background-color: #f8f8f8;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }
    header h1 {
      margin: 0;
      font-weight: 700;
      font-size: 1.8em;
    }
    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #333;
      font-weight: 500;
    }
    nav a:hover {
      color: #c0392b;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1612061800808-1a42de6f5764?auto=format&fit=crop&w=1470&q=80') center/cover no-repeat;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      text-align: center;
      position: relative;
    }
    .hero::after {
      content: '';
      position: absolute;
      top:0; left:0;
      width:100%; height:100%;
      background-color: rgba(0,0,0,0.4);
    }
    .hero-content {
      position: relative;
      z-index: 1;
    }
    .hero h2 {
      font-size: 2.5em;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 1.2em;
      margin-bottom: 30px;
    }
    .hero button {
      padding: 12px 30px;
      border: none;
      background-color: #c0392b;
      color: #fff;
      font-size: 1em;
      cursor: pointer;
      border-radius: 5px;
    }
    .hero button:hover {
      background-color: #e74c3c;
    }
    section {
      padding: 60px 40px;
      max-width: 1100px;
      margin: auto;
    }
    section h2 {
      font-size: 2em;
      text-align: center;
      margin-bottom: 40px;
      color: #c0392b;
    }
    .services, .contact-info {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }
    .service-box, .contact-box {
      flex: 1 1 300px;
      margin: 20px;
      padding: 20px;
      border: 1px solid #eee;
      border-radius: 8px;
      text-align: center;
      transition: transform 0.3s;
      background-color: #fafafa;
    }
    .service-box:hover, .contact-box:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .service-box img {
      max-width: 100%;
      border-radius: 8px;
      margin-bottom: 15px;
    }
    footer {
      background-color: #f8f8f8;
      padding: 20px;
      text-align: center;
      font-size: 0.9em;
      color: #666;
    }
    a.button-link {
      text-decoration: none;
      color: #fff;
      display: inline-block;
      padding: 12px 30px;
      background-color: #c0392b;
      border-radius: 5px;
      margin-top: 10px;
    }
    a.button-link:hover {
      background-color: #e74c3c;
    }
  </style>
</head>
<body>

  <!-- HEADER -->
  <header>
    <h1>Josane Sampaio</h1>
    <nav>
      <a href="#servicos">Serviços</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <!-- HERO -->
  <div class="hero">
    <div class="hero-content">
      <h2>Beleza e cuidado com estilo</h2>
      <p>Transformando seu visual com profissionalismo e sofisticação</p>
      <button onclick="window.location.href='#contato'">Agende seu horário</button>
    </div>
  </div>

  <!-- SERVIÇOS -->
  <section id="servicos">
    <h2>Serviços</h2>
    <div class="services">
      <div class="service-box">
        <img src="https://images.unsplash.com/photo-1595433562696-4f7db9c5c2c8?auto=format&fit=crop&w=600&q=80" alt="Corte e penteado">
        <h3>Corte e Penteado</h3>
        <p>Do clássico ao moderno, cuidamos do seu visual com precisão e estilo.</p>
      </div>
      <div class="service-box">
        <img src="https://images.unsplash.com/photo-1588776814546-85f7f9e3eeb2?auto=format&fit=crop&w=600&q=80" alt="Alongamento de cílios">
        <h3>Alongamento de Cílios</h3>
        <p>Realce o olhar com técnicas de extensão que garantem naturalidade e beleza.</p>
      </div>
      <div class="service-box">
        <img src="https://images.unsplash.com/photo-1611822150138-1231f9f3d6a8?auto=format&fit=crop&w=600&q=80" alt="Manicure e pedicure">
        <h3>Manicure e Pedicure</h3>
        <p>Unhas impecáveis e bem cuidadas, com atenção aos detalhes.</p>
      </div>
    </div>
  </section>

  <!-- CONTATO -->
  <section id="contato">
    <h2>Contato</h2>
    <div class="contact-info">
      <div class="contact-box">
        <h3>Endereço</h3>
        <p>Rua da Beleza, 123 – Centro, Cidade/Estado</p>
      </div>
      <div class="contact-box">
        <h3>Telefone</h3>
        <p>(00) 12345-6789</p>
      </div>
      <div class="contact-box">
        <h3>Redes Sociais</h3>
        <p><a class="button-link" href="https://instagram.com/josanesampaio" target="_blank">Instagram</a></p>
        <p><a class="button-link" href="https://facebook.com/josanesampaio" target="_blank">Facebook</a></p>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    &copy; 2025 Espaço de Beleza Josane Sampaio. Todos os direitos reservados.
  </footer>

</body>
</html>
