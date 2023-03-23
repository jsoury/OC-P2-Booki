# Projet2 transformez une maquette En site web

## Objectif

intégration des maquettes de design en HTML / CSS, qui serviront de base de code pour le reste du développement.

## Spécifications fonctionnelles

- Les usagers pourront rechercher des hébergements dans la ville de leur choix. Le champ de recherche est un champ de saisie, le texte doit donc pouvoir être édité par l’utilisateur. Il faut englober ce champ dans un formulaire pour que ce dernier soit valide auprès du W3C. La partie recherche ne doit pas être fonctionnelle.
- Chaque carte d’hébergement ou d’activité devra être cliquable dans son intégralité (pas uniquement le titre). Pour l’instant, les liens sont vides. On peut utiliser un attribut pour simuler la présence d’un lien.

```
<a href="#">mon lien</a>
```

- Les filtres doivent changer d’apparence au survol. Je te laisse décider de l’effet approprié, je n’ai pas encore eu le temps de me pencher dessus. Par contre, ils ne doivent pas être fonctionnels.
- Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont des liens. Ils doivent mener respectivement vers la section “Hébergements à Marseille” et “Activités à Marseille”.

## Spécifications techniques

- Deux maquettes ont été réalisées : l’une desktop et l’autre mobile. Le site devra être également adapté aux formats tablette. Pour les tablettes, nous sommes libres de faire les adaptations nécessaires. Il est important qu’aucun élément ne soit coupé, et que le texte ait une taille suffisante.
- Concernant les breakpoints, nous avons convenu avec le designer UI d’utiliser 992 px et 768 px. 992 px pour les écrans d’ordinateurs et 768 px pour les tablettes, et tout ce qui est en dessous de 768 pour les téléphones portables.
- Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement dit, en desktop first), puis les tablettes et enfin les téléphones. L’utilisation des Media Queries nous permettra de réaliser l’intégration pour les différents supports.
- Plusieurs formats et tailles d’images ont été exportés. Il faudra choisir le format le plus adapté par rapport à la résolution et au temps de chargement
- Les icônes proviennent de la bibliothèque Font Awesome. Nous pouvons passer par un CDN pour faciliter le chargement des icônes.
- Les couleurs de la charte sont le bleu (#0065FC), une version plus claire de ce bleu (#DEEBFF) et le gris pour le fond (#F2F2F2).
- La police du site est Raleway. Nous pouvons passer par Google Font pour importer facilement cette police dans le code : [font google](https://fonts.google.com/specimen/Raleway).
- Il est important d’utiliser les pixels et les pourcentages plutôt que les REM et les EM.
- Il est important d’utiliser Flexbox plutôt que Grid car c’est la techno que l’équipe maîtrise le mieux.
- Aucun framework CSS (type BootStrap ou Tailwind CSS) ou préprocesseur CSS (type Sass ou Less) ne doit être utilisé.
- Il est important d’utiliser des balises sémantiques (type `main`,`header`, `nav`, etc.).
- Le code doit être valide aux validateurs [W3C HTML](https://validator.w3.org/) et [CSS](https://jigsaw.w3.org/css-validator/).
- La maquette doit être compatible avec les dernières versions de Google Chrome et de Mozilla Firefox. Il faudra tester le prototype sur ces deux navigateurs.
- Il n’est pas nécessaire de versionner le code.

# OC-P2-transformez une maquette En site web (Booki)

[![](https://img.shields.io/w3c-validation/default?targetUrl=https%3A%2F%2Fjsoury.github.io%2FOC-P2-Booki%2F)](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjsoury.github.io%2FOC-P2-Booki%2F)

Intégration des maquettes de design en HTML / CSS, qui serviront de base de code pour le reste du développement.

- voir le [projet](https://jsoury.github.io/OC-P7-lesPetitsPlats/).

## 1. Contexte

Vous avez trouvé votre premier stage en tant que développeur web chez Booki, , une petite entreprise proposant un outil de planification de vacances !

## 2. Objectifs

Vous devez réaliser l’intégration des [maquettes](<https://www.figma.com/file/r9YJyUkpVdrxzBBKGH7reY/Maquettes-Booki-(desktop%2C-mobile%2C-tablette)>) de design en HTML / CSS, qui serviront de base de code pour le reste du développement.

## 3. Spécifications

- HTML, CSS

## 4. Démarrage

[Code source](https://github.com/jsoury/OC-P2-Booki)

### 4.1. IDE

- [Visual Studio code](https://code.visualstudio.com/)

### 4.2. Prérequis

- [Liver server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

### 4.3 Utilisation

- Clonez ce dépôt sur votre ordinateur:

```bash
git clone https://github.com/jsoury/OC-P2-Booki.git
```

- Exécuter index.html

## 5. Auteur

- [![](https://img.shields.io/badge/Portfolio-Jonathan%20SOURY-orange)](https://js-portfolio-hgzextusx-jsoury.vercel.app/)
- [![](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/jonathan-soury/)

<img src="https://github-readme-stats.vercel.app/api?username=jsoury&show_icons=true"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs?username=jsoury&layout=compact"/>

## 6. License

License MIT

Copyright (c) [2022] [Jonathan SOURY]

Permission est accordée, sans frais, à toute personne obtenant une copie
de ce logiciel et des fichiers de documentation associés (le "Logiciel"), pour traiter
dans le Logiciel sans restriction, y compris, sans s'y limiter, les droits
utiliser, copier, modifier, fusionner, publier, distribuer, sous-licencier et/ou vendre
copies du Logiciel, et de permettre aux personnes à qui le Logiciel est
fourni pour ce faire, sous réserve des conditions suivantes :

L'avis de droit d'auteur ci-dessus et cet avis d'autorisation doivent être inclus dans tous
des copies ou des parties substantielles du Logiciel.

LE LOGICIEL EST FOURNI "TEL QUEL", SANS GARANTIE D'AUCUNE SORTE, EXPRESSE OU
IMPLICITES, Y COMPRIS, MAIS SANS S'Y LIMITER, LES GARANTIES DE QUALITÉ MARCHANDE,
ADÉQUATION À UN USAGE PARTICULIER ET ABSENCE DE CONTREFAÇON. EN AUCUN CAS LE
LES AUTEURS OU LES DÉTENTEURS DU COPYRIGHT SERONT RESPONSABLES DE TOUTE RÉCLAMATION, DOMMAGE OU AUTRE
RESPONSABILITÉ, QUE CE SOIT DANS UNE ACTION CONTRACTUELLE, DÉLICTUELLE OU AUTRE, RÉSULTANT DE,
EN DEHORS OU EN RELATION AVEC LE LOGICIEL OU L'UTILISATION OU D'AUTRES TRANSACTIONS DANS LE
LOGICIEL.
