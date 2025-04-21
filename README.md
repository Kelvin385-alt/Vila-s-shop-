# Vila-s-shop-
Vendas 
<!DOCTYPE html><html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vila's Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f9f9f9;
        }
        header {
            background-color: #111;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #444;
            color: white;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 10px;
            text-decoration: none;
        }
        .container {
            padding: 20px;
        }
        .product {
            background: white;
            padding: 15px;
            margin: 10px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            display: inline-block;
            width: 250px;
            vertical-align: top;
        }
        .product img {
            width: 100%;
            border-radius: 6px;
        }
        .product h3 {
            margin: 10px 0 5px;
        }
        .product p {
            margin: 0 0 10px;
        }
        .whatsapp-button {
            display: inline-block;
            background: #25d366;
            color: white;
            padding: 10px 15px;
            border-radius: 5px;
            text-decoration: none;
        }
        footer {
            background-color: #111;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Vila's Shop</h1>
        <p>Produtos sob encomenda - Preços acessíveis e entrega rápida!</p>
    </header><nav>
    <a href="#">Início</a>
    <a href="#produtos">Produtos</a>
    <a href="#contato">Contato</a>
</nav>

<div class="container" id="produtos">
    <h2>Nossos Produtos</h2>
    <div class="product">
        <img src="https://via.placeholder.com/250x150" alt="Tênis Moderno">
        <h3>Tênis Moderno</h3>
        <p>Confortável e estiloso.</p>
        <a href="https://wa.me/258863347014" class="whatsapp-button">Encomendar</a>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/250x150" alt="Perfume Importado">
        <h3>Perfume Importado</h3>
        <p>Aroma marcante e duradouro.</p>
        <a href="https://wa.me/258863347014" class="whatsapp-button">Encomendar</a>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/250x150" alt="Acessório">
        <h3>Acessório Estiloso</h3>
        <p>Para completar o visual.</p>
        <a href="https://wa.me/258863347014" class="whatsapp-button">Encomendar</a>
    </div>
</div>

<footer id="contato">
    <p>© 2025 Vila's Shop | Contacto via WhatsApp: <a href="https://wa.me/258863347014" style="color: #25d366;">+258 86 334 7014</a></p>
</footer>

</body>
</html>
