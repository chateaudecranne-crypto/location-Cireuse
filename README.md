# Déploiement sur GitHub Pages

## Étapes

1. Créez un compte sur https://github.com/
2. Créez un nouveau dépôt public, par ex. `cireuse-landing`
3. Cliquez **Add file → Upload files** et glissez tout le contenu de ce dossier :
   - index.html
   - dossier `images/` (avec vos photos renommées)
   - README.txt
4. Cliquez sur **Commit changes**

## Activer GitHub Pages
1. Allez dans l’onglet **Settings** de votre dépôt
2. Descendez dans la section **Pages**
3. Choisissez **Deploy from a branch**
4. Sélectionnez la branche `main`, dossier `/root`
5. Sauvegardez

GitHub va générer votre site à l’adresse :
```
https://VOTRE_PSEUDO.github.io/cireuse-landing/
```

## Remplacer les images
- `images/cireuse-action.jpg` → photo bouteille plongée dans la cire
- `images/cireuse-machine.jpg` → photo de la machine seule
- `images/cireuse-utilisation.jpg` → photo en situation (utilisation)
- `images/logo.svg` → votre logo (SVG ou PNG)
- `images/og-image-cireuse-cir22.jpg` → image de partage pour réseaux sociaux

Remplacez ces fichiers par vos photos réelles (gardez les mêmes noms).



## Brancher le formulaire (Formspree – sans code)
1. Allez sur https://formspree.io → Create form → choisissez "Classic".
2. Copiez l'URL de votre formulaire, par ex. `https://formspree.io/f/abcdwxyz`.
3. Ouvrez `index.html` et remplacez l'attribut `action="https://formspree.io/f/xxxxxxxx"` par votre URL.
4. Cliquez "Test form" dans Formspree si besoin pour valider l'email.
5. Les messages arriveront directement dans votre boîte e‑mail.
