# Poème du jour (Android)

## Obtenir l'appli
1. Sur github.com : **+ → New repository**, nom `poeme-du-jour`, **Public ou Private**, créer.
2. **uploading an existing file** : glissez TOUT le contenu de ce dossier (dont `www`, `package.json`, `capacitor.config.json`, `.gitignore`).
3. Le dossier caché `.github` peut ne pas se glisser : cliquez **Add file → Create new file**, tapez `.github/workflows/build.yml` comme nom, collez le contenu du fichier `build.yml`, puis **Commit**.
4. Onglet **Actions** : la construction démarre seule (5 à 10 minutes). Si besoin : *Construire l'APK → Run workflow*.
5. Quand elle est verte, allez dans **Releases** (colonne de droite du dépôt) et téléchargez `poeme-du-jour.apk` depuis votre téléphone.
6. Ouvrez le fichier ; Android demande d'autoriser l'installation depuis ce navigateur : acceptez.
7. À l'ouverture, autorisez les notifications. Puis ajoutez vos PDF et vos horaires dans les réglages.

## Mettre à jour
Remplacez `www/index.html` dans le dépôt : un nouvel APK est construit automatiquement.
