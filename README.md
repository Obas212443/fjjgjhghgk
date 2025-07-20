<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sign In</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f1f1f1;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .login-box {
      background-color: white;
      padding: 40px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      width: 300px;
    }

    .login-box img {
      display: block;
      margin: 0 auto 20px;
      width: 40px;
    }

    .login-box h2 {
      text-align: center;
      margin-bottom: 20px;
    }

    .login-box input[type="text"],
    .login-box input[type="password"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    .login-box button {
      width: 100%;
      padding: 10px;
      background-color: #007db8;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    .login-box label {
      font-size: 14px;
    }

    .login-box input[type="checkbox"] {
      margin-right: 5px;
    }
  </style>
</head>
<body>
  <div class="login-box">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/33/Yellow_circle_with_g.svg/768px-Yellow_circle_with_g.svg.png" alt="Logo">
    <h2>Sign In</h2>
    <form>
      <input type="text" placeholder="Username" required>
      <input type="password" placeholder="Password" required>
      <label><input type="checkbox"> Stay signed in</label>
      <button type="submit">Sign In</button>
    </form>
  </div>
</body>
</html>
