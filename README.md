# site-de-pesca

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Pesca</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #004d00;
            color: rgb(6, 151, 1);
            padding: 15px;
            font-size: 24px;
        }
        .banner {
            background-image: url('banner.jpg'); /* Substitua com a URL da imagem */
            background-size: cover;
            background-position: center;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: rgb(158, 7, 7);
            font-size: 28px;
            font-weight: bold;
        }
        .produtos {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .produto {
            border: 1px solid #0ba867;
            border-radius: 10px;
            padding: 10px;
            margin: 10px;
            width: 200px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>Loja de Pesca</header>
    <div class="banner">Bem-vindo à melhor loja de pesca!</div>
    <section class="produtos">
        <div class="produto">
            <img src="vara-pesca.jpg" alt="Vara de Pesca" width="150">
            <p>Vara de Pesca Profissional</p>
            <p>R$ 199,99</p>
        </div>
        <div class="produto">
            <img src="carretilha exemplo.png" alt="Molinete" width="200">
            <p>Carretilha Ultra Resistente</p>
            <p>R$ 149,99</p>
        </div>
    </section>
    <img src="favicon.ico" alt="">
</body>
</html>
