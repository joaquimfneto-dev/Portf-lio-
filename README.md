# Portf-lio-
Meu portfólio pessoal.
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Joaquim Neto | Dev</title>

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: #0f172a;
      color: #e2e8f0;
    }

    header {
      text-align: center;
      padding: 100px 20px;
    }

    header h1 {
      font-size: 42px;
    }

    header p {
      color: #94a3b8;
      font-size: 18px;
    }

    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 20px;
      border-radius: 6px;
      background: #38bdf8;
      color: black;
      font-weight: bold;
      text-decoration: none;
      transition: 0.3s;
    }

    .btn:hover {
      background: #0ea5e9;
    }

    section {
      max-width: 900px;
      margin: auto;
      padding: 40px 20px;
    }

    h2 {
      color: #38bdf8;
      margin-bottom: 20px;
    }

    .card {
      background: #1e293b;
      padding: 25px;
      border-radius: 10px;
      margin-bottom: 20px;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .tech {
      display: inline-block;
      background: #334155;
      padding: 5px 10px;
      border-radius: 5px;
      margin: 5px;
      font-size: 14px;
    }

    footer {
      text-align: center;
      padding: 30px;
      color: #64748b;
    }
  </style>
</head>

<body>

<header>
  <h1>Joaquim Neto</h1>
  <p>Desenvolvedor em formação | HTML | JavaScript</p>

  <a class="btn" href="https://www.linkedin.com/in/joaquimneto-dev" target="_blank">
    Meu LinkedIn
  </a>
</header>

<section>
  <h2>Sobre mim</h2>
  <div class="card">
    <p>
      Estudante de Engenharia da Computação com foco em desenvolvimento web.
      Buscando minha primeira oportunidade como desenvolvedor.
    </p>
  </div>
</section>

<section>
  <h2>Projetos</h2>

  <div class="card">
    <h3>Power Bank</h3>
    <p>Projeto acadêmico de desenvolvimento de dispositivo portátil de energia.</p>
    <p><strong>Tecnologias:</strong></p>
    <span class="tech">Eletrônica</span>
    <span class="tech">Projeto em equipe</span>
  </div>

</section>

<section>
  <h2>Tecnologias</h2>
  <div class="card">
    <span class="tech">HTML</span>
    <span class="tech">JavaScript</span>
    <span class="tech">Lógica de Programação</span>
    <span class="tech">Eletrônica</span>
  </div>
</section>

<section>
  <h2>Contato</h2>
  <div class="card">
    <p>Email: joaquimneto.dev@gmail.com</p>
    <p>
      LinkedIn: 
      <a href="https://www.linkedin.com/in/joaquimneto-dev" target="_blank">
        linkedin.com/in/joaquimneto-dev
      </a>
    </p>
  </div>
</section>

<footer>
  <p>© 2026 Joaquim Neto</p>
</footer>

</body>
</html>
