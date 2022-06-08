<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="utf-8" />
    <!--  VIEWPORT  Responsive sur la largeur d'ecran  -->
    <link rel="stylesheet" href="./css/normalize.css" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <!--  POLICE D ECRITURE : Raleway  -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
    <!--  CDN ICONES DU SITE  -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css" />
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous" />
    <!--  CSS du site  -->
  <style>html:lang(fr) {}

body {
    margin: 0;
    font-family: "Raleway", sans-serif;
    margin: 0;
}

* {
    box-sizing: border-box;
}

header {
    display: flex;
    justify-content: space-between;
}

main {
    margin-left: 45px;
    margin-right: 45px;
}


/****************HEADER****************/


/*                LOGO                */

.header-logo {
    display: flex;
}

.header-logo-image {
    height: 46px;
    margin: 52px;
    margin-bottom: 30px;
}


/*                MENU                */

.header-menu {
    margin-right: 40px;
}

.header-menu-block {
    list-style-type: none;
    display: flex;
    padding: 0;
    margin: 0;
}

.header-menu-block-liste-lien {
    color: #0065FC;
    text-decoration: none;
    text-align: center;
}

.header-menu-block-liste-texte {
    display: block;
    width: 140px;
    line-height: 125px;
    color: black;
    font-size: 14px;
}

.header-menu-block-liste-texte:hover {
    border-top: 3px solid #0065FC;
    color: #0065FC;
}


/*            VU TABLETTE HEADER                */

@media all and (min-width: 768px) and (max-width: 991px) {}


/*            VU MOBILE HEADER                 */

@media (max-width: 767px) {
    header {
        flex-direction: column;
        width: 100%;
    }
    main {
        margin-left: 0px;
        margin-right: 0px;
    }
    /*LOGO*/
    .header-logo {
        justify-content: center;
    }
    .header-logo-image {
        height: 58px;
        margin: 0px;
        padding-bottom: 0px;
        margin-top: 25px;
        margin-bottom: 0px;
    }
    /*MENU*/
    .header-menu {
        display: flex;
        margin-right: 0px;
        margin-bottom: 20px;
    }
    .header-menu-block {
        width: 100%;
        text-align: center;
    }
    .header-menu-block-liste:nth-child(1) {
        flex-basis: 50%;
    }
    .header-menu-block-liste:nth-child(2) {
        flex-basis: 50%;
    }
    /*Liste*/
    .header-menu-block-liste {
        flex: auto;
        margin: 0;
        height: 65px;
        text-align: center;
        line-height: 20px;
        justify-content: center;
        border-bottom: 3px #F2F2F2 solid;
    }
    /*Liste survolee*/
    .header-menu-block-liste:hover {
        border-bottom: 3px #0065FC solid;
    }
    /*texte*/
    .header-menu-block-liste-texte {
        display: block;
        width: 100%;
        line-height: 62px;
        border-top: 3px solid white;
        color: black;
    }
    /*liste survolee modification du texte*/
    .header-menu-block-liste:hover .header-menu-block-liste-texte {
        border-top: none;
        color: #0065FC;
    }
    /*Lien*/
    .header-menu-block-liste-lien {
        color: blue;
        font-size: 17px;
        text-decoration: none;
        text-align: center;
    }
}


/**************RECHERCHE***************/


/*             STRUCTURE              */

.recherche {
    display: flex;
    justify-content: flex-start;
    flex-direction: column;
}

.recherche-formulaire {
    display: flex;
    justify-content: flex-start;
    flex-direction: row;
    margin-top: 16px;
}


/*             TITRE ET SOUS TITRE              */

.recherche-titre {
    font-size: 19px;
    font-weight: bold;
    margin: 0;
}

.recherche-soustitre {
    font-size: 14px;
    font-weight: lighter;
    margin: 0;
    margin-top: 10px;
}


/*             ICONE POSITION            */

.recherche-formulaire-icone {
    background-color: #F2F2F2;
    color: #000000;
    border-top-left-radius: 25%;
    border-bottom-left-radius: 25%;
    width: 40px;
    height: 40px;
    font-size: 15px;
    text-align: center;
    line-height: 40px;
}


/*             BARRE DE RECHERCHE            */

