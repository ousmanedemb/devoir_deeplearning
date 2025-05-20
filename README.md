
Prédiction du Niveau d'Expérience avec BERT
==============================================

Ce projet utilise **BERT** pour prédire le **niveau d'expérience requis** à partir de la **description d'une offre d'emploi**.  
Une interface **Gradio** permet de tester le modèle facilement.

📁 Fichiers importants
----------------------
- fake_job_postings 2.csv : jeu de données avec descriptions d'offres et niveaux d'expérience.
- devoir_deeplearning.ipynb : Notebook Python pour entraîner BERT et lancer Gradio.
- requirements.txt : bibliothèques à installer.

Lancer le projet
-------------------
1. Installer les dépendances :

    pip install -r requirements.txt

2. Lancer le noteboot :

    devoir_deeplearning.ipynb

3. Une interface Gradio s'ouvrira dans ton navigateur.

🔧 Technologies utilisées
-------------------------
- BERT (bert-base-uncased)
- Transformers (HuggingFace)
- PyTorch
- Gradio
