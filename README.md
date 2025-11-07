# <b> Ryle's Card Sorting Page </b>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Card Collection</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <h1>Card Collection</h1>

  <section>
    <h2>Sorted by Release Date</h2>
    <div class="card-grid">
      <div class="card">
        <h3>Lightning Steed</h3>
        <p>Release: 2019-11-30</p>
        <p>Class: Veteran</p>
        <p>Rarity: Epic</p>
      </div>
      <div class="card">
        <h3>Deadly Assassin</h3>
        <p>Release: 2015-02-04</p>
        <p>Class: Priest</p>
        <p>Rarity: Rare</p>
      </div>
      <div class="card">
        <h3> Hunter</h3>
        <p>Release: 2017-09-22</p>
        <p>Class: Standard</p>
        <p>Rarity: Common</p>
      </div>
    </div>
  </section>

  <section>
    <h2>Sorted by Class</h2>
    <div class="card-grid">
      <div class="card warrior">Flame Knight – Warrior</div>
      <div class="card priest">Mystic Healer – Priest</div>
      <div class="card rogue">Shadow Rogue – Rogue</div>
    </div>
  </section>

  <section>
    <h2>Sorted by Rarity</h2>
    <div class="card-grid">
      <div class="card common">Shadow Rogue – Common</div>
      <div class="card rare">Mystic Healer – Rare</div>
      <div class="card epic">Flame Knight – Epic</div>
    </div>
  </section>

</body>
</html>

body {
  font-family: Times New Roman;
  margin: 20px;
  background: #fafafa;
  color: #333;
}

h1 {
  text-align: center;
  margin-bottom: 40px;
}

