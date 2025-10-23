<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Volleyball Rankings</title>
  <link rel="stylesheet" href="style.css" />
  <script src="myscripts.js"></script>
</head>
<body>



  <header>
    <h1>🏐 Volleyball Rankings</h1>
    <p class="update">Updated October 2025</p>
    <div class="nav-links">
        <a href="">Home</a>
        <a href="">Shop</a>
        <a href="">Events</a>
    </div>

    
  </header>


  <main>
    <table>
      <thead>
        <tr>
          <th>Rank</th>
          <th>Team</th>
          <th>Wins</th>
          <th>Losses</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>#1</td>
          <td>Spike Masters</td>
          <td>18</td>
          <td>2</td>
        </tr>
        <tr>
          <td>#2</td>
          <td>Net Defenders</td>
          <td>16</td>
          <td>4</td>
        </tr>
        <tr>
          <td>#3</td>
          <td>Dolphines Court</td>
          <td>15</td>
          <td>5</td>
        </tr>
        <tr>
          <td>#4</td>
          <td>Ace Squad</td>
          <td>13</td>
          <td>7</td>
        </tr>
        <tr>
          <td>#5</td>
          <td>smash king </td>
          <td>11</td>
          <td>9</td>
        </tr>
      </tbody>
    </table>
  </main>

  <footer>
    <p>© 2025 Volleyball Rankings</p>
  </footer>
</body>
</html>


* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Poppins", sans-serif;
  background-color: #f5f7fa;
  color: #333;
  display: flex;
  flex-direction: column;
  align-items: center;
  min-height: 100vh;
}


.nav-links a {
  text-decoration: none;
  color: #007bff;
  padding: 20px;;
}
header {
  text-align: center;
  margin: 40px 0 20px;
}

header h1 {
  font-size: 2.5rem;
  color: #007bff;
}

header p {
  color: #666;
  margin-top: 8px;
}


table {
  width: 90%;
  max-width: 700px;
  border-collapse: collapse;
  background: #fff;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

thead {
  background-color: #007bff;
  color: #fff;
}

th, td {
  padding: 14px 20px;
  text-align: left;
}

tbody tr:nth-child(even) {
  background-color: #f2f6fc;
}

tbody tr:hover {
  background-color: #e6f0ff;
  transition: background 0.2s ease;
}

footer {
  margin-top: 40px;
  color: #888;
  font-size: 0.9rem;
  text-align: center;
  padding-bottom: 20px;
}

@media (max-width: 600px) {
  th, td {
    padding: 10px;
    font-size: 0.9rem;
  }

  header h1 {
    font-size: 2rem;
  }
}





