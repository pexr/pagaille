# Pagaille

## Vision

Le site `Pagaille` propose des moyens d'action à tous les citoyens qui veulent aider "sans risque" à enrailler le système qui détruit le climat et le vivant. Ces personnes engagées dans de petites actions de désobéissance civile detinées à générer de la pagaille sont appelées fièrement des `'Madame Pagaille'` et `'Monsieur Pagaille'` (en référence à la [série de livres pour enfants](https://fr.wikipedia.org/wiki/Monsieur_Madame)). Les moyens proposés sont **toujours** non-violents.


## Développement

Dans le répertoire `./content`: le contenu [1] du futur site de `Monsieur/Madame pagaille`: http://www.pagaille.org. Le [README](./content/README.md) à la racine de ce répertoire étant destiné à la page d'accueil.

L'idée est de converger sur un contenu `en français et au format markdown` dans un premier temps puis de basculer en html/css dans le sous répertoire `./site/fr`: site statique facilement déployable vers n'importe quel serveur pour plus de résilience [2] ;)

Si certain.e.s se sentaient motivé.e.s pour lancer des versions dans d'autres langues, il leur suffirait de contribuer à ce dépôt en proposant de traductions dans les sous-répertoires dédiés (`./site/en, ./site/es, etc...`)

### Reste à faire

Trouver un.e designer pour:
  - travailler un logo, facile à dessiner rapidement par n'importe qui (de 7 à 99 ans) et qui représente le concept de "pagaille", non-violente et déterminée.
  - concevoir le rendu web du répertoire `./content` dans le sous-répertoire `./site/fr` (CSS, typographie, etc)
  - concevoir un site de quelques kBytes pour:
    - limiter l'impact sur la planète
    - permettre d'y accéder facilement même avec une connectivité limitée
    - permettre l'hébergement gratuit sur des offres "Free" même pour un trafic important. Par exemple, un site d'1 MB peut être servi 20 000 fois par mois sur le plan "Free" de Zeit, cf. https://zeit.co/pricing). A 300 kB, on monte à 60 000! D'où l'intérêt d'avoir un site optimisé côté rendu (css, images) tout en conservant un site plaisant à parcourir.

Une identité visuelle forte permettra de booster le message (comme a pu le faire extinction rebellion)

*Notes:*
- [1] contenu non mis en forme, aucun style.
- [2] [now.sh](https://zeit.co/home), [surge.sh](https://surge.sh/)

