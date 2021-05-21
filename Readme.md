# Abnormal_Sound_Detection

Afin de pouvoir utiliser les modèles, il convient de mettre dans le dossier archive les fichiers audio disponibles à cette URL en conservant l'arborescence:
https://www.kaggle.com/daisukelab/dc2020task2

Le dossier npy contient les fichiers .npy de nos audio a charger dans nos différents notebook

Nous avons les différents notebooks suivants:
    1. AE => Les différents essais de model d'AutoEncodeur
    2. Classificateur_ID_hybride => modèle de classification sur les ID pour détection normal anormal 
    3. Classificateur_ID_RNN => modèle de classification sur les ID pour détection normal anormal a l'aide d'un model RNN
    4. Dataviz => notebook contenant toute les datavisualisation
    5. Template => notebook appeler dans les différents modèles, il contient tous les imports et un appel aux fonctions utiles
    6. functions_utils => notebook contenant toute les fonctions utilisé et chargé dans le Template

Lien du code streamlit 
https://github.com/yos95/demoStreamlit_AnomalySD