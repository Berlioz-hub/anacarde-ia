# Anacarde IA
Assistant intelligent pour le diagnostic des maladies de l'anacarde au Bénin.
## Objectif
Aider les producteurs d'anacarde béninois à identifier les maladies de leurs plants à partir d'une simple photo, via WhatsApp.
## Comment ça marche
1. L'agriculteur envoie une photo de feuille sur WhatsApp
2. Le modèle IA analyse la photo
3. L'agriculteur reçoit un diagnostic et des conseils
## Le modèle
- **Type :** Classification d'images (MobileNetV2)
- **Classes :** Anthracnose, Gummosis, Healthy, Leaf_miner, Red_rust
- **Entraînement :** 13 415 images
## Outils utilisés
- Google Colab (entraînement)
- Teachable Machine (prototype)
- WhatsApp Business (interface)
- TensorFlow (modèle)
## Prochaines étapes
- [ ] Tester avec 10 agriculteurs
- [ ] Automatiser sur WhatsApp
- [ ] Étendre à d'autres cultures
## Auteur
Berlioz Nassara
- GitHub : @Berlioz-hub
- Email : dahberlo731@gmail.com
## Licence
Ce projet est open source.
