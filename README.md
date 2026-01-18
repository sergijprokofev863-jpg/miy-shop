
Html
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <title>Все для дому та сім'ї</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Магазин «Все для дому та сім'ї» — товари для дому, хозтовари та кухонні приладдя. Замовлення через Telegram або телефон.">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f2f2f2;
            color: #333;
        }
        header {
            background: #2c7be5;
            color: #fff;
            padding: 25px 15px;
            text-align: center;
        }
        .container {
            max-width: 1100px;
            margin: auto;
            padding: 20px;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 20px;
        }
        .card {
            background: #fff;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            text-align: center;
        }
        .card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }
        .card h3 {
            margin: 15px 0 5px;
        }
        .card p {
            padding: 0 15px;
            font-size: 14px;
        }
        .btn {
            display: inline-block;
            margin: 15px 0 20px;
            padding: 10px 18px;
            background: #2c7be5;
            color: #fff;
            text-decoration: none;
            border-radius: 6px;
        }
        .btn:hover {
            background: #1a5fc4;
        }
        footer {
            background: #222;
            color: #ccc;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
        a {
            color: #2c7be5;
            text-decoration: none;
        }
    </style>
</head>
<body>

<header>
    <h1>Все для дому та сім'ї</h1>
    <p>Зручні та корисні товари для кожного дому</p>
</header>

<div class="container">
    <h2>Наші товари</h2>

    <div class="products">
        <div class="card">
            <img src="https://picsum.photos/400/300?random=1" alt="Все для дому">
            <h3>Все для дому</h3>
            <p>Практичні речі для комфорту та затишку у вашій оселі.</p>
            <a class="btn" href="https://t.me/Prokofiev_X">Замовити</a>
        </div>

        <div class="card">
            <img src="https://picsum.photos/400/300?random=2" alt="Хозтовари">
            <h3>Хозтовари</h3>
            <p>Все необхідне для прибирання та господарства.</p>
            <a class="btn" href="https://t.me/Prokofiev_X">Замовити</a>
        </div>

        <div class="card">
            <img src="https://picsum.photos/400/300?random=3" alt="Кухонні приладдя">
            <h3>Кухонні приладдя</h3>
            <p>Зручні інструменти та дрібниці для кухні.</p>
            <a class="btn" href="https://t.me/Prokofiev_X">Замовити</a>
        </div>
    </div>

    <h2 style="margin-top:30px;">Контакти</h2>
    <p>📲 Telegram: <a href="https://t.me/Prokofiev_X">Prokofiev_X</a></p>
    <p>📞 Телефон: <strong>098 947 7418</strong></p>
</div>

<footer>
    <p>© 2026 Магазин «Все для дому та сім'ї»</p>
</footer>

</body>
</html> 