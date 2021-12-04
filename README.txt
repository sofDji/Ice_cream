***** Train ice cream data *****

Ce mettre dans le dossier "Ice_cream\my_project_v2\samples\custom"

et lancer la commande : python custom.py train --dataset=path\to\datasets\custom\train --weights=coco

Le résultats du training sont mis dans le dossier : "Ice_cream\my_project_v2\logs"

***** Detect ice cream ******

Ce mettre dans le dossier "Ice_cream\my_project_v2\samples\custom"

et lancer la commande : python custom.py splash --weights=path\to\mask_rcnn_ice_cream_0010.h5 --image=path\to\image.jpg

Le résultats du splash sont mis dans le dossier : "Ice_cream\my_project_v2\samples\custom"

