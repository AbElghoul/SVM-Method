# SVM-Method
• Introduction:
• Data set utiliser :
La base de donnée utiliser est une base de donnée contient des images des voitures et des bateaux
1. Importation de librairies :
Les SVMs sont une famille d’algorithmes d‘apprentissage automatique qui permettent
de résoudre des problèmes tant de classification que de régression ou de détection
d’anomalie. Ils sont connus pour leurs solides garanties théoriques, leur grande flexibilité
ainsi que leur simplicité d’utilisation même sans grande connaissance de data mining.
    
2. Les Fonction utiliser dans le prétraitement :
   3. Importation les données d’apprentissage:
L’extraction des caractéristiques et les écrire dans le fichier index001.csv
  

4. Importation les données de test:
  5. Traitement sur les données de test et d’apprentissage :
   6. La fonction Fit (apprentissage) :
 

 7. Insérer les résultats dans le fichier result.csv:
8. Le calcule du taux de test :
9. Résultat et taux de test (95%):
      

10. Conclusion :
 
Support Vector Machine (SVM) est utilisé comme classificateur linéaire ou non linéaire basé sur le noyau utilisé. Si nous utilisons un noyau linéaire, alors le classificateur et donc la limite de prédiction sont linéaires. Ici, pour séparer deux classes, nous devons tracer une ligne. La ligne est telle qu’il y a
une marge maximale. Cette ligne est tracée à égale distance des deux ensembles. Nous dessinons deux autres lignes de chaque côté, appelées vecteurs de support. Les SVM apprennent des vecteurs de support, contrairement aux autres modèles d’machine learning qui apprennent à partir des données correctes et incorrectes. Par exemple, supposons que nous ayons deux classes: les pommes et les oranges. Dans ce cas, SVM apprend les exemples qui sont les plus à droite dans les pommes (une pomme ressemblant à une orange) et les plus à gauche dans les oranges (une orange ressemblant à une pomme); c’est-à-dire qu’ils examinent les cas extrêmes. Par conséquent, ils fonctionnent mieux la plupart du temps.
