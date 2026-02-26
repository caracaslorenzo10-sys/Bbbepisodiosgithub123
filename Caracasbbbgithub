<!DOCTYPE html>
<html>
<head>
  <title>Meu Site Oficial</title>
  <style>
    body { font-family: Arial; background:#111; color:white; text-align:center; }
    .box { background:#222; padding:20px; margin:20px; border-radius:10px; }
    input, button, textarea { padding:10px; margin:5px; }
    button { background:#00ff88; border:none; cursor:pointer; }
  </style>
</head>
<body>

<h1>🔥 Meu Site Oficial 🔥</h1>

<div class="box">
  <h2>Postar Episódio (Admin)</h2>
  <input type="text" id="titulo" placeholder="Título do episódio">
  <br>
  <textarea id="descricao" placeholder="Descrição"></textarea>
  <br>
  <button onclick="postar()">Postar</button>
</div>

<div class="box">
  <h2>📺 Episódios</h2>
  <div id="episodios"></div>
</div>

<div class="box">
  <h2>💬 Chat ao Vivo</h2>
  <input type="text" id="nome" placeholder="Seu nome">
  <input type="text" id="mensagem" placeholder="Mensagem">
  <button onclick="enviar()">Enviar</button>
  <div id="chat"></div>
</div>

<script>
let adminEmail = "seuemail@gmail.com"; // TROCAR

function postar() {
  let titulo = document.getElementById("titulo").value;
  let desc = document.getElementById("descricao").value;

  let ep = document.createElement("div");
  ep.innerHTML = "<h3>" + titulo + "</h3><p>" + desc + "</p>";
  document.getElementById("episodios").appendChild(ep);
}

function enviar() {
  let nome = document.getElementById("nome").value;
  let msg = document.getElementById("mensagem").value;

  let nova = document.createElement("p");
  nova.innerText = nome + ": " + msg;
  document.getElementById("chat").appendChild(nova);
}
</script>

</body>
</html>
