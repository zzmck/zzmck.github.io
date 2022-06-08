<html lang="fr">

<head>
    <meta charset="utf-8" />
    <!--  VIEWPORT  Responsive sur la largeur d'ecran  -->
    <link rel="stylesheet" href="https://serveursbot.net/projet2/css/normalize.css" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <!--  POLICE D ECRITURE : Raleway  -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
    <!--  CDN ICONES DU SITE  -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css" />
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous" />
    <!--  CSS du site  -->

    <link rel="stylesheet" href="https://serveursbot.net/projet2/css/style.css" />
    <!--  TITRE  -->
    <title>Booky</title>
</head>

<body>
    <div id="block-page">
        <!-- DEBUT HEADER : LOGO et MENU-->
        <header>
            <!--BLOC FIXE POUR DECALAGE DES ANCRES-->
            <!--LOGO-->
            <div class="header-logo"><img class="header-logo-image" src="https://serveursbot.net/projet2/images/logo/Booki@3x.png" alt="Logo" /></div>

            <div>
                <nav class="header-menu">
                    <ul class="header-menu-block">
                        <li class="header-menu-block-liste"><a class="header-menu-block-liste-lien" href="#lien-hebergement"><span class="header-menu-block-liste-texte">Hébergements</span></a></li>
                        <li class="header-menu-block-liste"><a class="header-menu-block-liste-lien" href="#lien-activites"><span class="header-menu-block-liste-texte">Activités</span></a></li>
                    </ul>
                </nav>

            </div>
        </header>
        <!-- FIN HEADER -->
        <!-- CONTENUE PAGE IMPORTANT : MAIN -->
        <main>
            <!-- DEBUT SECTION RECHERCHE : TITRE / SOUS TITRE / FORMULAIRE -->

            <div class="recherche">
                <!--TITRE-->
                <h1 class="recherche-titre">Trouvez votre hébergement pour des vacances de rêve</h1>
                <!--SOUS TITRE-->
                <h2 class="recherche-soustitre">En plein centre ville ou en pleine nature</h2>
                <div>
                    <!--FORMULAIRE-->
                    <form class="recherche-formulaire">
                        <div><i class="fas fa-map-marker-alt recherche-formulaire-icone"></i></div>
                        <div id="recherche-formulaire-zonetexte"><input class="recherche-formulaire-zonetexte-champ" type="text" value="Marseille, France" /></div>
                        <div><button class="recherche-formulaire-bouton-bureau" type="button">Rechercher</button>
                            <button class="recherche-formulaire-bouton-mobile" type="submit"><i class="fas fa-search"></i></button></div>
                    </form>
                </div>
            </div>

            <!-- FIN SECTION RECHERCHE -->

            <!-- DEBUT SECTION FILTRE : TITRE / 4 BOUTONS / INFORMATION -->
            <div class="filtre">
                <div class="filtre-container">
                    <!--TITRE-->
                    <div class="filtre-container-titre">
                        <h3 class="filtre-container-titre-texte">Filtres</h3>
                    </div>
                    <!--4 BOUTONS-->
                    <div class="filtre-container-ligne">
                        <div class="filtre-container-ligne-bouton">
                            <a href="#"><span class="filtre-container-ligne-bouton-icone"><i class="fas fa-money-bill-wave"></i></span><span class="filtre-container-ligne-bouton-texte">Économique</span></a>
                        </div>
                        <div class="filtre-container-ligne-bouton">
                            <a href="#"><span class="filtre-container-ligne-bouton-icone"><i class="fas fa-child"></i></span><span class="filtre-container-ligne-bouton-texte">Familial</span></a>
                        </div>
                        <div class="filtre-container-ligne-bouton">
                            <a href="#"><span class="filtre-container-ligne-bouton-icone"><i class="fas fa-heart"></i></span><span class="filtre-container-ligne-bouton-texte">Romantique</span></a>
                        </div>
                        <div class="filtre-container-ligne-bouton">
                            <a href="#"><span class="filtre-container-ligne-bouton-icone"><i class="fas fa-dog"></i></span><span class="filtre-container-ligne-bouton-texte">Animaux autorisés</span></a>
                        </div>
                    </div>
                </div>
                <!--INFORMATION-->
                <p class="filtre-information">
                    <span class="filtre-information-icone"><i class="fas fa-info filtre-information-icone-modification"></i></span><span class="filtre-information-texte">Plus de 500 logements sont disponibles dans cette ville</span>
                </p>
            </div>
            <!-- FIN SECTION FILTRE -->

            <!-- DEBUT SECTION HEBERGEMENT ET POPULAIRE -->
            <div class="conteneur">
                <!-- SECTION HEBERGEMENT -->
                <div id="lien-hebergement" class="hebergements">
                    <!-- TITRE -->
                    <h3 class="hebergements-titre">Hébergements à Marseille</h3>

                    <!-- LISTE HEBERGEMENTS -->
                    <div class="hebergement-section">
                        <div class="hebergement-section-carte">
                            <div class="hebergement-section-carte-blochaut">
                                <p class="hebergement-section-carte-blochaut-image" style="background-image: url('https://serveursbot.net/projet2/images/hebergements/4_small/marcus-loke-WQJvWU_HZFo-unsplash.jpg');"></p>
                            </div>
                            <p class="hebergement-section-nomhebergement">Auberge La Cannebière</p>
                            <p class="hebergement-section-prixhebergement">Nuit à partir de <span class="hebergement-section-prixhebergement-gras">25€</span></p>
                            <p class="hebergement-section-etoiles">
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star"></i>
                            </p>
                        </div>
                        <div class="hebergement-section-carte">
                            <div class="hebergement-section-carte-blochaut">
                                <p class="hebergement-section-carte-blochaut-image" style="background-image: url('https://serveursbot.net/projet2/images/hebergements/4_small/fred-kleber-gTbaxaVLvsg-unsplash.jpg');"></p>
                            </div>
                            <p class="hebergement-section-nomhebergement">Hôtel du port</p>
                            <p class="hebergement-section-prixhebergement">Nuit à partir de <span class="hebergement-section-prixhebergement-gras">52€</span></p>
                            <p class="hebergement-section-etoiles">
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star"></i>
                            </p>
                        </div>
                        <div class="hebergement-section-carte">
                            <div class="hebergement-section-carte-blochaut">
                                <p class="hebergement-section-carte-blochaut-image" style="background-image: url('https://serveursbot.net/projet2/images/hebergements/4_small/reisetopia-B8WIgxA_PFU-unsplash.jpg');"></p>
                            </div>
                            <p class="hebergement-section-nomhebergement">Hôtel Les mouettes</p>
                            <p class="hebergement-section-prixhebergement">Nuit à partir de <span class="hebergement-section-prixhebergement-gras">76€</span></p>
                            <p class="hebergement-section-etoiles">
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star"></i>
                            </p>
                        </div>
                        <div class="hebergement-section-carte">
                            <div class="hebergement-section-carte-blochaut">
                                <p class="hebergement-section-carte-blochaut-image" style="background-image: url('https://serveursbot.net/projet2/images/hebergements/4_small/annie-spratt-Eg1qcIitAuA-unsplash.jpg');"></p>
                            </div>
                            <p class="hebergement-section-nomhebergement">Hôtel de la mer</p>
                            <p class="hebergement-section-prixhebergement">Nuit à partir de <span class="hebergement-section-prixhebergement-gras">46€</span></p>
                            <p class="hebergement-section-etoiles">
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star"></i>
                            </p>
                        </div>
                        <div class="hebergement-section-carte">
                            <div class="hebergement-section-carte-blochaut">
                                <p class="hebergement-section-carte-blochaut-image" style="background-image: url('https://serveursbot.net/projet2/images/hebergements/4_small/nicate-lee-kT-ZyaiwBe0-unsplash.jpg');"></p>
                            </div>
                            <p class="hebergement-section-nomhebergement">Auberge Le Panier</p>
                            <p class="hebergement-section-prixhebergement">Nuit à partir de <span class="hebergement-section-prixhebergement-gras">23€</span></p>
                            <p class="hebergement-section-etoiles">
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star"></i>
                            </p>
                        </div>
                        <div class="hebergement-section-carte">
                            <div class="hebergement-section-carte-blochaut">
                                <p class="hebergement-section-carte-blochaut-image" style="background-image: url('https://serveursbot.net/projet2/images/hebergements/4_small/febrian-zakaria-M6S1WvfW68A-unsplash.jpg');"></p>
                            </div>
                            <p class="hebergement-section-nomhebergement">Hôtel chez Amina</p>
                            <p class="hebergement-section-prixhebergement">Nuit à partir de <span class="hebergement-section-prixhebergement-gras">96€</span></p>
                            <p class="hebergement-section-etoiles">
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star hebergement-section-etoile-selectionnee"></i>
                                <i class="fa fa-star"></i>
                            </p>
                        </div>
                    </div>
                    <!-- AFFICHER PLUS -->
                    <p class="hebergements-afficherplus"><a class="hebergements-afficherplus-lien" href="#">Afficher plus</a></p>
                </div>
                <!-- FIN SECTION HEBERGEMENT -->

                <!-- SECTION POPULAIRE -->
                <aside class="populaire">
                    <!-- TITRE -->
                    <h3 class="populaire-titre">
                        <span class="populaire-titre-texte">Les plus populaires</span>
                        <span><i class="fa fa-star populaire-titre-etoilenoire"></i></span>
                    </h3>
                    <!-- LOGEMENT POPULAIRE -->
                    <div class="populaire-section">
                        <!-- LOGEMENT HAUT -->
                        <div class="populaire-section-carte">
                            <div class="populaire-section-carte-block-gauche">
                                <p class="populaire-section-carte-block-gauche-image populaire-taille-image-haut" style="background-image: url('https://serveursbot.net/projet2/images/hebergements/4_small/emile-guillemot-Bj_rcSC5XfE-unsplash.jpg');"></p>
                            </div>
                            <div class="populaire-section-carte-block-droit">
                                <div class="populaire-section-carte-block-droit-texte">
                                    <p class="populaire-section-carte-block-droit-texte-nom">Hôtel Le soleil du matin</p>
                                    <p class="populaire-section-carte-block-droit-texte-prix">Nuit à partir de <span class="populaire-section-carte-block-droit-texte-prix-gras">128€</span></p>
                                </div>
                                <p class="populaire-section-carte-block-droit-etoiles">
                                    <i class="fa fa-star populaire-section-carte-block-droit-etoiles-selectionnee"></i>
                                    <i class="fa fa-star populaire-section-carte-block-droit-etoiles-selectionnee"></i>
                                    <i class="fa fa-star populaire-section-carte-block-droit-etoiles-selectionnee"></i>
                                    <i class="fa fa-star populaire-section-carte-block-droit-etoiles-selectionnee"></i>
                                    <i class="fa fa-star populaire-section-carte-block-droit-etoiles-selectionnee"></i>
                                </p>
                            </div>
                        </div>
                        <!-- LOGEMENT MILIEU -->
                        <div class="populaire-section-carte">
                            <div class="populaire-section-carte-block-gauche">
                                <p class="populaire-section-carte-block-gauche-image populaire-taille-image-milieu" style="background-image: url('https://serveursbot.net/projet2/images/hebergements/4_small/aw-creative-VGs8z60yT2c-unsplash.jpg');"></p>
                            </div>
                            <div class="populaire-section-carte-block-droit">
                                <div class="populaire-section-carte-block-droit-texte">
                                    <p class="populaire-section-carte-block-droit-texte-nom">Au coeur de l'eau Chambres d'hôtes</p>
                                    <p class="populaire-section-carte-block-droit-texte-prix">Nuit à partir de <span class="populaire-section-carte-block-droit-texte-prix-gras">71€</span></p>
                                </div>
                                <p class="populaire-section-carte-block-droit-etoiles">
                                    <i class="fa fa-star populaire-section-carte-block-droit-etoiles-selectionnee"></i>
                                    <i class="fa fa-star populaire-section-carte-block-droit-etoiles-selectionnee"></i>
                                    <i class="fa fa-star populaire-section-carte-block-droit-etoiles-selectionnee"></i>
                                    <i class="fa fa-star populaire-section-carte-block-droit-etoiles-selectionnee"></i>
                                    <i class="fa fa-star"></i>
                                </p>
                            </div>
                        </div>
                        <!-- LOGEMENT BAS -->
                        <div class="populaire-section-carte">
                            <div class="populaire-section-carte-block-gauche">
                                <p class="populaire-section-carte-block-gauche-image populaire-taille-image-bas" style="background-image: url('https://serveursbot.net/projet2/images/hebergements/4_small/febrian-zakaria-sjvU0THccQA-unsplash.jpg');"></p>
                            </div>
                            <div class="populaire-section-carte-block-droit">
                                <div class="populaire-section-carte-block-droit-texte">
                                    <p class="populaire-section-carte-block-droit-texte-nom">Hôtel Tout bleu et Blanc</p>
                                    <p class="populaire-section-carte-block-droit-texte-prix">Nuit à partir de <span class="populaire-section-carte-block-droit-texte-prix-gras">68€</span></p>
                                </div>
                                <p class="populaire-section-carte-block-droit-etoiles">
                                    <i class="fa fa-star populaire-section-carte-block-droit-etoiles-selectionnee"></i>
                                    <i class="fa fa-star populaire-section-carte-block-droit-etoiles-selectionnee"></i>
                                    <i class="fa fa-star populaire-section-carte-block-droit-etoiles-selectionnee"></i>
                                    <i class="fa fa-star populaire-section-carte-block-droit-etoiles-selectionnee"></i>
                                    <i class="fa fa-star"></i>
                                </p>
                            </div>
                        </div>
                    </div>
                </aside>
                <!-- FIN SECTION POPULAIRE -->
            </div>
            <!-- FIN SECTION HEBERGEMENT ET POPULAIRE -->

            <!-- DEBUT SECTION ACTIVITES -->
            <div id="lien-activites" class="activites">
                <!-- TITRE -->
                <h3 class="activites-titre">Activités à Marseille</h3>
                <!-- ACTIVITES -->
                <div class="activites-conteneur">
                    <div class="activites-conteneur-section">
                        <div class="activites-conteneur-section-carte">
                            <span class="activites-conteneur-section-carte-simple-premiere activites-carte-simple" style="background-image: url('https://serveursbot.net/projet2/images/activites/3_medium/reno-laithienne-QUgJhdY5Fyk-unsplash.jpg');"></span>
                            <span class="activites-conteneur-section-carte-texte">Vieux Port</span>
                        </div>
                    </div>
                    <div class="activites-conteneur-section">
                        <div class="activites-conteneur-section-carte">
                            <span class="activites-conteneur-section-carte-double-gauche-haut activites-carte-double" style="background-image: url('https://serveursbot.net/projet2/images/activites/3_medium/paul-hermann-QFTrLdQIRhI-unsplash.jpg');"></span>
                            <span class="activites-conteneur-section-carte-texte">Fort de Pomègues</span>
                        </div>
                        <div class="activites-conteneur-section-carte">
                            <span class="activites-conteneur-section-carte-double-gauche-bas activites-carte-double" style="background-image: url('https://serveursbot.net/projet2/images/activites/3_medium/kevin-hikari-rV_Qd1l-VXg-unsplash.jpg');"></span>
                            <span class="activites-conteneur-section-carte-texte">Îles du Frioul</span>
                        </div>
                    </div>
                    <div class="activites-conteneur-section">
                        <div class="activites-conteneur-section-carte">
                            <span class="activites-conteneur-section-carte-simple-seconde activites-carte-simple" style="background-image: url('https://serveursbot.net/projet2/images/activites/3_medium/kilyan-sockalingum-NR8-cBCN3aI-unsplash.jpg');"></span>
                            <span class="activites-conteneur-section-carte-texte">Parc National des Calanques</span>
                        </div>
                    </div>
                    <div class="activites-conteneur-section">
                        <div class="activites-conteneur-section-carte">
                            <span class="activites-conteneur-section-carte-double-droite-haut activites-carte-double" style="background-image: url('https://serveursbot.net/projet2/images/activites/3_medium/florian-wehde-xW9e8gdotxI-unsplash.jpg');"></span>
                            <span class="activites-conteneur-section-carte-texte">Notre-Dame-de-la-garde</span>
                        </div>
                        <div class="activites-conteneur-section-carte">
                            <span class="activites-conteneur-section-carte-double-droite-bas activites-carte-double" style="background-image: url('./images/activites/3_medium/lena-paulin-wH2-EJoDcV0-unsplash.jpg');"></span>
                            <span class="activites-conteneur-section-carte-texte">Parc Longchamp</span>
                        </div>
                    </div>
                </div>
            </div>
            <!-- FIN SECTION ACTIVITES -->
        </main>
        <!-- FIN SECTION IMPORTANT MAIN -->
        <!-- DEBUT FOOTER -->
        <footer class="findepage">
            <div class="findepage-container">
                <!-- SECTION 1 -->
                <div class="findepage-premiere-section">
                    <!-- TITRE -->
                    <h3 class="findepage-section-titre">A propos</h3>
                    <!-- LISTE -->
                    <ul class="findepage-section-laisons">
                        <li class="findepage-section-laisons-liste">
                            <a class="findepage-section-laisons-liste-lien" href="#">Fonctionnement du site</a>
                        </li>
                        <li class="findepage-section-laisons-liste">
                            <a class="findepage-section-laisons-liste-lien" href="#">Conditions générales de vente</a>
                        </li>
                        <li class="findepage-section-laisons-liste">
                            <a class="findepage-section-laisons-liste-lien" href="#">Données et confidentialité</a>
                        </li>
                    </ul>
                </div>
                <!-- SECTION 2 -->
                <div class="findepage-autre-section">
                    <!-- TITRE -->
                    <h3 class="findepage-section-titre">Nos hébergements</h3>
                    <!-- LISTE -->
                    <ul class="findepage-section-laisons">
                        <li class="findepage-section-laisons-liste">
                            <a class="findepage-section-laisons-liste-lien" href=" # ">Charte qualité</a>
                        </li>
                        <li class="findepage-section-laisons-liste">
                            <a class="findepage-section-laisons-liste-lien" href="# ">Soumettre votre hôtel</a>
                        </li>
                    </ul>
                </div>
                <!-- SECTION 3 -->
                <div class="findepage-autre-section ">
                    <!-- TITRE -->
                    <h3 class="findepage-section-titre ">Assistance</h3>
                    <!-- LISTE -->
                    <ul class="findepage-section-laisons">
                        <li class="findepage-section-laisons-liste">
                            <a class="findepage-section-laisons-liste-lien" href="# ">Centre d'aide</a>
                        </li>
                        <li class="findepage-section-laisons-liste">
                            <a class="findepage-section-laisons-liste-lien" href="# ">Nous contacter</a>
                        </li>
                    </ul>
                </div>
            </div>
        </footer>
        <!-- FIN FOOTER -->
    </div>
</body>

</html>
