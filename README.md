# DetectionDeTexte_easyOCR

Ce mini-projet permet : 
* La détection de texte à partir des images en utilisant Python et le package easyOCR.
* La détection de texte Arabe et le conserver dans un fichier texte.
* La détection de texte Anglais et son affichage direct sur l'image.

Pour plus de détails : [Présentation PPT](https://github.com/lilou1radi/DetectionDeTexte_OCR/blob/master/TextDetection.pdf)

### - A propos d'easyOCR :
EasyOCR est un package python qui permet de convertir l'image en texte. C'est de loin le moyen le plus simple d'implémenter l'OCR et a accès à plus de 70 langues, dont l'anglais, le chinois, le japonais, le coréen, l'hindi, bien d'autres sont en cours d'ajout. 

EasyOCR est construit avec Python et la bibliothèque de deep learnig Pytorch.

Avoir un GPU pourrait accélérer l'ensemble du processus de détection. La partie détection utilise l'algorithme CRAFT et le modèle de reconnaissance est CRNN. 

### - Installation avec pip :
*pip install easyocr*

#### + Lien utile :
https://www.pyimagesearch.com/2020/09/14/getting-started-with-easyocr-for-optical-character-recognition/
