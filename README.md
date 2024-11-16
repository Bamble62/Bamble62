- 👋 Hi, I’m @Bamble62
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Bamble62/Bamble62 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Магазин Одежды</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; }
        .item { margin: 20px; border: 1px solid #ddd; padding: 10px; }
        button { background: #0088cc; color: white; padding: 10px; border: none; cursor: pointer; }
    </style>
</head>
<body>
    <h1>Магазин Одежды</h1>
    <div class="item">
        <img src="https://example.com/image1.jpg" alt="Товар 1" width="200">
        <p>Футболка - 2000₸</p>
        <button onclick="buyItem('Футболка')">Купить</button>
    </div>
    <div class="item">
        <img src="https://example.com/image2.jpg" alt="Товар 2" width="200">
        <p>Худи - 5000₸</p>
        <button onclick="buyItem('Худи')">Купить</button>
    </div>
    <script>
        function buyItem(item) {
            window.Telegram.WebApp.showAlert(`Вы выбрали: ${item}. Напишите админу для заказа!`);
        }
    </script>
</body>
</html>
