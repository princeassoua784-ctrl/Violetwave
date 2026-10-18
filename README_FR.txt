VIOLET WAVE — PROJET ANDROID

Le projet contient le lecteur Violet Wave dans une WebView Android et le sélecteur de fichiers audio.
Ce ZIP n'est PAS un APK compilé.

MÉTHODE RAPIDE POUR OBTENIR L'APK SANS ORDINATEUR (via GitHub Actions)
1. Sur ton téléphone, connecte-toi à GitHub et crée un dépôt (repository) vide.
2. Envoie-y le contenu de ce dossier ZIP décompressé, en gardant le dossier .github/workflows/build-apk.yml.
3. Ouvre l'onglet Actions du dépôt et sélectionne « Build Violet Wave APK ».
4. Appuie sur « Run workflow » si le build ne démarre pas automatiquement.
5. Quand le build est terminé en vert, ouvre son exécution et télécharge l'artefact « Violet-Wave-APK ».
6. Décompresse l'artefact : il contient app-debug.apk. Ouvre-le sur Android pour l'installer. Android peut demander d'autoriser l'installation depuis cette source.

COMPILATION LOCALE
Dans Android Studio, utilise Gradle 8.9, Java 17 et Android SDK 35, puis lance : gradle assembleDebug
L'APK sera normalement dans app/build/outputs/apk/debug/app-debug.apk.

La compilation n'a pas été exécutée ici. Le workflow est préparé, mais il faut l'exécuter dans GitHub pour produire et vérifier l'APK. Ne partage jamais de mot de passe ni de clé de signature.
