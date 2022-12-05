# Kaggle_Competition_Salary_Prediction

### OBJETIVO 
- Preparar los datos para los diversos modelos (proceso empírico)
- Entrenar y Testear modelos de Machine Learning
- Subir los resultados con el mejor modelo entrenado de Machine Learning
- Hacer pull request con la presentación en la carpeta de 'PPTS'
- Crear repo propio del proyecto (issue)

### WORK PROCESS
- Importación de ficheros Salaries_data.csv (datos para trabajar) y Testeo.csv (datos para predecir)

##### PREPARACIÓN DE DATOS - EXPLORACIÓN, LIMPIEZA Y TRANSFORMACIÓN
- Exploración de datos. EDA process.
- Limpiezas realizadas:
    - Job_title - Categorización de columna en 3 job_tytles: Data Analyst, Data Engineer y Data Scientist.
    - Employee residence - Categorización de columna en 8 posibles valores.
    - Company location - Categorización de columna en 8 posibles valores.
    - Eliminación de Outliers.
- En base al salario medio total, se ha calculado la diferencia del salario medio de cada categoría y se ha incluido una nueva columna con el coeficiente resultante.
- Transformación de columnas:
    - Categóricas - Se aplica label encoding para preparar los datos para el modelo de predicción a utilizar.
    - Numéricas - Se normalizan los datos.
    
##### MACHINE LEARNING
- Definición del modelo de Machine Learning - Se crea una función para definir los errores de cada modelo (rmse, mae y r2).
- Se escoge el modelo que menos error tiene.
- Se entrena el modelo y se crea predicción para subir a la competición de Kaggle.

    