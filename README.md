# bigBizYou-test

Exercice test technique :

L’objectif de l’exercice est de créer un projet contenant une page d’accueil accèssible à tous les internautes ainsi qu’un espace sécurisé.

Les technologies à employer sont :
- framework PHP : Symfony
- Framework CSS : SEMANTIC UI ( https://semantic-ui.com/ ). 

Le projet devra nous être envoyé sous forme de fichier ZIP (Sources + DUMP de la DB).


Description :


Le projet doit contenir les Urls/routes suivantes :

La homepage :   /

Une page de connexion à une espace admin : /login

Une page d’inscription avec les champs « login / mdp / email «  

La page d’accueil Admin : /admin/home. Uniquement accessibles avec les droits utilisateur USER_ADMIN


- La page d’accueil doit avoir l’aspect suivant : https://semantic-ui.com/examples/homepage.html (remplacer le texte « Imagine-a-Company  » page Bienvenue)
- Les boutons "log in" et "Sign Up" ne doivent pas êtres affichés quand le user est connecté.


- La page Login accessible depuis le bouton « login » , doit avoir l’aspect suivant : https://semantic-ui.com/examples/login.html

- La page inscription doit être accessible via le bouton «  Sign Up » . Pas de mise en forme imposée.

- La page /admin/home  contenir le texte suivant : Bienvenue {login de l’utilisateur} !


Toutes les pages doivent garder le même header et footer.
