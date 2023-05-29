# M11_Projecte-Final: Predicción de resultados de fútbol de la primera división española con ML

Key words: #Python, #ML supervisado, #Regresión, #Clasficación #Metricas de avaluación, #Balanceo #GridSearch #RandomSearch #PCA

Librerías usadas: Numpy, Pandas, Matplot, Seaborn, Scikit-learn, 

Modelos de ML usados
    a) Regresión: SVR, KNR, LR
    b) Clasificación: KNN, DTC, SVC, KNC, LogisticRegression
    
BBDD: original de BDFutbol
    a) Features: Variables subjetivas según mi parecer.
    b) Target: Goles Locales y Goles Visitantes (Regresión), Resultado partido (1-Victoria Local, 2-Victoria Visitantes, 3-Empate
    
Métricas para avaluar los modelos
    a) Regresión: MAE, R2
    b) Clasificación: Matriz de Confusión, Classification report, F1_micro
    
Búsqueda de mejorar el modelo: Hiperparametros, PCA, Balanceo
