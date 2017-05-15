# Catan Board - Étapes de création

## Preparation

Le plateau est composé de 3 couches :
- **la côte** (top) : ~4mm, cadre principal 
- **Trous** (bottom) : trou entre les hexagones
- **base** : base solide pour rigidifier l'ensemble

![layers](../images/layers.jpg)

Vous pouvez choisir différents types de matériaux. Pour mon prototype, j'ai choisi du bouleau contreplaqué.

## ️️✂️ Couper

J'ai choisi de faire mes découpe sur une [Trotec Speedy 300](https://www.troteclaser.com/en/laser-machines/laser-engravers-speedy-series/) dans mon Fablab local. Si vous avez le même type de découpeuse laser ou au moins un **espace de découpe de 726mm x 432mm**, vous pouvez directement utiliser les fichiers dans `src/inkscape/` :
- `bottom-center.svg` : centre du cadre, **4**mm d'épaisseur*
- `bottom-left.svg` : cadre gauches^, **4**mm d'épaisseur*
- `bottom-right.svg` : cadre droite, **4**mm d'épaisseur*
- `centers.svg` : petites pièces à mettre dans les trous, **6.5**mm d'épaisseur*
- `top-center.svg` : trous centraux, **4**mm d'épaisseur*
- `top-left.svg` : trous gauches, **4**mm d'épaisseur*
- `top-right.svg` : trous droites, **4**mm d'épaisseur*

*\* vous pouvez faire varier l'épaisseur*

Vous pouvez aussi prendre les fichiers **Illustrators** et faire vos propres exports 😉

![cut](../images/cut.jpg)
![pieces](../images/pieces.jpg)

Vous pouvez aussi **enlever des bouts de la base** si vous souhaitez un système d'accroche.

![base](../images/base.jpg)

Quand tout est découpé, il est conseillé de **poncer vos pièces**.

![sand](../images/sand.jpg)

## 🍯 Coller

Premièrement, vous devez coller vos **trous (bottom) sur la base**

![glue1](../images/glue1.jpg)

...ensuite, les **petites pièces dans les trous**

![glue2](../images/glue2.jpg)

... et pour finir, **le cadre (top) sur les trous (bottom)**

![glue3](../images/glue3.jpg)

En fonction de votre colle, vous devrez **presser les différentes parties ensemble** pendant un certain temps.

## ✨ Finalisation

Vous devez couper autour de votre plateau afin de permettre la jonction des différentes parties, réduire la taille totale et créer une jolie forme.

![saw](../images/saw.jpg)
![finish](../images/finish.jpg)

Finalement, je vous recommande d'appliquer un **vernis** de votre choix afin de protéger votre plateau.

![result](../images/result.jpg)

