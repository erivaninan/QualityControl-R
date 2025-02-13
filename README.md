# QualityControl-R 🌟

Ce répertoire a été conçu dans le cadre d'un cours de contrôle qualité délivré en M2 à Sorbonne Université.
L'entièreté du répertoire a été codé en langage R.

Il contient 4 TD ainsi qu'un projet, couvrant les thèmes suivants : 

Voici la liste des fichiers et leur description :

- **`1. TD Tests`**
Consigne : Simulation d'une loi (dans mon cas la loi uniforme sur [0,3]), puis application des tests statistiques :
   1) avec H0 proche de la vérité
   2) avec H0 loin de la vérité
  
Après avoir effectué les tests statistique, faire varier n (= taille de l'échantillon), répéter M fois (simulation et test) pour analyser les probabilités empiriques de test et de rejet.

- **`2. TD Cartes de contrôle`**
  Construction de cartes x̄ et R pour suivre la stabilité d’un processus.
  Étude de la normalité des données via QQ plot.
  Cartes de non-conformité (p, c, t) et utilisation des lois binomiale et de Poisson.
  Estimation et comparaison de l’écart-type avec différentes méthodes.
  Capabilité du processus et calcul du Cpk.
  
- **`3. TD CUSUM`**
   Construction et analyse de cartes CUSUM pour détecter des dérives.
   Comparaison avec cartes EWMA et moyenne mobile.
   Étude de l’auto-corrélation et son impact sur la surveillance du processus.
   Utilisation de modèles AR(2) pour améliorer la détection des dérives.

- **`4. TD Échantillonnage`**
   Plans d’échantillonnage (simple, progressif, multiple).
   Utilisation de la loi de Poisson pour estimer les risques d’acceptation/rejet d’un lot.
   Comparaison entre contrôle quantitatif et qualitatif (ex : mesures directes vs tests par calibres).
   Évaluation des risques α (acheteur) et β (fournisseur) pour les décisions d’acceptation.

- **`Projet`**
   Analyse statistique pour le contrôle qualité de données environnementales : Étude de la particule de monoxyde de carbone (CO) dans l'air dans la région de Paris en 2023 et 2024.
   Étude de séries temporelles de pollution issues d’une station régionale (Atmo-France).
   Tests statistiques sur la moyenne, variance, médiane et quantiles (Wilcoxon, Mann-Whitney, Cox-Stuart).
   Validation des distributions par tests d’adéquation et étude de la corrélation. Définition d’un protocole de contrôle qualité et vérification de la stabilité des données.

---

### Auteur

Erivan INAN
