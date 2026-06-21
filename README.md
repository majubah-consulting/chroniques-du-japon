Chroniques du Japon
Description
Chroniques du Japon est un site éducatif qui propose une traversée visuelle de la civilisation japonaise, des mythes fondateurs jusqu'au Japon contemporain. Sa vocation est de rendre accessible l'histoire et la culture du Japon à travers des récits, des images et des ressources interactives.
Le site est organisé autour de plusieurs grands axes :
Chronologie interactive : un panorama de 17 époques de l'histoire japonaise (des kami au Japon moderne), avec pour chaque période une introduction, des dates clés et un emblème cliquable vers une fiche détaillée.
Thèmes transversaux : des rubriques dédiées aux samouraïs, au katana, à la culture, à l'héritage et à la figure de Miyamoto Musashi.
Ressources : une page dédiée aux « voies japonaises » (道 dō) explorant six disciplines traditionnelles : le kendo, la forge du katana, le jardin japonais, la calligraphie, l'architecture et Musashi / Vagabond.
Le design s'inspire de l'esthétique japonaise (papier washi, couleurs nocturnes et rouges, typographies Garamond et Shippori Mincho). Toutes les images sont accompagnées de textes alternatifs et le site est navigable au clavier grâce à des liens "skip to content".
Structure du projet
La racine du dépôt contient :
index.html : la page d’accueil présentant la chronologie interactive et les principales rubriques.
ressources.html : la page des ressources détaillant les six voies japonaises.
support.js et image-slot.js : scripts JavaScript pour la navigation et l’affichage dynamique.
galerie/ : répertoire contenant les images des cartes et des ressources (kendo.png, forgeron.png, etc.).
estampes/ : répertoire d’images et de vidéos pour la page d’accueil et les estampes.
README.md : le fichier que vous lisez.
Installation et utilisation locale
Le site est entièrement statique (HTML, CSS, JS). Pour le visualiser localement :
Clonez ce dépôt sur votre machine :
git clone https://github.com/votre-compte/chroniques-du-japon.git
Ouvrez le fichier index.html dans votre navigateur préféré. Tout doit fonctionner hors connexion.
Si vous modifiez le code, rechargez simplement la page pour voir vos changements. Aucun serveur n’est nécessaire.
Déploiement sur GitHub Pages
Pour publier le site en ligne avec GitHub Pages :
Assurez-vous que la page d’accueil s’appelle index.html. GitHub Pages sert automatiquement ce fichier à la racine du dépôt.
Dans les paramètres du dépôt, activez GitHub Pages (Settings → Pages) en choisissant la branche main et le dossier /root ou / comme source.
Après validation, le site sera disponible à l’adresse https://<votre-compte>.github.io/<nom-du-repo>/.
(Optionnel) Achetez un nom de domaine et configurez un enregistrement CNAME pour le faire pointer vers votre site.
Contribuer
Les contributions sont les bienvenues ! Vous pouvez :
Corriger des fautes ou des coquilles.
Améliorer l’accessibilité et la navigation.
Proposer de nouvelles fiches historiques ou culturelles.
Optimiser les images (compression WebP).
Pour contribuer, effectuez un fork du dépôt, créez une branche, apportez vos modifications puis ouvrez une Pull Request.
Crédits
Contenu et rédaction : [Votre nom ou équipe]
Images et illustrations : sources libres de droits ou mentionnées dans les pages.
Police Shippori Mincho par Google Fonts.
Police EB Garamond par Google Fonts.
Icônes et éléments graphiques inspirés de la tradition japonaise.
Licence
Précisez ici la licence de votre projet (MIT, Creative Commons, etc.). À défaut, indiquez que le contenu est mis à disposition « tous droits réservés ».
