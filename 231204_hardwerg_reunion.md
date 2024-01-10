
# 231204 - hardwerg / ergloss

**Pour le moment le site de l'erg est une piste pour accueillir le projet de documentation**

   * Problèmes
       * Confusion avec le contenu existant / administratif
       * Faire une plus grand place au "texte" / limitier l'espace de la carte
       * Repenser le menu, trop dense / peu hiérarchisé - visibiler le Service Social / Les organes
Il y a le site de la Bàg qui est extérieur (non référencé sur le site) qui peut très facilement être repris en main par les générations suivantes.



## **WINTERSCHOOL ATELIER**

   * Documentation des espaces numériques de l'erg
       * Interroger Stéphane Noël - les blog / site gravitent autour de l'erg
           * Liste des espaces établie par Maxime et Stéphane [https://pads.erg.be/p/r.9fee040521e1e6e2bc0fcfdbf958f4a4](https://pads.erg.be/p/r.9fee040521e1e6e2bc0fcfdbf958f4a4)
       * Interroger Sammy sur son utilisation du wiki
       * Laurence sur l'historique du Wiki de l'erg
       * Faire une cartographie des espaces d'information / pour les étudiant·es, prof etc.
       * Documenter les initiatives étudiant·es / les interpaces "transdisciplinaires : la Bobine etc... Documenter l'histoire de ces espaces


## Projet à mener dans ce wiki:

   * Site hardware proposition d'achat ordinateur portable
       * Lister les magasins / espaces d'achat dans Bruxelles
       * Faire des liens avec le Service social pour l'aide à l'achat
           * Ne pas acheter d'office du neuf
       * Faire un arbre a choix d'ordinateur
       * Bien documenter les sources et les maintenir (les archiver via ex : Archive Box / WebArchive)
       * Vous pouvez contacter CF2D aussi, Marc Wathieu avait commencé un partenariat dénommé SAS: [http://www.erg.be/Le\_SAS/](http://www.erg.be/Le\_SAS/) + [http://www.erg.be/Le\_SAS/Convention\_CF2D\_ERG.pdf](http://www.erg.be/Le\_SAS/Convention\_CF2D\_ERG.pdf)
       * J'avais écrit (Stéphanie) à l'époque ce petit guide pour acheter un Thinkpad d'occasion: [http://pads.ustensile.be/r/ordinateur.md](http://pads.ustensile.be/r/ordinateur.md) Mais il sera bientôt obsolète car Lenovo a changé leur nomenclature


## TODO:

#### Theophile: 

   * Retrouver les brouillons de la page hardware (oups) DONE
   * Partager avec Joan (via wiki ou autre) DONE
   * faire une affiche pour le workshop
   * LA COM
   * réfléxion modalité 
       * espace d'encodage pour des gens qui passent, un ordi ouvert accessible
        

   * Joan : 
   * ~~Commencer a rediger le projet d'atelier de la Winterschool~~


   * CE : 
   * Créer un «Linktree» > alternative open source : [https://linkstack.org/](https://linkstack.org/)
   * Après la mise en place proposer au Service Social ?
   * 

   * 

### 231208

#### Personnes impliqué·es / qui utilisent le Wiki :

   * Sammy
       * Actualité / communication


Frédéric Dupont

   * Transférer la documentation de la permance vidéo. 
       * Programme pour convertir les pdf en Markdown:
           * [https://github.com/VikParuchuri/marker](https://github.com/VikParuchuri/marker) basé sur [https://huggingface.co/facebook/nougat-base](https://huggingface.co/facebook/nougat-base) (llm)


Stéphanie Vilayphiou

   * A participé à la construction du site mais n'a pas la main sur tout le code (pour changer des aspects structurels) > Michael Murtaugh de constantzw qui a participé la construction du site / Laurence va le contacter ou faire appel à Nicolas pour nous aider. / Alexia de Visscher a aussi participé activement à la conception du wiki


Wendy L.

   * A nourri le wiki, mis à jour des pages, en a créer...


MediaWiki Formating :

    

    [https://www.mediawiki.org/wiki/Help:Formatting](https://www.mediawiki.org/wiki/Help:Formatting)

    [https://www.mediawiki.org/wiki/Extension:WikiMarkdown](https://www.mediawiki.org/wiki/Extension:WikiMarkdown)



## Comprendre le wiki.erg

[https://wiki.erg.be/w/Sp%C3%A9cial:Pages\_sp%C3%A9ciales](https://wiki.erg.be/w/Sp%C3%A9cial:Pages\_sp%C3%A9ciales) > Formulaires sémantiques



### Créer une page

Recherche l'article → si il n'existe pas → on peut le créer ! 



#### Modifier une page wiki

   * Deux options :
       * Modifier
       * Modifier avec le formulaire
           * Certaines pages peuvent être composées à partir de formulaire, type : Catégorie:Sites satellites
               * Les formulaires peuvent être modifiés, on peut ajouter des champs etc.




### Transformer / Extraire du Markdown d'une page web

Extension Firefox : **Markdownload**

La conversion n'est pas toujours parfaite.



### Faire des copies des sources externe avec web.archive.org

Pour sauvegarder des sources externes auquelles le site fait référence

Extension:

[https://addons.mozilla.org/en-US/firefox/addon/wayback-machine\_new/](https://addons.mozilla.org/en-US/firefox/addon/wayback-machine\_new/)

[https://chromewebstore.google.com/detail/wayback-machine/fpnmgdkabkmnadcjpehmlllkndpkmiak?hl=en-US](https://chromewebstore.google.com/detail/wayback-machine/fpnmgdkabkmnadcjpehmlllkndpkmiak?hl=en-US)



### Convertir du MARKDOWN > MEDIAWIKI format avec Pandoc

pandoc --from=MARKDOWN --to=MEDIAWIKI fichier.md --output=mediawiki.txt



### MARKDOWN



**gras**

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

=== MEDIAWIKI ===



'''gras'''



#### Exemple de wiki modifié: 

    [https://wiki.archlinux.org/](https://wiki.archlinux.org/)

    [https://designnumerique.be/wiki/DESIGN\_NUMERIQUE](https://designnumerique.be/wiki/DESIGN\_NUMERIQUE)

    [https://monoskop.org/Monoskop](https://monoskop.org/Monoskop)

    → demander à Alexia de Visscher de Design numérique, elle en a sûrement une énorme liste

    

### Changer affichage du Wiki

   * En étant connecté·e
       * Préferences > apparence > vector > enregistrer
       * Prend l'apparence d'un wiki "classique"


### Modules complémentaires à installer

#### Display Title

Permet de modifier le nom affiché d'une page sans en modifier l'url

[https://www.mediawiki.org/wiki/Extension:Display\_Title/fr](https://www.mediawiki.org/wiki/Extension:Display\_Title/fr)

(Proposition pour faire coexister des titres insitutionnels / et informels, d'usage)





## Observations sur l'ergonomie du site: 

   * Corps de texte trop large, à mettre en sans-serif (?) → pourquoi pas, par contre on essaie de n'utiliser que des typos d'étudiant·e·s actuel·le·s ou ancien·ne·s de l'erg parce que c'est chouette quand même :)
   * Couleur pas forcément harmonieuse → c'est subjectif ;) mais pas de souci pour changer, il y aura toujours quelqu'un pour dire que ce n'est pas harmonieux... ;)
   * Sommaire à améliorer et avec des sous-sections
       * Le réglage de la "profondeur" de la TOC (Table des matières / Table of content) se fait dans le CSS [https://www.mediawiki.org/wiki/Manual:Table\_of\_contents/fr#Ajout\_de\_la\_table\_des\_mati%C3%A8res](https://www.mediawiki.org/wiki/Manual:Table\_of\_contents/fr#Ajout\_de\_la\_table\_des\_mati%C3%A8res)
   * Les cadres d'images pas en violet et/ou pas aussi large
   * Rendre plus simple d'avoir que le wiki et ne pas avoir le panneau de gauche par défault
   * Travailler le *reponsive* et rendre plus accessible le travailler sur petit écrans, notamment mobile, rendre 
   * css -> accessibilité et inclusivité
       * [https://simplecss.org/demo](https://simplecss.org/demo)
       * [https://design-accessible.fr/](https://design-accessible.fr/)
   * Pouvoir masquer la carte → on peut changer la taille des cadres avec la souris, mais on pourrait penser à un bouton pour que ce soit plus clair
   * Optimiser l'éditeur de page (pour les petits écrans).
   * Ajouter l'extension VisualEditor pour faciliter l'édition des articles 


### Préalables au Workshop

(Voir au dessus)

    

## Objectifs de Workshop de la Winterschool

   * Rendre plus accessible l'accès à certaines pages
       * Service Social
       * Espaces transdisciplinaires
           * L'espace de documentation générale (guides/tutoriel etc.)
       * Inscription
           * Les enseignant·es (actuelles et anciennes)


   * Trouver des moyens de transmettre la culture de la documentation.
       * Prendre contact avec les personnes de ergote, ergtv, RideauDePerle etc pour documenter un peu leur histoire
           * Des gens pour faire des permanences (ce que Ergloss aurait pu être)
           * Des tutorats (personnes de contact)
       * Si on ne parvient a "instaurer une culture" esssayer d'annualiser ces moments de documentation, Winter school, workshop (ou avoir un jobiste sur une période)


   * Les processus de documentation
       * Comment documenter ? Faire un petit guide, quelques points à aborder...
       * Quelles sont les autres pratiques de documentation à l'erg, parfois non numérique ?
       * Avoir une version imprimable du wiki ? cf. [https://www.mediawiki.org/wiki/PDF\_export](https://www.mediawiki.org/wiki/PDF\_export)
           * Kiwix ([https://kiwix.org/en/)](https://kiwix.org/en/)) version (outils de création d'archive web qui permettrait de consuter le wiki sans internet, l'ayant préalablement téléchargé sous format zim [https://youzim.it/](https://youzim.it/)
   * Documenter la documentation même !
       * Les outils pour Scraper
       * Récupérer les vidéos de ergTV sur Youtube et Facebook avec Yt-dl


   * Produire l'historique des espaces "transversaux" et mettre à jour leur indexation


   * Cartographier les espaces numériques
       * Cloud / Mail / InfosErg / Mattermost / Valves / wiki.erg / Teamup (réservation d'espaces) → pour réserver des choses, Nextcloud propose des formulaires de réservation liés à des calendriers, c'est gratuit et déjà installé sur les serveurs de l'erg
       * Les ressources documentaires
           * Les archives vidéo (Vimeo) Peertube
           * Projet d'archivage des Mémoires
           * Pandora (vidéothèque hébergée à l'erg)
       * Les sites liés à des cours
       * Les sites sattelites
           * Notifier ceux qui sont abandonnés
               * [https://clubtravail.tumblr.com/chantmentale](https://clubtravail.tumblr.com/chantmentale)


   * Comment archiver / garder la trace du passages des gens ?
       * Les anciens enseignant·es
       * Les équipes d'étudiant·es


   * Scraper des sources extérieures pour les archiver
       * Flickr de Marc Wathieu [https://www.flickr.com/groups/erg\_brussels/pool/](https://www.flickr.com/groups/erg\_brussels/pool/)




#### Proposition d'organisation des pages des espaces "transversaux"

(Trouver un terme moins administratif pour ces espaces)

   * Description
       * Lien avec autres cours/AP/club
       * Si besoin de nouvelles personnes, un avis pour de nouveaux membres, contact mail
   * Contact / Nous rejoindre
       * A quel moment ? Dans quel espace ?
       * Dans quel espace on se rejoint ?
   * Historique
       * Baliser avec des dates, lancement, arrêt (spécifié dans les catégories "arrêté")
   * Equipe / Membres historiques
       * Leur contacts (rendre accessible les contacts seulement pour les personnes connectées?)
   * Liste des projets ou production finies ou en cours, avec lien vers page wiki si documenté
   * Mettre des légendes sous les images
   * Médias / Photos
   * Liens externes


### Description du Workshop

#### Wikithon erg.wiki

3 journées, de 10h à 16h

Ouvert à toustes


Si l'école fourmille d’initiatives, de pratiques innombrables, la plupart d'entre elles disparaissent et tombent dans l'oubli lorsque les personnes sortent de l'école. Faute de temps, ces gestes, ces outils, ces expériences personnelles et collectives ne sont que peu documentées. La semaine de Winterschool est l'occasion de s'arrêter un peu, et de faire le bilan, calmement, de toutes ces pratiques et de les transmettre, les documenter !

Le wiki.erg sera l'espace de documentation de ces pratiques, ces trois journées seront l'occasion de repenser collectivement le wiki de l'erg : son allure, son accessibilité, son organisation etc.

Elles seront aussi l'occasion d'enrichir les pages wiki des "espaces transversaux" : ergote Radio, le N.E.S, EàT, ergtv, le Club textile, la BàG, le Rideau de Perles etc. Il sera question de documenter l'activité présente de ces espaces, mais aussi leur histoire : inscrire les noms des personnes qui y ont pris part pourrait permettre par exemple de faciliter la transmission entre les générations d'étudiant·es.

Concrètement lors de l'atelier : nous allons à la fois apprendre à se saisir du wiki (créer des pages, les modifier etc.) faire un état des lieux du : "déjà-là", aménager cet espace. Mais aussi enquêter, passer des coups de fil, envoyer des mails, poser entre deux portes des questions, pour savoir : ce qu'il se fait - ce qu'il se faisait et depuis quand ?

Le wiki sera aussi le lieu où publier des guides "comment acheter un ordinateur d'occasion" ou encore partager des modes d'emploi : une installation sonore, vidéo, le plan d'un meuble que l'on a construit etc.

Sur Youtube, Facebook, Flickr ou Instagram sont déposées de précieuses archives, il sera question d'indexer ces espaces mais aussi de siphonner leur contenu : pour les héberger en lieu sûr ! 

Il n'est pas nécessaire d'avoir des connaissances poussées en informatique, on va apprendre ensemble à se saisir de ces outils. Vous pouvez aussi participer aux enquêtes, ou tout simplement passer déposer des documents, renseigner une page, raconter un bout d'histoire.

Si vous avez des connaissances en *scraping* (siphonnage), ou en CSS n'hésitez pas, votre aide peut aussi être précieuse !





### A FAIRE préparation de l'atelier :

   * Guide de syntaxe Wiki a imprimer
   * Faire une communication autour de l'atelier
   * Avoir un pad avec les trucs à faire pour que les personnes ne soient pas perdues et puissent prendre part à l'atelier assez librement / trouvent une porte d'entrée.
   * Préparer un ordi accessible aux personnes de passage pour qu'elle puissent ajouter des infos / naviguer dans le wiki.
   * Guide / Série de questions a se poser pour composer une fiche ?


### Questions pour Stéphanie Vilayphiou :

   * Identifiants SFTP
       * Qui jusque là se chargeait de l'administration du site ? Moi (Stéphanie) mais par défaut car il n'y a jamais vraiment eu de décision claire. Je voudrais justement communiquer aux autres enseignant·e·s et équipe technique (Maxime?) comment maintenir le serveur
   * Histoire du projet, qui était impliqué, à quel moment ça s'est fait
   * Quels étaient les choix au niveau de l'ergonomie ? La philosophie du projet ?
   * Il y a t-il de la documentation sur le CSS du site ? / des conseils ?
   * Qu'est-ce qui a et n'a pas marché pour toi ? 
       * Fédérer des gens pour venir à un workshop (pas de moment dédié)
       * Pas d'étudiant·es pour accompagner ça


Carte Jacques Bertin 

VPS : Serveur dédié

Au début pas de VPS - hébergé sur un RaspB dans la salle d'art numérique

All to all > hébergeur Web à Bruxelles

[https://wiki.erg.be/w/MediaWiki:Foreground.css](https://wiki.erg.be/w/MediaWiki:Foreground.css)



[https://www.art.yale.edu/](https://www.art.yale.edu/)



espace à travailler



menu

carte

accessibilité et design graphique du site

pratique 





### Demande prêt matos



Ecran PC x1

Câble HDMI 1m x1

Multiprise (8) x2

PC Portable x2 (c'est pour aller sur Wiki)

Souris x2

Rallonge 5m x2

Cable RJ45 10m x1



## Réunion Stephanie



    /var/www/

/var/www/html # pour la redirection vers `m` 

    /var/www/wiki.erg.be/public\_html/ # le wiki 

    /var/www/wiki.erg.be/public\_html/m # la carte en D3.js 

    /var/www/wiki.erg.be/public\_html/mw # mediawiki  



    m/dist/ # le js de la carte, a été modifié à la main dans le passé par Stephanie

    mw/extension # pour les extension

    mw/skins/foreground # thème de base modifié par l'équipe

    mw/skins/foreground/assets/fonts # pour les typo



Faire un tar du site avant de travailler dessus. mettre à jours le mediawiki         

   * dump la db et tar         
   * tar les configs
   * aller voir sur mediawiki les procédures de backup et restore
   * Créer un git sur le serveur git de l'école


[https://visionscarto.net/la-semiologie-graphique-a-50-ans](https://visionscarto.net/la-semiologie-graphique-a-50-ans)

[https://hypergeo.eu/jacques-bertin/](https://hypergeo.eu/jacques-bertin/)



### Exemple de wiki académique ou scolaire customizer

[https://www.art.yale.edu/](https://www.art.yale.edu/)



### Pages de wiki à mettre à jours

   * [https://en.wikipedia.org/w/index.php?search=%C3%89cole+de+Recherche+Graphique+-+%C3%89cole+Sup%C3%A9rieure+des+Arts\&title=Special%3ASearch\&fulltext=1\&ns0=1](https://en.wikipedia.org/w/index.php?search=%C3%89cole+de+Recherche+Graphique+-+%C3%89cole+Sup%C3%A9rieure+des+Arts\&title=Special%3ASearch\&fulltext=1\&ns0=1)
   * [https://en.wikipedia.org/wiki/List\_of\_universities\_in\_Belgium](https://en.wikipedia.org/wiki/List\_of\_universities\_in\_Belgium)
   * [https://en.wikipedia.org/wiki/Institut\_Saint-Luc](https://en.wikipedia.org/wiki/Institut\_Saint-Luc)
   * [https://wiki.erg.be/w/Erg\_%C3%A0\_distance](https://wiki.erg.be/w/Erg\_%C3%A0\_distance)


### LE CSS

[https://wiki.erg.be/w/MediaWiki:Foreground.css](https://wiki.erg.be/w/MediaWiki:Foreground.css)



Dossier

M : map

mw : wiki



guillaume.frederic0@gmail.com

Proposer a Alexia

Destruction du serveur par le feu (serveur OVH brule à Strasbourg en 2021 et pas de sauvegarde chez Domainepublic)  - dernière sauvegarde après 2019 



Faire une liste des missions (dynamique)

Faire un récap en fin de journée



Sonder ce qui doitêtre mis à jour dans le Wiki :

Lancer des pages au hasard pour voir ce qu'il faut compléter

Page orphelines (aucun lien de dirigent vers elles)



Faire une page sur la workshop

Centraliser les informations

Ce qu'il y a a faire

Le programme

Renforcer page Wikipédia de l'Erg

Comment signifier l'archive ?



Annualiser une ménage de printemps

Charte d'utilisation / Bonne pratique

Guide utilisation du site

Guide rédaction d'une page



Lister les extension a ajouter

Sommaire (profondeur / apparition / dissimulation)

Backup [https://www.mediawiki.org/wiki/Manual:Backing\_up\_a\_wiki](https://www.mediawiki.org/wiki/Manual:Backing\_up\_a\_wiki)





A FAIRE



CheatSheet MediaWiki (syntaxe) erg.Wiki 

Faire une page du Workshop

Vendredi : Texte + Affiche à envoyer à Sammy

Mail à Wendy pour organisation

Lister des gens a contacter pour collecter

Recettes d'erg à tabe -> plugin de recettes




