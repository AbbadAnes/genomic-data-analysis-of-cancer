<h1>Genomic-data-analysis-of-cancer</h1>
<p align="center">
  <img src="https://storage.googleapis.com/kainofreelancerpictures/anes/10.logo-ueve.jpg" width="50%" title="logo">
</p>

Some genes, which play a regular role throughout our lives, can
mutate. This disturbance is sufficient for the appearance of cancer cells, which makes gene expression is a very important element in the diagnosis of neoplastic diseases.
Today it is possible to predict the type of cancer cells based on
on their genetic expressions but tumors produce a huge amount
of genes, which makes the classification of cancer types difficult.
The purpose of the project is to complete clinical diagnoses by classifying cancerous tumors from their genetic expressions, using statistical methods and machine learning.
<h2> Tools : </h2>
Python ( Sickit-Learn ) , R , Atlas Data, The Cancer Genome Atlas Program
<h2>Données</h2>
56,000 genes
6700 Patients
<h2> Treated cancers </h2>
- Breast cancer
<br>
- Prostate cancer
<br>
- Skin cancer
<br>
- Lung cancer
<br>
- Mouth cancer
<br>
- Bladder cancer
<br>
- Thyroid cancer
<br>
- Bronchial and lung cancer
<br>
- Low grade gongomas
<br>
- Kidney cancer
<br>
<h1> Data Analysis </h1>
<h2> Analysis of variance (ANOVA) </h2>
<p>
  Using the ANOVA statistical test we managed to extract the best genes to better predict the cancer type of a patient
</p>
<p align="center">
  <img src="https://storage.googleapis.com/kainofreelancerpictures/anes/best.png" title="learning curve">
</p>

237/5000
we see that the highest "ENS" gene that has obtained the highest score and therefore (the smallest P-value) is not used to predict the different types of cancer, but rather it is the preaching predictor of "LGG" cancer ( low grade giloma)

<h1>Learning</h1>
<h2>Algorithm</h2>
<p align="center">
  SVM ( Support Vector Machine )
  <br><br>
  <img src="https://zestedesavoir.com/media/galleries/3985/5128cf36-de17-4ebb-9495-90c9d85f006f.png" width="350" title="hover text">
</p>
<h1>Performance</h1> 
<h2>Accuracy</h2>
Accuracy = # correct predictions / # total predictions
<br>
<strong> Accuracy = 98% </strong>
<h2>Learning curves</h2>
<h4>Depending on the genes/h4>
<p align="center">
  <img src="https://storage.googleapis.com/kainofreelancerpictures/anes/g%C3%A8nes.png" title="learning curve">
</p>
<h4>Depending on the patients</h4>
<p align="center">
  <img src="https://storage.googleapis.com/kainofreelancerpictures/anes/PATIENT.png" title="learning curve">
</p>
<h2>how to use the code?</h2>
1. Clone the project and uncompress code.rar
<br>
2. In the R folder you will find the necessary scripts to get the data from the TCGA platform
<br>
3. In the Python folder you find a visualization.py file to visualize the data, and a second implementation.py file that contains all the steps of the project.
<h2> Contributionz</ h2>
<h3> Project realized by: </ h3>
- Anes Abdelfatah ABBAD.
<br>
- Amira KETFI.
<br>
- Pope Wade DAOUDA
<br>
<h3> Supervised By: </h3>
- Blaise Hanczar.
<h3> Thank's to </h3>
  - Houda ABBAD.
  <br>
  - Ahmed SAADALLAH
