# Simulation du théorème de Poncelet

Ce projet propose une série de simulations interactives autour du **théorème de Poncelet**, réalisées dans le cadre d'un TIPE (classe de MP, 2025). Il s'agit d'explorer visuellement les trajectoires de polygones fermés dans différents types de "billards" géométriques : cercle, ellipse…

---

## Contenu du projet

Le notebook simule successivement :

1.  Des trajectoires dans un **billard circulaire**.
2.  Des trajectoires dans un **billard elliptique**.
3. L’évolution du paramètre de Poncelet quand on translate **l’ellipse intérieure** (selon Ox puis Oy) dans une configuration donnée.

Chaque partie inclut des **visualisations graphiques** (PDF) ainsi que des **animations GIF** qui illustrent le comportement des trajectoires.

---

## Exemples de rendus

- `plot(30).pdf` : visualisation d’une trajectoire dans un billard circulaire.
- `plot(31).pdf` : visualisation d’une trajectoire dans un billard elliptique.
- `animation_poncelet (1).gif`, `animation_poncelet (2).gif` : évolution du paramètre de Poncelet en fonction de la position de l’ellipse intérieure.

---

## Bibliothèques utilisées

Ce projet utilise les bibliothèques suivantes :

- `numpy`
- `matplotlib.pyplot`
- `matplotlib.patches`
- `imageio.v2`
- `IPython.display`
- `base64`
- `os`
- `math`

---

## Utilisation

Ce projet se présente sous forme d’un **notebook Jupyter** :

1. Ouvrir le fichier `poncelet_simulation.ipynb` dans un environnement Jupyter (ou sur [Basthon](https://notebook.basthon.fr)).
2. Exécuter les cellules dans l’ordre pour générer les figures et les animations.
3. Les GIFs sont sauvegardés et un lien de téléchargement est proposé via l'interface Basthon.

---

## Fichiers importants

- `poncelet_simulation.ipynb` – notebook principal contenant les simulations.
- `animation_poncelet (1).gif`, `animation_poncelet (2).gif` – animations générées automatiquement.
- `plot(30).pdf`, `plot(31).pdf` – figures statiques enregistrées.

---

## À propos

Projet réalisé dans le cadre du **TIPE** (Travaux d'Initiative Personnelle Encadrés), filière MP 2025. Ce travail m’a permis de mettre en œuvre des compétences en **algorithmique**, **visualisation mathématique** et **programmation scientifique**, en lien avec mes intérêts en **informatique et géométrie algorithmique**.

---

## Contact

N'hésitez pas à me contacter si vous avez des questions ou suggestions à propos du projet.
