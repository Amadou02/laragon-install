# L'environnement de développement web Laragon

Laragon est un environnement de développement complet, simple et léger, qui
tourne uniquement sous **Windows™**.

## Installation et configuration

1.  Récupérez [l'exécutable](Laragon/laragon-full.exe) fourni ou téléchargez
    l'édition **Laragon Full** directement sur le [site officiel de
    Laragon](https://laragon.org/download/).

2.  Installez Laragon

    1.  Double-clic avec le bouton gauche sur
        « [laragon-full.exe ](Laragon/laragon-full.exe)».

    2.  Sélectionner la langue et cliquer avec le bouton gauche sur le bouton
        « Ok».

    3.  Choisir le [dossier
        d’installation](Laragon/assets/dossier-installation.png) et cliquer avec
        le bouton gauche sur le bouton « Suivant ».

    4.  Cliquer avec le bouton gauche sur « Suivant » dans l’assistant
        d’installation de Laragon.

    5.  Sélectionner des [options](Laragon/assets/auto-start.png) (2 et 3) et
        cliquer avec le bouton gauche sur « Suivant »

    6.  Cliquer avec le bouton gauche sur le bouton « Installer »

    7.  Cliquer avec le bouton gauche sur le bouton « Terminer »

    8.  Finir l’installation – démarrage de Laragon
        ([screen](Laragon/assets/interface-laragon.png)).

    9.  Découverte de Laragon
        ([video](https://www.youtube.com/watch?v=eUTJh0Yyc8U)) – [18 :31].

    10. Configurer le dossier.

3.  Choisissez le dossier racine (root) pour tous les projets

    1.  Cliquer avec le bouton droit sur l’application Laragon ([ouverture menu
        contextuel](Laragon/assets/config-step1.PNG)).

    2.  Navigation : www \> Échanger de Document Root \> Sélectionner un autre,
        puis cliquer ([screen](Laragon/assets/config-step2.PNG)).

    3.  Créer un nouveau dossier (Ce PC \>
        [Documents](Laragon/assets/config-step5.PNG))

        1.  Clic droit \> Nouveau \> [Dossier](Laragon/assets/config-step6.PNG)

        2.  Nom du dossier « [www ](Laragon/assets/config-step7.PNG)».

4.  Choisissez l’extension des vhost
    ([screen](Laragon/assets/extension-vhost.PNG))

    1.  Clic droit sur l’application Laragon (ouverture du menu contextuel).

    2.  Cliquer sur préférences

    3.  Modifier l’extension en « .dev ».

5.  Créez votre premier projet

    1.  Cliquer sur le bouton « Démarrer » pour lancer les serveurs.

    2.  Clic droit sur l’application Laragon (ouverture du menu contextuel)

    3.  Navigation : Créer un site web rapidement \> Blank

    4.  Nom du projet (nommage en minuscule sans espace, sans underscrore, ni
        caractères accentués).

    5.  Créer un fichier index.php à la racine du dossier créé dans votre
        répertoire « root » (**…/Documents/www**).

    6.  Éditer index.php, ajouter du texte.

    7.  Consulter la page à l’adresse « **mondossier.dev** »

## Partage de site avec nGrok

nGrok est une application gratuite qui va permettre de partager sur internet son
site en cours de développement dans un environnement local (Votre PC).

Elle va créer un tunnel et vous fournir une adresse temporaire du type
« **vwxyz.ngrok.com »** permettant la consultation de votre site en ligne.

### Partage avec nGrok sur Laragon.

1.  Clic droit sur l’application Laragon (menu contextuel).

2.  Navigation : « www \> Partager \> Partager-\>  « monsite.dev »

3.  Copier et partager le lien généré.

## Migration de Wamp, Xampp vers Laragon

Suivre [les instructions de
migration](https://laragon.org/download/migrate-from-wamp.html) fournies dans la
documentation officielle.

1.  Copier le code depuis le document root de Wamp / Xampp (www / htdocs).

2.  Sauvegarder (dump) des bases de données.

3.  Arrêter de Wamp / Xampp

4.  Démarrer Laragon

5.  Restaurer les bases de données.

## Gestion des données avec Laragon

La visualisation par défaut se fait via le **client heidiSQL**.

-   Cliquez sur le bouton « Base de données ».

Utiliser d’autres clients SQL

1.  Clic droit sur l’application Laragon (menu contextuel)

2.  Navigation : MySQL \> phpMyAdmin (par exemple).
