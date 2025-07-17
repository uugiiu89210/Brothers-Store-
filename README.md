# Brothers-Store-
Brothers Store Demo Site
<!DOCTYPE html><html lang="mn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Brothers Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }
    header {
      background-color: #000;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .logo {
      max-width: 120px;
    }
    h1 {
      margin: 10px 0 0 0;
    }
    .container {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
      gap: 20px;
    }
    .product {
      border: 1px solid #ddd;
      border-radius: 8px;
      background: white;
      padding: 15px;
      text-align: center;
    }
    .product img {
      max-width: 100%;
      height: 150px;
      object-fit: cover;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://chat.openai.com/cdn/BrothersStoreLogo.png" alt="Brothers Store logo" class="logo" />
    <h1>Brothers Store</h1>
    <p>Хэрэгцээт бүхнийг нэг дороос</p>
  </header>
  <div class="container">
    <h2>Бараанууд</h2>
    <div class="products">
      <div class="product">
        <img src="https://cdn.pixabay.com/photo/2021/03/11/14/17/headphones-6086787_1280.jpg" alt="Bluetooth чихэвч">
        <h3>Bluetooth чихэвч</h3>
        <p>55,000₮</p>
        <p>Дууны чанар өндөр, утасгүй</p>
      </div>
      <div class="product">
        <img src="https://cdn.pixabay.com/photo/2020/09/01/15/02/handbag-5534891_1280.jpg" alt="Эмэгтэй цүнх">
        <h3>Эмэгтэй цүнх</h3>
        <p>75,000₮</p>
        <p>Арьсан, 3 төрлийн халаастай</p>
      </div>
      <div class="product">
        <img src="https://cdn.pixabay.com/photo/2017/08/06/00/03/shoes-2583455_1280.jpg" alt="Спорт пүүз">
        <h3>Спорт пүүз</h3>
        <p>120,000₮</p>
        <p>Ус нэвтэрдэггүй, агаар сайн нэвтрүүлдэг</p>
      </div>
      <div class="product">
        <img src="https://cdn.pixabay.com/photo/2020/01/13/17/57/watch-4761147_1280.jpg" alt="Smart Watch">
        <h3>Smart Watch</h3>
        <p>89,000₮</p>
        <p>Даралт, алхам хэмжинэ, усны хамгаалалттай</p>
      </div>
    </div>
  </div>
  <footer>
    <p>📩 r478450@gmail.com | 📱 85844848 | <a href="https://www.facebook.com/share/16omHWUeE9/" style="color:lightblue">Facebook хуудас</a></p>
  </footer>
</body>
</html>
