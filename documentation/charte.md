---
title: AP1 - Portfolio - Charte graphique
author: Mathieu Castagné
creator: Typora.inc
subject: charte
header:
footer: ${title} - ${author} - Page ${pageNo} / ${totalPages}
---

# AP1 - Portfolio - Charte graphique

**Date de création :** 24/11/2026 - M. Castagné

**Date de modification :** 27/11/2026 - M. Castagné

**Version :** 1.1

**Sommaire :**

> [TOC]

<div style="page-break-after:always"></div>

## 1. Contexte du projet

Ce document présente la charte graphique de mon portfolio, réalisé dans le cadre de l’atelier de professionnalisation 1 du BTS Services informatiques aux organisations (SIO), option Solutions d’infrastructure, systèmes et réseaux (SISR). Le site présente mon profil d’étudiant en alternance, mon parcours, mes projets et ma veille technologique, à de futurs employeurs comme au jury du BTS. La charte s’adresse au prestataire qui réalisera le site en HTML et CSS. Elle lui donne les couleurs, les polices, le logo et les composants, les maquettes de chaque page sur ordinateur et sur mobile, et la logique de navigation.

## 2. Explication de l’identité visuelle

Le portfolio mélange deux styles des années 70. La mise en page est brutaliste, comme les bâtiments administratifs en béton de cette époque : angles droits, bordures épaisses, ombres pleines décalées, et une police à chasse fixe pour les étiquettes et les boutons, comme sur les anciens terminaux. Les couleurs et les titres viennent de la pop des mêmes années : couleurs franches en aplats, titres dans une police « groovy », arc-en-ciel en cadres emboîtés et cercles concentriques. J’ai aussi repris des éléments de l’administration de la série Loki : des fiches de dossier et des tampons pour les projets, un écran cathodique pour la veille technologique et des arches.

J’ai fait ce choix pour deux raisons. Je voulais un site qu’on reconnaisse tout de suite, avec une mise en page stricte mais des couleurs chaleureuses. Et cet univers de bureau, où tout est classé et documenté, ressemble à mon travail : au support informatique, je traite des tickets, je rédige des procédures et je documente mes interventions. Les couleurs chaudes rappellent aussi mes débuts dans l’accueil et la relation client.

Le logo représente Djed, un tigre-cerf, personnage que j’ai créé. C’est une silhouette blanche dans un carré anthracite, où seuls l’œil sable et la truffe apparaissent. Cette forme simple, en aplats comme dans les dessins animés des années 70, reste lisible même en petit et va avec les angles droits du site. Le logo est animé sur la page d’accueil, au centre d’un arc-en-ciel carré, et il est repris dans l’en-tête de toutes les pages.

La décoration se limite aux titres, aux séparations et aux illustrations : les textes à lire restent sur un fond uni, sans effet.

## 3. Éléments de déclinaison de l’identité visuelle

### 3.1. Couleurs

La palette compte quatre couleurs, toujours utilisées en aplats, sans dégradé ni transparence.

| Couleur | Hexadécimal | RVB | Rôle | Exemples d’usage |
| --- | --- | --- | --- | --- |
| Sable | `#F9D493` | 249, 212, 147 | Fond principal | Fond des pages, grands titres sur bleu, boutons principaux |
| Anthracite | `#3C3A4A` | 60, 58, 74 | Texte, contours et ombres | Texte courant, en-tête, pied de page, bordures, ombres décalées, introduction de la page Veille |
| Bleu | `#5079B9` | 80, 121, 185 | Accent | Accueil, barres sous les titres, tampons de statut, cadre de l’écran de la page Veille |
| Blanc | `#FFFFFF` | 255, 255, 255 | Fond secondaire | Cartes, section Projets, bandes de rayures |

Les sections alternent leurs fonds (sable, bleu, blanc, anthracite) pour marquer le passage d’une partie à l’autre sans séparateur supplémentaire.

**Contrastes**

Les associations de couleurs respectent le niveau AA des règles d’accessibilité WCAG 2.1 : un contraste d’au moins 4,5:1 pour le texte courant et de 3:1 pour le grand texte (24 px, ou 19 px en gras).

