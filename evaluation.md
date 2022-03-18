# Grille d'évaluation pour le TP3
## Structure, sémantique, accessibilité, API des formulaires HTML5
- [X] __Regrouper les éléments de formulaire de même nature__ (.95/1 point)  
  - Utiliser des `<fieldsets>`  
  - Faire des groupes d’`<option>`s dans une liste déroulante
- [X] __Étiqueter__ (.85/1 point)  
  - Étiqueter les groupes d’éléments de formulaire   
  - Nommer chaque groupe avec une `<legend>`  
  - Étiqueter un groupe d’`<option>`s d’une liste déroulante  
  - Étiqueter avec un `<label>` les champs de formulaire  
- [X] __Tester l'accessibilité__ (.65/1 point)  
  - Rendre (garder) le formulaire navigable au clavier  
  - Baliser avec précision les éléments de formulaire  
  - Bien choisir le type du `<input>`   
  - Code sémantique et valide pour l’ensemble du document  
- [X] __Ajouter des containtes de saisie__ (1 point)  
  - Identifier par un attribut approprié les champs obligatoires du formulaire  
  - Ajouter des contraintes de saisie sur les champs de formulaire  

## Styles CSS
- [X] __Aligner les éléments de formulaire__ (.75/1 point)
    - Contrôler les espacements 
- [X] __Intégrer tous les contenus__  (.95/1 point)  
  - Selon les guides visuels (ou mieux !)
- [X] __Styler l’interactivité__  (.85/1 point)
  - État focus, état checked des éléments de formulaires  
  - États des hyperliens (link, visited, hover, active)  
  - Styler les messages d’erreur
  - Utiliser des sprites CSS  
- [X] __Styler les boutons radio__  (.85/1 point) 
  - en les gardant accessibles au clavier

## Méthodes de travail favorisant la collaboration
- [X] __Organiser et documenter la feuille de styles__  (.85/1 point)
- [X] __Utiliser le contrôle des versions GIT__  (1 point)
    - Un minimum de 3 commits est attendu pour les étapes html, css, contrôle qualité finale



## Note et commentaires
<span style='color:red'>8.7 / 10</span>

- Les contraintes sur les champs de saisie (attributs required, pattern...) sont bien réalisés. L'attribut title est utilisé pour expliquer le motif attendu.
- Le formulaire se navigue bien au clavier
- Il manque le message d'erreur pour Province ou État.
- La structure pour le téléphone doit être corrigé en plaçant le p.erreur consécutif au div.rangee qui contient les 3 segments du numéro de téléphone.
- [Plusieurs erreurs HTML](pdf/erreurs-html.pdf)
  - Les messages d'erreur sont en dehors des `<p class="erreur">`
  - L'étiquette du `<select>` n'est pas relié

![](images/select-for.png)

## Barème
| Barème | sur 1 |
|--------|-------|
| A+     | 1     |
| A      | 0.95  |
| B+     | 0.9   |
| B      | 0.85  |
| C+     | 0.8   |
| C      | 0.75  |
| D      | 0.65  |
