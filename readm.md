<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>AutoClean - Lavagem Automotiva</title>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.3/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-icons/1.11.3/font/bootstrap-icons.min.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
    }
    header {
      background: linear-gradient(135deg, #005bea, #00c6fb);
      color: white;
      text-align: center;
      padding: 60px 20px;
    }
    header h1 {
      font-size: 2.5rem;
      font-weight: bold;
    }
    .btn-whatsapp {
      background-color: #25d366;
      color: white;
      font-weight: bold;
    }
    .btn-whatsapp:hover {
      background-color: #1ebe5d;
      color: white;
    }
    section {
      padding: 60px 20px;
    }
    .servico i {
      font-size: 2rem;
      color: #005bea;
      margin-bottom: 10px;
    }
    footer {
      background: #222;
      color: #aaa;
      padding: 20px;
      text-align: center;
    }
    footer i {
      font-size: 1.5rem;
      margin: 0 10px;
      color: #fff;
    }
  </style>
</head>
<body>

  <!-- HERO -->
  <header>
    <h1>AutoClean</h1>
    <p>Lavagem automotiva premium no seu bairro</p>
    <a href="https://wa.me/5599999999999" target="_blank" class="btn btn-whatsapp btn-lg rounded-pill mt-3">
      <i class="bi bi-whatsapp"></i> Agendar no WhatsApp
    </a>
  </header>

  <!-- SERVIÇOS -->
  <section id="servicos" class="container text-center">
    <h2 class="mb-4">Nossos Serviços</h2>
    <div class="row">
      <div class="col-md-4 servico">
        <i class="bi bi-droplet"></i>
        <h5>Lavagem Completa</h5>
        <p>Exterior e interior impecáveis.</p>
      </div>
      <div class="col-md-4 servico">
        <i class="bi bi-sun"></i>
        <h5>Polimento</h5>
        <p>Pintura renovada e brilhante.</p>
      </div>
      <div class="col-md-4 servico">
        <i class="bi bi-brush"></i>
        <h5>Higienização Interna</h5>
        <p>Bancos e estofados livres de sujeira.</p>
      </div>
    </div>
  </section>

  <!-- GALERIA -->
  <section id="trabalhos" class="container text-center">
    <h2 class="mb-4">Trabalhos Realizados</h2>
    <div class="row">
      <div class="col-md-6 mb-3">
        <img src="img/trabalho1.jpg" class="img-fluid rounded-4" alt="Antes e depois da lavagem">
      </div>
      <div class="col-md-6 mb-3">
        <img src="img/trabalho2.jpg" class="img-fluid rounded-4" alt="Carro detalhado e limpo">
      </div>
    </div>
  </section>

  <!-- CONTATO -->
  <section id="contato" class="container text-center">
    <h2 class="mb-4">Fale Conosco</h2>
    <p>Entre em contato e agende seu horário:</p>
    <a href="https://wa.me/5599999999999" target="_blank" class="btn btn-whatsapp btn-lg rounded-pill m-2">
      <i class="bi bi-whatsapp"></i> WhatsApp
    </a>
    <a href="https://instagram.com/seuperfil" target="_blank" class="btn btn-primary btn-lg rounded-pill m-2">
      <i class="bi bi-instagram"></i> Instagram
    </a>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>© 2025 AutoClean - Todos os direitos reservados</p>
    <div>
      <a href="https://wa.me/5599999999999" target="_blank"><i class="bi bi-whatsapp"></i></a>
      <a href="https://instagram.com/seuperfil" target="_blank"><i class="bi bi-instagram"></i></a>
    </div>
  </footer>

</body>
</html>