.recherche-formulaire-zonetexte-champ {
    border: 1px solid #F2F2F2;
    background-color: white;
    padding-top: 11px;
    padding-bottom: 11px;
    padding-left: 16px;
    width: 200px;
    outline-color: #deebff;
    color: black;
    font-size: 14px;
    font-weight: bold;
}

.recherche-formulaire-zonetexte {
    width: 200px;
}


/*             BOUTON DE VALIDATION            */

.recherche-formulaire-bouton-bureau {
    background-color: #0065FC;
    border: none;
    color: white;
    padding: 10px 0px;
    text-align: center;
    margin: 0px 0px;
    cursor: pointer;
    width: 120px;
    height: 40px;
    font-size: 15px;
    font-weight: bold;
    border-bottom-right-radius: 15px;
    border-top-right-radius: 15px;
}

.recherche-formulaire-bouton-bureau:hover {
    background-color: #deebff;
    color: #0065FC;
}

.recherche-formulaire-bouton-mobile {
    display: none;
    background-color: #0065FC;
    color: white;
    border-radius: 32%;
    border-style: none;
    width: 55px;
    height: 55px;
    font-size: 18px;
    text-align: center;
    line-height: 40px;
}


/*            VU RECHERCHE TABLETTE                */

@media all and (min-width: 768px) and (max-width: 991px) {}


/*            VU RECHERCHE MOBILE            */

@media (max-width: 767px) {
    .recherche {
        margin-left: 20px;
        margin-right: 20px;
    }
    .recherche-titre {
        font-size: 23px;
    }
    .recherche-soustitre {
        font-size: 17px;
        font-weight: lighter;
        margin: 0;
        margin-top: 13px;
        margin-bottom: 16px;
    }
    .recherche-formulaire-titre {
        font-size: 24px;
    }
    .recherche-formulaire-soustitre {
        font-size: 18px;
        margin-top: 20px;
    }
    .recherche-formulaire-bouton-bureau {
        display: none;
    }
    .recherche-formulaire-bouton-mobile {
        display: block;
    }
    .recherche-formulaire-zonetexte {
        width: 100%;
        font-size: 20px;
    }
    .recherche-formulaire-zonetexte-champ {
        width: 110%;
        font-size: 20px;
        padding-top: 15px;
        padding-bottom: 15px;
        padding-left: 16px;
    }
    .recherche-formulaire-icone {
        width: 55px;
        height: 55px;
        font-size: 20px;
        line-height: 53px;
        border-top-left-radius: 33%;
        border-bottom-left-radius: 33%;
    }
}


/****************FILTRE****************/


/*            STRUCTURE            */

.filtre {
    display: flex;
    justify-content: flex-start;
    flex-direction: column;
}

.filtre-container {
    display: inline-flex;
    justify-content: flex-start;
    flex-direction: row;
    flex-wrap: wrap;
}

.filtre-container-ligne {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    flex-direction: row;
    align-content: center;
}

.filtre-information {
    display: flex;
    margin-left: 0px;
}


/*            TITRE FILTRE            */

.filtre-container-titre {
    margin: 0;
    margin-top: 24px;
    padding-right: 29px;
}

.filtre-container-titre-texte {
    color: black;
    font-size: 16px;
    font-weight: bold;
}


/*            BOUTON FILTRE            */

.filtre-container-ligne-bouton {
    align-items: center;
    margin-top: 25px;
    margin-right: 20px;
    padding-right: 20px;
    padding-left: 0px;
    height: 48px;
    border-top: 2.5px solid #F2F2F2;
    border-right: 2.5px solid #F2F2F2;
    border-bottom: 2.5px solid #F2F2F2;
    border-radius: 47px;
    cursor: pointer;
}

.filtre-container-ligne-bouton-icone {
    display: inline-block;
    background-color: #deebff;
    color: #0065FC;
    font-size: 16px;
    border-radius: 50%;
    width: 44px;
    height: 44px;
    text-align: center;
    line-height: 46px;
    margin-block: -1px;
}

.filtre-container-ligne-bouton-texte {
    display: inline-block;
    font-size: 15px;
    font-weight: bold;
    margin-left: 4px;
    padding-top: 8px;
    padding-left: 8px;
    color: black;
}

