# Modele-detection-des-masques-
Modèle intelligent pour la détection des masques

Partie 1 : Base de données, Analyse et Préparation

il faut développer les étapes suivantes :

– Charger les images.

– Penser à redimensionner les images selon le modèle VGG16.

– Splitter les données en données d’apprentissage, validation et test.

– Visualiser les images de la classe Avec_Masque et Sans_Masque.

​

Partie 2 : Architecture CNN sur Tensorflow

​

Cette deuxième partie est réservée pour développer le modèle CNN sur tensorflow, et lancée par la suite l’apprentissage de CNN.

   -  Au début, il faut préparer et appliquer la Data Augmentation sur les données d’apprentissage.
   -  Charger et configurer le modèle VGG16 pour l’application souhaitée.
   -  Appeler le ModelCheckpoint pour sauvgarder le meilleurs modèle durant l’apprentissage (from keras.callbacks import ModelCheckpoint)
   -  Lancer un apprentissage en utilisant les données d’apprentissage et les données de validation avec un historique.
   -  Tracer les courbes d’accuracy et d’erreur de train et validation.
   -  Calculer l’accuracy et la matrice de confusion sur les données de test.

​

Partie 3 : Application

​

Nous cherchons à tester le modèle développé sur des nouvelles images.

​

Pour un début, cherchez des images sur le net ou prenez photos entre vous et tester le résultat de votre modèle en affichant le message : Avec masque ou Non masque sur l’image. (cv2.putText(Img, message, (x, y), cv2.FONT_HERSHEY_SIMPLEX, .5, (0,0,0)))

​

Par la suite, vous êtes censés à développer un code python qui va activer la Webcam et identifier si la personne qui est devant la Webcam porte un masque en affichant le message : Avec masque ou Non masque sur l’image.
