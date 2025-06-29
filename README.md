# Car-maintenances-
<!DOCTYPE html><html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cars Maintenance & Pièces</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #000;
      color: #fff;
    }
    header {
      background-color: #ff9f50;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    nav {
      background-color: #222;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px;
    }
    nav a {
      color: #ff9f50;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 30px;
    }
    .services, .products, .contact {
      background-color: #111;
      margin: 20px 0;
      border-radius: 10px;
      padding: 20px;
    }
    .button {
      background-color: #ff9f50;
      color: #000;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
      border-radius: 5px;
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      border: none;
    }
    footer {
      background-color: #222;
      text-align: center;
      padding: 20px;
      color: #888;
    }
  </style>
</head>
<body>
  <header>
    <h1>Cars Maintenance & Pièces</h1>
    <p><em>Roulé sans inquiétude</em></p>
  </header>  <nav>
    <a href="#services">Services</a>
    <a href="#products">Produits</a>
    <a href="#contact">Contact</a>
  </nav>  <section class="services" id="services">
    <h2>Nos Services</h2>
    <p>Nous offrons la réparation et le diagnostic de véhicules diesel et essence. Notre équipe assure un entretien professionnel et rapide.</p>
    <button class="button">Remplir un formulaire de réparation</button>
  </section>  <section class="products" id="products">
    <h2>Nos Produits</h2>
    <ul>
      <li>Pièces moteur</li>
      <li>Filtres et huiles</li>
      <li>Batteries</li>
      <li>Freins, courroies, et plus...</li>
    </ul>
    <button class="button">Acheter maintenant</button>
  </section>  <section class="contact" id="contact">
    <h2>Contact & Demande de Maintenance</h2>
    <form>
      <input type="text" placeholder="Nom complet" required>
      <input type="email" placeholder="Adresse email" required>
      <input type="text" placeholder="Modèle de véhicule">
      <textarea placeholder="Détail du problème ou besoin"></textarea>
      <button type="submit" class="button">Envoyer</button>
    </form>
  </section>  <footer>
    <p>&copy; 2025 Cars Maintenance & Pièces. Tous droits réservés.</p>
  </footer>
</body>
</html>
