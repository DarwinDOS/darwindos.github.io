<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Моё 3D Портфолио</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: 'Inter', sans-serif;
      background: #0f172a;
      color: #e2e8f0;
      line-height: 1.6;
    }

    header {
      padding: 40px 20px;
      text-align: center;
      background: linear-gradient(135deg, #1e293b, #020617);
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    header p {
      color: #94a3b8;
    }

    .container {
      max-width: 1100px;
      margin: 40px auto;
      padding: 0 20px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 30px;
    }

    .card {
      background: #1e293b;
      border-radius: 16px;
      overflow: hidden;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .card:hover {
      transform: translateY(-8px);
      box-shadow: 0 10px 30px rgba(0,0,0,0.5);
    }

    .card iframe {
      width: 100%;
      height: 300px;
      border: none;
    }

    .card-content {
      padding: 15px;
    }

    .card-content h3 {
      margin-bottom: 8px;
    }

    .card-content p {
      font-size: 0.9rem;
      color: #94a3b8;
    }

    footer {
      text-align: center;
      padding: 30px;
      margin-top: 40px;
      color: #64748b;
      border-top: 1px solid #1e293b;
    }

    a {
      color: #38bdf8;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

<header>
  <h1>Моё 3D Портфолио</h1>
  <p>3D Artist | Game Assets | Visualization</p>
</header>

<section class="container">
  <div class="grid">

    <!-- Model 1 -->
    <div class="card">
      <iframe src="https://sketchfab.com/models/YOUR_MODEL_ID_1/embed" allowfullscreen></iframe>
      <div class="card-content">
        <h3>Название модели 1</h3>
        <p>Краткое описание модели.</p>
      </div>
    </div>

    <!-- Model 2 -->
    <div class="card">
      <iframe src="https://sketchfab.com/models/YOUR_MODEL_ID_2/embed" allowfullscreen></iframe>
      <div class="card-content">
        <h3>Название модели 2</h3>
        <p>Краткое описание модели.</p>
      </div>
    </div>

    <!-- Model 3 -->
    <div class="card">
      <iframe src="https://sketchfab.com/models/YOUR_MODEL_ID_3/embed" allowfullscreen></iframe>
      <div class="card-content">
        <h3>Название модели 3</h3>
        <p>Краткое описание модели.</p>
      </div>
    </div>

  </div>
</section>

<footer>
  <p>© 2026 DarwinDOS | Сделано с ❤️</p>
</footer>

</body>
</html>
