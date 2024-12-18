# AvalutionAndroid

### README pour l'Évaluation Android : Application Consommant une API Publique

---

#### **Description du projet :**
Ce projet est une application Android utilisant Jetpack Compose et l'API publique de Rick and Morty. L'application affiche une liste de personnages et leurs détails grâce à une architecture MVVM moderne.

---

### **API Choisie :** Rick and Morty API

- **Base URL :** https://rickandmortyapi.com/
- **Endpoints Utilisés :**
  1. Liste des personnages : `/api/character`
  2. Détails d'un personnage : `/api/character/{id}`

---

### **Fonctionnalités Implémentées :**
1. Affichage d'une liste paginée des personnages (nom, image, statut).
2. Navigation vers un écran de détails pour afficher des informations supplémentaires sur un personnage.
3. Gestion de la navigation avec `NavController`.
4. Ajout de sons et vibrations lors des interactions utilisateur.
5. Support multilingue (anglais et français).
6. Gestion des thèmes clairs et sombres.

---

### **Architecture :**
Le projet suit l'architecture MVVM (Model-View-ViewModel) :

- **Data Layer** :
  - `Retrofit` pour les appels API.
  - `Repository` pour centraliser les données.
- **Domain Layer** :
  - Modèles et cas d'utilisation.
- **UI Layer** :
  - Composants d'interface utilisateur avec Jetpack Compose.
  - Écrans de liste et de détails.

---

### **Outils et Librairies :**
- **Jetpack Compose** : Interface utilisateur déclarative.
- **Retrofit** : Appels API.
- **Hilt** : Injection de dépendances.
- **Coil** : Chargement d'images.
- **NavController** : Gestion de la navigation.

---

### **Comment exécuter le projet :**
1. Clonez le dépôt :
   ```bash
   git clone <url-du-repo>
   ```

2. Ouvrez le projet dans Android Studio.
3. Synchronisez les dépendances Gradle.
4. Lancez l'application sur un émulateur ou un appareil physique.

---


### **Améliorations Futures :**
- Ajout d'un système de pagination pour charger les personnages dynamiquement.
- Tests unitaires et d'intégration.
- Gestion des erreurs réseau et affichage d'un état vide.
