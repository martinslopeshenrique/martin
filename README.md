<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Peças de Carro</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="Logo da Loja">
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Produtos</a></li>
                <li><a href="#">Sobre Nós</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
        <div class="search-bar">
            <input type="text" placeholder="Buscar...">
        </div>
        <div class="cart">
            <a href="#">Carrinho (0)</a>
        </div>
    </header>
    <main>
        <section class="banner">
            <img src="banner.jpg" alt="Promoções de Peças">
        </section>
        <section class="highlights">
            <h2>Produtos em Destaque</h2>
            <div class="product-item">
                <img src="peca-destaque1.jpg" alt="Peça em Destaque 1">
                <h3>Peça em Destaque 1</h3>
                <p>R$ 200,00</p>
            </div>
            <div class="product-item">
                <img src="peca-destaque2.jpg" alt="Peça em Destaque 2">
                <h3>Peça em Destaque 2</h3>
                <p>R$ 150,00</p>
            </div>
        </section>
        <section class="news">
            <h2>Novidades</h2>
            <div class="product-item">
                <img src="nova-peca1.jpg" alt="Nova Peça 1">
                <h3>Nova Peça 1</h3>
                <p>R$ 180,00</p>
            </div>
            <div class="product-item">
                <img src="nova-peca2.jpg" alt="Nova Peça 2">
                <h3>Nova Peça 2</h3>
                <p>R$ 220,00</p>
            </div>
        </section>
        <section class="offers">
            <h2>Ofertas Especiais</h2>
            <div class="product-item">
                <img src="oferta-peca1.jpg" alt="Oferta Peça 1">
                <h3>Oferta Peça 1</h3>
                <p>R$ 170,00</p>
            </div>
            <div class="product-item">
                <img src="oferta-peca2.jpg" alt="Oferta Peça 2">
                <h3>Oferta Peça 2</h3>
                <p>R$ 130,00</p>
            </div>
        </section>
    </main>
    <footer>
        <div class="contact-info">
            <p>Endereço: Rua Exemplo, 123, Cidade, Estado</p>
            <p>Telefone: (00) 1234-5678</p>
            <p>Email: contato@lojadepecas.com.br</p>
        </div>
        <div class="social-media">
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">Twitter</a>
        </div>
    </footer>
</body>
</html>
/* styles.css */

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

header .logo img {
    height: 50px;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.search-bar input {
    padding: 5px;
}

.cart a {
    color: #fff;
    text-decoration: none;
}

.banner img {
    width: 100%;
    height: auto;
}

main {
    padding: 20px;
}

.product-item {
    margin-bottom: 20px;
}

.product-item img {
    width: 100%;
    height: auto;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

footer .contact-info p,
footer .social-media a {
    margin: 5px 0;
}

footer .social-media a {
    color: #fff;
    text-decoration: none;
    margin: 0 10px;
}