.filtre-container-ligne-bouton:hover {
    background-color: #256efe;
}

.filtre-container-ligne-bouton:hover .filtre-container-ligne-bouton-texte {
    color: white;
}


/*            INFORMATION FILTRE            */

.filtre-information-icone {
    color: #005fcc;
    border-radius: 50%;
    width: 24px;
    height: 41px;
    text-align: center;
    line-height: 35px;
    display: inline-block;
}

.filtre-information-texte {
    font-size: 14px;
    font-weight: lighter;
    margin: 0;
    margin-top: 8px;
    margin-left: 10px;
}

.filtre-information-icone-modification {
    background: white;
    width: 24px;
    height: 24px;
    border-radius: 50%;
    text-align: center;
    font-size: 11px;
    line-height: 19px;
    vertical-align: middle;
    padding: 0px;
    border: 2px solid #F2F2F2;
}

.fa-info {
    color: #005fcc;
}


/*            VU FILTRE TABLETTE                */

@media all and (min-width: 768px) and (max-width: 991px) {}


/*           VU FILTRE MOBILE            */

@media (max-width: 767px) {
    .filtre {
        margin-left: 0px;
        margin-right: 0px;
    }
    .filtre-container-titre {
        margin-top: 15px;
    }
    .filtre-container-titre-texte {
        margin-bottom: 0px;
        font-size: 20px;
    }
    .filtre-container-ligne {
        justify-content: space-between;
    }
    .filtre-container {
        margin-left: 22px;
        margin-right: 22px;
    }
    .filtre-container-ligne-bouton {
        margin-top: 13px;
        padding-right: 25px;
        height: 55px;
        margin-right: 0px;
    }
    .filtre-container-ligne-bouton-texte {
        font-size: 17px;
    }
    .filtre-container-ligne-bouton-icone {
        font-size: 19px;
        width: 51px;
        height: 51px;
        line-height: 52px;
    }
    .filtre-information {
        margin-left: 20px;
        margin-top: 34px;
        margin-bottom: 35px;
    }
    .filtre-information-icone {
        line-height: 32px;
    }
    .filtre-information-icone-modification {
        width: 25px;
        height: 25px;
        font-size: 12px;
        line-height: 22px;
    }
    .filtre-information-texte {
        font-size: 17px;
        margin-left: 11px;
    }
}


/****************HEBERGEMENT ET POPULAIRE****************/


/*            STRUCTURE GENERAL            */

.conteneur {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-between;
    width: 100%;
}


/*            STRUCTURE HEBERGEMENT            */

.hebergements {
    display: flex;
    flex-direction: column;
    width: 65%;
    background-color: #F2F2F2;
    border-radius: 25px;
    padding-bottom: 40px;
    padding-left: 20px;
    padding-right: 20px;
}

.hebergement-section {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-around;
    width: 100%;
    margin-bottom: 30px;
}


/*            STRUCTURE POPULAIRE            */

.populaire {
    display: flex;
    flex-direction: column;
    width: 32%;
    background-color: #F2F2F2;
    border-radius: 25px;
}

.populaire-section {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: space-around;
    width: 100%;
    background-color: rgba(255, 0, 0, 0);
    align-items: center;
}


/*            STRUCTURE ARTICLES HEBERGEMENT            */

.hebergement-section-carte {
    margin-top: 20px;
    background-color: white;
    height: fit-content;
    padding-bottom: 11px;
    width: 31%;
    border-radius: 18px;
}

.hebergement-section-carte:hover {
    box-shadow: inset 0 0 6px #b0b0b0, 0 0 20px #999999;
    cursor: pointer;
}


/*            STRUCTURE ARTICLES POPULAIRE            */

.populaire-section-carte {
    width: 87%;
    display: flex;
    flex-direction: row;
    height: fit-content;
    padding-bottom: 10px;
    margin-bottom: 30px;
    border-radius: 14px;
    background-color: white;
}

.populaire-section-carte:hover {
    box-shadow: inset 0 0 6px #b0b0b0, 0 0 20px #999999;
    cursor: pointer;
}


/*         FORMATAGE DU TEXTE               */

.hebergements-titre {
    margin-left: 13px;
    margin-bottom: 0px;
    margin-top: 40px;
}

