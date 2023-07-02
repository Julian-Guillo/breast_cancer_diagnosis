# Desarrollo de modelos predictivos para la detección de cáncer de mama.

Trabajo final del Master en Bioestadística de la Universitat de Valencia. Ajuste de diferentes clasificadores binarios con el objetivo de diagnosticar casos de cáncer de mama lo más precisamente posible, utilizando como predictores 30 características de los núcleos celulares obtenidos de muestras histológicas tumorales. 

El código de R utilizado en el trabajo está disponible en el archivo, [codigo_tfm_julian_guillo.Rmd](codigo_tfm_julian_guillo.Rmd). Puedes decargar el archivo `sesion_completa.RData` con todos los modelos, tablas y gráficas guardados [aquí](https://drive.google.com/file/d/1oPOFmcbMv_tt53IcoR2q17VMIUIM72uD/view?usp=drive_link). Se recomienda cargar este archivo antes de ejecutar el código de  para evitar tener que ajustar de nuevo todos los modelos.

Para jugar con una parte de los datos y visualizar cómo cambia la predicción de un modelo de regresión logística en función del valor de 4 covariables del banco de datos, puedes acceder a [esta aplicación web](https://julianguillo.shinyapps.io/breast_cancer_shinyapp/).
