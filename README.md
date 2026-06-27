# Predicción de *Attrition*

La salida voluntaria de empleados representa un desafío para las organizaciones, ya que genera costos adicionales de reemplazo, capacitación e integración de nuevo talento; afectación en la continuidad operativa y la productividad del equipo; así como pérdida de conocimiento institucional. De modo que desarrollar modelos predictivos capaces de identificar anticipadamente a los colaboradores con mayor riesgo de abandono resulta de interés para orientar estrategias de retención y optimizar la gestión del talento humano.

En este sentido, el presente análisis tiene como objetivo desarrollar y comparar distintos modelos de aprendizaje supervisado para la predicción de la rotación voluntaria de empleados a partir de variables demográficas, laborales, salariales y de satisfacción organizacional, contenidas en el conjunto de datos *IBM HR Analytics Employee Attrition*, descargado de [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset).

Los modelos desarrollados fueron:

- Modelos de regresión logística con regularizaciones Lasso y Ridge.
- Modelos de ensamble como Bosques aleatorios, AdaBoost y XGBoost.
- Redes neuronales MLP.

Tras evaluar su desempeño, XGBoost resultó la alternativa más adecuada para apoyar la identificación temprana de empleados con más riesgo de abandonar la compañía, para así contribuir al diseño de estrategias preventivas de retención. Este modelo logró identificar correctamente del conjunto de prueba al 74% de empleados que abandonaron la compañía, alcanzando además, una precisión del 60%.

Notas:

- El código y el análisis se pueden consultar en el jupyter notebook [ProyectoFinal_Mod5.ipynb](). 
- El conjunto de datos se encuentra en el archivo [WA_Fn-UseC_-HR-Employee-Attrition.csv](WA_Fn-UseC_-HR-Employee-Attrition.csv).  
- Los paquetes necesarios para poder ejecutar el código pueden encontrarse en el archivo [requirements.txt](requirements.txt).

Autores:

- Brenda Poulette Torres Vargas
- Diego Betancourt Peralta
- Erick Iván Canul Hernández
- José Omar Gutiérrez Gutiérrez
- Maximiliano Hernández Pérez
