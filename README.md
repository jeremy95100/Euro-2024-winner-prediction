# Euro 2024 Prediction

Ce projet vise à prédire le vainqueur des matchs de l'Euro 2024 en utilisant la théorie des probabilités de Poisson. La méthode repose sur l'hypothèse que le nombre de buts marqués par chaque équipe dans un match de football peut être modélisé en utilisant une distribution de Poisson.

## Comment ça marche ?

La prédiction du vainqueur d'un match se fait en utilisant les probabilités de Poisson pour estimer le nombre de buts marqués par chaque équipe. Ensuite, en comparant les estimations de buts marqués des deux équipes, on détermine la probabilité de chaque résultat possible (victoire de l'équipe à domicile, victoire de l'équipe à l'extérieur, match nul). Finalement, la probabilité d'une équipe de gagner est calculée en fonction des probabilités de chaque résultat.

## Comment utiliser le code ?

1. Assurez-vous d'avoir Python installé sur votre système.
2. Clonez ce dépôt sur votre machine.
3. Installez les dépendances en exécutant `pip install -r requirements.txt`.
4. Utilisez les fichiers de données disponibles pour entraîner le modèle ou utilisez vos propres données.
5. Exécutez le script principal pour faire des prédictions.


## Exemple d'utilisation

```bash
python src/main.py
