Ce repository est un projet étudiant (M1-Centrale Nantes-DataScience) qui vise à mettre en application sur un jeu de données des méthodes d inférence Bayesienne
Le jeu de données utilisé, dénommé "eyes" présente pour plusieurs singes la logueur d'onde la mieux capté par une partie de leur oeil 

L'enjeu de l'étude est d'écrire un algorithme de Markov Chain Monte Carlo (MCMC) permettant de simuler des variables aléatoires selon le modèle que l'on suppose sur les données : 
Une mixture gaussienne à deux composantes 

"eyes_explications.pdf" contient l'énoncé du sujet  
"gibbs.qmd" contient le code de l'echantillonneur à proprement parler   
"projet_bayes_rapport.pdf" contient une explication de l'étude, les maths necessaires à l'echantilloneur, ainsi que les conclusions au vu des resultats  
"Validation du modème ME" illustre, par une méthode à noyeaux, la pertinence d'un mélange gaussien comme modèle    
"tests_MH" contient les tests effectués pour ajuster au mieux les paramètres de l'algo MH
