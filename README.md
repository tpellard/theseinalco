# README #

`theseinalco.sty` version 1.0 2024-06-11

### À propos de ce dépôt ###

Ce dépôt accueille le fichier style LaTeX pour les thèses en sciences humaines proposé dans le cadre de la formation LaTeX de l'[Inalco](http://www.inalco.fr/).

Le style respecte les directives de l'école doctorale de l'[Inalco](http://www.inalco.fr/) concernant la présentation des thèses de doctorat, mais il est prévu pour pouvoir être adapté à des mémoires de master ou d'habilitation, et aux travaux réalisés dans d'autres institutions.

La présentation est volontairement sobre et adopte des marges généreuses.

### Particularités ###

* de nombreux champs de métadonnées à remplir permettent de réaliser automatiquement une page de titre mentionnant toutes les informations requises (université, école doctorale, discipline, diplôme, titre, auteur, date, directeur, rapporteurs, jury…)
* prise en charge du cas des thèses en cotutelle

### Prérequis ###

* un système LaTeX récent
* la classe `scrbook`
* les extensions `scrhack`, `setspace`, `tabularray`, `tocbasic`

### Fichiers ###

* `theseinalco.sty`: le fichier style
* `modele.tex`: un exemple d'utilisation avec XeLaTeX et la police libre [Linux Libertine](http://www.linuxlibertine.org/)
* `inalco-logo-color.pdf`: le fichier image du logo de l'[Inalco](http://www.inalco.fr/)
* `modele.pdf`: le résultat de l'exemple d'utilisation

### Mode d'emploi ###

* télécharger le fichier `theseinalco.sty` et le placer dans le même dossier que le fichier `.tex` ou bien dans un dossier que LaTeX peut trouver
* déclarer `\usepackage{theseinalco}` dans le document `.tex`, de préférence au début du préambule, et dans un document de classe `scrbook`
* consulter l'exemple `modele.tex` pour voir notamment comment remplir les métadonnées

### Problèmes et suggestions ###

N'hésitez pas à me contacter (Thomas Pellard, <thomas.pellard@cnrs.fr>) en cas de problème ou pour me suggérer des améliorations.
