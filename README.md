# Prevision_series_chronologiques

j'ai travaille sur une série chronologique mensuelle (Indice de chiffre d'affaires - Commerce et réparation de motocycles) comportant 272 observations, non corrigées, le but de ce projet est de prédire la série pour l'année à venir.

Au debut, j'ai écrit une introduction qui comprenait une brève présentation de la série, indiquait la source exacte des données et fournissait une infographie de haute qualité.

Partie consacrée aux méthodes de décomposition: Un tableau de Buys-Ballot  a été constitué. Différentes méthodes d'analyse ont été utilisées pour déterminer une tendance globale, pour désaisonnaliser la série. j'ai découpé la série brute en un échantillon d’estimation et un échantillon de prévision (comportant les 12 dernières observations).

Partie consacrée au lissage : Sur l’échantillon d’estimation, j'ai appliqué sur la série brute la méthode de Holt, la méthode de Holt-Winters additive et la méthode de Holt Winters multiplicative. Les constantes de lissage sont améliorés pour le MAPE grâce au solveur. La valeur finale des constantes obtenues est donnée, ainsi que le MAPE correspondant. Pour chaque méthode, J'ai fait un graphique sur l'échantillon d'estimation représentant les valeurs prédites et les valeurs observées.La meilleure méthode a été choisi. j'ai appliqué cette meilleure méthode de lissage à la prévision des douze dernières données et j'ai calculé le MAPE sur ces 12 données.

Partie consacrée à la méthode de Box-Jenkins : Sur l’échantillon d’estimation, j'ai sélectionné le meilleur modèle ARMA en explicitant mon raisonnement et en détaillant mon stratégie d’estimation. Tous les tests nécessaires a été montré.j'ai appliqué le modèle pour la prévision des douze dernières données et j'ai présenté le MAPE correspondant.

Conclusion : j'ai construit un  tableau final donnant les prévisions par la meilleure méthode de lissage et par le meilleur modèle de Box et Jenkins et ensuite j'ai trouvé la meilleure méthode.