| Texte / fond | Contraste | Usage autorisé |
| --- | --- | --- |
| Anthracite sur blanc, ou blanc sur anthracite | 11,1:1 | Tout texte |
| Anthracite sur sable, ou sable sur anthracite | 7,8:1 | Tout texte |
| Blanc sur bleu, ou bleu sur blanc | 4,4:1 | Grand texte uniquement |
| Sable sur bleu, ou bleu sur sable | 3,1:1 | Grand texte uniquement |
| Anthracite sur bleu | 2,5:1 | À éviter pour du texte |
| Sable sur blanc | 1,4:1 | Décoration uniquement |

### 3.2. Typographie

Le site utilise trois polices :

- **Shrikhand**, une police « groovy » typique des années 70, uniquement pour les titres ;
- **Space Mono** (Bold), une police à chasse fixe, pour la navigation, les boutons, les étiquettes, les dates et les tampons, toujours en majuscules ;
- **DM Sans**, très lisible à l’écran, pour tous les textes à lire.

| Élément | Police | Ordinateur | Mobile | Particularités |
| --- | --- | --- | --- | --- |
| Nom sur la page d’accueil | Shrikhand | 104 px | 56 px | Sable sur bleu, ombre en escalier anthracite (3, 6 et 9 px), interligne 100 % |
| Titres de page | Shrikhand | 60 px | 40 px | Suivis d’une barre de 120 × 10 px, interligne 112 % |
| Titres de carte | Shrikhand | 28 px | 24 px | Interligne 115 % |
| Nom dans l’en-tête | Shrikhand | 26 px | 20 px | Sable sur anthracite |
| Navigation | Space Mono Bold | 14 px | 12 px | Majuscules, espacement des lettres 4 % |
| Boutons | Space Mono Bold | 15 px | 14 px | Majuscules, espacement des lettres 4 % |
| Étiquettes et dates | Space Mono Bold | 12 à 16 px | 12 à 14 px | Majuscules, espacement des lettres 4 % |
| Tampons de statut | Space Mono Bold | 19 px | 19 px | Bleu sur sable : 19 px minimum pour le contraste |
| Présentation de l’accueil | DM Sans Bold | 22 px | 19 px | Blanc sur bleu : le gras est obligatoire pour le contraste |
| Sous-titres de carte | DM Sans Bold | 23 à 24 px | 20 à 21 px | Interligne 125 % |
| Texte d’introduction | DM Sans Regular | 20 px | 17 px | Interligne 165 % |
| Texte courant | DM Sans Regular | 17 à 18 px | 16 px | Interligne 160 à 165 % |
| Liens dans le texte | DM Sans Bold | 16 à 17 px | 16 px | Soulignés |

Entre le format mobile et le format ordinateur, les tailles évoluent progressivement avec la largeur de l’écran.

**Intégration**

Les trois polices proviennent de Google Fonts et sont distribuées sous licence libre SIL Open Font License 1.1, qui autorise leur utilisation sur un site. Elles sont hébergées directement avec le site, au format WOFF2, dans le dossier `html/assets/fonts`, plutôt que chargées depuis les serveurs de Google, pour que l’adresse IP des visiteurs ne soit pas transmise à Google.

Leur chargement suit les guidelines CSS de Kiwipedia :

- les polices sont au format WOFF2, limitées aux caractères latins ;
- le site ne charge que trois fichiers de police : Shrikhand Regular, Space Mono Bold, et DM Sans en version variable, qui réunit le Regular et le Bold dans un seul fichier ;
- elles sont déclarées avec `font-display: swap`, pour que le texte s’affiche tout de suite avec la police de secours ;
- les tailles du tableau sont en pixels pour faciliter la lecture des maquettes, mais elles sont écrites en `rem` dans le CSS (1 rem = 16 px), pour que le visiteur puisse agrandir le texte.

Kiwipedia conseille de se limiter à deux familles de polices. J’en garde trois, parce que la police à chasse fixe fait partie de l’identité brutaliste du site. Pour limiter le poids des pages, chaque famille ne tient que dans un fichier.

Polices de secours, si une police ne se charge pas :

- titres : `'Shrikhand', Georgia, serif` ;
- interface : `'Space Mono', 'Courier New', monospace` ;
- texte : `'DM Sans', system-ui, sans-serif`.

### 3.3. Logo, icônes et boutons

#### Logo

