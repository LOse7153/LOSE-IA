# LOSE IA

Application Android de prédiction football.

## Principes
- Aucun match, score ou statistique ne doit être inventé.
- Les matchs réels seront fournis par une source sportive/API autorisée.
- Les matchs virtuels restent séparés des matchs réels.
- Les prédictions sont probabilistes et ne constituent pas des garanties.

## Contenu prévu
- Matchs du lundi au dimanche
- Analyse IA
- Score exact probable
- 1N2
- Over/Under
- Corners
- Cartons jaunes
- Tirs cadrés
- 1re et 2e mi-temps
- Confiance
- Live
- Virtuels
- IA TIPSTER
- TIPS GOS
- Historique prédiction/résultat

## Construire l'APK avec GitHub
Le dépôt contient un workflow GitHub Actions dans `.github/workflows/build-apk.yml`.
Après avoir envoyé ce projet dans un dépôt GitHub, ouvre l'onglet **Actions**, lance le workflow
et récupère l'APK dans les **Artifacts**.

La connexion à une API sportive réelle devra être ajoutée avant de considérer l'application comme
alimentée par des matchs en temps réel.
