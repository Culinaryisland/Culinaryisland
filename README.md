- 👋 Hi, I’m @Culinaryisland
- <!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Кулінарний Острівець</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background-color: #ff7043;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
            font-size: 36px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background: url('https://via.placeholder.com/1920x500') no-repeat center center;
            background-size: cover;
            color: white;
        }
        .hero h2 {
            font-size: 48px;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }
        .product {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 150px;
            border-radius: 8px;
        }
        .product-info {
            flex: 1;
            margin-left: 20px;
        }
        .product h3 {
            margin: 0;
        }
        .order-form {
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }
        .order-form h3 {
            margin-bottom: 10px;
        }
        .order-form label {
            display: block;
            margin: 10px 0 5px;
        }
        .order-form input, .order-form textarea, .order-form select, .order-form button {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        .order-form button {
            background-color: #ff7043;
            color: white;
            border: none;
            cursor: pointer;
        }
        .order-form button:hover {
            background-color: #e95d35;
        }
        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 20px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Кулінарний Острівець</h1>
        <p>Ваш смак у нашій турботі</p>
    </header>
    <nav>
        <a href="#products">Продукти</a>
        <a href="#order">Замовлення</a>
        <a href="#contact">Контакти</a>
    </nav>
    <div class="hero">
        <h2>Свіжі напівфабрикати з любов'ю</h2>
        <p>Замовляйте вареники, пельмені, млинчики та багато іншого</p>
    </div>
    <div class="container" id="products">
        <h2>Наша продукція</h2>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Вареники">
            <div class="product-info">
                <h3>Вареники</h3>
                <p>З картоплею, сиром, м'ясом та іншими начинками.</p>
                <p><strong>Ціна:</strong> від 100 грн/кг</p>
            </div>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Пельмені">
            <div class="product-info">
                <h3>Пельмені</h3>
                <p>Класичні, домашні, міні та багато іншого.</p>
                <p><strong>Ціна:</strong> від 120 грн/кг</p>
            </div>
        </div>
    </div>
    <div class="container" id="order">
        <h2>Замовлення</h2>
        <form class="order-form">
            <h3>Заповніть форму для замовлення</h3>
            <label for="name">Ваше ім'я:</label>
            <input type="text" id="name" name="name" placeholder="Введіть ваше ім'я" required>

            <label for="phone">Телефон:</label>
            <input type="tel" id="phone" name="phone" placeholder="Введіть ваш номер телефону" required>

            <label for="address">Адреса доставки:</label>
            <textarea id="address" name="address" placeholder="Введіть вашу адресу" required></textarea>

            <label for="product">Оберіть продукт:</label>
            <select id="product" name="product" required>
                <option value="Вареники">Вареники</option>
                <option value="Пельмені">Пельмені</option>
                <option value="Млинці">Млинці</option>
                <option value="Котлети">Котлети</option>
            </select>

            <label for="quantity">Кількість (кг):</label>
            <input type="number" id="quantity" name="quantity" placeholder="Введіть кількість" required>

            <button type="submit">Оформити замовлення</button>
        </form>
    </div>
    <footer>
        <p>Кулінарний Острівець &copy; 2025 | Всі права захищені</p>
    </footer>
</body>
</html>
