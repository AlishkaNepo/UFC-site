<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>UFC 344</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet">
</head>
<body>

<header>
  <div class="logo">UFC 344</div>
  <nav class="nav">
  </nav>
</header>
<style>* {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Inter', sans-serif;
    }

    body {
      background: #0d0d0d;
      color: #fff;
    }

    header {
      background: linear-gradient(90deg, #c40000, #7a0000);
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 26px;
      font-weight: 700;
      letter-spacing: 2px;
    }

    .nav a {
      color: #fff;
      text-decoration: none;
      margin-left: 20px;
      font-weight: 600;
      transition: 0.3s;
    }

    .nav a:hover {
      opacity: 0.7;
    }

    .container {
      max-width: 1200px;
      margin: 40px auto;
      padding: 0 20px;
    }

    .event-header {
      background: #1a1a1a;
      padding: 20px;
      border-radius: 12px;
      margin-bottom: 30px;
    }

    .event-header h1 {
      font-size: 28px;
      margin-bottom: 10px;
    }

    .fights {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }

    .fight-card {
      background: #111;
      border-radius: 16px;
      padding: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.5);
      transition: 0.3s;
    }

    .fight-card:hover {
      transform: scale(1.02);
    }

    .fighters {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .fighter {
      text-align: center;
    }

    .vs {
      font-size: 22px;
      font-weight: bold;
      color: #c40000;
    }

    .weight {
      text-align: center;
      margin-top: 15px;
      font-size: 14px;
      color: #aaa;
    }

    footer {
      text-align: center;
      position:absolute;
      color: #666;
      left:575px;
      top:675px;
    }
    #tomi{
        width: 55px;
        height:55px;
        border-radius:50%;
    }
     #ali{
        width: 65px;
        height:55px;
        border-radius:50%;
    }
   
    .container2 {
    position:absolute;
    width:1150px;
    height:130px;
    left:190px;
    }

    .fights2 {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }

    .fight-card2 {
      background: #111;
      border-radius: 16px;
      padding: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.5);
      transition: 0.3s;
    }

    .fight-card:hover2 {
      transform: scale(1.02);
    }

    .fighters2 {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .fighter2 {
      text-align: center;
    }

    .vs2 {
      font-size: 22px;
      font-weight: bold;
      color: #c40000;
    }

    .weight2 {
      text-align: center;
      margin-top: 15px;
      font-size: 14px;
      color: #aaa;
    }
#era{
    width:55px;
    height:55px;
    border-radius:50%;
}
#beka{
    width:55px;
    height:55px;
    border-radius:50%;
}</style>

<div class="container">

  <div class="event-header">
    <h1>Главный кард — 5 Января</h1>
    <p>Место проведения: Рим,Италия</p>
  </div>

  <div class="fights" id="fightsContainer">

    <!-- КАРТОЧКА БОЯ (ШАБЛОН) -->
    <div class="fight-card">
      <div class="fighters">
        <div class="fighter">
          <img src="tomi.jpg" alt="Боец 1" id="tomi" title="Баккали Танат,действующий чемпион легкого веса">
          <div class="name" title="Баккали Танат,действующий чемпион легкого веса">Танат</div>
        </div>

        <div class="vs">VS</div>

        <div class="fighter">
          <img src="ali.jpg" alt="Боец 2" id="ali" title="Дуйсен Али,действующий чемпион полулегкого веса">
         <div class="name" title="Дуйсен Али,действующий чемпион полулегкого веса">Али</div>
        </div>
      </div>
      <div class="weight">Лёгкий вес • Главный бой</div>
    </div>

  </div>
</div>

<footer>
  © 2025 My Fight Promotion. Все права защищены.
</footer>
<div class="container2">
  <div class="fights2" id="fightsContainer2">

    <!-- КАРТОЧКА БОЯ (ШАБЛОН) -->
    <div class="fight-card2">
      <div class="fighters2">
        <div class="fighter2">
          <img src="beka.jpg" alt="Боец 3" id="beka" title="Бейсембай Бексултан,претедент на звание чемпиона в полусреднем весе">
          <div class="name2" title="Бейсембай Бексултан,претедент на звание чемпиона в полусреднем весе">Бексултан</div>
        </div>

        <div class="vs2">VS</div>

        <div class="fighter2">
          <img src="era.jpg" alt="Боец 4" id="era" title="Жумабай Ерасыл,претедент на звание чемпиона в полусреднем весе">
          <div class="name2" title="Жумабай Ерасыл,претедент на звание чемпиона в полусреднем весе">Ерасыл</div>
        </div>
      </div>
      <div class="weight2">Полусредний вес • Главный бой</div>
    </div>

  </div>
</div>


</body>
</html>
