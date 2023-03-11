Tuto de Grafikart : https://youtu.be/LNqBKTeeiWo?t=550
(Pas la source du code)

## Remarque sur le grow
Si je mets un `flex-grow: 2` sur un élément A et `flex-grow: 1` sur un élément B, alors, lors de l'agrandissement pour remplir l'espace restant,A s'agradira 2 fois plus vite que B.

Exemple :

Si, sans agrandissement, A=B=100px, puis que j'agrandis la fenêtre de 150px,
alors A s'agrandira de 100px et B de 50px, et on aura donc A=200px et B=150px.