Le logo représente Djed, un tigre-cerf vu de profil, tourné vers la droite. Sa silhouette blanche est recadrée dans un carré anthracite à angles droits : les bois sortent par le haut, et les bords droit et bas du carré coupent la tête. Seuls l’œil sable et la truffe anthracite ressortent sur la silhouette. Comme il n’a ni contours ni petits détails, il reste lisible de 16 px à plusieurs centaines de pixels. Un seul logo suffit donc pour tous les usages.

![Déclinaisons du logo : logo, en-tête, favicon et avatar](medias/logo_declinaisons.png)

| Version | Fichier | Usage | Taille |
| --- | --- | --- | --- |
| Logo | `djed-logo.svg` | Page d’accueil (version animée), en-tête, carte du projet Portfolio | 16 px minimum |
| En-tête | Logo dans un cadre sable de 3 px | En-tête de toutes les pages | 64 px sur ordinateur, 48 px sur mobile |
| Favicon | `favicon.svg`, `favicon.ico`, `apple-touch-icon.png` | Onglet du navigateur, raccourci sur mobile | 16, 32 et 180 px |
| Avatar | `djed-avatar-512.png` | Photo de profil GitHub, logo centré sur un fond sable | 512 px |

Règles d’utilisation :

- le logo garde toujours son carré anthracite : la silhouette blanche n’est jamais posée seule sur un fond clair, où elle disparaîtrait ;
- sur un fond anthracite, comme l’en-tête, il est entouré d’un cadre sable de 3 px pour se détacher du fond ;
- un espace libre d’au moins 10 % de sa largeur est laissé autour du logo ;
- le logo n’est jamais déformé, recoloré, retourné (Djed regarde toujours vers la droite), arrondi, ni orné d’une ombre ou d’un dégradé ;
- sur les sites qui affichent les photos de profil en rond, on utilise l’avatar : le logo y est centré sur un fond sable, pour que les bois ne soient pas coupés ;
- dans l’en-tête, son texte alternatif est « Logo de Mathieu Castagné, retour à l’accueil ».

Sur la page d’accueil, le logo est animé, au centre d’un arc-en-ciel carré : quatre cadres emboîtés, anthracite, sable, blanc et bleu, qui reprennent les angles droits du logo. Le fichier SVG est intégré directement dans le code HTML, et non appelé par une balise `img`, pour que la feuille de style puisse cibler ses calques : `bois-avant`, `silhouette`, `paupiere`, `pupille`, `truffe`. L’animation reste discrète (clignement de la paupière, léger balancement du bois) et se désactive pour les visiteurs qui ont réduit les animations dans leur système (`prefers-reduced-motion`). Comme le SVG est intégré dans le code, il contient un élément `<title>` qui reprend son texte alternatif, comme le demandent les guidelines Accessibilité de Kiwipedia.

#### Icônes

Le site n’utilise que deux icônes, LinkedIn et GitHub, dans le pied de page. Ce sont les icônes officielles de ces deux services, en blanc, de 20 px, au format SVG comme le recommande Kiwipedia, et optimisées avec SVGOMG. Le nom du réseau est écrit à côté de l’icône : l’icône est donc décorative. Elle a un texte alternatif vide, ou l’attribut `aria-hidden="true"` si le SVG est intégré dans le code, et c’est le lien qui porte l’intitulé défini dans le document de contenu. Les icônes ne sont jamais ajoutées en CSS avec `::before` ou `::after`.

Si d’autres icônes deviennent nécessaires, elles seront dessinées au trait, de la couleur du texte. Les emojis et les icônes en couleur sont exclus.

#### Boutons et liens

![Boutons et liens : bouton principal, état au survol, bouton secondaire, lien, navigation, étiquette et tampon](medias/boutons_etats.png)

| Élément | Apparence | Au survol |
| --- | --- | --- |
| Bouton principal | Fond sable, texte anthracite en Space Mono Bold 15 px majuscules, bordure anthracite de 4 px, angles droits, ombre pleine décalée de 6 px, marges intérieures de 13 × 26 px | Le bouton « s’enfonce » : il glisse de 2 px vers le bas et la droite, et son ombre passe à 4 px |
| Bouton secondaire | Identique au bouton principal, sur fond blanc | Identique au bouton principal |
| Lien dans le texte | DM Sans Bold, anthracite, souligné | Soulignement plus épais |
| Lien de navigation | Space Mono Bold 14 px, majuscules, blanc sur anthracite | Fond sable et texte anthracite, comme le lien de la page active |
| Sélecteur de langue | FR / EN dans un cadre bordé de sable | La langue active a un fond sable |
| Étiquette | Space Mono Bold 12 à 14 px, majuscules, fond blanc, bordure anthracite de 3 px | Pas d’interaction |
| Tampon de statut | Space Mono Bold 19 px, majuscules, bleu, bordure bleue de 3 px, inclinée de 5° | Pas d’interaction |

