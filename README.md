<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tela de Login</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #f0f4f8;
    }

    .login-container {
      background-color: #d6e4f0; /* tom claro azul */
      padding: 40px;
      border-radius: 15px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
      width: 300px;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .login-container img {
      width: 80px;
      margin-bottom: 20px;
    }

    .login-container h2 {
      margin-bottom: 10px;
    }

    .input-group {
      width: 100%;
      margin-bottom: 15px;
    }

    .input-group label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
      color: #333;
    }

    .input-group input {
      width: 100%;
      padding: 8px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .login-container button {
      margin-top: 10px;
      padding: 10px 20px;
      border: none;
      background-color: #4d8df5;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }

    .login-container button:hover {
      background-color: #3a77d2;
    }
  </style>
</head>
<body>

  <div class="login-container">
    <!-- Ícone de usuário -->
    <img src="https://img.icons8.com/ios-filled/100/000000/user-male-circle.png" alt="User Icon">

    <div class="input-group">
      <label for="usuario">Usuário</label>
      <input type="text" id="usuario" placeholder="Digite seu usuário">
    </div>

    <div class="input-group">
      <label for="senha">Senha</label>
      <input type="password" id="senha" placeholder="Digite sua senha">
    </div>

    <button>Entrar</button>
  </div>

</body>
</html>
