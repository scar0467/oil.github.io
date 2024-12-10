<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Магазин Моторных Масел</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
/*         header {
            background-color: #35424a;
            color: #ffffff;
            padding: 10px 0;
            text-align: center;
        } */
        .container {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            padding: 10px;
        }
        .product-card {
            background-color: #ffffff;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 10px 0;
            width: 90%; /* Ширина карточки для мобильных устройств */
            max-width: 400px; /* Ограничение ширины для больших экранов */
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
        }
        .product-image {
            width: 100%;
            height: auto;
            border-bottom: 1px solid #ddd;
        }
        .product-info {
            padding: 15px;
        }
        .product-title {
            font-size: 16px;
            margin-bottom: 10px;
        }
        .product-description {
            font-size: 14px;
            color: #666;
            margin-bottom: 10px;
        }
        .product-price {
            font-size: 16px;
            font-weight: bold;
            color: #333;
            margin-bottom: 10px;
        }

        /* Медиа-запросы для небольших экранов */
        @media (max-width: 480px) {
            .product-title {
                font-size: 14px;
            }
            .product-description {
                font-size: 12px;
            }
            .product-price {
                font-size: 14px;
            }
        }
    </style>
</head>
<body>


<main class="container">
    <div class="product-card">
        <img src="https://w7.pngwing.com/pngs/890/55/png-transparent-motor-oil-exxonmobil-lubricant-lubricant-motorcycle-oil-engine-thumbnail.png" alt="Масло 1" class="product-image">
        <div class="product-info">
            <h2 class="product-title">Моторное масло 5W-30</h2>
            <p class="product-description">Высококачественное синтетическое масло для легковых автомобилей с превосходными защитными свойствами.</p>
            <p class="product-price">1200 ₽</p>
        </div>
    </div>

    <div class="product-card">
        <img src="https://w7.pngwing.com/pngs/297/514/png-transparent-motorcycle-exxonmobil-motor-oil-lubricant-motorcycle-motorcycle-oil-engine-thumbnail.png" alt="Масло 2" class="product-image">
        <div class="product-info">
            <h2 class="product-title">Моторное масло 10W-40</h2>
            <p class="product-description">Полусинтетическое масло для двигателей с увеличенным сроком службы и отличной стабильностью.</p>
            <p class="product-price">900 ₽</p>
        </div>
    </div>

    <div class="product-card">
        <img src="https://w7.pngwing.com/pngs/355/501/png-transparent-car-castrol-motor-oil-european-automobile-manufacturers-association-synthetic-oil-car-diesel-fuel-car-transport-thumbnail.png" alt="Масло 2" class="product-image">
        <div class="product-info">
            <h2 class="product-title">Моторное масло 10W-40</h2>
            <p class="product-description">Полусинтетическое масло для двигателей с увеличенным сроком службы и отличной стабильностью.</p>
            <p class="product-price">900 ₽</p>
        </div>
    </div>

    <div class="product-card">
        <img src="https://w7.pngwing.com/pngs/631/579/png-transparent-mobil-1-synthetic-oil-motor-oil-lubricant-engine-diesel-fuel-oil-transport-thumbnail.png" alt="Масло 2" class="product-image">
        <div class="product-info">
            <h2 class="product-title">Моторное масло 10W-40</h2>
            <p class="product-description">Полусинтетическое масло для двигателей с увеличенным сроком службы и отличной стабильностью.</p>
            <p class="product-price">900 ₽</p>
        </div>
    </div>

    <div class="product-card">
        <img src="https://w7.pngwing.com/pngs/355/501/png-transparent-car-castrol-motor-oil-european-automobile-manufacturers-association-synthetic-oil-car-diesel-fuel-car-transport-thumbnail.png" alt="Масло 2" class="product-image">
        <div class="product-info">
            <h2 class="product-title">Моторное масло 10W-40</h2>
            <p class="product-description">Полусинтетическое масло для двигателей с увеличенным сроком службы и отличной стабильностью.</p>
            <p class="product-price">900 ₽</p>
        </div>
    </div>

    <div class="product-card">
        <img src="https://w7.pngwing.com/pngs/631/579/png-transparent-mobil-1-synthetic-oil-motor-oil-lubricant-engine-diesel-fuel-oil-transport-thumbnail.png" alt="Масло 2" class="product-image">
        <div class="product-info">
            <h2 class="product-title">Моторное масло 10W-40</h2>
            <p class="product-description">Полусинтетическое масло для двигателей с увеличенным сроком службы и отличной стабильностью.</p>
            <p class="product-price">900 ₽</p>
        </div>
    </div>

    <!-- Добавьте больше карточек товаров по аналогии -->

</main>

</body>
</html>
