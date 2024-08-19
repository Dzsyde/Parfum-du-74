# Parfum-du-74
De nouvelles senteur accessible à tous ! Vous trouverez ici des produits de qualité
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Magasin de Parfums</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenue sur notre boutique de parfums</h1>
        <p>Découvrez notre collection exclusive de parfums raffinés</p>
    </header>
    
    <main>
        <section class="product">
            <img src="https://via.placeholder.com/300" alt="Ensemble de Parfums">
            <h2>Ensemble de Parfums</h2>
            <p class="price">Prix : 25 €</p>
            <button class="buy-button">Acheter</button>
        </section>

        <section class="product">
            <img src="https://via.placeholder.com/300" alt="Parfums Variés">
            <h2>Parfums Variés</h2>
            <p class="price">Prix : 20 €</p>
            <button class="buy-button">Acheter</button>
        </section>

        <section class="product">
            <img src="https://via.placeholder.com/300" alt="Parfum Amirat Al Arab">
            <h2>Parfum Amirat Al Arab</h2>
            <p class="price">Prix : 10 €</p>
            <button class="buy-button">Acheter</button>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Ma Boutique de Parfums. Tous droits réservés.</p>
    </footer>
</body>
</html>
/* Styles globaux */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

/* En-tête */
header {
    background-color: #3a3a3a;
    color: #fff;
    padding: 20px;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

header p {
    font-size: 1.2em;
    margin: 10px 0 0;
}

/* Contenu principal */
main {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin: 20px;
}

/* Section produit */
.product {
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin: 20px;
    padding: 20px;
    width: calc(33% - 40px); /* Pour trois produits en ligne avec marge */
    box-sizing: border-box;
    text-align: center;
}

.product img {
    max-width: 100%;
    height: auto;
    border-bottom: 1px solid #ddd;
    margin-bottom: 10px;
}

.product h2 {
    font-size: 1.5em;
    margin: 10px 0;
}

.product .price {
    font-size: 1.2em;
    color: #e44d26;
    margin: 10px 0;
}

.product .buy-button {
    background-color: #e44d26;
    border: none;
    color: #fff;
    padding: 10px 20px;
    font-size: 1em;
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.product .buy-button:hover {
    background-color: #c43c20;
}

/* Pied de page */
footer {
    background-color: #3a3a3a;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
