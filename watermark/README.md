# Script de watermarking pour ESN
Par David Resin, ESN EPF Lausanne, 2021-2023
[ESNTools sur GitHub](https://www.github.com/DavidResin/esntools)

## Avant l'utilisation

1. Installer Python 3.9
2. Exécuter `pip install -r requirements.txt`

## Pour utiliser

1. Insérer les images à traiter dans le dossier `input/`.
2. Exécuter le script avec la commande suivante :
   ```bash
   python watermark.py
   ```
3. Les images traitées seront sauvegardées dans le dossier `output/`. Les images invalides seront déplacées dans le dossier `invalid/`.

> [!NOTE]
> Les images déposées dans le dossier `input/` peuvent être organisées en sous-dossiers. La structure des dossiers sera préservée dans les dossiers `output/` et `invalid/`.