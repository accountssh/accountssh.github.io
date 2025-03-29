<!DOCTYPE html>
<html lang="de">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Yumelin Accounts Shop</title>
 <link rel="stylesheet" href="styles.css">
</head>
<body>
 <header>
 <nav>
 <ul>
 <li><a href="#home">Startseite</a></li>
 <li><a href="#accounts">Accounts</a></li>
 <li><a href="#warenkorb">Warenkorb</a></li>
 <li><a href="#registrieren">Registrieren</a></li>
 <li><a href="#anmelden">Anmelden</a></li>
 </ul>
 </nav>
 </header>
 <main>
 <section id="home">
 <h1>Willkommen im Yumelin Accounts Shop!</h1>
 <p>Hier findest du die besten Accounts für Fortnite, Apex Legends und Roblox!</p>
 </section>
 <section id="accounts">
 <h2>Accounts</h2>
 <ul>
 <li><a href="#fortnite">Fortnite Accounts</a></li>
 <li><a href="#apex-legends">Apex Legends Accounts</a></li>
 <li><a href="#roblox">Roblox Accounts</a></li>
 </ul>
 </section>
 <section id="warenkorb">
 <h2>Warenkorb</h2>
 <p>Dein Warenkorb ist leer.</p>
 </section>
 <section id="registrieren">
 <h2>Registrieren</h2>
 <form>
 <label für="name">Name:</label>
 <input type="text" id="name" name="name"><br><br>
 <label für="email">E-Mail:</label>
 <input type="email" id="email" name="email"><br><br>
 <label für="passwort">Passwort:</label>
 <input type="password" id="passwort" name="passwort"><br><br>
 <input type="submit" value="Registrieren">
 </form>
 </section>
 <section id="anmelden">
 <h2>Anmelden</h2>
 <form>
 <label für="email">E-Mail:</label>
 <input type="email" id="email" name="email"><br><br>
 <label für="passwort">Passwort:</label>
 <input type="password" id="passwort" name="passwort"><br><br>
 <input type="submit" value="Anmelden">
 </form>
 </section>
 </main>
 <footer>
 <p>Yumelin Accounts Shop 2023</p>
 </footer>
</body>
</html>

Und hier ist ein grundlegendes CSS-Template für das Design:

body {
 background-color: #000;
 color: #fff;
 font-family: Arial, sans-serif;
}

header {
 background-color: #ff0000;
 padding: 20px;
 text-align: center;
}

nav ul {
 list-style: none;
 margin: 0;
 padding: 0;
}

nav li {
 display: inline-block;
 margin-right: 20px;
}

nav a {
 color: #fff;
 text-decoration: none;
}

main {
 display: flex;
 flex-direction: column;
 align-items: center;
 padding: 20px;
}

section {
 background-color: #333;
 padding: 20px;
 margin-bottom: 20px;
 box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
}

h1, h2 {
 color: #ff0000;
}

form {
 display: flex;
 flex-direction: column;
 align-items: center;
}

label {
 margin-bottom: 10px;
}

input[type="text"], input[type="email"], input[type="password"] {
 width: 100%;
 height: 40px;
 margin-bottom: 20px;
 padding: 10px;
 border: none;
 border-radius: 5px;
 box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
}

input[type="submit"] {
 width: 100%;
 height: 40px;
 background-color: #ff0000;
 color: #fff;
 padding: 10px;
 border: none;
 border-radius: 5px;
 cursor: pointer;
}

footer {
 background-color: #333;
 padding: 20px;
 text-align: center;
 clear: both;
}
