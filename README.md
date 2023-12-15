- 👋 Hi, I’m @usename92
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
usename92/usename92 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulaire</title>
</head>
<body>

    <h2>Formulaire</h2>

    <form action="traitement.php" method="post">
        <label for="pays">Pays:</label>
        <select name="pays" id="pays">
            <option value="france">France</option>
            <option value="espagne">Espagne</option>
            <option value="italie">Italie</option>
            <!-- Ajoutez d'autres options selon vos besoins -->
        </select>
        <br>

        <label for="etatCivil">État civil:</label>
        <input type="radio" name="etatCivil" value="celibataire">Célibataire
        <input type="radio" name="etatCivil" value="marie">Marié(e)
        <br>

        <label for="nom">Nom:</label>
        <input type="text" name="nom" id="nom" required>
        <br>

        <label for="prenom">Prénom:</label>
        <input type="text" name="prenom" id="prenom" required>
        <br>

        <label for="dateNaissance">Date de naissance:</label>
        <input type="date" name="dateNaissance" id="dateNaissance" required>
        <br>

        <label for="telephone">Numéro de téléphone:</label>
        <input type="tel" name="telephone" id="telephone" required>
        <br>

        <label for="email">E-mail:</label>
        <input type="email" name="email" id="email" required>
        <br>

        <label for="codePostal">Code postal:</label>
        <input type="text" name="codePostal" id="codePostal" required>
        <br>

        <label for="ville">Ville:</label>
        <input type="text" name="ville" id="ville" required>
        <br>

        <input type="submit" value="Envoyer">
    </form>

</body>
</html>
