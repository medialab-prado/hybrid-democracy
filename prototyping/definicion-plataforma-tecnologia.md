**Cambio de backend y opcion de la plataforma tecnologica** 

En la propuesta original del prototipo tendria como backend La Forxa. La Forxa es software livre y fue desarollada por el proponente deste proyecto. Esta baseada en el software y protocolo Git. Fue desarollado en lenguaje de programación Gol (de Google).

El modelo de git es adecuada para la documentación porque permite visualizar la historia y no sólo el producto final. Reto es cómo traducir la visión a un modelo de datos y las interacciones de usuarios con la plataforma.

**Problemas:**
Hay algunas fragilidades neste momento para seguirmos con la Forxa como backend. No permite la edicción colaborativa síncrona. La comunidade de desarollo de Gol es aunque muy pequeña. La app de la Forxa esta incompleta.
Se hace hicapié en la cuestión visual, más que tener la solucción tecnológica más perfecta, pues lo más importante es la usabilidad.

**Solucion:**
Vamos adoptar tecnologias más mainstream para que tengamos una comunidad más grande al inicio. Decidimos utilizar la app de GitHub. Esta decision implica en algunos limites a la soberania de los dados. No vamos utilizar las "issues" (incidencias) de Github porque esta feature no permite la migracion posterior de los datos para otras plataformas Git.
Usaremos el concepto de ramas (y no de las issues) para organizar los dos ejes (Receta Lenta y Mapa de Aprendizage) de la documentacion del prototipo.
Tendremos que construir la aplicacion que ira interecionar con la app de Github.
