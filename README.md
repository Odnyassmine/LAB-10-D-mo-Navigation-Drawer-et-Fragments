NavifationDrawer Demo 📱
Cette application Android est une démonstration moderne de l'utilisation d'un Navigation Drawer (menu latéral) pour naviguer entre différents fragments, incluant une gestion dynamique de listes et une interface personnalisée.
🚀 Fonctionnalités
•
Menu Latéral (Navigation Drawer) : Permet de basculer entre trois écrans principaux :
◦
Fragment 1 : Un écran de bienvenue simple.
◦
Fragment 2 : Un écran alternatif avec un design épuré.
◦
Fragment List : Une liste dynamique numérotée (Item 1, Item 2, etc.).
•
Toolbar Personnalisée : Barre d'action avec un titre spécifique et bouton menu "hamburger".
•
Bouton d'Action Flottant (FAB) : Un bouton d'action rapide en bas à droite déclenchant une Snackbar.
•
Gestion des Fragments : Utilisation de supportFragmentManager pour des transitions fluides sans recharger l'activité.
•
Thème Personnalisé : Palette de couleurs basée sur un bleu profond (#3F51B5).
🛠 Technologies utilisées
•
Langage : Kotlin 2.0.21
•
Build System : Gradle KTS (Kotlin Script)
•
Android Gradle Plugin (AGP) : 9.0.1 (utilisant le support Kotlin intégré)
•
Architecture : Fragments & View Binding
•
Composants UI :
◦
DrawerLayout & NavigationView
◦
CoordinatorLayout & FloatingActionButton
◦
ListFragment
◦
Material Design 3
📁 Structure du Projet
Kotlin
app/src/main/java/com/example/navigationdrawerdemo/
├── MainActivity.kt      # Activité principale gérant le Drawer et la navigation
├── BlankFragment.kt     # Fragment d'accueil
├── BlankFragment2.kt    # Second fragment de démonstration
├── FragmentList.kt      # Fragment affichant la liste personnalisée
└── ui/                  # Dossier pour les composants UI additionnels

app/src/main/res/
├── layout/              # Fichiers XML de l'interface (Activity, Fragments, Items)
├── menu/                # Définition du menu latéral et du menu toolbar
└── values/              # Couleurs, thèmes et chaînes de caractères (strings.xml)
⚙️ Configuration Requise
•
Android Studio : Version Jellyfish ou plus récent recommandé.
•
SDK Minimum : API 24 (Android 7.0)
•
SDK Cible : API 36
🛠 Installation
1.
Clonez le dépôt ou téléchargez les fichiers.
2.
Ouvrez le projet dans Android Studio.
3.
Attendez la synchronisation Gradle (le projet utilise le support Kotlin natif d'AGP 9.0).
4.
Connectez un appareil physique ou lancez un émulateur.
5.
Cliquez sur Run 'app'.

Aperçu:

<img width="413" height="820" alt="Screenshot 2026-05-08 180739" src="https://github.com/user-attachments/assets/53fc00bd-7723-4e2d-8190-f157add96d26" />

<img width="368" height="823" alt="Screenshot 2026-05-08 182151" src="https://github.com/user-attachments/assets/bc6df29a-bd6d-4c3a-abf7-91c95e7da9fb" />

<img width="444" height="934" alt="Screenshot 2026-05-08 182938" src="https://github.com/user-attachments/assets/c9ceb8e0-0f4a-4286-a049-a84018e018f2" />








