<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <title>Logowanie</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #eef;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      flex-direction: column;
    }
    .login-box {
      background-color: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
      text-align: center;
    }
    input {
      margin: 10px;
      padding: 10px;
      width: 200px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    button {
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    #smile {
      font-size: 100px;
      margin-top: 20px;
      display: none;
    }
  </style>
</head>
<body>
  <div class="login-box">
    <h2>Zaloguj się</h2>
    <input type="text" id="username" placeholder="Nazwa użytkownika"><br>
    <input type="password" id="password" placeholder="Hasło"><br>
    <button onclick="login()">Zaloguj</button>
    <div id="message"></div>
  </div>
  <div id="smile">😄</div>

  <script>
    const accounts = {
      mikloszyn: "1234",
      kolaga123: "4321"
    };

    function login() {
      const user = document.getElementById("username").value;
      const pass = document.getElementById("password").value;
      const message = document.getElementById("message");
      const smile = document.getElementById("smile");

      if (accounts[user] === pass) {
        message.innerHTML = "Witaj, " + user + "!";
        smile.style.display = "block";
      } else {
        message.innerHTML = "Nieprawidłowa nazwa lub hasło.";
        smile.style.display = "none";
      }
    }
  </script>
</body>
</html>
