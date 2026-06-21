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
support.js et image-slot.js : le premier charge le moteur de rendu (runtime React) de la page d’accueil interactive ; image-slot.js gère les emplacements d’images à déposer.
galerie/ : répertoire contenant les images des cartes et des ressources (kendo.png, forgeron.png, etc.).
estampes/ : répertoire d’images et de vidéos pour la page d’accueil et les estampes.
README.md : le fichier que vous lisez.
Installation et utilisation locale
Le site est entièrement statique (HTML, CSS, JS). Pour le visualiser localement :
Clonez ce dépôt sur votre machine :
git clone https://github.com/votre-compte/chroniques-du-japon.git
Servez le dossier via un petit serveur HTTP local (par exemple `python3 -m http.server`), puis ouvrez http://localhost:8000/. Un serveur est recommandé : la page d’accueil charge des ressources via fetch(), ce qui est bloqué lors d’une ouverture directe en file://.
Note : la page d’accueil (index.html) nécessite une connexion Internet, car elle charge React et les polices Google Fonts depuis un CDN. La page ressources.html, elle, s’affiche sans connexion.
Si vous modifiez le code, rechargez simplement la page pour voir vos changements.
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
Contenu et rédaction : Chroniques du Japon (à personnaliser avec votre nom ou celui de votre équipe).
Images et illustrations : sources libres de droits ou mentionnées dans les pages.
Police Shippori Mincho par Google Fonts.
Police EB Garamond par Google Fonts.
Icônes et éléments graphiques inspirés de la tradition japonaise.
Licence
Contenu et textes : © Chroniques du Japon — tous droits réservés. Remplacez par une licence formelle (MIT, Creative Commons, etc.) si vous souhaitez autoriser explicitement la réutilisation.
