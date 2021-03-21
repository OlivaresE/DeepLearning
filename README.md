# DeepLearning
Prácticos materia optativa Deep Learning @ Diplo Datos Cohorte 2020/2021

El repositorio cuenta con tres (3) Notebooks desarrolladas en Colaboratory y sus correspondientes archivos de MlFlow. En ellas se prueban los siguientes tres experimentos sobre el dataset del MeLiChallenge del año 2019:

1) CNN sobre la totalidad del dataset: https://colab.research.google.com/drive/1qkkS470CW5vZxDGqXmHVjzV_NW2m_bCQ?usp=sharing
2) CNN sobre un dataset reducido en un órden de magnitud: https://colab.research.google.com/drive/1icfjrmtvigbYJFpHfW81P01E6GaL-vQd?usp=sharing
3) MLP sobre un dataset reducido en un órden de magnitud

En general, se trabajó sobre un dataset reducido por las limitaciones de hardware que ofrece el Colaboratory. Las pruebas se vuelven tediosas y lentas y un error pequeño de código
puede significar mucho tiempo perdido ya que cada operación sobre los datos conlleva un tiempo considerable.
Pudo correrse el modelo CNN con una baja cantidad de épocas sobre el dataset completo para evaluar la performance vs el modelo sobre el dataset con dataset reducido.
Se usó como parámetro de evaluación del modelo el balanced accuracy (bacc en los notebooks) y se observó:
1) Al contrario de lo esperado, el bacc aumenta entre iteraciones de épocas.
2) Se obtienen valores bajos del parámetro.

Se pudo cumplir con los requisitos de la materia, implementando modelos reales sobre el dataset. Los problemas centrales tuvieron que ver con la imposibilidad técnica de probar en
tiempo los modelos en Nabucodonosor y el límite de hardware de Colaboratory. También, se observó que el desempeño de los modelos simples como el MLP y CNN con parámetros 
básicos es bastante pobre.
