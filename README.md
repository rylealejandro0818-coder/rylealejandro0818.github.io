# <b> Ryle's Card Sorting Page </b>

card-sorter/
  index.html
  style.css

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
    <h2>Sorted by Release Date<h2>
      <div class="card-grid">
        <div class="card">
          <h3>Death Ruler</h3>
          <p>Release: 2021-12-30</p>
          <p>Class: Monarch</p>
          <p>Rarity: Unique</p>
        </div>
        <div class="card">
          <h3>Aztec Madman</h3>
          <p>Release: 2022-02-12</p>
          <p>Class: Berserker</p>
          <p>Rarity: Rare</p>
        </div>  
        <h3> Silent Assassin</h3>
          <p>Release: 2022-03-25</p>
          <p>Class: Crook</p>
          <p>Rarity: Common</p>
        </div>
    </div>
  </section>

  <section>
    <h2>Sorted by Class</h2>
    <div class="card-grid">
      <div class="card crook">Silent Assassin - Crook</div>      
      <div class="card berserker">Aztec Madman - Berserker</div>
      <div class="card monarch">Death Ruler - Monarch</div>
    </div>
  </section>

  <section>
    <h2>Sorted by Rarity</h2>
    <div class="card-grid">
      <div class="card crook">Silent Assassin - Common</div>      
      <div class="card berserker">Aztec Madman - Rare</div> 
      <div class="card monarch">Death Ruler - Unique</div>
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

.card-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
  justify-content: center;
}

.card {
  background: black;
  border-radius: 8px;
  padding: 15px;
  width: 180px;
  box-shadow: 0 2px 6px rgba(0,0,0,0,1);
  text-align: center;
  transition: transform 0.2s;
}

.card:hover {
  transform: scale(1.05);
}

/* Classes by rarity for color distinction */
.common { border-top: 4px solid gray; }
.rare { border-top: 4px solid yellow; }
.unique { border-top: 4px solid red; }

.ruler (background: #ffe6e6;}
.madman (background: #e6f0ff;}
.crook (background: #f0e6ff;}