Accessibilité :

- quand un élément est sélectionné au clavier, il reçoit un contour de 3 px : bleu sur un fond clair, sable sur un fond anthracite. Ce contour passe par `:focus-visible` et n’est jamais supprimé ;
- sur mobile, les boutons et les liens de navigation mesurent au moins 44 px de haut, pour rester faciles à toucher ;
- les blocs de texte n’ont pas de hauteur fixe, pour que le contenu reste lisible avec un zoom à 200 % ;
- aucune information ne passe uniquement par la couleur : la page active, par exemple, est aussi signalée aux lecteurs d’écran.

#### Images et illustrations

Les images suivent les guidelines HTML et Performances de Kiwipedia :

- le logo et les icônes sont en SVG ;
- la photo et les captures d’écran sont en WebP, à la taille où elles sont affichées ;
- chaque image a ses attributs `width` et `height`, pour que la page ne bouge pas pendant le chargement ;
- les images placées plus bas que le premier écran sont chargées en différé (`loading="lazy"`) ;
- les images qui portent une information ont le texte alternatif du document de contenu, et les images décoratives (rayures, cadres, motifs) ont un texte alternatif vide.

## 4. Maquettage responsive de chaque page

J’ai suivi les étapes de conception des guidelines Webdesign de Kiwipedia (Alsacréations), toutes réalisées dans Figma : d’abord l’arborescence du site (partie 5), puis un wireframe en niveaux de gris pour fixer la structure de chaque page, et enfin une maquette qui applique la charte. Chaque page est présentée en version ordinateur (1440 px de large) et en version mobile (390 px de large). Les pages Projet AP3 et Projet AP4 partagent la même mise en page.

