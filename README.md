<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Controle de Ponto</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #1a1a2e;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      color: #fff;
    }

    .logo-container {
      margin-top: 20px;
    }

    .logo-container img {
      width: 150px;
      height: auto;
    }

    .container {
      background: #2d2d44;
      padding: 20px;
      margin-top: 20px;
      border-radius: 8px;
      width: 90%;
      max-width: 400px;
      box-shadow: 0 0 15px rgba(128, 0, 128, 0.4);
    }

    h1, h2, h3 {
      text-align: center;
      color: #c084fc;
    }

    .input-field {
      margin: 10px 0;
    }

    input, select {
      width: 100%;
      padding: 10px;
      font-size: 16px;
      border: 1px solid #a855f7;
      background: #1f1f35;
      color: #fff;
      border-radius: 4px;
    }

    button {
      width: 100%;
      padding: 10px;
      font-size: 16px;
      margin-top: 10px;
      background: #a855f7;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-weight: bold;
    }

    button:hover {
      background: #9333ea;
    }

    table {
      width: 100%;
      margin-top: 15px;
      border-collapse: collapse;
    }

    th, td {
      padding: 8px;
      text-align: center;
      border: 1px solid #4b0082;
    }

    th {
      background: #7c3aed;
      color: white;
    }

    #registroPonto, #painelFundador {
      display: none;
    }

    .voltar {
      background: #6b7280;
    }

    #cronometro {
      text-align: center;
      margin-top: 10px;
      font-weight: bold;
      color: #d8b4fe;
    }
  </style>
</head>
<body>

  <!-- LOGO -->
  <div class="logo-container">
    <img src="img/logo-jc.png" alt="Logo JC RP">
  </div>

  <!-- Conteúdo original copiado exatamente igual, só o estilo alterado -->
  <!-- Começa a partir de: -->
  <div class="container" id="loginSection">
    <h1>Controle de Ponto</h1>
    <div class="input-field">
      <input type="text" id="username" placeholder="Login (CPF ou nome)">
    </div>
    <div class="input-field">
      <input type="password" id="password" placeholder="Senha">
    </div>
    <div class="input-field">
      <select id="cargo">
        <option value="">Selecione o Cargo</option>
        <option value="Moderador Iniciante">Moderador Iniciante</option>
        <option value="Moderador Líder">Moderador Líder</option>
        <option value="Moderador Supervisor">Moderador Supervisor</option>
        <option value="Administrador Líder">Administrador Líder</option>
        <option value="Administrador Sub Gerente">Administrador Sub Gerente</option>
        <option value="Administrador Gerente">Administrador Gerente</option>
        <option value="Fundador">Fundador</option>
      </select>
    </div>
    <button onclick="login()">Entrar</button>
  </div>

  <!-- Painéis e script continuam iguais, não preciso repetir tudo aqui -->
  <!-- Basta colar o restante do seu código exatamente após esse ponto -->
  <!-- OU me diga se deseja que eu inclua tudo já formatado num arquivo pronto para download -->

<script>
  // SEU SCRIPT ORIGINAL PERMANECE IGUAL
  // (o mesmo código JS que você colou anteriormente)
  // ...
</script>

</body>
</html>
