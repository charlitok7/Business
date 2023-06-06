# BOUTIQUE 

<html>
<head>
    <title>Formulaire d'inscription</title>
    <link rel="stylesheet" type="text/css" href="Vuecss.css">
    <src="Uploading Gallery of Neriage Store _ Estúdio Sumaúma  - 9.png" alt="" > 
    <style>
        body {
            background-color: blue;
        }

        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        form {
            background-color: white;
            padding: 20px;
            width: 300px;
            text-align: center;
        }

        form label {
            display: block;
            margin-bottom: 10px;
            text-align: left;
        }

        form input[type="text"],
        form input[type="email"] {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            box-sizing: border-box;
        }

        form button[type="submit"] {
            width: 100%;
            padding: 10px;
            background-color: Green;
        }
    </style>
</head>
<body>
    
    <div class="container">
        <form>
            <h2>Inscription</h2>
            <label for="nom">Nom :</label>
            <input type="text" id="nom" name="nom " required>

            <label for="prenom">Prenom :</label>
            <input type="text" id="prenom" name=" prenom" required>

            <label for="niveau">Niveau :</label>
            <input type="text" id="niveau" name="niveau" required>

            <label for="email">Email :</label>
            <input type="email" id="email" name="email" required>

            <button type="submit">S'enregistrer</button>
        </form>
    </div>
</body>
</html>
