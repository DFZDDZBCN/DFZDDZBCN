<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Spotify Login</title>
    <style>
      body {
        font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
        background-color: #1c1c1c;
        color: #fff;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 0;
      }

      .login-box {
        width: 300px;
        padding: 20px;
        background-color: #222;
        border-radius: 5px;
        box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.3);
        display: flex;
        flex-direction: column;
        align-items: center;
      }

      .login-box h2 {
        text-align: center;
        margin-bottom: 20px;
      }

      .login-box input[type="text"],
      .login-box input[type="password"] {
        width: 100%;
        padding: 10px;
        margin-bottom: 10px;
        border: none;
        border-radius: 5px;
        background-color: #333;
        color: #fff;
      }

      .login-box input[type="submit"] {
        width: 100%;
        padding: 10px;
        background-color: #1ed760;
        color: #222;
        border: none;
        border-radius: 5px;
        cursor: pointer;
      }

      .login-box input[type="submit"]:hover {
        background-color: #1db959;
      }
    </style>
  </head>
  <body>
    <div class="login-box">
      <h2>Login to SPOTIFY</h2>
      <form>
        <input type="text" placeholder="Email or username" />
        <input type="password" placeholder="Password" />
        <input type="submit" value="Log in" />
      </form>
    </div>
  </body>
</html>
