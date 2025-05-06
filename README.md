# Privat-sel-1<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Privat Sale HONI</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>🚀 Privat Sale Sedang Berlangsung!</h1>
        <p>Jangan lewatkan kesempatan eksklusif ini!</p>
        <div id="status-sale"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>body {
    font-family: Arial, sans-serif;
    background: #111;
    color: #fff;
    text-align: center;
}

.container {
    margin-top: 50px;
}

#status-sale {
    font-size: 20px;
    font-weight: bold;
    color: #ff4500;
}document.getElementById("status-sale").innerHTML = "Privat Sale Sedang Berlangsung!";
