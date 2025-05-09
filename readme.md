#  Projet R : Analyse de la composition d'une séquence ADN

Ce projet propose une petite analyse bioinformatique en R, visant à étudier la fréquence des nucléotides dans une séquence ADN au format FASTA.

---

## Fichiers inclus

- `analyse_nucleotides.Rmd` : Rapport R Markdown complet (code, graphiques, commentaires)
- `sequence_test.fasta` : Exemple de séquence ADN

---

## Fonctionnalités

- Lecture de fichier FASTA avec Biostrings
- Comptage des bases A, T, C, G
- Visualisation : barplot (`ggplot2`) et pie chart (`pie()`)
- Sauvegarde automatique du pie chart au format PNG
- Rapport généré en `.html` via R Markdown

---

## Lancer le projet

### Prérequis :

```r
install.packages("ggplot2")
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("Biostrings")

##  Auteure

Rim Hamouda 

[🔗 https://www.linkedin.com/in/rim-hamouda-b33992214/) | (https://github.com/RimHamouda)
