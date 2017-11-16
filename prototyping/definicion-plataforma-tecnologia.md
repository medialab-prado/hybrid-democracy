**Cambio de backend y opcion de la plataforma tecnologica** 

La propuesta original del prototipo estaba basada en A Forxa do Co-Lab, una herramienta desarrollada por los promotores el proyecto en el año 2016 para el Laboratorio Ciudadano de A Coruña. A Forxa es software libre y está basada en el software y protocolo Git. Fue desarollada en el lenguaje de programación Go, ![A Forxa](https://forxa.colab.coruna.gal/).

El modelo de Git es adecuado para la documentación porque permite visualizar la historia y no sólo el producto final. El reto es traducir esta visión a un modelo de datos y definir las interacciones de los usuarios con la plataforma.

**Problemas:**

Hay algunas fragilidades en este momento para seguir con la Forxa como backend: no permite la edición colaborativa,la comunidade de desarollo de Go es aún muy pequeña y la API de la Forxa esta incompleta.
Se hace hicapié en la cuestión visual. Más que tener la solucción tecnológica más acabada, lo más importante ahora es la usabilidad.

**Solucion de interoperabilidad:**

Vamos a adoptar tecnologias más generalistas para que tengamos una comunidad más grande al inicio. Decidimos utilizar la API de GitHub. Esta decision implica en algunos limites a la soberania de los datos. No vamos utilizar las "issues" (incidencias) de Github porque esta feature no permite la migracion posterior de los datos para otras plataformas Git.
Usaremos el concepto de ramas (y no de las issues) para organizar los dos ejes (Receta Lenta y Mapa de Aprendizaje) de la documentacion del prototipo.
Tendremos que construir la aplicacion que consumirá la API de Github.