.populaire-titre {
    display: flex;
    margin-left: 30px;
    margin-right: 24px;
    margin-bottom: 20px;
    margin-top: 40px;
    justify-content: space-between;
}

.hebergements-titre,
.populaire-titre {
    font-size: 20px;
    font-weight: bold;
}

.hebergements-afficherplus-lien {
    font-size: 16px;
    font-weight: bold;
    padding-top: 10px;
    margin: 0px;
}

.populaire-section-carte-block-droit-texte-nom,
.hebergement-section-nomhebergement,
.hebergement-section-prixhebergement-gras,
.populaire-section-carte-block-droit-texte-prix-gras {
    font-weight: bold;
}

.populaire-section-carte-block-droit-texte-nom {
    font-size: 15px;
    padding-top: 12px;
    margin: 0px;
    padding-left: 20px;
}

.populaire-section-carte-block-droit-texte-prix {
    font-size: 12px;
    padding-top: 6px;
    margin: 0px;
    padding-left: 20px;
}

.hebergement-section-prixhebergement {
    font-size: 13px;
    padding-top: 0px;
    margin-top: 4px;
    margin-bottom: 0px;
    margin-left: 20px;
}

.hebergement-section-nomhebergement {
    font-size: 15px;
    padding-top: 0px;
    margin-top: 4px;
    margin-bottom: 0px;
    margin-left: 20px;
}


/*           FORMATAGE DES ETOILES       */

.hebergement-section-etoiles {
    color: #F2F2F2;
    padding-top: 10px;
    margin: 0;
    margin-left: 20px;
    font-size: 10px;
}

.populaire-section-carte-block-droit-etoiles {
    color: #F2F2F2;
    padding-top: 25px;
    margin: 0;
    margin-left: 20px;
    font-size: 10px;
}

.populaire-section-carte-block-droit {
    align-items: end;
    width: 70%;
}

.hebergement-section-etoile-selectionnee {
    color: #0065FC;
}

.populaire-section-carte-block-droit-etoiles-selectionnee {
    color: #0065FC;
}

.populaire-section-carte:hover .populaire-section-carte-block-droit-etoiles-selectionnee {
    color: rgba(255, 208, 0, 0.949);
}

.hebergement-section-carte:hover .hebergement-section-etoile-selectionnee {
    color: rgba(255, 208, 0, 0.949);
}


/*       FORMATAGE DES IMAGES     */


/*       HEBERGEMENTS     */

.hebergement-section-carte-blochaut-image {
    width: 96%;
    height: 110px;
    background-size: cover!important;
    background-position: center;
    border-radius: 14px 14px 0px 0px;
    margin: 5px;
    /* background-attachment: local;*/
}


/*       POPULAIRE     */

.populaire-section-carte-block-gauche {
    width: 47%;
    height: 136px;
}

.populaire-section-carte-block-droit-texte {
    width: 75%;
    height: 90px;
}

.populaire-section-carte-block-gauche-image {
    width: 100%;
    height: 100%;
    background-position: center;
    border-radius: 14px 0px 0px 14px;
    margin: 5px;
    background-attachment: scroll;
}

.populaire-taille-image-haut {
    background-size: 200px;
}

.populaire-taille-image-milieu {
    background-size: 188px;
}

.populaire-taille-image-bas {
    background-size: 140px;
}


/*       LIEN HEBERGEMENT SAVOIR PLUS       */

.hebergements-afficherplus-lien {
    text-decoration: none;
    color: black;
}

.hebergements-afficherplus {
    margin: 0px;
    padding-top: 18px;
    margin-left: 12px;
}


/*            VU HERBGEMENT ET POPULAIRE TABLETTE                */

@media all and (min-width: 768px) and (max-width: 991px) {}


/*       VU HEBERGEMENT ET POPULAIRE MOBILE       */

