Projet WEB GL

1) Cloner le dépôt
2) Lancer un " php -S localhost:8080 " dans le dossier "projetWebGL
3) Ouvrir son navigateur et taper "localhost:8080"
4) Admirer le chef d'oeuvre et jouer avec les commandes.

OU

Accéder via l'URL :  webgl.valentincarrichon.fr

Commandes :
  - ESPACE pour exploser le mur à la méthode de Miley Cirus ( rester appuyer et jouable une seule fois )
  - Z Q S D pour déplacer le bonhomme de paille sur la scene
  - A pour faire grossir le bonhomme de paille ( rester appuyer )
  - E pour rétrécir le bonhomme de paille ( rester appuyer )
  - Pointer vers le cavalier pour animer le dragon

Le loading s'enlève lorsque le model du Dragon a finit de s'importer. Comme c'est le plus long à importer, j'ai mis à ce niveau-ci.
Selon le pc, ca peut mettre un peu de temps. ( Personnellement, en 6 secondes, la scène s'affiche). Donc si elle ne s'affiche pas, il faut juste patienter que le dragon charge.


Les models ne sont pas de moi.
Seul le texte AVENGERS est de moi, réalisé sous cinéma 4D.

Problèmes rencontrés :
  -J'ai rencontrer pas mal de soucis sur l'import des fichiers fbx. J'ai voulu modifier l'attitude des personnages dans cinéma4D, mais lors de l'import sur ma scene, ceux-ci était complétement bugué. Ex: De base, certains persos était en T-pose, j'ai voulu ramener les bras le long du corps, donc baisser de 90° les bras. Lors de l'import, je me retrouvais avec des bras dans des positions bizarre, style 140° avec tout les morceaux de bras dans toutes les directions.
  
  -J'ai voulu un moment effectuer un COMMIT mais je possédais un fichier trop volumineux pour le push, et avec ma connexion c'était galère.
  -J'ai donc clone le dépôt dans un autre repertoire, rajouter mes modifs pour a nouveaux PUSH sinon je ne pouvais plus le faire.

N'ayant pas assisté au dernier cours, la partie sur les Raycaster ma pas mal posé de soucis. En esperant avoir résolu le problème prochainement. (UP : Problème résolu mais surement pas de la meilleure des manières)
