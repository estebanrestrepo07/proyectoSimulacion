# Proyecto Simulación

El siguiente repositorio contiene la base de datos y el script
para la realización de los puntos requeridos en el proyecto

* La base de datos puede ser obtenida directamente del respositorio dentro de la carperta db o en el siguiente enlace https://www.kaggle.com/saurograndi/airplane-crashes-since-1908/notebooks
* El script-Notebook se encuentra en el folder Notebooks con nombre *proyectoSimulacion.ipynb*


> *El script esta pensado para ejecutarse en orden de arriba hacia abajo.*
> *El script esta separado por secciones para que se comprenda de forma adecuada y corresponda a los puntos del proyecto*

### Inicio e Importación de librerias

En esta primera sección donde se indica el titulo del proyecto y los integrantes que lo componen
están el scripts que corresponde a las importaciones de las librerias necesarias para la 
realización del proyecto

### Introducción y configuración

Para esta sección del script es donde (cada punto representa el codigo que se debe ejecutar en ese orden:
* Se lee la base de datos 
* Se verifican el porcentaje de valores nulos que tiene cada columna de la base de datos
* Se eliminan aquellas columnas que tienen alto porcentaje de valores faltantes o que son irrelavantes para el proyecto
* Se llenan y/o actualizan las columnas que contienen valores *NaN* y que serán usadas en el proyecto y adicional se crea una columna extra correspondiente al porcentaje de fatalidad
* Con fin de ilustrar se agregó información respecto a los operadores con mayor número de accidentes
* Con fin de ilustrar se agregó información respecto a los lugares más peligrosos
* En este punto de código se creara un dataset de serie correspondiente a los niveles de fatalidad para abordar el problema de clasificacion
* Ilustramos el dataset con el que se trabajará

> *Las siguientes 5 secciones correspondientes a los modelos que se van a trabajar*
> *pueden ser ejecutadas en difenrente orden*
### Analisis Discriminante Cuadrático
Para esta sección del script es donde se desarrollará el QDA (cada punto representa el código que se debe ejecutar en ese orden):
* Código con la función del experimento del QDA
* Ejecutar la funcion para expemerimentar el QDA y asignar el mejor QDA para la tabla de resultados final

### Ventana de Parzen (Metodo kernel)
Para esta sección del script es donde se desarrollará el QDA (cada punto representa el código que se debe ejecutar en ese orden):
* Código que contiene las funciones de errorClass, kernel_gaussiano, parzenWindow y parzenClass
* Código con la función del experimento de Parzen
* Ejecutar la función para expemerimentar Parzen y asignar el mejor resultado para la tabla de resultados final

### Gradient Boosting Tree (GBT)
Para esta sección del script es donde se desarrollará el Gradient Boosting Tree (GBT) (cada punto representa el código que se debe ejecutar en ese orden):
* Código con la función del experimento de GBT
* Ejecutar la función para expemerimentar el GBT y asignar el mejor GBT para la tabla de resultados final

### Redes Neuronales Artificiales (RNN)
Para esta sección del script es donde se desarrollará el Redes Neuronales Artificiales (RNN) (cada punto representa el código que se debe ejecutar en ese orden):
* Código con la función del experimento de mlpc
* Ejecutar la función para expemerimentar el mlpc y asignar el mejor mlpc para la tabla de resultados final

### Máquinas de soporte vectorial
Para esta sección del script es donde se desarrollará el Máquinas de soporte vectorial (cada punto representa el código que se debe ejecutar en ese orden):
* Código con la función del experimento de SVC
* Ejecutar la función para expemerimentar el SVC y asignar el mejor SVC para la tabla de resultados final


### Resultados Conjunto Test

> *Para poder evidenciar los Resultados del Conjunto de Test de forma adecuada, se requiere ejecutar los modelos de las secciones previas a esta*

* Ilustramos los mejores resultados del conjunto de Test


### Medidas de correlación y de índice de Fisher
> *Para poder ejecutar  Medidas de correlación y de índice de Fisher de forma adecuada, se requiere ejecutar la secciones de [Inicio e Importación] y [Introducción y Configuración]*

* En este primer código se puede ejecutar los resultados de Correlación
* En este código se ejecuta los resultados del indice de fisher

### Selección de características por método de búsqueda secuencial ascendente o descendente
> *Para poder ejecutar  Selección de características por método de búsqueda secuencial ascendente o descendente de forma adecuada, se requiere ejecutar la secciones de [Inicio e Importación] y [Introducción y Configuración]*

Para esta sección del script es donde se desarrollará Selección de características por método de búsqueda secuencial ascendente o descendente (cada punto representa el código que se debe ejecutar en ese orden):
* Código con la seleccion de caracteristicas por metodo de busqueda secuencial
* Mostramos el Dataframe con los resultados de SFS

### Extracción de características por el método PCA
> *Para poder ejecutar Extracción de características por el método PCA de forma adecuada, se requiere ejecutar la secciones de [Inicio e Importación] y [Introducción y Configuración]*

Para esta sección del script es donde se desarrollará Extracción de características por el método PCA (cada punto representa el código que se debe ejecutar en ese orden):
* Código con las funciones correspondientes para realizar el método PCA
* Código para evidenciar los resultados al experimentar PCA


