# Projet-2
Début de l'html du projet numéro deux.
<html lang="fr">

    <head>
        <meta charset="utf-8"/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Reservia</title>
        <link rel="stylesheet" href="style.css" />
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.1/css/all.css" />
    </head>

<body>
    <!-- Header -->
    <header class="header-area w1440p">
        <a class="logo" href="reservia.html"><img src="images/logo/reservia.svg" alt="logo de la société reservia" /></a>
        <nav class="navbar flex">
            <a class="nav-link active" href="#hebergements">Hébergements</a>
            <a class="nav-link" href="#activites">Activités</a>
            <a class="nav-link" href="#">S'inscrire</a>
        </nav>
            
    </header>
    <!--Barre de recherche, et filtre de recherche-->
    <section class="search-area w1440p">
        <h1>Trouvez votre hébergement pour des vacances de rêve</h1>
        <p>En plein centre ville ou en pleine nature</p>
        <form class="search-form flex">
            <div class="search-icon bg--grey">
                <i class="fas fa-map-marker-alt"></i>
            </div>
            <input class="search-input" type="search" name="place" id="place" placeholder="Marseille, France" />
            <button class="search-button bg--blue-primary" type="submit">
                Rechercher
            </button>
        </form>
        <!--les filtres-->
        <section class="filters-area flex">
            <h2>Filtres</h2>
            <div class="filters-choice flex">
                <i class="fas fa-money-bill-wave filters-icon flex bg--blue-secondary blue-primary"></i>
                <h3 class="flex">Économique</h3>
            </div>
            <div class="filters-choice flex">
                <i class="fas fa-child filters-icon flex bg--blue-secondary blue-primary"></i>
                <h3 class="flex">Familial</h3>
            </div>
            <div class="filters-choice flex">
                <i class="fas fa-heart filters-icon flex bg--blue-secondary blue-primary"></i>
                <h3 class="flex">Romantique</h3>
            </div>
            <div class="filters-choice flex">
                <i class="fas fa-dog filters-icon flex bg--blue-secondary blue-primary"></i>
                <h3 class="flex">Animaux autorisés</h3>
            </div>
            <div class="filters-info flex">
                <i class="fas fa-info filters-info-icon blue-primary"></i>
                <p class="filters-info-text">
                    Plus de 500 logements sont disponibles dans cette ville
                </p>
            </div>
        </section>
    </section>
    <!-- Hébergements -->
    <section class="hebergements grid w1440p" id="hebergements">
        <div class="hebergements-area grid">
            <h2>Hébergements à Marseille</h2>
            <a class="hebergements-card bg--white" href="#">
                <figure class="m0">
                    <img class="hebergements-card-img" src="./images/hebergements/small/canne.jpg"
                        alt="Une chambre de l'auberge cannebière, lit superposé avec vu sur cour " />
                    <figcaption class="hebergements-card-img-caption">
                        <h3>Aubèrge la Cannebière</h3>
                    </figcaption>
                </figure>
                <p class="hebergements-card-price">
                    Nuit à partir de <strong>25€</strong>
                </p>
                <div class="hebergements-card-description flex">
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star grey-star"></i>
                </div>
            </a>
            <a class="hebergements-card bg--white" href="#">
                <figure class="m0">
                    <img class="hebergements-card-img" src="./images/hebergements/small/port.jpg"
                        alt="Une chambre de l'hôtel du port, avec deux lits " />
                    <figcaption class="hebergements-card-img-caption">
                        <h3> hôtel du port </h3>
                    </figcaption>
                </figure>
                <p class="hebergements-card-price">
                    Nuit à partir de <strong>52€</strong>
                </p>
                <div class="hebergements-card-description flex">
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                </div>
            </a>
            <a class="hebergements-card bg--white" href="#">
                <figure class="m0">
                    <img class="hebergements-card-img" src="./images/hebergements/small/mouettes.jpg"
                        alt="Une chambre de l'hôtel les mouettes, avec une penderie " />
                    <figcaption class="hebergements-card-img-caption">
                       <h3> Hôtel Les Mouettes </h3>
                    </figcaption>
                </figure>
                <p class="hebergements-card-price">
                    Nuit à partir de <strong>76€</strong>
                </p>
                <div class="hebergements-card-description flex">
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star grey-star"></i>
                </div>
            </a>
            <a class="hebergements-card bg--white" href="#">
                <figure class="m0">
                    <img class="hebergements-card-img" src="./images/hebergements/small/mer.jpg"
                        alt="Lit auberge de la mer, tableau océan au dessus du lit" />
                    <figcaption class="hebergements-card-img-caption">
                       <h3> Aubèrge de la mer </h3>
                    </figcaption>
                </figure>
                <p class="hebergements-card-price">
                    Nuit à partir de <strong>46€</strong>
                </p>
                <div class="hebergements-card-description flex">
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star grey-star"></i>
                    <i class="fas fa-star grey-star"></i>
                </div>
            </a>
            <a class="hebergements-card bg--white" href="#">
                <figure class="m0">
                    <img class="hebergements-card-img" src="./images/hebergements/small/panier.jpg"
                        alt="Une chambre de l'auberge cannebière, lit superposé avec vu sur cour " />
                    <figcaption class="hebergements-card-img-caption">
                      <h3> Aubèrge Le Panier </h3>
                    </figcaption>
                </figure>
                <p class="hebergements-card-price">
                    Nuit à partir de <strong>23€</strong>
                </p>
                <div class="hebergements-card-description flex">
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star grey-star"></i>
                </div>
            </a>
            <a class="hebergements-card bg--white" href="#">
                <figure class="m0">
                    <img class="hebergements-card-img" src="./images/hebergements/small/amina.jpg"
                        alt="Une chambre de l'auberge cannebière, lit superposé avec vu sur cour " />
                    <figcaption class="hebergements-card-img-caption">
                       <h3> Hôtel chez Amina </h3>
                    </figcaption>
                </figure>
                <p class="hebergements-card-price">
                    Nuit à partir de <strong>96€</strong>
                </p>
                <div class="hebergements-card-description flex">
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                </div>
            </a>
            <a class="hebergements-link-more" href="#">Afficher plus</a>
        </div>
        <aside class="hebergements-popular grid">
            <div class="hebergements-popular-title flex m0">
                <h2 class="flex">Les plus populaires</h2>
                <i class="fas fa-chart-line hebergements-popular-title-icon"></i>
            </div>
            <a class="hebergements-popular-card bg--white flex">
                <figure class="hebergements-popular-card-img m0">
                    <img src="./images/hebergements/small/soleil.jpg"
                        alt="une chambre de l'hotel du soleil, avec un style arabesque" />
                </figure>
                <div class="hebergements-popular-card-img-caption">
                    Hôtel Le soleil du matin
                    <p class="hebergements-popular-car-price">
                        Nuit à partir de <strong>128€</strong>
                    </p>
                    <div class="hebergements-popular-card-description flex">
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                    </div>
                </div>
            </a>
            <a class="hebergements-popular-card bg--white flex">
                <figure class="hebergements-popular-card-img m0">
                    <img src="./images/hebergements/small/eau.jpg"
                        alt="une chambre de l'hotel du soleil, avec un style arabesque" />
                </figure>
                <div class="hebergements-popular-card-img-caption">
                    Au coeur de l'eau Chambres d'hôtes
                    <p class="hebergements-popular-car-price">
                        Nuit à partir de <strong>71€</strong>
                    </p>
                    <div class="hebergements-popular-card-description flex">
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star grey-star"></i>
                    </div>
                </div>
            </a>
            <a class="hebergements-popular-card bg--white flex">
                <figure class="hebergements-popular-card-img m0">
                    <img src="./images/hebergements/small/bleu.jpg"
                        alt="une chambre de l'hotel du soleil, avec un style arabesque" />
                </figure>
                <div class="hebergements-popular-card-img-caption">
                    Hôtel Tout bleu et Blanc
                    <p class="hebergements-popular-car-price">
                        Nuit à partir de <strong>68€</strong>
                    </p>
                    <div class="hebergements-popular-card-description flex">
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star grey-star"></i>
                    </div>
                </div>
            </a>
        </aside>
    </section>
    <!-- Activité -->
    <section class="activites-area w1440p" id="activites">
        <h1>Activités à Marseille</h1>
        <a class="activites-area-card activites-area-card1" href="#">
            <figure class="activites-area-card-figure m0">
                <img class="activites-area-card-figure-img" src="./images/activites/medium/vieux.jpg"
                    alt="Vu du vieux port et ses bateaux à quai, avec la ville en arrière-plan" />
            </figure>
            <h3 class="activites-card-img-caption">Vieux Port</h3>
        </a>
        <a class="activites-area-card activites-area-card2" href="#">
            <figure class="activites-area-card-figure m0">
                <img class="activites-area-card-figure-img" src="./images/activites/small/pormegues.jpg"
                    alt="Vue du fort entre deux rochers" />
            </figure>
            <h3 class="activites-card-img-caption">Fort de Pomègues</h3>
        </a>
        <a class="activites-area-card activites-area-card3" href="#">
            <figure class="activites-area-card-figure m0">
                <img class="activites-area-card-figure-img" src="./images/activites/small/frioul.jpg"
                    alt="Vue lointaine de l'île de frioul depuis un point d'observation" />
            </figure>
            <h3 class="activites-card-img-caption">Île du Frioul</h3>
        </a>
        <a class="activites-area-card activites-area-card4" href="#">
            <figure class="activites-area-card-figure m0">
                <img class="activites-area-card-figure-img"
                    src="./images/activites/medium/calanques.jpg"
                    alt="Vue en plongée sur le parc national de Calanques" />
            </figure>
            <h3 class="activites-card-img-caption">Parc National de Calanques</h3>
        </a>
        <a class="activites-area-card activites-area-card5" href="#">
            <figure class="activites-area-card-figure m0">
                <img class="activites-area-card-figure-img" src="./images/activites/small/garde.jpg"
                    alt="Vue lointaine de Notre-Dame-de-la-Garde et ses alentours" />
            </figure>
            <h3 class="activites-card-img-caption">Notre-Dame-de-la-Garde</h3>
        </a>
        <a class="activites-area-card activites-area-card6" href="#">
            <figure class="activites-area-card-figure m0">
                <img class="activites-area-card-figure-img" src="./images/activites/small/Long.jpg"
                    alt="Vue de la facade extérieur du parc Longchamp" />
            </figure>
            <h3 class="activites-card-img-caption">Parc Longchamp</h3>
        </a>
    </section>
    <!-- Footer -->
    <footer class="bg--grey">
        <div class="footer-area grid">
            <nav class="flex footer-nav">
                <h3>À propos</h3>
                <a href="#">Fonctionnement du site</a>
                <a href="#">Conditions générales de vente</a>
                <a href="#">Données et confidentialités</a>
            </nav>
            <nav class="flex footer-nav">
                <h3>Nos hébergements</h3>
                <a href="#">Charte de qualité</a>
                <a href="#">Soumettre votre hôtel</a>
            </nav>
            <nav class="flex footer-nav">
                <h3>Assistance</h3>
                <a href="#">Centre d'aide</a>
                <a href="#">Nous contacter</a>
            </nav>
        </div>
    </footer>
</body>

</html>
