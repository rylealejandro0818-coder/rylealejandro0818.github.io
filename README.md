# <b> Ryle's Card Sorting Page </b>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  We perform card sorting according to Date, Class, and Rarity
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <h1>Card Sorting Demo</h1>

  <div class="controls">
    <label for="sort">Sort by:</label>
    <select id="sort">
      <option value="releaseDate">Release Date</option>
      <option value="class">Class</option>
      <option value="rarity">Rarity</option>
    </select>
  </div>
  
<div class="card-container" id="cardContainer"></div>

  <script src="script.js"></script>
</body>
</html>
