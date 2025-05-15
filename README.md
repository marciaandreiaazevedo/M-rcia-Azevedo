<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Cantora | [O Teu Nome]</title>
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background-color: #fdf9f6;
      color: #2b2b2b;
    }
    header {
      background-color: #f5ebe0;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    nav {
      text-align: center;
      margin-top: 1rem;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #8b5e3c;
      font-weight: bold;
    }
    section {
      padding: 3rem 1rem;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      color: #b08968;
      border-bottom: 1px solid #e0cfc2;
      padding-bottom: 0.5rem;
    }
    .bio, .videos, .agenda, .contacto {
      margin-top: 2rem;
    }
    .videos iframe {
      width: 100%;
      max-width: 560px;
      height: 315px;
      margin-bottom: 1rem;
      border: none;
    }
    .agenda ul {
      list-style: none;
      padding: 0;
    }
    .agenda li {
      margin-bottom: 1rem;
      background: #fff;
      padding: 1rem;
      border-left: 5px solid #b08968;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }
    form {
      display: grid;
      gap: 1rem;
    }
    input, textarea {
      padding: 0.75rem;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1rem;
      width: 100%;
    }
    button {
      background-color: #b08968;
      color: white;
      padding: 0.75rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background-color: #f5ebe0;
      text-align: center;
      padding: 2rem 1rem;
      margin-top: 3rem;
    }
    .social a {
      margin: 0 10px;
      color: #8b5e3c;
      text-decoration: none;
      font-size: 1.5rem;
    }
    .download {
      margin-top: 1rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>[O Teu Nome Artístico]</h1>
    <p>Cantora profissional para eventos, estúdios e espetáculos ao vivo</p>
    <nav>
      <a href="#bio">Sobre</a>
      <a href="#videos">Media</a>
      <a href="#agenda">Agenda</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section id="bio" class="bio">
    <h2>Sobre Mim</h2>
    <p>Sou uma cantora profissional com experiência em palcos nacionais e internacionais. Ofereço performances ao vivo para casamentos, eventos corporativos, festas privadas, e gravo vocais para estúdios e projetos musicais.</p>
    <div class="download">
      <a href="presskit.pdf" download>Download Press Kit</a>
    </div>
  </section>

  <section id="videos" class="videos">
    <h2>Media</h2>
    <iframe src="https://www.youtube.com/embed/TEU_VIDEO_AQUI" allowfullscreen></iframe>
    <iframe src="https://www.youtube.com/embed/OUTRO_VIDEO" allowfullscreen></iframe>
  </section>

  <section id="agenda" class="agenda">
    <h2>Agenda</h2>
    <ul>
      <li><strong>15 de Junho, 2025</strong> — Casamento em Lisboa</li>
      <li><strong>29 de Junho, 2025</strong> — Evento corporativo, Porto</li>
      <li><strong>12 de Julho, 2025</strong> — Concerto acústico, Coimbra</li>
    </ul>
  </section>

  <section id="contacto" class="contacto">
    <h2>Contacto</h2>
    <form>
      <input type="text" placeholder="Nome" required />
      <input type="email" placeholder="Email" required />
      <textarea rows="5" placeholder="Mensagem" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <div class="social">
      <a href="https://www.instagram.com/teuperfil" target="_blank">Instagram</a>
      <a href="https://www.youtube.com/@teucanal" target="_blank">YouTube</a>
      <a href="mailto:teu@email.com">Email</a>
    </div>
    <p>&copy; 2025 [O Teu Nome]. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
