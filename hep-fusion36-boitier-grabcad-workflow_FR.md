# Concevoir un boîtier Arduino Uno (GrabCAD Workflow)

Ce tuto vous montre un **flux de travail** très utile

1.  télécharger un modèle 3D depuis Internet, 
2. l'importer dans Fusion360, 
3. puis créer plus de géométrie à partir de ce modèle.

## Partie 1:

- Obtenez un compte GrabCAD.com.
- S'identifier.
- [Rechercher 'Arduino Uno'](https://grabcad.com/library)
    ![](https://i.imgur.com/QxJQQlo.png)
- Cliquez sur quelques modèles, et voyez celui que vous aimez.
- Vous voulez un modèle qui a le format STEP, IGES, SAT, F3D ou SolidWorks disponible dans les téléchargements.
    ![](https://i.imgur.com/lIGqgwX.png)
    ![](https://i.imgur.com/ikjHkGn.png)
    - _(Les fichiers les plus courants que vous pouvez obtenir et utiliser dans Fusion360 sont des fichiers STEP (_.ste, _.step, _.stp), IGES (_ige, _.iges, _igs), des fichiers SAT/SMT (_.sat , _.smt), et SolidWorks Files (_.prt, _.asm, _.sldprt, _.sldasm).
    - Voir cette page dans les documents Fusion pour une [liste complète des fichiers supportés](https://knowledge.autodesk.com/support/fusion-360/dépannage/caas/sfdcarticles/sfdcarticles/Comment-importer-ou-ouvrir-un-fichier-dans-Autodesk-Fusion-360.html).
- Téléchargez le modèle de modèle 3D uniquement en cliquant directement sur le fichier ou téléchargez Tout.
    ![](https://i.imgur.com/iZfyIvq.png)
    ![](https://i.imgur.com/r3TANHS.png)
- Open Fusion360
- En option, créez un nouveau projet
    ![](https://i.imgur.com/Fvxv7h6.png)
- Cliquez sur le téléchargement
    ![](https://i.imgur.com/hTYahQa.png)
- Sélectionnez le fichier que vous venez de télécharger et cliquez sur télécharger
    ![](https://i.imgur.com/6F46kh7.png)
- Attendez que le processus se termine
- Démarrer un nouveau design
    ![](https://i.imgur.com/8AHRr2E.png)
- Sauvegardez le design
    - Pour sélectionner le dossier dans lequel enregistrer le design, vous pouvez cliquer sur le bouton 'voir plus'
    ![](https://i.imgur.com/Ex6mhRF.png)
- Insérez l'Arduino dans notre nouveau design
    ![](https://i.imgur.com/OdYVUMI.png)
    - Vous devrez peut-être utiliser les poignées de rotation pour positionner le modèle correctement
   ![](https://i.imgur.com/nE3j9dw.png)
- Masquer le panneau de données
    ![](https://i.imgur.com/FumkrJ5.png)
- Assurez-vous que vous êtes dans l'espace de travail 'Modèle'
    ![](https://i.imgur.com/RbVCVmb.png)
- Nouveau composant
    ![](https://i.imgur.com/SFO1IRZ.png)
- Nomme le
    ![](https://i.imgur.com/BH6nj0N.png)
- Assurez-vous qu'il est activé
    ![](https://i.imgur.com/1X2DJGw.png)
- Nouveau plan décalé
    ![](https://i.imgur.com/X1zO0Q7.png)
- Offset du fond de l'arduino 3mm
    ![](https://i.imgur.com/jCXIs7H.png)
- Créez une nouvelle esquisse et sélectionnez le plan que vous venez de créer
- Utilisez l'outil de projet pour projeter la géométrie arduino sur votre croquis
    ![](https://i.imgur.com/eTlz8mN.png)
- Vous pouvez cliquer sur des entités individuelles comme des cercles ou des arêtes, ou cliquer sur le face d'arduino pour projeter toutes les fonctionnalités.
    ![](https://i.imgur.com/yC7CKZ2.png)
    ![](https://i.imgur.com/EoZMjiE.png)
- Masquer le composant arduino
  ![](https://i.imgur.com/VXuK11T.png)
- Utilisez l'outil de décalage pour décaler le bord extérieur 4 mm
    ![](https://i.imgur.com/JpowA2q.png)
    ![](https://i.imgur.com/pb8I6v1.png)
- Sélectionnez et supprimez autre chose que le contour et les trous
    ![](https://i.imgur.com/LN2htvl.png)
- Arrêter le croquis
    ![](https://i.imgur.com/aGQ19W7.png)
- Sélectionnez tous les profils d'esquisse
    ![](https://i.imgur.com/Mq8mAec.png)
- Afficher l'arduino
    ![](https://i.imgur.com/F3zmO62.png)
- Démarrer une commande d'extrusion vers le haut
- Cliquez et faites glisser sur la flèche un peu plus haut
    ![](https://i.imgur.com/nNBX5lY.png)
- Maintenant, cliquez sur la partie supérieure de l'arduino (le connecteur), et la distance d'extrusion s'alignera sur ce point.
    ![](https://i.imgur.com/1b9pOe6.png)
- Allez dans la boîte de dialogue et ajoutez '+4' à la distance d'extrusion
    - (Ou `-4` - cela dépend de la direction de votre première extrusion.Important est que vous ajoutiez une distance.)
  ![](https://i.imgur.com/N5zhWCq.png)
- Nous avons un nouveau corps!
    ![](https://i.imgur.com/ozjz8IO.png)
- Sauvegarder :-)
    ![](https://i.imgur.com/A5Ujrug.png)
- Construire un midplane entre le haut et le bas
    ![](https://i.imgur.com/SD8Ozsa.png)
    ![](https://i.imgur.com/dkjWnSx.png)
- Utilisez la commande Split Body pour diviser le corps avec ce plan
    ![](https://i.imgur.com/lvL1UvK.png)
    ![](https://i.imgur.com/5l7TdOO.png)
- Masquer la construction, masquer les esquisses et afficher la vue Corps
    ![](https://i.imgur.com/Igy1KUF.png)
- Cacher le haut du corps
    ![](https://i.imgur.com/y7oxX9D.png)
- Utilisez la commande shell pour faire un mur de 3,5 mm
    - cliquez sur la face supérieure de notre boîte
    ![](https://i.imgur.com/26G3DRV.png)
    ![](https://i.imgur.com/cxMeVrr.png)
- Répétez pour la moitié supérieure
    ![](https://i.imgur.com/46qfsUR.png)
- Créer une nouvelle esquisse en cliquant sur la partie supérieure de notre partie BOTTOM
    - Ceci "projette" automatiquement le visage sur le nouveau croquis
     ![](https://i.imgur.com/8DL5PBx.png)
- Décaler le contour comme avant, 1.8mm dans le modèle.
     ![](https://i.imgur.com/grq4Mun.png)
- Arrêtez l'esquisse, assurez-vous que cette nouvelle esquisse est visible et masquez l'ancienne esquisse.
     ![](https://i.imgur.com/Edlumq6.png)
- Ici, je passe aux couleurs pour mieux voir les différents composants
     ![](https://i.imgur.com/QIMpuoj.png)
- Extruder la partie intérieure de l'esquisse 4 mm vers le haut
     ![](https://i.imgur.com/tCI5E5R.png)
- Rendre le croquis visible à nouveau (il se cache automatiquement lors de l'extrusion pour la première fois) et rendre la 2ème moitié visible
     ![](https://i.imgur.com/a6GxaVd.png)
- Extruder l'esquisse interne dans le modèle, en le coupant.
     ![](https://i.imgur.com/YC4rzoN.png)
- Utilisez l'outil d'analyse de section pour voir les intérieurs.
     ![](https://i.imgur.com/96HNNvB.png)
     ![](https://i.imgur.com/fnsc8vE.png)
- Réalise que tu as fait une erreur.
     ![](https://i.imgur.com/vTzB9Eb.png)
- Editer la 2ème commande shell de 4mm à 3.5mm
     ![](https://i.imgur.com/vbmDhFz.png)
     ![](https://i.imgur.com/GMDp0Yv.png)
- Maintenant, nous avons **une simple boîte Arduino!**
     ![](https://i.imgur.com/r8Iyg5a.png)

## Toutefois! Deuxième partie:

- Nous n'avons pas fini. Quand on y regarde de près, il y a quelques choses que nous devons faire pour que la boîte fonctionne vraiment. Nous devons faire quelques ajustements.
- Il y a **TROIS** plus de choses que nous devons faire pour que cette boîte fonctionne. Pouvez-vous comprendre ce qu'ils sont et comment les faire? (Lire la suite pour une solution.)

### Ajoutez plus d'espace en bas et en haut.
- Nous avons oublié de compenser l'épaisseur du mur. Il y a un chevauchement clair sur le fond entre l'arduino (et ses broches) et la boîte.
     ![](https://i.imgur.com/ONWdwYv.png)
- Pour résoudre ce problème, faites un clic droit sur la première commande, plan de décalage, et passez en mode d'édition.
    - Changez-le à 6.5mm (3 + 3.5 (épaisseur de la boîte))
     ![](https://i.imgur.com/T2DwFq4.png)
     ![](https://i.imgur.com/JsgWZwS.png)
- C'est nettement mieux.
     ![](https://i.imgur.com/bwhYe6i.png)
- Maintenant, en haut, éditez simplement la première extrusion. Ajouter un autre 3,5 mm à la longueur extrudée, totalisant maintenant 23 mm.
     ![](https://i.imgur.com/QUHsMaZ.png)
     ![](https://i.imgur.com/6tioVwh.png)
- Maintenant, l'arduino a de l'espace à la fois au-dessus et au-dessous.
     ![](https://i.imgur.com/foGi82z.png)

### Ajouter "tolérance" entre la moitié supérieure et inférieure.
 
- Nous allons imprimer notre boîte en 3D, et l'impression 3D ajoute un peu d'imprécision dans le mélange. Nous devons concevoir un petit espace (environ 0,2 mm) entre les murs de sorte que les deux moitiés s'emboîtent réellement.
     ![](https://i.imgur.com/8pxJym3.png)
- Cachez la partie supérieure.
- Retournez et modifiez l'esquisse au milieu.
    - Faire un nouveau décalage, cette fois 1.6mm
     ![](https://i.imgur.com/irZZasU.png)
    - Nous avons maintenant deux lignes, à 0,2 mm l'une de l'autre
     ![](https://i.imgur.com/lLBUVj2.png)
- Retournez et éditez la dernière extrusion.
    - Cliquez sur cette bande de 0,2 mm que nous venons de créer pour l'ajouter à l'extrusion.
     ![](https://i.imgur.com/jFCHAYf.png)
- Afficher le haut et voir, il y a maintenant un écart de 0.2mm entre les pièces!
     ![](https://i.imgur.com/G3UeoKd.png)

### Trous de découpe pour connecteurs
- Enfin, nous devons découper l'espace pour les connecteurs.
     ![](https://i.imgur.com/Gm9RaRd.png)
- Masquer l'analyse de section
     ![](https://i.imgur.com/2CGCEBd.png)
- Faire un nouveau croquis sur la face latérale de la boxe où les connecteurs sont
     ![](https://i.imgur.com/y7G6UEO.png)
- Puisque nous avons commencé un croquis sur un visage et non sur un plan, le 'nouveau croquis' fait automatiquement une projection du visage sur le croquis. Nous ne le voulons pas maintenant. Sélectionnez tout et appuyez sur Supprimer. Maintenant, nous avons un croquis vide.
     ![](https://i.imgur.com/yvezdYh.png)
- Sélectionnez l'outil Projet et projetez le connecteur USB. Il suffit de cliquer sur son visage.
     ![](https://i.imgur.com/DWalkst.png)
     ![](https://i.imgur.com/jahg3OQ.png)
- Cacher les corps
- Continuez à utiliser l'outil Projet pour projeter le connecteur d'alimentation.
     ![](https://i.imgur.com/8aWZt5x.png)
- Ajoutons de la tolérance aux deux projections avec l'outil offset. Peut-être 0,4 mm?
     ![](https://i.imgur.com/llKCrcs.png)
     ![](https://i.imgur.com/kr9Ptgk.png)
- Double-cliquez sur le rectangle du projet à l'intérieur pour le sélectionner. Ensuite, faites un clic droit et sélectionnez "Géométrie de construction". Cela rend la forme visible - ligne pointillée - mais elle sera cachée aux commandes comme l'extrusion, ce qui rendra le travail plus facile.
    - ![](https://i.imgur.com/skcpf42.png)
    - Vous pouvez cacher l'arduino pour voir le croquis plus facilement.
     ![](https://i.imgur.com/PlKfVhV.png)
     ![](https://i.imgur.com/gdUYPCS.png)
- Faites de même pour l'autre connecteur.
     ![](https://i.imgur.com/0KfgSv9.png)
- Supprime l'autre géométrie à l'intérieur superflue.
     ![](https://i.imgur.com/FSB18kS.png)
     ![](https://i.imgur.com/CJyMRD3.png)
- Arrête le croquis et Affiche les corps.
     ![](https://i.imgur.com/XP2FVeJ.png)
- Extruder les deux profils d'esquisse dans les corps pour «couper» les trous.
     ![](https://i.imgur.com/b4Pa7Cn.png)
- Tadaaaa! Nous avons eu un cas d'arduino probablement fonctionnel!

- Bonus: Vous pouvez sélectionner les bords extérieurs et ajouter un 'chanfrein' de 0,8 mm pour rendre la boîte plus fraîche et plus lisse.
     ![](https://i.imgur.com/R4cBTdj.png)
     ![](https://i.imgur.com/uecw8Yz.png)
     ![](https://i.imgur.com/sDwGJqG.png)
- PS: Maintenant, il serait temps de faire un autre croquis sur le dessus et d'ajouter quelques découpes super cool! C'est à toi de voir. PS: vous pouvez importer des fichiers dxf ou svg depuis Inkscape ou Illustrator ...
- Que serait un design sans cool?
- Icône 'Gentleman' créé par iconsmind.com pour le projet Noun. (Creative Commons)
 ![](https://i.imgur.com/tSRTGnF.png)
 
 - PSS:
 
**Pourquoi ai-je laissé les erreurs** (comme une mauvaise distance d'extrusion) dans ce tutoriel au lieu de le rendre parfait dès le début?

Parce que c'est comme ça que vous travaillez dans le monde réel. **Vous faites quelque chose assez rapidement sans trop réfléchir, puis revenez et changez les choses jusqu'à ce que ça marche.**

Profitez du processus!