@media (max-width: 767px) {
    .conteneur {
        flex-direction: column-reverse;
    }
    .hebergements {
        padding-left: 7px;
        padding-right: 7px;
        width: 100%;
        padding-bottom: 25px;
        background-color: white;
    }
    .populaire {
        width: 100%;
        border-radius: 0px;
        margin-bottom: 12px;
        padding-bottom: 29px;
    }
    .hebergements-titre {
        margin-top: 28px;
        margin-left: 18px;
        margin-bottom: 0px;
        font-size: 21px;
    }
    .hebergement-section {
        align-items: center;
        flex-direction: column;
        margin-bottom: 0px;
    }
    .hebergement-section-carte {
        width: 90%;
        box-shadow: inset 0 0 2px #d3d3d3, 0 0 10px #d3d3d3;
    }
    .populaire-titre {
        margin-top: 40px;
        margin-bottom: 30px;
        margin-left: 30px;
        margin-right: 30px;
        font-size: 23px;
    }
    .populaire-section-carte {
        padding-bottom: 0px;
        margin-bottom: 10px;
        box-shadow: inset 0 0 2px #d3d3d3, 0 0 10px #d3d3d3;
    }
    .hebergements-afficherplus {
        margin: 0;
        margin-left: 20px;
        margin-top: 11px;
    }
    .hebergement-section-carte-blochaut-image {
        width: 97%;
        height: 118px;
        background-size: 344px;
        background-position: center;
        border-radius: 16px 16px 0px 0px;
        margin: 5px;
        background-attachment: local;
    }
    .populaire-section-carte-block-gauche-image {
        width: 125px;
        height: 125px;
    }
    .populaire-taille-image-haut {
        background-size: 211px;
    }
    .populaire-taille-image-milieu {
        background-size: 190px;
    }
    .populaire-taille-image-bas {
        background-size: 135px;
    }
    .hebergements-afficherplus-lien {
        font-size: 17px;
        font-weight: bold;
        padding-top: 10px;
        margin: 0px;
    }
    .populaire-section-carte-block-droit-texte-prix {
        padding-top: 6px;
        padding-left: 12px;
        margin: 0px;
        font-size: 14px;
        margin-top: 0px;
        margin-left: 0px;
    }
    .hebergement-section-nomhebergement {
        font-size: 15px;
        margin: 0px;
        padding: 0px;
        padding-top: 4px;
        margin-left: 18px;
    }
    .hebergement-section-prixhebergement {
        font-size: 14px;
        margin: 0px;
        padding: 0px;
        padding-top: 4px;
        margin-left: 18px;
    }
    .hebergement-section-etoiles {
        margin-left: 17px;
        padding-top: 7px;
        font-size: 11px;
    }
    .populaire-section-carte-block-droit-etoiles {
        margin-left: 10px;
        padding-top: 14px;
        font-size: 12px;
    }
    .populaire-section-carte-block-droit-texte-nom {
        font-size: 17px;
        margin-top: 7px;
        margin-left: 0px;
        padding-left: 12px;
        padding-bottom: 0px;
    }
}


/****************ACTIVITES****************/


/*            STRUCTURE GENERAL            */

.activites {
    width: 100%;
    margin-bottom: 40px;
    display: flex;
    flex-direction: column;
}

.activites-conteneur {
    display: inline-flex;
    flex-direction: row;
    justify-content: space-between;
    flex-wrap: wrap;
    width: 100%;
}

.activites-conteneur-section {
    display: flex;
    flex-direction: column;
    width: 23%;
    justify-content: space-between;
    margin: 0px;
    padding: 0px;
}

.activites-carte-simple {
    display: flex;
    flex-direction: column;
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    border-bottom: none;
    width: 100%;
}

.activites-carte-double {
    display: flex;
    flex-direction: column;
    background-size: cover;
    justify-items: baseline;
    width: 100%;
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    border-bottom: none;
}


/*            TITRE            */

.activites-titre {
    margin-left: 0px;
    padding-top: 40px;
    margin-bottom: 25px;
    font-size: 20px;
}


/*            SECTION ET ARTICLE            */

.activites-conteneur-section-carte {
    height: auto;
    margin-left: 0px;
    width: 100%;
    border-radius: 25px;
    box-shadow: inset 0 0 1px #b0b0b0, 0 0 7px#999999;
}

.activites-conteneur-section-carte:hover {
    box-shadow: inset 0 0 6px #b0b0b0, 0 0 20px #999999;
    cursor: pointer;
}


/*            TEXTE FIN DE CARDS            */

.activites-conteneur-section-carte-texte {
    display: block;
    padding: 17px 20px;
    border: 1px solid #f2f2f2;
    border-top: none;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
    font-weight: bold;
    font-size: 14px;
}


