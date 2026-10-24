scraper-livres-excel# Scraper de catalogue vers Excel

Script Python qui récupère automatiquement les données d'un catalogue
en ligne et les exporte dans un fichier Excel prêt à l'emploi.

## Ce qu'il fait
- Parcourt les 50 pages du catalogue
- Extrait titre, prix, note, disponibilité et lien de chaque livre
- Convertit les prix en nombres (filtrables dans Excel)
- Exporte `livres.xlsx` + affiche un résumé
- Pause entre les requêtes pour ne pas surcharger le site

## Utilisation
```bash
pip install -r requirements.txt
python scraper.py
```

## Exemple de résultat
![Capture du fichier Excel](capture.png)

1000 livres récupérés, prix moyen 35.07 £, note moyenne 2.92 / 5.

*Démo réalisée sur books.toscrape.com, un site prévu pour s'entraîner.*

## Besoin d'un scraper sur mesure ?
Contact : Contactez-moi via mon profil GitHub
