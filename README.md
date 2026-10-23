# Publication GitHub Pages

Ce dossier contient la version prête à publier du site HC Project. Il n'y a ni compilation ni dépendance à installer.

## Fichiers

- `index.html` : page d'accueil du site.
- `Assets/` : images utilisées par la page.

## Publication

1. Ouvrez votre dépôt GitHub et choisissez **Add file > Upload files**.
2. Téléversez `index.html`, `README.md`, `CNAME` et le dossier `Assets/` depuis ce dossier, à la racine du dépôt. Ne téléversez pas le dossier `github-pages` lui-même comme sous-dossier.
3. Validez avec **Commit changes** sur la branche `main`.
4. Dans le dépôt, ouvrez **Settings > Pages**.
5. Sous **Build and deployment**, choisissez **Deploy from a branch**, puis `main` et `/(root)`, et cliquez sur **Save**.
6. Sous **Custom domain**, saisissez `hc-project.fr`, puis cliquez sur **Save**. Activez **Enforce HTTPS** dès que GitHub le propose.
7. Dans la gestion DNS de votre nom de domaine, créez quatre enregistrements **A** pour `@`, pointant respectivement vers `185.199.108.153`, `185.199.109.153`, `185.199.110.153` et `185.199.111.153`. Supprimez les anciens enregistrements A qui entreraient en conflit.
8. Attendez la propagation DNS; l'adresse publique sera `https://hc-project.fr`.

La page originale `HC-Project-Welcome-KM-Counter.html` du projet n'a pas été renommée ni modifiée par la préparation de ce paquet.