/*            FORMATAGE DES IMAGES            */

.activites-conteneur-section-carte-double-gauche-haut {
    background-position: 56% 40%;
    background-size: 278px;
    height: 160px;
}

.activites-conteneur-section-carte-double-gauche-bas {
    background-position: 50% 13%;
    height: 106px;
}

.activites-conteneur-section-carte-double-droite-haut {
    background-position: 50% 11%;
    height: 120px;
}

.activites-conteneur-section-carte-double-droite-bas {
    background-position: 50% 15%;
    height: 140px;
}

.activites-conteneur-section-carte-simple-premiere {
    background-position: 50% 0%;
    background-size: 600px;
    height: 350px;
}

.activites-conteneur-section-carte-simple-seconde {
    background-position: 49% 0%;
    background-size: 600px;
    height: 350px;
    filter: brightness(1.2);
}


/*            VU ACTIVITES TABLETTE                */

@media all and (min-width: 768px) and (max-width: 991px) {}


/*           VU ACTIVITES MOBILE           */

@media (max-width: 767px) {
    .activites-titre {
        padding-top: 0px;
        margin-bottom: 24px;
        font-size: 22px;
        margin-left: 29px;
    }
    .activites-conteneur {
        flex-direction: column;
        align-items: center;
    }
    .activites-conteneur-section {
        width: 87%;
    }
    .activites-conteneur-section-carte {
        margin-bottom: 20px;
    }
    .activites-conteneur-section-carte-double-gauche-haut {
        background-position: 40% 45%;
        height: 120px;
        background-size: 100%;
    }
    .activites-conteneur-section-carte-double-gauche-bas {
        background-position: 40% 32%;
        height: 120px;
        background-size: 100%;
    }
    .activites-conteneur-section-carte-double-droite-haut {
        background-position: 40% 26%;
        height: 120px;
        background-size: 100%;
    }
    .activites-conteneur-section-carte-double-droite-bas {
        background-position: 40% 32%;
        height: 120px;
        background-size: 100%;
    }
    .activites-conteneur-section-carte-simple-premiere {
        background-position: 40% 24%;
        height: 133px;
        background-size: 100%;
    }
    .activites-conteneur-section-carte-simple-seconde {
        background-position: 40% 32%;
        height: 120px;
        background-size: 100%;
        filter: brightness(1.2);
    }
    .activites-conteneur-section-carte-texte {
        font-size: 16px;
    }
}


/****************FOOTER****************/


/*            STRUCTURE GENERAL            */

.findepage {
    height: 100%;
    width: 100%;
    background-color: #f2f2f2;
}

.findepage-container {
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    flex-wrap: wrap;
}


/*            TITRES            */

.findepage-section-titre {
    padding-left: 40px;
    font-size: 20px;
}


/*            LISTES            */

.findepage-premiere-section {
    margin: 10px;
    margin-left: 10px;
    width: 27%;
    font-size: 15px;
    margin-top: 20px;
}

.findepage-autre-section {
    margin: 0px;
    padding-left: 33px;
    padding-top: 20px;
    width: 27%;
    font-size: 15px;
    margin-right: 54px;
}

.findepage-section-laisons {
    list-style-type: none;
}

.findepage-section-laisons-liste {
    margin-top: 10px;
}


/*            LIENS            */

.findepage-section-laisons-liste-lien {
    text-decoration: none;
    color: black;
}

.findepage-section-laisons-liste:hover {
    color: #0065FC;
}


/*            VU FOOTER TABLETTE                */

@media all and (min-width: 768px) and (max-width: 991px) {}


/*            VU FOOTER MOBILE            */

@media (max-width: 767px) {
    .findepage-container {
        flex-direction: column;
        padding-bottom: 35px;
    }
    .findepage-premiere-section {
        margin: 0px;
        margin-left: 0px;
        width: 100%;
        margin-top: 12px;
    }
    .findepage-autre-section {
        margin: 0px;
        margin-top: 0px;
        width: 100%;
        padding-left: 0px;
    }
    .findepage-section-titre {
        font-size: 17px;
    }
    .findepage-section-laisons-liste {
        font-size: 15px;
        cursor: pointer;
    }
}</style>
    <!--  TITRE  -->
    <title>Booky</title>
