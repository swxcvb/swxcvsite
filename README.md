# swxcvsite
Achetez vos compléments alimentaires en toute confiance, khidma n9iya, service sérieux.
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ma Boutique de Compléments Alimentaires</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }

    header {
      background-color: #4CAF50;
      color: white;
      padding: 1rem;
      text-align: center;
    }

    h1 {
      margin: 0;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 2rem;
      gap: 2rem;
    }

    .product {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
      width: 250px;
      text-align: center;
      padding: 1rem;
    }

    .product img {
      max-width: 100%;
      border-radius: 10px;
    }

    .product h3 {
      margin: 0.5rem 0;
    }

    .product p {
      color: #555;
    }

    .product button {
      background-color: #4CAF50;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 0.5rem;
    }

    .product button:hover {
      background-color: #45a049;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Ma Boutique de Compléments Alimentaires</h1>
  </header>

  <div class="container">
    <div class="product">
      <img src="images/produit1.jpg" alt="Complément 1">
      <h3>Protéine Whey</h3>
      <p>Complément riche en protéines pour la récupération musculaire.</p>
      <button onclick="ajouterAuPanier('Protéine Whey')">Ajouter au panier</button>
    </div>

    <div class="product">
      <img src="images/produit2.jpg" alt="Complément 2">
      <h3>Vitamine C</h3>
      <p>Renforce le système immunitaire naturellement.</p>
      <button onclick="ajouterAuPanier('Vitamine C')">Ajouter au panier</button>
    </div>

    <div class="product">
      <img src="images/produit3.jpg" alt="Complément 3">
      <h3>Omega 3</h3>
      <p>Bon pour le cœur et le cerveau.</p>
      <button onclick="ajouterAuPanier('Omega 3')">Ajouter au panier</button>
    </div>
  </div>

  <footer>
    &copy; 2026 Ma Boutique. Tous droits réservés.
  </footer>

  <script>
    function ajouterAuPanier(produit) {
      alert(produit + " a été ajouté au panier !");
    }
  </script>

</body>
</html>
