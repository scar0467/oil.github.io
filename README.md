<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ассортимент моторных масел</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f4f4f9;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            padding: 10px;
            border-bottom: 1px solid #ccc;
            text-align: left;
        }
        th {
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>

<h1>Ассортимент моторных масел</h1>
<p>Добро пожаловать! Здесь вы можете ознакомиться с ассортиментом моторных масел, доступных на наших АЗС.</p>

<table id="oilTable">
    <thead>
        <tr>
            <th>Название</th>
            <th>Тип</th>
            <th>Вязкость</th>
            <th>Цена</th>
        </tr>
    </thead>
    <tbody>
        <!-- Данные будут загружены здесь с помощью JavaScript -->
    </tbody>
</table>

<script>
    const oils = [
        { name: "Масло X", type: "Синтетическое", viscosity: "5W-30", price: "1000 руб" },
        { name: "Масло Y", type: "Минеральное", viscosity: "10W-40", price: "800 руб" },
        { name: "Масло Z", type: "Синтетическое", viscosity: "0W-20", price: "1200 руб" }
        // Добавьте больше объектов с маслами, если необходимо
    ];

    function loadData() {
        const tableBody = document.querySelector("#oilTable tbody");
        oils.forEach(oil => {
            const row = document.createElement("tr");
            row.innerHTML = `
                <td>${oil.name}</td>
                <td>${oil.type}</td>
                <td>${oil.viscosity}</td>
                <td>${oil.price}</td>
            `;
            tableBody.appendChild(row);
        });
    }

    // Загрузка данных при загрузке страницы
    window.onload = loadData;
</script>

</body>
</html>
