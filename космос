<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Всесвіт: Подорож у Космос</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: linear-gradient(#050d1e, #0d1e40);
      color: #f0f8ff;
      line-height: 1.7;
    }

    header {
      text-align: center;
      padding: 40px 20px;
      background: #0a1128;
      box-shadow: 0 2px 10px #000;
    }

    h1 {
      font-size: 3em;
      color: #00bfff;
      margin-bottom: 10px;
    }

    p.lead {
      font-size: 1.3em;
      color: #b0c4de;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
    }

    section {
      margin-bottom: 50px;
    }

    h2 {
      color: #1e90ff;
    }

    img {
      width: 100%;
      border-radius: 10px;
      margin-top: 15px;
      box-shadow: 0 0 15px #00bfff99;
    }

    footer {
      background: #0a1128;
      text-align: center;
      color: #888;
      padding: 20px;
      font-size: 0.9em;
    }

    /* ===== Анімація планет ===== */
    .solar-system-wrapper {
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 60px 0;
      background: radial-gradient(#000014, #000);
    }

    .solar-system {
      position: relative;
      width: 700px;
      height: 700px;
    }

    .sun {
      position: absolute;
      width: 60px;
      height: 60px;
      background: radial-gradient(circle, #ffdd00, #ff9900);
      border-radius: 50%;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      box-shadow: 0 0 30px 10px #ffaa00;
    }

    .orbit {
      position: absolute;
      border: 1px dashed rgba(255, 255, 255, 0.2);
      border-radius: 50%;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      transition: animation-duration 0.3s ease;
    }

    .planet {
      position: absolute;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      top: 0;
      left: 50%;
      transform: translate(-50%, -50%);
      transform-origin: center center;
      transition: transform 0.3s ease;
    }

    /* Орбіти та швидкість */
    .mercury-orbit { width: 100px; height: 100px; animation: rotate 5s linear infinite; }
    .venus-orbit   { width: 150px; height: 150px; animation: rotate 8s linear infinite; }
    .earth-orbit   { width: 200px; height: 200px; animation: rotate 12s linear infinite; }
    .mars-orbit    { width: 260px; height: 260px; animation: rotate 18s linear infinite; }
    .jupiter-orbit { width: 330px; height: 330px; animation: rotate 24s linear infinite; }
    .saturn-orbit  { width: 420px; height: 420px; animation: rotate 30s linear infinite; }

    .mercury { background: gray; }
    .venus   { background: gold; }
    .earth   { background: #2a9df4; }
    .mars    { background: #d14a28; }
    .jupiter { background: #ffcc66; width: 30px; height: 30px; }
    .saturn {
      background: #deb887;
      width: 26px;
      height: 26px;
      position: relative;
    }

    /* Кільця Сатурна */
    .saturn::before {
      content: "";
      position: absolute;
      width: 40px;
      height: 10px;
      border: 2px solid #c2b280;
      border-radius: 50%;
      left: -7px;
      top: 8px;
      transform: rotate(30deg);
    }

    /* Hover: уповільнення */
    .orbit:hover {
      animation-duration: 60s !important;
    }

    @keyframes rotate {
      from { transform: translate(-50%, -50%) rotate(0deg); }
      to   { transform: translate(-50%, -50%) rotate(360deg); }
    }

    .orbit .planet {
      transform: translateX(50%) translateY(-50%);
    }
  </style>
</head>
<body>

  <header>
    <h1>Всесвіт: Подорож у Космос</h1>
    <p class="lead">Від планет Сонячної системи до далеких галактик — усе, що ви хотіли знати про космос.</p>
  </header>

  <div class="container">
    <section>
      <h2>🔭 Що таке космос?</h2>
      <p>Космос — це безмежний простір, який починається одразу після атмосфери Землі. Тут панує темрява, безповітряність, мільйони зірок, планет, галактик і, можливо, інше життя. Вважається, що Всесвіт виник близько 13,8 мільярда років тому внаслідок Великого вибуху. З того часу він постійно розширюється.</p>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/ESO_-_Milky_Way.jpg/1280px-ESO_-_Milky_Way.jpg" alt="Чумацький Шлях - наша галактика">
    </section>

    <section>
      <h2>🪐 Сонячна система</h2>
      <p>Сонячна система складається з нашого Сонця та всіх небесних тіл, що обертаються навколо нього. Найвідоміші планети: Меркурій, Венера, Земля, Марс, Юпітер, Сатурн, Уран і Нептун. На Юпітері — гігантська буря, а Сатурн славиться своїми кільцями.</p>
      <img src="https://upload.wikimedia.org/wikipedia/commons/9/97/The_Solar_System_planets.png" alt="Планети Сонячної системи">
    </section>

    <section>
      <h2>🚀 Дослідження космосу</h2>
      <p>У 1961 році Юрій Гагарін став першим космонавтом, а в 1969 Ніл Армстронг — першим, хто ступив на Місяць. Сьогодні місії NASA, ESA, SpaceX досліджують Марс, запускають телескопи та мріють про подорожі до інших зірок.</p>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Mars_Rover_Perseverance_-_PIA23764.jpg/1280px-Mars_Rover_Perseverance_-_PIA23764.jpg" alt="Марсохід Perseverance досліджує Марс">
    </section>

    <section>
      <h2>🌌 Анімація Сонячної системи</h2>
      <p>Наведи курсор на будь-яку орбіту — обертання планети уповільниться для детального спостереження.</p>
      <div class="solar-system-wrapper">
        <div class="solar-system">
          <div class="sun"></div>

          <div class="orbit mercury-orbit">
            <div class="planet mercury"></div>
          </div>
          <div class="orbit venus-orbit">
            <div class="planet venus"></div>
          </div>
          <div class="orbit earth-orbit">
            <div class="planet earth"></div>
          </div>
          <div class="orbit mars-orbit">
            <div class="planet mars"></div>
          </div>
          <div class="orbit jupiter-orbit">
            <div class="planet jupiter"></div>
          </div>
          <div class="orbit saturn-orbit">
            <div class="planet saturn"></div>
          </div>
        </div>
      </div>
    </section>
  </div>

  <footer>
    <p>© 2025 Всесвіт. Сайт створено для всіх, хто мріє про зірки ✨</p>
  </footer>

</body>
</html>
