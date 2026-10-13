# Caisse Agri-Garden

Caisse de vente de sapins pour tablette Android. Elle fonctionne hors ligne une fois installée.

## Mise en ligne sur GitHub Pages (une seule fois)

1. Connectez-vous sur https://github.com.
2. Cliquez sur **New** (nouveau dépôt) :
   - Repository name : `caisse-sapins`
   - Cochez **Public**
   - Cliquez sur **Create repository**
3. Sur la page du dépôt, cliquez sur **uploading an existing file** (ou **Add file → Upload files**).
4. Dézippez `caisse-sapins-github.zip` sur votre PC, puis glissez **tout le contenu** dans la page :
   `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` et le dossier `icons`.
5. Cliquez sur **Commit changes**.
6. Allez dans **Settings → Pages** :
   - Source : **Deploy from a branch**
   - Branch : **main**, dossier **/ (root)**
   - Cliquez sur **Save**
7. Attendez 1 à 2 minutes. L'adresse s'affiche en haut de la page Pages :
   `https://<votre-compte>.github.io/caisse-sapins/`

## Installation sur une tablette

1. Connectez la tablette à internet (wifi ou partage de connexion).
2. Ouvrez l'adresse dans **Chrome**.
3. Menu **⋮ → Installer l'application** (ou **Ajouter à l'écran d'accueil**).
4. Lancez l'app depuis l'icône Agri-Garden.
5. Dans **Paramètres de la tablette** :
   - **Charger un catalogue…** et choisissez le fichier `catalogue.json` ;
   - choisissez le **point de vente** de la tablette, puis **Enregistrer**.

À partir de là, l'app fonctionne sans internet.

## Mettre à jour l'app

Remplacez les fichiers sur GitHub (**Add file → Upload files**, puis **Commit**).
Les tablettes prennent la nouvelle version la prochaine fois qu'elles ouvrent l'app avec du réseau.

## Mettre à jour les prix ou les produits

Pas besoin de toucher à GitHub. Envoyez le nouveau `catalogue.json` sur la tablette, puis chargez-le via **Paramètres de la tablette → Charger un catalogue…**.

## Bonnes pratiques

- Exportez les ventes au moins **deux fois par jour** (midi et soir) : menu **⋮ → Exporter / partager les ventes du jour**.
- N'effacez jamais les données de Chrome sur les tablettes de caisse.
- Une tablette = un point de vente.
