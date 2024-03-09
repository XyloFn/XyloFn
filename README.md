<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inscription au Tournoi 1v1.lol</title>
</head>
<body>

    <h1>Inscription au Tournoi 1v1.lol</h1>

    <form action="/inscription" method="post">
        <label for="pseudo">Pseudonyme 1v1.lol :</label>
        <input type="text" id="pseudo" name="pseudo" required>

        <label for="email">Adresse e-mail :</label>
        <input type="email" id="email" name="email" required>

        <label for="discord">Nom d'utilisateur Discord :</label>
        <input type="text" id="discord" name="discord" required>

        <label for="armes">Niveau des armes (doivent être au niveau 10) :</label>
        <input type="number" id="armes" name="armes" min="10" max="10" required>

        <label for="map">Map préférée (Zone Wars) :</label>
        <input type="text" id="map" name="map" required>

        <button type="submit">S'inscrire</button>
    </form>

</body>
</html>
