<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Ajude uma Instituição de Adoção de Animais com doações de ração, brinquedos e voluntariado.">
    <meta name="author" content="Sua Instituição">
    <title>Encontra seu Animal Aqui</title>

    <meta name="theme-color" content="#ff9800"> 
    <link rel="icon" href="favicon.ico" type="image/x-icon"> 

    <link rel="apple-touch-icon" href="icons/apple-icon-180x180.png">
    <link rel="icon" sizes="192x192" href="icons/android-icon-192x192.png"> 

    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f9f9f9;
        }
        header {
            background-color: #043db9;
            padding: 20px;
            color: white;
            font-size: 26px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        .container {
            max-width: 1200px;
            margin: 40px auto;
            padding: 20px;
            background: white;
            border-radius: 15px;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
            box-sizing: border-box;
        }
        img {
            width: 100%;
            max-width: 600px;
            border-radius: 15px;
            box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
        }
        img:hover {
            transform: scale(1.05);
        }
        .button {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 30px;
            background-color: #043db9;
            color: white;
            text-decoration: none;
            border-radius: 30px;
            font-weight: bold;
            text-transform: uppercase;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #043db9;
        }
        footer {
            background-color: #043db9;
            padding: 20px;
            color: white;
            font-size: 18px;
            text-align: center;
        }
        .donate-options {
            text-align: left;
            margin-top: 20px;
        }
        .social-icons {
            margin-top: 30px;
        }
        .social-icons a {
            margin: 0 10px;
            text-decoration: none;
            font-size: 24px;
            color: #ff9800;
            transition: color 0.3s;
        }
        .social-icons a:hover {
            color: #e68900;
        }

        /* Responsividade */
        @media (max-width: 768px) {
            header {
                font-size: 22px;
            }
            .container {
                padding: 15px;
            }
            img {
                width: 90%;
                max-width: 500px;
            }
        }

        @media (max-width: 480px) {
            header {
                font-size: 20px;
            }
            .container {
                padding: 10px;
            }
            img {
                width: 100%;
                max-width: 400px;
            }
            footer {
                font-size: 16px;
            }
        }
    </style>
</head>
<body>
    <header>Ajude os Animais</header>
    <div class="container">
        <h2>Ajude uma Instituição de Adoção de Animais</h2>
        <p>Doe ração, brinquedos e outros itens para ajudar cães e gatos resgatados!</p>
        <img src="https://static9.depositphotos.com/1003346/1115/v/450/depositphotos_11157216-stock-illustration-sad-puppy-dachshund.jpg" alt="Animais para adoção">
        
        <h3>Como Doar?</h3>
        <div class="donate-options">
            <p><strong>1. Doação de Itens:</strong> Entregue ração, brinquedos e outros suprimentos no endereço: Rua Exemplo, 123, Cidade.</p>
            <p><strong>2. Doação em Dinheiro:</strong> Pix: ajuda@instituicao.com</p>
            <p><strong>3. Voluntariado:</strong> Entre em contato pelo WhatsApp: (11) 99999-9999</p>
        </div>

        <div class="social-icons">
            <a href="https://facebook.com" target="_blank">Facebook</a>
            <a href="https://instagram.com" target="_blank">Instagram</a>
            <a href="https://twitter.com" target="_blank">Twitter</a>
        </div>

        <a href="https://pagamento-link.com" class="button">Faça sua Doação Agora</a>
    </div>
    
    <footer>
        <p>Obrigado por apoiar nossa causa!</p>
    </footer>
</body>
</html>

