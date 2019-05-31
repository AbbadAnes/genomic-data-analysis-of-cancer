<h1>Genomic-data-analysis-of-cancer</h1>
Utilisation des données génétiques des patients pour prédire les types de cancer
<h2> Basé Sur : </h2>
Python ( Sickit-Learn ) , R , Atlas Data, The Cancer Genome Atlas Program
<h2>Données</h2>
56,000 gènes
6700 Patients
<h2>Cancers traités</h2>
- Cancer du sein
- Cancer du Prostate
- Cancer de la peau
- Cancer du paumon
- Cancer de la Bouche
- Cancer de la vessie
- Cancer de la thyroide
- Cancer des bronches et du poumon
- Gilomes de bas grade
- Cancer du rein
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
<h2>Courbe d'apprentissage</h2>
<h4>En fonction des gènes</h4>
<p align="center">
  <img src="https://storage.googleapis.com/kainofreelancerpictures/anes/g%C3%A8nes.png" title="learning curve">
</p>
<h4>En fonction des patients</h4>
<p align="center">
  <img src="https://storage.googleapis.com/kainofreelancerpictures/anes/PATIENT.png" title="learning curve">
</p>

