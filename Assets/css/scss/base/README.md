##  DOSSIER BASE
Le dossier base/ contient ce que nous pourrions appeler le code standard (boilerplate) du projet. On pourrait y trouver par exemple le fichier de reset, quelques règles typographiques, et probablement une feuille de style définissant quelques styles standard pour les éléments HTML les plus employés (que j’ai l’habitude d’appeler _base.scss).

#### Exemple :

        _base.scss
        _reset.scss
        _typography.scss

Si votre projet utilise beaucoup d’animations CSS, vous pouvez envisager d’ajouter un fichier _animations.scss contenant les définitions de @keyframes pour toutes vos animations.
 Si vous n’utilisez les animations que de façon sporadique, laissez leur déclaration près des sélecteurs qui les emploient.

