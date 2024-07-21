<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            color: #333;
        }
        .bio {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .bio img {
            border-radius: 50%;
            width: 120px;
            height: 120px;
            object-fit: cover;
            margin-bottom: 20px;
        }
        .bio p {
            font-size: 18px;
            color: #666;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            margin: 10px;
            font-size: 18px;
            color: #fff;
            background-color: #28a745; /* Cor verde */
            border: none;
            border-radius: 5px;
            text-decoration: none;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #218838;
        }
        @media (max-width: 600px) {
            .button {
                display: block;
                width: 100%;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="bio">
            <img src="sua-foto.jpg" alt="Foto de David">
            <h1>Sobre Mim</h1>
            <p>Olá, sou David Lawrence, apaixonado por tecnologia e criação de conteúdo na área de informática. Este site é o meu espaço para compartilhar conhecimentos, dicas e novidades sobre o mundo da tecnologia. Explore meu canal do YouTube, acompanhe minhas redes sociais e descubra meus e-books e outros produtos!</p>
            <a href="https://www.youtube.com/c/seucanal" class="button">Canal do YouTube</a>
            <a href="https://www.instagram.com/seuperfil" class="button">Instagram</a>
            <a href="https://www.tiktok.com/@seuperfil" class="button">TikTok</a>
            <a href="https://www.seusite.com/loja" class="button">Loja de E-books</a>
        </div>
    </div>
</body>
</html>
