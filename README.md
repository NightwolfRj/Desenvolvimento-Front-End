<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>New Technology</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      line-height: 1.6;
      background-color: #f9fafe;
      color: #333;
      scroll-behavior: smooth;
    }

    header {
      background-color: #1e1e2f;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    nav {
      background-color: #2e2e4f;
      padding: 1rem;
      display: flex;
      justify-content: center;
      gap: 2rem;
    }

    nav a {
      color: #ffffff;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #00bcd4;
    }

    .destaque {
      padding: 3rem 1rem;
      background-color: #eef2f7;
    }

    .grid-destaque {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 2rem;
      align-items: center;
      max-width: 1100px;
      margin: auto;
    }

    .grid-destaque img {
      width: 100%;
      border-radius: 12px;
    }

    .info-produto h2 {
      font-size: 2rem;
      color: #1e1e2f;
      margin-bottom: 1rem;
    }

    .info-produto p {
      font-size: 1rem;
      color: #555;
    }

    .recursos {
      padding: 3rem 1rem;
      background-color: #ffffff;
    }

    .flex-recursos {
      display: flex;
      gap: 2rem;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
      max-width: 1100px;
      margin: auto;
    }

    .lista-recursos {
      flex: 1;
      display: flex;
      flex-direction: column;
      gap: 1.5rem;
    }

    .recurso {
      display: flex;
      align-items: flex-start;
      gap: 1rem;
    }

    .recurso span {
      font-size: 2rem;
      color: #00bcd4;
    }

    .recurso h3 {
      margin: 0;
      font-size: 1.2rem;
      color: #222;
    }

    .recurso p {
      color: #666;
      font-size: 0.95rem;
    }

    .imagem-recursos {
      flex: 1;
      text-align: center;
    }

    .imagem-recursos img {
      max-width: 100%;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    }

    .contato {
      padding: 3rem 1rem;
      background-color: #f4f7fb;
      max-width: 800px;
      margin: auto;
    }

    .contato h2 {
      text-align: center;
      margin-bottom: 2rem;
      font-size: 2rem;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    input, textarea {
      padding: 0.8rem;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 1rem;
    }

    button {
      background-color: #00bcd4;
      color: white;
      padding: 0.8rem;
      border: none;
      border-radius: 8px;
      font-weight: bold;
      font-size: 1rem;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #0197a6;
    }

    @media (max-width: 768px) {
      .grid-destaque {
        grid-template-columns: 1fr;
        text-align: center;
      }

      .flex-recursos {
        flex-direction: column;
        align-items: center;
        text-align: center;
      }

      .recurso {
        justify-content: center;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>New Technology</h1>
    <p>Transforme sua rotina com tecnologia</p>
  </header>

  <nav>
    <a href="#destaque">Destaque</a>
    <a href="#recursos">Recursos</a>
    <a href="#contato">Contato</a>
  </nav>

  <section class="destaque" id="destaque">
    <div class="grid-destaque">
      <img src="https://images.samsung.com/pt/galaxy-watch6/feature/galaxy-watch6-kv-pc.jpg" alt="Five Galaxy Watch6 can be seen in a diagonal line. All five are showing different watch faces with different watch bands attached.">
      <div class="info-produto">
        <h2>Samsung Galaxy Watch 6</h2>
        <p>O Produto Incrível foi feito para facilitar sua vida com praticidade e inovação.</p>
      </div>
    </div>
  </section>

  <section class="recursos" id="recursos">
    <div class="flex-recursos">
      <div class="lista-recursos">
        <div class="recurso">
          <span>⚡</span>
          <div>
            <h3>Alta Performance</h3>
            <p>Velocidade e eficiência em todas as tarefas.</p>
          </div>
        </div>
        <div class="recurso">
          <span>🎨</span>
          <div>
            <h3>Design Moderno</h3>
            <p>Visual elegante que combina com Trabalho, academia, encontros e até eventos mais formais.</p>
          </div>
        </div>
        <div class="recurso">
          <span>🔗</span>
          <div>
            <h3>Conectividade</h3>
            <p>Compatível com os principais dispositivos do mercado. Pontos fortes: Tela linda, ótima performance e integração com Android.</p>
          </div>
        </div>
      </div>
      <div class="imagem-recursos">
        <iframe width="789" height="444" src="https://www.youtube.com/embed/2vOceSQXjvA" 
        title="Galaxy Watch6 | Watch6 Classic: Official Unboxing | Samsung​" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
        referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
      </div>
    </div>
  </section>

  <section class="contato" id="contato">
    <h2>Entre em Contato</h2>
    <form>
      <input type="text" placeholder="Seu nome" required />
      <input type="email" placeholder="Seu e-mail" required />
      <textarea rows="5" placeholder="Sua mensagem..." required></textarea>
      <button type="submit">Enviar Mensagem</button>
    </form>
  </section>
</body>
</html>
