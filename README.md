<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HASINA TRIP - Agence de Voyage</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background: url('background-baobab.jpg') no-repeat center center fixed;
            background-size: cover;
            color: white;
            text-shadow: 1px 1px 4px rgba(0,0,0,0.7);
        }
        header {
            background-color: rgba(0, 0, 0, 0.6);
            padding: 20px;
            text-align: center;
        }
        header h1 {
            font-size: 3em;
            margin: 0;
        }
        nav {
            text-align: center;
            padding: 10px;
            background-color: rgba(0, 0, 0, 0.5);
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        main {
            padding: 40px;
            background-color: rgba(0, 0, 0, 0.4);
            max-width: 800px;
            margin: auto;
            border-radius: 10px;
        }
        .destination img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            margin-top: 10px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.6);
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>HASINA TRIP</h1>
        <p>Explorez Madagascar avec passion</p>
    </header>
    <nav>
        <a href="#destinations">Destinations</a>
        <a href="#offres">Offres Spéciales</a>
        <a href="#paiement">Paiement</a>
        <a href="#contact">Contact</a>
    </nav>
    <main>
        <h2>Bienvenue chez HASINA TRIP</h2>
        <p>Votre agence de voyage spécialisée dans les merveilles de Madagascar. Découvrez des paysages à couper le souffle, des cultures fascinantes et une aventure inoubliable avec notre équipe locale passionnée.</p>

        <h3 id="destinations">Nos Destinations</h3>
        <div class="destination">
            <h4>Morondava et l'Allée des Baobabs</h4>
            <img src="baobab-morondava.jpg" alt="Allée des Baobabs">
        </div>
        <div class="destination">
            <h4>Parc National de l'Isalo</h4>
            <img src="isalo.jpg" alt="Parc National de l'Isalo">
        </div>
        <div class="destination">
            <h4>Tsingy de Bemaraha</h4>
            <img src="tsingy.jpg" alt="Tsingy de Bemaraha">
        </div>
        <div class="destination">
            <h4>Nosy Be & plages paradisiaques</h4>
            <img src="nosybe.jpg" alt="Plage de Nosy Be">
        </div>

        <h3 id="offres">Offres Spéciales</h3>
        <p>Réservez maintenant et bénéficiez de 10% de réduction sur votre premier circuit à Madagascar !</p>

        <h3 id="paiement">Mode de Paiement</h3>
        <p>Nous acceptons les paiements via :</p>
        <ul>
            <li>Mobile Money (Orange Money, Telma Money, MVola)</li>
            <li>Carte VISA et MasterCard</li>
        </ul>

        <h3 id="contact">Contactez-nous</h3>
        <p>Email : contact@hasinatrip.mg</p>
        <p>Téléphone : +261 34 00 000 00</p>
    </main>
    <footer>
        &copy; 2025 HASINA TRIP - Tous droits réservés
    </footer>
</body>
</html>