Le fichier de travail est consultable dans Figma : [CCI-SIO26-Portfolio-CastagneMathieu](https://www.figma.com/design/gxz28leTO9DOgBRwYq32k5/CCI-SIO26-Portfolio-CastagneMathieu).

Passage de l’ordinateur au mobile :

- les grilles de cartes passent de deux colonnes à une seule ;
- la barre de navigation passe sur deux lignes ;
- les boutons de la page d’accueil s’empilent et prennent toute la largeur ;
- les titres réduisent selon les tailles indiquées en partie 3.2.

Les versions mobiles les plus longues sont découpées en colonnes, à lire de gauche à droite.

<div style="page-break-after:always"></div>

### 4.1. Accueil

En-tête, zone d’accueil sur fond bleu avec le nom, la présentation et deux boutons, logo animé au centre de l’arc-en-ciel carré, rayures, pied de page.

#### Wireframe

<img src="medias/wireframe_accueil_ordinateur.png" alt="Wireframe de la page Accueil, version ordinateur" style="max-height: 23cm;">

#### Version ordinateur

<img src="medias/maquette_accueil_ordinateur.png" alt="Maquette de la page Accueil, version ordinateur" style="max-height: 23cm;">

#### Version mobile

<img src="medias/maquette_accueil_mobile.png" alt="Maquette de la page Accueil, version mobile" style="max-height: 23cm;">

<div style="page-break-after:always"></div>

### 4.2. Parcours

Titre, photo dans un cadre en arche et introduction, frise chronologique, cartes « Expériences professionnelles » et « Formations », carte « Engagement associatif ».

#### Wireframe

<img src="medias/wireframe_parcours_ordinateur.png" alt="Wireframe de la page Parcours, version ordinateur" style="max-height: 23cm;">

#### Version ordinateur

<img src="medias/maquette_parcours_ordinateur.png" alt="Maquette de la page Parcours, version ordinateur" style="max-height: 23cm;">

#### Version mobile

<img src="medias/maquette_parcours_mobile_colonnes.png" alt="Maquette de la page Parcours, version mobile, découpée en colonnes" style="max-height: 23cm;">

<div style="page-break-after:always"></div>

### 4.3. Projets

Titre, introduction, puis quatre fiches de dossier, chacune avec son image, son tampon de statut, son titre et sa présentation.

#### Wireframe

<img src="medias/wireframe_projets_ordinateur.png" alt="Wireframe de la page Projets, version ordinateur" style="max-height: 23cm;">

#### Version ordinateur

<img src="medias/maquette_projets_ordinateur.png" alt="Maquette de la page Projets, version ordinateur" style="max-height: 23cm;">

#### Version mobile

<img src="medias/maquette_projets_mobile_colonnes.png" alt="Maquette de la page Projets, version mobile, découpée en colonnes" style="max-height: 23cm;">

<div style="page-break-after:always"></div>

### 4.4. Projets AP3 et AP4

Gabarit commun aux deux projets : lien de retour, titre, encart, quatre fiches d’information et bouton de retour vers la page Projets.

#### Wireframe

<img src="medias/wireframe_projet_ap_ordinateur.png" alt="Wireframe des pages Projet AP3 et AP4, version ordinateur" style="max-height: 23cm;">

#### Version ordinateur

<img src="medias/maquette_projet_ap_ordinateur.png" alt="Maquette des pages Projet AP3 et AP4, version ordinateur" style="max-height: 23cm;">

#### Version mobile

<img src="medias/maquette_projet_ap_mobile.png" alt="Maquette des pages Projet AP3 et AP4, version mobile" style="max-height: 23cm;">

<div style="page-break-after:always"></div>

### 4.5. Veille technologique

Introduction sur fond anthracite avec la problématique et le motif de cible, cartes « Pourquoi ce sujet » et « Méthode de veille », synthèse affichée dans un écran, capture du canal Telegram.

#### Wireframe

<img src="medias/wireframe_veille_ordinateur.png" alt="Wireframe de la page Veille technologique, version ordinateur" style="max-height: 23cm;">

#### Version ordinateur

<img src="medias/maquette_veille_ordinateur.png" alt="Maquette de la page Veille technologique, version ordinateur" style="max-height: 23cm;">

#### Version mobile

<img src="medias/maquette_veille_mobile_colonnes.png" alt="Maquette de la page Veille technologique, version mobile, découpée en colonnes" style="max-height: 23cm;">

<div style="page-break-after:always"></div>

### 4.6. Mentions légales

Titre et carte réunissant les quatre rubriques.

#### Wireframe

<img src="medias/wireframe_mentions_legales_ordinateur.png" alt="Wireframe de la page Mentions légales, version ordinateur" style="max-height: 23cm;">

#### Version ordinateur

<img src="medias/maquette_mentions_legales_ordinateur.png" alt="Maquette de la page Mentions légales, version ordinateur" style="max-height: 23cm;">

#### Version mobile

<img src="medias/maquette_mentions_legales_mobile.png" alt="Maquette de la page Mentions légales, version mobile" style="max-height: 23cm;">

<div style="page-break-after:always"></div>

### 4.7. Plan du site

Titre et arborescence des pages du site.

#### Wireframe

<img src="medias/wireframe_plan_du_site_ordinateur.png" alt="Wireframe de la page Plan du site, version ordinateur" style="max-height: 23cm;">

#### Version ordinateur

<img src="medias/maquette_plan_du_site_ordinateur.png" alt="Maquette de la page Plan du site, version ordinateur" style="max-height: 23cm;">

#### Version mobile

<img src="medias/maquette_plan_du_site_mobile.png" alt="Maquette de la page Plan du site, version mobile" style="max-height: 23cm;">

<div style="page-break-after:always"></div>

## 5. Logique de navigation dans le site

Le site compte huit pages, organisées sur trois niveaux : l’accueil, cinq pages principales, puis les pages de détail des projets AP3 et AP4. Chaque page existe en français et en anglais. Les deux schémas ci-dessous ont été réalisés dans le même fichier Figma que les maquettes.

### 5.1. Schéma de navigation

<img src="medias/schema_navigation.png" alt="Schéma de navigation du site : en-tête et pied de page présents sur toutes les pages, arborescence sur trois niveaux, de l’accueil jusqu’aux pages Projet AP3 et Projet AP4" style="max-height: 23cm;">

Règles de navigation :

- L’en-tête et le pied de page sont les mêmes sur toutes les pages. Les quatre rubriques principales sont dans la barre de navigation, le plan du site et les mentions légales dans le pied de page. Depuis n’importe quelle page, on atteint donc une page principale en un clic, et les pages Projet AP3 et Projet AP4 en deux clics.
- Le logo et le nom, à gauche de l’en-tête, ramènent à l’accueil.
- Dans la barre de navigation, le lien de la page affichée est sur fond sable avec un texte anthracite. Il porte aussi l’attribut `aria-current="page"` pour les lecteurs d’écran. Sur les pages Projet AP3 et Projet AP4, c’est le lien Projets qui reste en évidence.
- Le sélecteur FR / EN affiche la même page dans l’autre langue, sans revenir à l’accueil. La langue active est sur fond sable.
- Sur téléphone, la barre de navigation passe sur deux lignes au lieu d’être cachée dans un menu : avec quatre liens seulement, tout reste visible.
- Les pages Projet AP3 et Projet AP4 ont un lien « Retour aux projets » en haut et en bas de page.
- Les liens LinkedIn et GitHub s’ouvrent dans le même onglet, pour ne pas ouvrir de nouvelle fenêtre sans prévenir. On revient au portfolio avec le bouton Précédent du navigateur.
- Le plan du site reprend toute l’arborescence. Il sert au visiteur qui ne trouve pas une page, et il aide les moteurs de recherche à parcourir le site.
- Chaque page a son propre titre d’onglet (balise `title`) et sa propre description pour les moteurs de recherche, définis dans le document de contenu.
- Chaque page déclare sa langue avec l’attribut `lang` (`fr` ou `en`). Dans le sélecteur, le lien « EN » porte `lang="en"` et `hreflang="en"`, et le lien « FR » porte `lang="fr"` et `hreflang="fr"`.
- Les deux liens « Voir le projet » de la page Projets ont un intitulé complet pour les lecteurs d’écran, « Voir le projet AP3 » et « Voir le projet AP4 », pour qu’on ne les confonde pas.
- Un lien « Aller au contenu » apparaît au premier appui sur la touche Tab. Il permet de sauter les liens de l’en-tête quand on navigue au clavier. Il est invisible le reste du temps, c’est pourquoi il n’apparaît pas sur les maquettes. L’ordre de tabulation suit l’ordre de lecture : logo, barre de navigation, sélecteur de langue, contenu, puis pied de page.

Les fichiers des pages suivent les conventions de nommage de Kiwipedia : en anglais, en minuscules et en kebab-case, car ils apparaissent dans les adresses du site. La version anglaise reprend les mêmes noms dans un dossier `en`.

| Page | Fichier |
| --- | --- |
| Accueil | `index.html` |
| Parcours | `background.html` |
| Projets | `projects.html` |
| Projet AP3 | `project-ap3.html` |
| Projet AP4 | `project-ap4.html` |
| Veille technologique | `horizon-scanning.html` |
| Mentions légales | `legal-notice.html` |
| Plan du site | `site-map.html` |

<div style="page-break-after:always"></div>

### 5.2. Parcours utilisateurs

Trois profils de visiteurs ont guidé l’organisation des pages. Pour chacun, le schéma indique les pages consultées, dans l’ordre, et le lien utilisé à chaque étape.

<img src="medias/parcours_utilisateurs.png" alt="Trois parcours utilisateurs : un recruteur qui consulte les projets puis le parcours, un jury du BTS SIO qui consulte le parcours, la veille puis les projets, et un visiteur anglophone sur mobile qui change de langue et utilise le plan du site" style="max-height: 23cm;">

**Parcours 1, recruteur ou tuteur d’entreprise.** Il a peu de temps. Le bouton principal de l’accueil l’amène directement aux projets, la partie la plus concrète du portfolio. Il consulte ensuite mon parcours, puis trouve mon profil LinkedIn dans le pied de page pour me contacter.

**Parcours 2, jury du BTS SIO.** Il suit l’ordre d’un dossier : parcours, veille technologique, puis projets. Chaque rubrique est dans la barre de navigation, il n’a donc jamais besoin de repasser par l’accueil.

**Parcours 3, visiteur anglophone sur mobile.** Le sélecteur de langue le garde sur la page en cours. Le plan du site lui permet d’atteindre directement la page qui l’intéresse, et le logo le ramène à l’accueil. Tous ces liens restent visibles sur un écran de téléphone.