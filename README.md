# minhas-fotos-para-vip
vem ver só eu e vc
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mateshoy | Site Profissional</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; background: #f0f0f0; color: #222; }
    header { background: linear-gradient(90deg, #111, #444); color: #fff; padding: 40px; text-align: center; }
    header h1 { margin: 0; font-size: 36px; }
    nav { background: #222; padding: 14px; text-align: center; position: sticky; top: 0; }
    nav a { color: white; margin: 0 18px; text-decoration: none; font-weight: bold; }
    nav a:hover { text-decoration: underline; }
    section { padding: 50px; max-width: 1000px; margin: auto; background: white; margin-top: 25px; border-radius: 10px; box-shadow: 0 0 15px rgba(0,0,0,0.1); }
    .galeria { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 20px; margin-top: 20px; }
    .galeria img { width: 100%; border-radius: 10px; object-fit: cover; height: 180px; background: #ccc; }
    .botao { display: inline-block; margin-top: 20px; padding: 12px 22px; background: #111; color: white; text-decoration: none; font-weight: bold; border-radius: 8px; }
    .botao:hover { background: #333; }
    footer { background: #111; color: white; text-align: center; padding: 25px; margin-top: 40px; }
  </style>
</head>
<body>

  <header>
    <h1>Mateshoy</h1>
    <p>Site Profissional Atualizado</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#fotos">Fotos</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="home">
    <h2>Bem-vindo</h2>
    <p>Este é o novo visual do seu site, mais moderno, estilizado e pronto para receber suas fotos e links importantes.</p>
    <a class="botao" href="https://instagram.com" target="_blank">Meu Instagram</a>
  </section>

  <section id="fotos">
    <h2>Galeria</h2>
    <p>Adicione suas fotos aqui (me envie que eu coloco no código).</p>

    <div class="galeria">
      <img src="loira1.jpg" alt="Foto" />
      <img src="foto2.jpg" alt="Foto 2" />
      <img src="foto3.jpg" alt="Foto 3" />
    </div>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>Email: seuemail@exemplo.com</p>
    <p>Instagram: @seuperfil</p>
  </section>

  <footer>
    © 2025 – Mateshoy. Todos os direitos reservados.
  </footer>

</body>
</html>

