
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - Review Film Harry Potter</title>
    <link href="https://fonts.googleapis.com/css2?family=Harry+Potter&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Harry Potter', sans-serif;
            background-color: #2c2f33; /* Warna gelap yang terinspirasi oleh Hogwarts */
            background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://example.com/harry-potter-background.jpg'); /* Ganti dengan URL gambar latar belakang yang sesuai */
            background-size: cover;
            background-position: center;
            margin: 0;
            padding: 0;
            color: #fff;
        }

        .login-container {
            max-width: 400px;
            margin: 100px auto;
            padding: 20px;
            background: rgba(0, 0, 0, 0.8);
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
            text-align: center;
        }

        h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
            text-shadow: 2px 2px 5px rgba(255, 215, 0, 0.8); /* Warna emas untuk efek bayangan */
        }

        form {
            display: flex;
            flex-direction: column;
        }

        label {
            margin: 10px 0 5px;
            font-size: 1.2em;
        }

        input {
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1em;
        }

        button {
            padding: 10px;
            background-color: #5cb85c;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.2em;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #4cae4c;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h2>Welcome to HOGWARTS FAMILY</h2>
        <form action="dashboard.html" method="GET">
            <label for="username">Username:</label>
            <input type="text" id="spell" name="spell" required>
            <label for="password">Password:</label>
            <input type="password" id="hogwarts" name="hogwarts" required>
            <button type="submit">Masuk</button>
        </form>
    </div>
</body>
</html>     
