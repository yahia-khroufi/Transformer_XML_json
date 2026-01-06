# DATAFLOW - Converter Pro 🚀

**DATAFLOW** est une application desktop performante développée en **Java v22**, conçue pour la conversion bidirectionnelle fluide entre les formats **XML** et **JSON**.

---

## 📺 Démonstration Vidéo
Découvrez l'application en action et son fonctionnement technique :
👉 **[Regarder la vidéo de démonstration sur Google Drive](VOTRE_LIEN_DRIVE_ICI)**

---

## 📋 Présentation du Projet
L'objectif de ce projet est d'offrir un outil simple et efficace pour transformer des données structurées. L'application propose deux approches complémentaires :
* **Mode Local (Sans API) :** Utilisation d'algorithmes personnalisés pour un traitement récursif des données.
* **Mode Externe (Avec API) :** Intégration de la bibliothèque `org.json` pour des conversions standardisées.

## 🛠️ Architecture Technique
Le projet respecte scrupuleusement le modèle **MVC** (Modèle-Vue-Contrôleur) pour une séparation claire des responsabilités :

* **Logiciel :** Java 22 (JDK)
* **Interface :** JavaFX avec FXML
* **Style :** CSS personnalisé (`modern-theme.css`)
* **Environnement :** Eclipse IDE

### Structure des fichiers clés :
* `Main.java` : Initialisation et lancement de l'application.
* `ConverterController.java` : Gestion de la logique de conversion et des événements.
* `PrimaryScene.fxml` : Design et structure visuelle de l'interface.

## 🚀 Fonctionnalités
* **Saisie flexible** : Collez directement du code ou importez des fichiers XML/JSON.
* **Conversion instantanée** : Transformation en un clic avec les boutons "Generate".
* **Interface Intuitive** : Zones d'entrée (Input) et de sortie (Output) distinctes pour une meilleure lisibilité.
* **Flexibilité totale** : Basculement facile entre le mode API et le mode local.

## ⚙️ Installation
1.  Clonez le dépôt : `git clone https://github.com/yahia-khroufi/Transformer_XML_json.git`
2.  Importez le projet dans **Eclipse**.
3.  Assurez-vous d'avoir le **SDK JavaFX** configuré dans votre Build Path.
4.  Lancez `Main.java`.

---
## ⚖️ Licence
Ce projet est sous licence MIT.
