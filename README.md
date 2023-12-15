<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulaire</title>
    <!-- Vous pouvez ajouter des liens vers des fichiers CSS ici si nécessaire -->
</head>
<body>

    <h2>Formulaire</h2>

    <form action="traitement.php" method="post">
        <!-- Votre formulaire ici -->
    </form>

</body>
</html>
<!-- traitement.php -->
<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    $pays = $_POST["pays"];
    $etatCivil = $_POST["etatCivil"];
    $nom = $_POST["nom"];
    $prenom = $_POST["prenom"];
    $dateNaissance = $_POST["dateNaissance"];
    $telephone = $_POST["telephone"];
    $email = $_POST["email"];
    $codePostal = $_POST["codePostal"];
    $ville = $_POST["ville"];

    // Faites quelque chose avec les données, par exemple les afficher
    echo "Pays: $pays <br>";
    echo "État civil: $etatCivil <br>";
    echo "Nom: $nom <br>";
    echo "Prénom: $prenom <br>";
    echo "Date de naissance: $dateNaissance <br>";
    echo "Numéro de téléphone: $telephone <br>";
    echo "E-mail: $email <br>";
    echo "Code postal: $codePostal <br>";
    echo "Ville: $ville <br>";
}
?>
