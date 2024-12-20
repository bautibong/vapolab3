<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VapoLab</title>
    <meta name="description" content="Descubre los mejores vapes con envío gratis. Calidad garantizada.">
    <meta name="keywords" content="vapes, vaporizadores, envío gratis, calidad garantizada">
    <meta name="author" content="VapoLab">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');

        body {
            font-family: 'Poppins', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        .logo {
            font-size: 2.5em;
            font-weight: 700;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background: linear-gradient(135deg, #b2dcd7, #f5f5f5);
        }
        .hero h1 {
            color: #2a2a2a;
            font-size: 3em;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 1.2em;
            color: #555;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .product-card {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            margin: 15px;
            padding: 15px;
            width: 300px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.2);
        }
        .product-card img {
            max-width: 100%;
            border-radius: 8px;
            display: block;
            margin: 0 auto;
        }
        .product-card h3 {
            margin: 15px 0 10px;
            color: #2a2a2a;
            font-size: 1.3em;
        }
        .product-card p {
            color: #666;
            font-size: 0.9em;
        }
        .stock {
            font-size: 1em;
            font-weight: bold;
            margin-top: 10px;
        }
        .in-stock {
            color: green;
        }
        .out-of-stock {
            color: red;
        }
        .contact {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
        }
        .contact a {
            color: #b2dcd7;
            text-decoration: none;
            font-weight: bold;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #444;
            color: #ccc;
        }
    </style>
</head>
<body>
    <header role="banner">
        <div class="logo">VapoLab</div>
    </header>

    <section class="hero" role="region" aria-labelledby="hero-heading">
        <h1 id="hero-heading">Bienvenido a VapoLab</h1>
        <p>Descubre los mejores vapes con envío gratis. Calidad garantizada.</p>
    </section>

    <section class="products" role="region" aria-labelledby="products-heading">
        <h2 id="products-heading" class="visually-hidden">Productos</h2>
        <div class="product-card" role="article">
            <img src="https://vapos.uy/wp-content/uploads/2024/08/wefume-strawberry-kiwi-600x600.webp" alt="WeFume" loading="lazy">
            <h3>WeFume</h3>
            <p>Elegante, moderno y con una experiencia única.</p>
            <p class="stock out-of-stock">Sin stock</p>
        </div>
        <div class="product-card" role="article">
            <img src="https://rosariovapeshop.com/wp-content/uploads/2024/11/1000490622-3.jpg" alt="ElfBar King Ice 40K" loading="lazy">
            <h3>ElfBar King Ice 40K</h3>
            <p>Diseño fresco y gran rendimiento para largas sesiones.</p>
            <p class="stock in-stock">En stock</p>
            <p>Sabores: Miami Mint</p>
        </div>
        <div class="product-card" role="article">
            <img src="https://indyargentina.com/cdn/shop/files/lost-mary-mixer-30000-orange-strawberry-684453_800x.jpg?v=1731086779" alt="LostMary Mixer" loading="lazy">
            <h3>LostMary Mixer</h3>
            <p>Colores vibrantes y una experiencia de vapeo incomparable.</p>
            <p class="stock in-stock">En stock</p>
            <p>Sabores: Watermelon Blowpop, Blueberry Watermelon</p>
        </div>
        <div class="product-card" role="article">
            <img src="https://jackvapestore.com/1988-large_default/elfbar-touch-10000-puffs-citrus-grape.jpg" alt="ElfBar 10K Touch" loading="lazy">
            <h3>ElfBar 10K Touch</h3>
            <p>Compacto, elegante y fácil de usar.</p>
            <p class="stock in-stock">En stock</p>
            <p>Sabores: Miami Mint</p>
        </div>
        <div class="product-card" role="article">
            <img src="https://podvapeshop.com/wp-content/uploads/2024/10/Elf-Bar-Bc-10000-Black-Gold-Pod-Descartavel.jpg" alt="ElfBar 10K Gold" loading="lazy">
            <h3>ElfBar 10K Gold</h3>
            <p>Diseño premium y sabores intensos.</p>
            <p class="stock in-stock">En stock</p>
            <p>Sabores: Blue Razz Ice, Peach Mango Watermelon</p>
        </div>
        <div class="product-card" role="article">
            <img src="https://atacadousa.com.py/img/p/1/9/9/2/1992-home_default.jpg" alt="ElfBar TE 30K" loading="lazy">
            <h3>ElfBar TE 30K</h3>
            <p>Ideal para quienes buscan variedad y potencia.</p>
            <p class="stock in-stock">En stock</p>
            <p>Sabores: Sour Raspberry, Sour Lush Gummy, Strawmelon Peach, Blue Sour Raspberry, Bubbaloo Grape</p>
        </div>
        <div class="product-card" role="article">
            <img src="https://vapesvault.com.ar/wp-content/uploads/2022/04/ignite-v150-600x600.jpg" alt="Ignite V150" loading="lazy">
            <h3>Ignite V150</h3>
            <p>Innovador y versátil, ideal para los amantes del vapeo.</p>
            <p class="stock out-of-stock">Sin stock</p>
        </div>
    </section>

    <section class="contact" role="region" aria-labelledby="contact-heading">
        <h2 id="contact-heading" class="visually-hidden">Contacto</h2>
        <p>Contáctanos para realizar tu pedido:</p>
        <p><a href="https://wa.me/3571510327" target="_blank" rel="noopener">WhatsApp: 3571510327</a></p>
    </section>

    <footer role="contentinfo">
        <p>© 2024 VapoLab. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
