# minecraft<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Página Exemplo</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      padding: 20px;
    }
    h1 {
      color: #333;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h1>Bem-vindo à minha página!</h1>
  <p>Essa é uma página HTML simples com um botão interativo.</p>
  <button onclick="mostrarMensagem()">Clique aqui</button>

  <script>
    function mostrarMensagem() {
      alert("Você clicou no botão!");
    }
  </script>
</body>
</html>
