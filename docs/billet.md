# Résumé de conférence CodeursEnSeine 2018 - Mélodie Boillet

## Cartouche d'identification

 - Manifestation : CodeursEnSeine 2018
 - Lieu : Kindarena - Palais des sports de Rouen
 - Conférence : Style(d) et React, même Compo
 - Horaire de la conférence : 12h00
 - Durée de la conférence : 15min
 - Conférenciers :
   - Marion DEVEAUX : [LinkedIn](https://www.linkedin.com/in/marion-deveaux-a70107a0/)
   - Valentin DESPORTES : [LinkedIn](https://www.linkedin.com/in/valentin-desportes-38b6bba7)
 - Audience : ~ 100 personnes
 - Auteur du billet : Mélodie Boillet
 - Mots-clés : ReactJS, StyledComponents, Attineos, Application Web, CSS.
 - URL de l'illustration : ![StyledComponents](https://cdn-images-1.medium.com/max/2000/1*TO5cYT14YsCfR-j1xdp8lw.png)
 - Quelques sources : 
   * https://www.styled-components.com/docs,
   * https://github.com/styled-components/styled-components,
   * https://alligator.io/react/styled-components/,
   * https://medium.com/tech-tajawal/react-styled-components-79e94f771732.

## Support
 - Aucun support car live coding.
 
   Répertoire avec l'application créée lors de la conférence : https://github.com/attineos/codeurs-en-seine-2018.
 - Nombre de diapos du support : 0
 - Plan du support :
    * Introduction et présentation de l'application avant utilisation de styled-components,
    * Explication des objectifs de la conférence,
    * Mise en place de styled-components dans l'application,
    * Améliorations et conclusion.

## Résumé
Le but de cette conférence en live coding était de présenter rapidement les bases de styled-components et de son utilisation. A l'aide d'une application web très simple avec seulement une image qui tourne plus ou moins vite en fonction des clics de l'utilisateur, les intervenants ont pu présenter comment fonctionne styled-components et comment l'intégrer à une application.
Il ont donc montré que les résultats obtenus sont les mêmes que ceux obtenus avec du simple CSS mais ont surtout mis en avant les avantages de son utilisation. L'un des principaux avantages est sa simplicité de mise en place. De plus, il permet de faire comme le CSS basique (style, couleur, animations, etc...) directement dans le code JavaScript. Cela permet de ne pas utiliser les classes mais d'appeler directement le bon composant. Le code en est donc allégé et plus facilement compréhensible et reprenable. Pour terminer, les intervenants ont montré qu'il était possible de créer des composants plus sophistiqués plus simplement qu'avec du simple CSS.

## Architecture et facteur qualité
Cette conférence et plus particulièrement l'utilisation de styled-components influe principalement sur le facteur qualité _Adaptabilité_. En effet, l'utilisation de styled-components permet de créer ses propres composants CSS en JavaScript directement dans le code de l'application web. Créer un composant nécessite peu de connaissances autres que celle du CSS, il est donc simple et rapide d'en créer. En effet, pour créer des composants, les intervenants ont simplement copié le code CSS dans la déclaration du composant dans un fichier JavaScript. De plus, les composants ainsi créés peuvent être étendus et réutilisés dans toute l'application. On peut donc faire de l'héritage de composants et en créer de nouveaux sans trop d'efforts. Ainsi, l'utilisation de styled-components permet de minimiser les efforts nécessaires à la modification de différents composants.
