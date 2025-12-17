<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Servidor IPTV Premium</title>
  <style>
    * { box-sizing: border-box; font-family: Arial, Helvetica, sans-serif; }
    body {
      margin: 0;
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
        url('https://images.unsplash.com/photo-1518770660439-4636190af475');
      background-size: cover;
      background-attachment: fixed;
      color: #fff;
    }
    header {
      padding: 30px 15px;
      text-align: center;
      background: rgba(0,0,0,0.7);
    }
    header h1 { font-size: 28px; margin-bottom: 10px; }
    header p { font-size: 14px; line-height: 1.6; }
    .container { padding: 20px; max-width: 1000px; margin: auto; }
    .beneficios, .planos {
      background: rgba(0,0,0,0.75);
      padding: 20px;
      border-radius: 12px;
      margin-bottom: 20px;
    }
    h2 { text-align: center; margin-bottom: 15px; }
    ul { list-style: none; padding: 0; }
    ul li { padding: 8px 0; border-bottom: 1px solid #333; }
    .planos-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
    }
    .plano {
      background: #0d6efd;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
    }
    .plano h3 { margin: 10px 0; }
    .plano span { font-size: 22px; font-weight: bold; }
    .btn {
      display: block;
      text-decoration: none;
      background: #25D366;
      color: #fff;
      padding: 12px;
      margin-top: 10px;
      border-radius: 8px;
      font-weight: bold;
    }
    .btn-pix { background: #ffc107; color: #000; cursor: pointer; }
    .pix-box {
      display: none;
      background: #fff;
      color: #000;
      padding: 15px;
      margin-top: 10px;
      border-radius: 8px;
      text-align: center;
      font-weight: bold;
    }
    .whatsapp-fixo {
      position: fixed;
      right: 15px;
      bottom: 15px;
      background: #25D366;
      color: #fff;
      padding: 15px;
      border-radius: 50%;
      font-size: 20px;
      text-decoration: none;
      box-shadow: 0 4px 10px rgba(0,0,0,0.5);
    }
  </style>
</head>
<body>

<header>
  <h1>Servidor IPTV Premium</h1>
  <p>
    ✔ Canais SD, HD e FHD<br>
    ✔ Filmes e Séries atualizados<br>
    ✔ Esportes ao vivo<br>
    ✔ Adulto (opcional)<br>
    ✔ Funciona em TV, Celular, TV Box e PC<br>
    ✔ Suporte rápido via WhatsApp
  </p>
</header>

<div class="container">

  <div style="text-align:center; margin-bottom:20px;">
    <a class="btn" style="max-width:300px; margin:auto;" href="https://wa.me/5585981743736?text=Olá,%20quero%20assinar%20um%20plano%20IPTV" target="_blank">💬 Falar no WhatsApp</a>
  </div>

  <section class="beneficios">
    <h2>Benefícios do Servidor</h2>
    <ul>
      <li>📺 +10.000 canais</li>
      <li>🎬 Filmes e séries atualizados diariamente</li>
      <li>⚽ Todos os canais esportivos</li>
      <li>🚀 Estável, sem travamentos</li>
      <li>🔒 Servidor seguro e privado</li>
    </ul>
  </section>

  <section class="planos">
    <h2>Planos e Valores</h2>
    <div class="planos-grid">

      <div class="plano">
        <h3>1 Mês</h3>
        <span>R$ 30</span>
        
        <div class="btn btn-pix" onclick="togglePix(this)">Pagar com PIX</div>
        <div class="pix-box">PIX: 85996640269</div>
      </div>

      <div class="plano">
        <h3>2 Meses</h3>
        <span>R$ 50</span>
        
        <div class="btn btn-pix" onclick="togglePix(this)">Pagar com PIX</div>
        <div class="pix-box">PIX: 85996640269</div>
      </div>

      <div class="plano">
        <h3>3 Meses</h3>
        <span>R$ 75</span>
        
        <div class="btn btn-pix" onclick="togglePix(this)">Pagar com PIX</div>
        <div class="pix-box">PIX: 85996640269</div>
      </div>

      <div class="plano">
        <h3>4 Meses</h3>
        <span>R$ 100</span>
        
        <div class="btn btn-pix" onclick="togglePix(this)">Pagar com PIX</div>
        <div class="pix-box">PIX: 85996640269</div>
      </div>

      <div class="plano">
        <h3>1 Ano</h3>
        <span>R$ 250</span>
        
        <div class="btn btn-pix" onclick="togglePix(this)">Pagar com PIX</div>
        <div class="pix-box">PIX: 85996640269</div>
      </div>

    </div>
  </section>

</div>

<a class="whatsapp-fixo" href="https://wa.me/5585981743736" target="_blank">💬</a>

<script>
  function togglePix(btn) {
    const pix = btn.nextElementSibling;
    pix.style.display = pix.style.display === 'block' ? 'none' : 'block';
  }
</script>

</body>
</html>
