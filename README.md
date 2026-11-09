# Student Planner – Groupe 7
Application web hors ligne (HTML/CSS/JS) empaquetée en Android avec Capacitor.

## Tester dans le navigateur
Ouvrir `www/index.html` (ou : `npx serve www`).

## Générer l'application Android
npm install
npx cap add android
npx cap sync android
npx cap open android
Puis dans Android Studio : Build > Build APK(s).
Après toute modification de `www/` : `npx cap sync android`.
