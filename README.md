<!DOCTYPE html>
<html lang="fr">

    <head>
        <link rel="stylesheet" href="style.css"> <!--Ajouter le fichier css-->
        <link href="fontawesome-free-5.15.1-web/css/all.css" rel="stylesheet"> <!--Faire télécharger la police-->
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Reservia</title>
    </head>

    <body>
        
        <header>
            <nav> <!--Le navigateur en haut a droite-->
                <ul>
                    <li><a href="#"><img src="Reservia/images/logo/Reservia.svg" alt="Reservia"></a></li>
                    <li><a href="#hebergement">Hébergement</a></li> <!-- Ancre-->
                    <li><a href="#activite">Activité</a></li>
                    <li><a href="#"><em>S'inscrire</em></a></li>
                </ul>
            </nav> <!--Fin du navigateur-->
                
            <div class="ligne1">Trouvez votre hébergement pour des vacances de rêve</div> 
            <div class="ligne2">En plein centre ville ou en pleine nature</div>

            <div id="barreDeRecherche"> <!--Bloc pour barre de recherche-->
                <span class="logoPosition">
                    <i class="fas fa-map-marker-alt"></i>
                </span>
                <input type="search" value="Marseille, France"> <!--Le formulaire-->
                <span class="bouton"> <!--Bouton Rechercher / Image search-->
                    <button type="button">
                        <i class="fas fa-search"></i>
                        <span>
                            Rechercher
                        </span>
                    </button>
                </span> <!--Bouton Rechercher--> 
            </div>

            <div id="filtre"> <!--Création des blocs "Filtres"-->
                <div class="filtre1">Filtres</div> <!--Le mot Filtre-->
                <div class="filtre2">
                    <div class="logo">
                        <i class="fas fa-money-bill-wave"></i>
                    </div>
                    <em>Economique</em>
                </div>
                <div class="filtre3">
                    <span class="logo">
                        <i class="fas fa-child"></i>
                    </span>
                    <em>Familial</em>
                </div>
                <div class="filtre4">
                    <span class="logo">
                        <i class="fas fa-heart"></i>
                    </span>
                    <em>Romantique</em>
                </div> 
                <div class="filtre5">
                    <span class="logo">
                        <i class="fas fa-dog"></i>
                    </span>
                    <em>Animaux autorisés</em>
                </div>
            </div>
            <div class="blocLigne3">
                <span class="logoI">
                    <i class="fas fa-info"></i>
                </span>
                <span class="ligne3">Plus de 500 logements sont disponibles dans cette ville</span>
            </div>
        </header>

        <section>
            <div class="blocGeneral"> <!--création du bloc general-->
                <div class="hebergementMarseille"><!--création du bloc 2-->
                    <h1 id="hebergement">Hébergements à Marseille</h1> <!--Ancre navigateur hebergement-->
                        <div class="hebergement"> <!--bloc contour-->
                            <a href="">
                                <div class="photoMarseille">
                                    <img src="Reservia/images/hebergements/4_small/marcus-loke-WQJvWU_HZFo-unsplash.jpg" alt="logement marcus">  
                                <div class="titrePhoto"> <!--Description du lieu-->
                                    Auberge la Cannebière
                                </div>
                                <div class="prixNuit"> <!--Prix de la nuit-->
                                    Nuit à partir de 25€
                                </div>
                                <div class="logoEtoileBleu">
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                        <em>
                                            <i class="fas fa-star"></i>
                                        </em>
                                </div>
                                </div>
                            </a>    
                        </div>
                                                        <!--SLOT1--> 
                        <div class="hebergement"> <!--bloc contour-->
                            <a href="">
                                <div class="photoMarseille">
                                    <img src="Reservia/images/hebergements/4_small/fred-kleber-gTbaxaVLvsg-unsplash.jpg" alt="logement fred">  
                                <div class="titrePhoto"> <!--Description du lieu-->
                                    Hôtel du port
                                </div>
                                <div class="prixNuit"> <!--Prix de la nuit-->
                                    Nuit à partir de 52€
                                </div>
                                <div class="logoEtoileBleu">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                </div>
                                </div>
                            </a>    
                        </div>
                                                         <!--SLOT2--> 
                        <div class="hebergement"> <!--bloc contour-->
                            <a href="">
                                <div class="photoMarseille">
                                    <img src="Reservia/images/hebergements/4_small/reisetopia-B8WIgxA_PFU-unsplash.jpg" alt="logement reisetopia">  
                                <div class="titrePhoto"> <!--Description du lieu-->
                                    Hôtel Les mouettes
                                </div>
                                <div class="prixNuit"> <!--Prix de la nuit-->
                                    Nuit à partir de 76€
                                </div>
                                <div class="logoEtoileBleu">
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                        <em>
                                            <i class="fas fa-star"></i>
                                        </em>
                                </div>
                                </div>
                            </a>    
                        </div>
                                                            <!--SLOT3--> 
                        <div class="hebergement"> <!--bloc contour-->
                            <a href="">
                                <div class="photoMarseille">
                                    <img src="Reservia/images/hebergements/4_small/annie-spratt-Eg1qcIitAuA-unsplash.jpg" alt="logement annie">  
                                <div class="titrePhoto"> <!--Description du lieu-->
                                    Hôtel de la mer
                                </div>
                                <div class="prixNuit"> <!--Prix de la nuit-->
                                    Nuit à partir de 46€
                                </div>
                                <div class="logoEtoileBleu">
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                        <em>
                                            <i class="fas fa-star"></i>
                                            <i class="fas fa-star"></i>
                                        </em>
                                </div>
                                </div>
                            </a>    
                        </div>
                                                               <!--SLOT4--> 
                        <div class="hebergement"> <!--bloc contour-->
                            <a href="">
                                <div class="photoMarseille">
                                    <img src="Reservia/images/hebergements/4_small/nicate-lee-kT-ZyaiwBe0-unsplash.jpg" alt="logement nicate">  
                                <div class="titrePhoto"> <!--Description du lieu-->
                                    Auberge Le Panier
                                </div>
                                <div class="prixNuit"> <!--Prix de la nuit-->
                                    Nuit à partir de 23€
                                </div>
                                <div class="logoEtoileBleu">
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                        <em>
                                            <i class="fas fa-star"></i>
                                        </em>
                                </div>
                                </div>
                            </a>    
                        </div>
                                                               <!--SLOT5--> 
                        <div class="hebergement"> <!--bloc contour-->
                            <a href="">
                                <div class="photoMarseille">
                                    <img src="Reservia/images/hebergements/4_small/febrian-zakaria-M6S1WvfW68A-unsplash.jpg" alt="logement febrian">  
                                <div class="titrePhoto"> <!--Description du lieu-->
                                    Hôtel chez Amina
                                </div>
                                <div class="prixNuit"> <!--Prix de la nuit-->
                                    Nuit à partir de 96€
                                </div>
                                <div class="logoEtoileBleu">
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                </div>
                                </div>
                            </a>    
                        </div>
                    <div class="suiteHebergement">
                        <a href="">
                            <p>
                                Afficher plus
                            </p>
                        </a>
                    </div>
                                                         <!--SLOT6-->
                </div>
                <div class="lesPlusPopulaires"> <!--Création du bloc 3-->
                    <h2>
                        Les plus populaires
                        <i class="fas fa-chart-line"></i>
                    </h2> 
                    <div class="hebergementPopulaire"> <!--bloc contour-->
                        <div class="photoPopulaire">
                            <a href="">
                                <img src="Reservia/images/hebergements/4_small/emile-guillemot-Bj_rcSC5XfE-unsplash.jpg" alt="logement emile"> 
                            </a>
                        </div>
                        <div class="titrePhotoPopulaire"> <!--Description du lieu-->
                            <a href="">
                                Hôtel Le soleil du <br>
                                matin
                            </a>
                        </div>
                            <div class="prixNuitPopulaire"> <!--Prix de la nuit-->
                                <a href="">
                                    Nuit à partir de 128€
                                </a>
                            </div>
                            <div class="placementEtoile"> <!--Pour placer les étoiles en bas-->
                                <div class="logoEtoileBleuPopulaire">
                                    <a href="">
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                    </a>
                                </div>  
                            </div>   
                    </div> 
                    <div class="hebergementPopulaire"> <!--bloc contour-->
                        <div class="photoPopulaire">
                            <a href="">
                                <img src="Reservia/images/hebergements/4_small/aw-creative-VGs8z60yT2c-unsplash.jpg" alt="logement creative"> 
                            </a>
                        </div> 
                        <div class="titrePhotoPopulaire"> <!--Description du lieu-->
                            <a href="">
                                Au coeur de l'eau <br>
                                Chambres d'hôtes
                            </a>
                        </div>
                        <div class="prixNuitPopulaire"> <!--Prix de la nuit-->
                            <a href="">
                                Nuit à partir de 71€
                            </a>
                        </div>
                        <div class="placementEtoile">
                            <div class="logoEtoileBleuPopulaire1">
                                <a href="">
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>    
                                </a>
                            </div>
                        </div>
                     
                    </div> 
                    <div class="hebergementPopulaire"> <!--bloc contour-->
                        <div class="photoPopulaire">
                            <a href="">
                                <img src="Reservia/images/hebergements/4_small/febrian-zakaria-sjvU0THccQA-unsplash.jpg" alt="logement febrian">
                            </a>
                        </div> 
                        <div class="titrePhotoPopulaire"> <!--Description du lieu-->
                            Hôtel Tout bleu et <br>
                            Blanc
                        </div>
                        <div class="prixNuitPopulaire"> <!--Prix de la nuit-->
                            <a href="">
                                Nuit à partir de 68€
                            </a>
                        </div>
                        <div class="placementEtoile">
                            <div class="logoEtoileBleuPopulaire1">
                                <a href="">
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                </a>     
                            </div>  
                        </div>
                    </div>
                </div>
            </div>
            <div class="titreActivite">
                <h3 id="activite"> <!--Ancre navigateur activite-->
                    Activités à Marseille
                </h3>
            </div>
            <div class="blocGeneralActivite"> <!--Bloc general activité-->
                <div class="activiteMarseille"> <!--Bloc contour--> 
                    <div class="photoActivite">
                        <a href="">
                            <img src="Reservia/images/activites/4_small/reno-laithienne-QUgJhdY5Fyk-unsplash.jpg" alt="vieux port">
                        </a>
                    </div>
                    <div class="titrePhotoActivite">
                        <a href="">
                            <p>
                                Vieux Port
                            </p>
                        </a>
                    </div>                    
                </div>                              <!--SLOT 1 ACTIVITE-->
                <div class="activiteMarseille1"> <!--Bloc contour-->
                    <div class="photoActivite1">
                        <a href="">
                            <img src="Reservia/images/activites/4_small/paul-hermann-QFTrLdQIRhI-unsplash.jpg" alt="fort de pomègues">
                        </a>
                    </div>
                    <div class="titrePhotoActivite">
                        <a href="">
                            <p>
                                Fort de pomègues
                            </p>
                        </a>
                    </div>    
                </div>                              <!--SLOT 2 ACTIVITE-->
                <div class="activiteMarseille2"> <!--Bloc contour-->
                    <div class="photoActivite2">
                        <a href="">
                            <img src="Reservia/images/activites/4_small/kevin-hikari-rV_Qd1l-VXg-unsplash.jpg" alt="iles du frioul">
                        </a>
                    </div>
                    <div class="titrePhotoActivite">
                        <a href="">
                            <p>
                                Iles du Frioul
                            </p>
                        </a>
                    </div>
                </div>                               <!--SLOT 3 ACTIVITE-->
                <div class="activiteMarseille"> <!--Bloc contour-->
                    <div class="photoActivite">
                        <a href="">
                            <img src="Reservia/images/activites/4_small/kilyan-sockalingum-NR8-cBCN3aI-unsplash.jpg" alt="parc national des calanques">
                        </a>
                    </div>
                    <div class="titrePhotoActivite">
                        <a href="">
                            <p>
                                Parc National des Calanques
                            </p>
                        </a>
                    </div>
                </div>                               <!--SLOT 4 ACTIVITE-->
                <div class="activiteMarseille3"> <!--Bloc contour-->
                    <div class="photoActivite3">
                        <a href="">
                            <img src="Reservia/images/activites/4_small/florian-wehde-xW9e8gdotxI-unsplash.jpg" alt="notre dame de la garde">
                        </a>
                    </div>
                    <div class="titrePhotoActivite">
                        <a href="">
                            <p>
                                Notre-Dame-de-la-Garde
                            </p>
                        </a>
                    </div>
                </div>                               <!--SLOT 5 ACTIVITE-->
                <div class="activiteMarseille4"> <!--Bloc contour-->
                    <div class="photoActivite4">
                        <a href="">
                            <img src="Reservia/images/activites/4_small/lena-paulin-wH2-EJoDcV0-unsplash.jpg" alt="parc longchamp">
                        </a>
                    </div>
                    <div class="titrePhotoActivite">
                        <a href="">
                            <p>
                                Parc Longchamp
                            </p>
                        </a>
                    </div>      
                </div>                               <!--SLOT 6 ACTIVITE-->
            </div>                                   <!--FIN DU BLOC GENERAL ACTIVITE-->
        </section>

        <footer>
            <div class="blocFooter"> <!--Bloc qui va contenir le footer-->
                <div class="titreFooter"> <!--1er liste-->
                    <p>
                        A propos
                    </p>
                    <ul>
                        <li><a href="">Fonctionnement du site</a></li>
                        <li><a href="">Conditions générales de vente</a></li>
                        <li><a href="">Données et confidentialité</a></li>          
                    </ul>
                </div>
                <div class="titreFooter"> <!--2eme liste-->
                    <p>
                        Nos Hébergement
                    </p>
                    <ul>
                        <li><a href="">Charte qualité</a></li>
                        <li><a href="">Soumettre votre hôtel</a></li>
                    </ul>
                </div>
                <div class="titreFooter"> <!--2eme liste-->
                    <p>
                        Assistance
                    </p>
                    <ul>
                        <li><a href="">Centre d'aide</a></li>
                        <li><a href="">Nous contacter</a></li>
                    </ul>
                </div>
            </div>
        </footer>
    </body>
</html>
