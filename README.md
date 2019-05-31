<h1>Genomic-data-analysis-of-cancer</h1>
Certains gènes, qui jouent un rôle ordinaire tout au long de notre vie, peuvent
muter. Ce dérèglement suffit à l’apparition des cellules cancéreuses, ce qui rend

l’expression génétique un élément très important dans le diagnostique des mala-
dies néoplasiques.

Aujourd’hui il est possible de prédire le type des cellules cancéreuses en se basant
sur leurs expressions génétiques, or les tumeurs produisent une énorme quantité
de gènes, ce qui rend la classification de ces dernières difficile.
Le but du projet consiste à compléter les diagnostics cliniques en classifiant les

tumeurs cancéreuses à partir de leurs expressions génétiques, en utilisant les mé-
thodes statistiques et d’apprentissage automatique.
<h2> Basé Sur : </h2>
Python ( Sickit-Learn ) , R , Atlas Data, The Cancer Genome Atlas Program
<h2>Données</h2>
56,000 gènes
6700 Patients
<h2>Cancers traités</h2>
- Cancer du sein
<br>
- Cancer du Prostate
<br>
- Cancer de la peau
<br>
- Cancer du paumon
<br>
- Cancer de la Bouche
<br>
- Cancer de la vessie
<br>
- Cancer de la thyroide
<br>
- Cancer des bronches et du poumon
<br>
- Gilomes de bas grade
<br>
- Cancer du rein
<br>
<h1>Analyse de données</h1>
<h2>Analyse de la variance ( ANOVA )</h2>
<p> 
 En utilisant le test statistique ANOVA nous avons réussi à extraire les meilleurs gènes pour prédire au mieux le type de cancer d'un patient
</p>
<p align="center">
  <img src="https://storage.googleapis.com/kainofreelancerpictures/anes/best.png" title="learning curve">
</p>
la on voit que le meilleiur gène "ENS" qui a obtenu le score le plus élevé et donc ( la plus petite P-value ) ne sert pas à prédire les differents types de cancers mais plutot c'est prédicteur prafait du cancer "LGG" ( gilome du bas grade )

<h1>Apprentissage</h1>
<h2>Algorithme utilisé</h2>
<p align="center">
  SVM ( Support Vector Machine )
  <br><br>
  <img src="https://zestedesavoir.com/media/galleries/3985/5128cf36-de17-4ebb-9495-90c9d85f006f.png" width="350" title="hover text">
</p>
<h1>Performance</h1> 
<h2>Accuracy</h2>
Accuracy = # prédictions correctes / # prédictions totales
<br>
<strong> Accuracy = 98% </strong>
<h2>Courbes d'apprentissage</h2>
<h4>En fonction des gènes</h4>
<p align="center">
  <img src="https://storage.googleapis.com/kainofreelancerpictures/anes/g%C3%A8nes.png" title="learning curve">
</p>
<h4>En fonction des patients</h4>
<p align="center">
  <img src="https://storage.googleapis.com/kainofreelancerpictures/anes/PATIENT.png" title="learning curve">
</p>
<h2>Comment utiliser le code ?</h2>
1. Clonez le projet et decompressez code.rar
<br>
2. Dans le dossier R vous trouverez les scripts nécessaires pour récuperer les données à partir de la platforme TCGA
<br>
3. Dans le dossier Python vous trouvez un fichier visualisation.py pour visulaiser les données, et un deuxième fichier implementation.py qui contient toutes les étapes de la réalisation du projet.
