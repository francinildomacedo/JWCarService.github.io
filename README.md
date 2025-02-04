<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>JW Car Services</title>
  <link rel="stylesheet" href="styles.css">
  <!-- Fonte Babi Black Italic (substituída por uma fonte similar) -->
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap" rel="stylesheet">
</head>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>JW Car Services - Mecânica em Campina Grande</title>
  <meta name="description" content="JW Car Services oferece serviços de mecânica automotiva, diagnóstico eletrônico, troca de óleo e muito mais em Campina Grande. Entre em contato agora!">
  <meta name="keywords" content="mecânica, carros, campina grande, diagnóstico automotivo, troca de óleo, revisão completa">
  <meta name="author" content="JW Car Services">
  <link rel="stylesheet" href="styles.css">
  <!-- Fonte Babi Black Italic (substituída por uma fonte similar) -->
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap" rel="stylesheet">
</head>
<body>
  <!-- Cabeçalho -->
  <header>
    <div class="container">
      <h1>JW Car Services</h1>
      <nav>
        <ul>
          <li><a href="#inicio">Início</a></li>
          <li><a href="#servicos">Serviços</a></li>
          <li><a href="#produtos">Produtos</a></li>
          <li><a href="#diagnostico">Diagnóstico</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Seção Inicial -->
  <section id="inicio" class="hero">
    <div class="container">
      <img src="https://via.placeholder.com/1200x400" alt="Frente da Oficina JW Car Services">
      <h2>Bem-vindo à JW Car Services</h2>
      <p>Sua oficina de confiança em Campina Grande!</p>
      <a href="#diagnostico" class="btn">Solicitar Diagnóstico</a>
    </div>
  </section>

  <!-- Seção de Serviços -->
  <section id="servicos" class="services">
    <div class="container">
      <h2>Nossos Serviços</h2>
      <table class="price-table">
        <thead>
          <tr>
            <th>Serviço</th>
            <th>Preço</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Troca de Óleo</td>
            <td>R$ 80,00</td>
          </tr>
          <tr>
            <td>Revisão Completa</td>
            <td>R$ 250,00</td>
          </tr>
          <tr>
            <td>Diagnóstico Eletrônico</td>
            <td>R$ 120,00</td>
          </tr>
          <tr>
            <td>Alinhamento e Balanceamento</td>
            <td>R$ 150,00</td>
          </tr>
        </tbody>
      </table>
    </div>
  </section>

  <!-- Seção de Produtos -->
  <section id="produtos" class="products">
    <div class="container">
      <h2>Nossos Produtos</h2>
      <ul>
        <li>Pneus Goodyear</li>
        <li>Filtros de Ar Bosch</li>
        <li>Óleo Lubrax</li>
        <li>Baterias Moura</li>
      </ul>
    </div>
  </section>

  <!-- Seção de Diagnóstico -->
  <section id="diagnostico" class="diagnostico">
    <div class="container">
      <h2>Solicite um Diagnóstico</h2>
      <form id="diagnostico-form">
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome" required>

        <label for="whatsapp">WhatsApp:</label>
        <input type="tel" id="whatsapp" name="whatsapp" placeholder="(XX) XXXXX-XXXX" required>

        <label for="descricao">Descrição detalhada do problema:</label>
        <textarea id="descricao" name="descricao" rows="5" required></textarea>

        <button type="submit" class="btn">Enviar</button>
      </form>
    </div>
  </section>

  <!-- Galeria de Fotos -->
  <section id="galeria" class="gallery">
    <div class="container">
      <h2>Galeria de Fotos</h2>
      <div class="gallery-images">
        <img src="https://via.placeholder.com/300" alt="Foto 1">
        <img src="https://via.placeholder.com/300" alt="Foto 2">
        <img src="https://via.placeholder.com/300" alt="Foto 3">
        <img src="https://via.placeholder.com/300" alt="Foto 4">
      </div>
    </div>
  </section>

  <!-- Mapa -->
  <section id="mapa" class="map">
    <div class="container">
      <h2>Onde Estamos</h2>
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3972.209965842193!2d-35.88470192477174!3d-7.225308372949057!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7ace85c3b5e6e3b%3A0x7f9f9f9f9f9f9f9f!2sRua%20Costa%20e%20Silva%2C%2040B%20-%20Jardim%20Quarenta%2C%20Campina%20Grande%20-%20PB!5e0!3m2!1sen!2sbr!4v1696523456789"
        width="100%" height="400" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </div>
  </section>

  <!-- Botão de Chamada -->
  <section id="chamada" class="call-button">
    <div class="container">
      <a href="tel:+5583989991944" class="btn">Ligue Agora</a>
    </div>
  </section>

  <!-- Rodapé -->
  <footer>
    <div class="container">
      <p>&copy; 2023 JW Car Services. Todos os direitos reservados.</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
