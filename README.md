<!DOCTYPE html>
<html lang="kk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Менің сайтым</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header, footer {
      background-color: #4CAF50;
      color: white;
      text-align: center;
      padding: 1em;
    }
    section {
      padding: 20px;
    }
    .contact {
      background: #f1f1f1;
      padding: 20px;
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Менің жеке сайтым</h1>
  </header>

  <section>
    <h2>Басты бет</h2>
    <p>Бұл менің жеке веб-сайтымның басты беті.</p>
  </section>

  <!-- 📞 Байланыс бөлімі -->
  <section class="contact">
    <h2>Байланыс</h2>
    <form>
      <label>Атыңыз:</label><br>
      <input type="text" placeholder="Атыңызды енгізіңіз"><br><br>
      <label>Электронды пошта:</label><br>
      <input type="email" placeholder="example@gmail.com"><br><br>
      <label>Хабарлама:</label><br>
      <textarea rows="4" placeholder="Хабарламаңызды жазыңыз"></textarea><br><br>
      <button type="submit">Жіберу</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Менің сайтым</p>
  </footer>

</body>
</html>