</head>

<body>
    <div id="block-page">
        <!-- DEBUT HEADER : LOGO et MENU-->
        <header>
            <!--BLOC FIXE POUR DECALAGE DES ANCRES-->
            <!--LOGO-->
            <div class="header-logo"><img class="header-logo-image" src="./images/logo/Booki@3x.png" alt="Logo" /></div>

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
                                <p class="hebergement-section-carte-blochaut-image" style="background-image: url('./images/hebergements/4_small/marcus-loke-WQJvWU_HZFo-unsplash.jpg');"></p>
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
                                <p class="hebergement-section-carte-blochaut-image" style="background-image: url('./images/hebergements/4_small/fred-kleber-gTbaxaVLvsg-unsplash.jpg');"></p>
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
                                <p class="hebergement-section-carte-blochaut-image" style="background-image: url('./images/hebergements/4_small/reisetopia-B8WIgxA_PFU-unsplash.jpg');"></p>
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
                                <p class="hebergement-section-carte-blochaut-image" style="background-image: url('./images/hebergements/4_small/annie-spratt-Eg1qcIitAuA-unsplash.jpg');"></p>
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
                                <p class="hebergement-section-carte-blochaut-image" style="background-image: url('./images/hebergements/4_small/nicate-lee-kT-ZyaiwBe0-unsplash.jpg');"></p>
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
                                <p class="hebergement-section-carte-blochaut-image" style="background-image: url('./images/hebergements/4_small/febrian-zakaria-M6S1WvfW68A-unsplash.jpg');"></p>
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
                                <p class="populaire-section-carte-block-gauche-image populaire-taille-image-haut" style="background-image: url('./images/hebergements/4_small/emile-guillemot-Bj_rcSC5XfE-unsplash.jpg');"></p>
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
                                <p class="populaire-section-carte-block-gauche-image populaire-taille-image-milieu" style="background-image: url('./images/hebergements/4_small/aw-creative-VGs8z60yT2c-unsplash.jpg');"></p>
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
                                <p class="populaire-section-carte-block-gauche-image populaire-taille-image-bas" style="background-image: url('./images/hebergements/4_small/febrian-zakaria-sjvU0THccQA-unsplash.jpg');"></p>
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
                            <span class="activites-conteneur-section-carte-simple-premiere activites-carte-simple" style="background-image: url('./images/activites/3_medium/reno-laithienne-QUgJhdY5Fyk-unsplash.jpg');"></span>
                            <span class="activites-conteneur-section-carte-texte">Vieux Port</span>
                        </div>
                    </div>
                    <div class="activites-conteneur-section">
                        <div class="activites-conteneur-section-carte">
                            <span class="activites-conteneur-section-carte-double-gauche-haut activites-carte-double" style="background-image: url('./images/activites/3_medium/paul-hermann-QFTrLdQIRhI-unsplash.jpg');"></span>
                            <span class="activites-conteneur-section-carte-texte">Fort de Pomègues</span>
                        </div>
                        <div class="activites-conteneur-section-carte">
                            <span class="activites-conteneur-section-carte-double-gauche-bas activites-carte-double" style="background-image: url('./images/activites/3_medium/kevin-hikari-rV_Qd1l-VXg-unsplash.jpg');"></span>
                            <span class="activites-conteneur-section-carte-texte">Îles du Frioul</span>
                        </div>
                    </div>
                    <div class="activites-conteneur-section">
                        <div class="activites-conteneur-section-carte">
                            <span class="activites-conteneur-section-carte-simple-seconde activites-carte-simple" style="background-image: url('./images/activites/3_medium/kilyan-sockalingum-NR8-cBCN3aI-unsplash.jpg');"></span>
                            <span class="activites-conteneur-section-carte-texte">Parc National des Calanques</span>
                        </div>
                    </div>
                    <div class="activites-conteneur-section">
                        <div class="activites-conteneur-section-carte">
                            <span class="activites-conteneur-section-carte-double-droite-haut activites-carte-double" style="background-image: url('./images/activites/3_medium/florian-wehde-xW9e8gdotxI-unsplash.jpg');"></span>
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
