<!DOCTYPE html><html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cartão Interativo</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
            padding: 50px;
        }
        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            display: inline-block;
        }
        .button {
            background: #ff4081;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        .hidden-message {
            display: none;
            margin-top: 20px;
            font-size: 18px;
            color: #333;
        }
    </style>
</head>
<body>
    <div class="card">
        <h2>Surpresa Especial!</h2>
        <button class="button" onclick="showMessage()">Toque Aqui</button>
        <p class="hidden-message" id="message">Você é incrível! Espero que seu dia seja maravilhoso! 💖</p>
    </div><script>
    function showMessage() {
        document.getElementById("message").style.display = "block";
    }
</script>

</body>
</html>
