<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cardápio da Lanchonete F</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff8ec;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #a52a2a;
            color: white;
            text-align: center;
            padding: 24px 16px;
        }

        header h1 {
            margin: 0;
            font-size: 35.2px;
        }

        header h2 {
            margin: 8px 0 0;
            font-weight: normal;
            font-size: 19.2px;
        }

        .comida {
            display: flex;
            flex-direction: column;
            gap: 32px;
            padding: 32px;
            max-width: 800px;
            margin: 0 auto;
        }

        .comida>div {
            background-color: #fff;
            border: 2px solid #a52a2a;
            border-radius: 10px;
            padding: 16px;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
        }

        h3 {
            margin-top: 0;
            border-bottom: 1px solid #a52a2a;
            padding-bottom: 8px;
            color: #a52a2a;
            cursor: pointer;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        li {
            margin-bottom: 16px;
        }

        .item {
            display: flex;
            justify-content: space-between;
            font-weight: bold;
        }

        .descricao {
            margin: 5px 0 11px;
            font-size: 15px;
            color: #555;
        }

        footer {
            background-color: #a52a2a;
            color: white;
            text-align: center;
            padding: 16px;
            margin-top: 32px;
        }

        footer p {
            margin: 5px 0;
        }

        #busca {
            display: block;
            margin: 32px auto 16px;
            padding: 8px;
            font-size: 16px;
            width: 80%;
            max-width: 400px;
            border: 2px solid #a52a2a;
            border-radius: 8px;
        }

        .escondido {
            display: none;
        }

        .destaque {
            background-color: #ffff99;
        }
    </style>
</head>

<body>
    <header>
        <h1>Cardápio da Lanchonete do Felpz</h1>
        <h2>Um sabor histórico.</h2>
    </header>

    <input type="text" id="busca" placeholder="Buscar item...">

    <div class="comida">
        <div class="lanche">
            <h3">Lanches</h3>
                <ul>
                    <li>
                        <div class="item">
                            <span>X-Burger</span>
                            <span>R$15,00</span>
                        </div>
                        <p class="descricao">Pão, carne, salada, queijo, tomate</p>
                    </li>
                    <li>
                        <div class="item">
                            <span>Frango</span>
                            <span>R$15,00</span>
                        </div>
                        <p class="descricao">Pão, frango, salada, queijo, tomate</p>
                    </li>
                    <li>
                        <div class="item">
                            <span>Especial</span>
                            <span>R$25,00</span>
                        </div>
                        <p class="descricao">O que tiver a gente bota dentro</p>
                    </li>
                </ul>
        </div>

        <div class="porcao">
            <h3">Porções</h3>
                <ul>
                    <li>
                        <div class="item">
                            <span>Camarão</span>
                            <span>R$35,00</span>
                        </div>
                        <p class="descricao">Porção de camarão para aproximadamente 5 pessoas</p>
                    </li>
                    <li>
                        <div class="item">
                            <span>Batata Frita</span>
                            <span>R$30,00</span>
                        </div>
                        <p class="descricao">Porção de batata frita para aproximadamente 5 pessoas</p>
                    </li>
                    <li>
                        <div class="item">
                            <span>Salame</span>
                            <span>R$50,00</span>
                        </div>
                        <p class="descricao">Porção de salame para aproximadamente 5 pessoas</p>
                    </li>
                </ul>
        </div>

        <div class="bebidas">
            <h3>Bebidas</h3>
            <ul>
                <li>
                    <div class="item">
                        <span>Coca-Cola</span>
                        <span>R$6,00</span>
                    </div>
                    <p class="descricao">Lata de Coca-Cola - 500ml</p>
                </li>
                <li>
                    <div class="item">
                        <span>Pepsi</span>
                        <span>R$5,00</span>
                    </div>
                    <p class="descricao">Lata de Pepsi - 500ml</p>
                </li>
                <li>
                    <div class="item">
                        <span>Suco</span>
                        <span>R$7,00</span>
                    </div>
                    <p class="descricao">Copo de suco - 500ml</p>
                </li>
            </ul>
        </div>
    </div>

    <footer>
        <p>Endereço: Rua Melinda Molobi</p>
        <p>Funcionamento: 14:00 - 22:00</p>
        <p>Criado por Felpão</p>
    </footer>
</body>

</html>
