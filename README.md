# RealMarioPartyChamp
for MPC website
<!DOCTYPE html>
<html>
<head>
  <title>Mario Party Champion</title>
</head>
<body>
  <h1>Welcome to the Mario Party Champion Website</h1>
  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#leaderboard">Leaderboard</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
  <section id="about">
    <h2>About the Mario Party Champion</h2>
    <p>This website is dedicated to the Mario Party Champion, where you can find information about the champion, view the current leaderboard and contact the champion.</p>
  </section>
  <section id="leaderboard">
    <h2>Current 2023 Leaderboard</h2>
    <table>
      <tr>
        <th>Rank</th>
        <th>Name</th>
        <th>Character</th>
      </tr>
      <tr>
        <td>1st (Champ)</td>
        <td>Ryan</td>
        <td>Waluigi</td>
      </tr>
      <tr>
        <td>2nd</td>
        <td>Brendan</td>
        <td>Yoshi</td>
      </tr>
      <tr>
        <td>3rd</td>
        <td>Beef</td>
        <td>Luigi</td>
      </tr>
      <tr>
        <td>4th</td>
        <td>Spirk</td>
        <td>Wario</td>
      </tr>
    </table>
  </section>
  <section id="contact">
    <h2>Contact the Mario Party Champion</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name"><br>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email"><br>
      <label for="message">Message:</label>
      <textarea id="message" name="message"></textarea><br>
      <input type="submit" value="Send">
    </form>
  </section>
</body>
</html>
