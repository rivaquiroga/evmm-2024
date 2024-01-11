# Escuela de Verano de Métodos Mixtos

Materiales del módulo "Minería de texto para el trabajo con archivos" (también conocido como "Web scraping para el trabajo con archivos") de la [Escuela de Verano de Métodos Mixtos](https://cienciapolitica.uc.cl/escuela-de-metodos-mixtos/emm-2024) organizada por el Instituto de Ciencia Política UC. 

Como el tema es muy amplio como para mostrar todo lo que se puede hacer durante 90 minutos, en el taller nos enfocaremos en la fase de adquisición de datos, es decir, en cómo extraer datos textuales para constituir un corpus de documentos para analizar en el futuro. 

## Preparación

Durante la sesión utilizaremos {rvest} y otros paquetes que son parte de lo que se conoce como [Tidyverse](https://www.tidyverse.org/), un conjunto de paquetes diseñados para el trabajo en ciencia de datos. Probablemente ya lo tengan instalado de la sesión del lunes. Además, es necesario instalar {janitor}, un paquete que nos servirá para formatear nombres de archivos. Puedes instalarlos con las siguientes líneas de código:

```
install.packages("tidyverse")
install.packages("janitor")
```

## Atajos de teclado útiles

Los siguientes atajos de teclado serán útiles al explorar las páginas web que _escrapearemos_.

| Acción | Windows / Linux | Mac |
|---|---|---|
| Abrir el panel de desarrollo | F12<br/>ctrl + shift + i | F12<br/>option + command +i |
| Abrir el panel de desarrollo con la opción de selección activada | ctrl + shift + c | option + command + c |

## Ejercicio práctico: extracción de texto de un sitio web

🔗 [La página web que _escrapearemos_](https://prensa.presidencia.cl/discurso.aspx?id=278977)

:page_facing_up: [El código escrito en clases](https://www.dropbox.com/scl/fi/sqlfjpu4tb83faknd1xng/01_extraccion-texto.R?rlkey=nn8pmw1dcrofpy52sk9wv2i44&dl=0)

## Materiales de apoyo

* La lectura central del módulo es el artículo de Nguyen et al. (2020), que entrega una visión general del flujo de trabajo con datos textuales: ["How We Do Things With Words: Analyzing Text as Social and Cultural Data"](https://www.frontiersin.org/articles/10.3389/frai.2020.00062/full).

* Un tutorial en español para revisar con más profundidad lo que veremos hoy: http://programminghistorian.org/es/lecciones/introduccion-al-web-scraping-usando-r

### Para profundizar en el tema de análisis de datos textuales con R

* Silge, J. & Robinson, D.: _Text mining with R_. <https://www.tidytextmining.com/>
* Hvitfeld, E. & Silge, J. _Supervised Machine Learning for Text Analysis in R_. <https://smltar.com/>

### Para profundizar en aspectos metodológicos del trabajo con textos en las Ciencias Sociales

* Grimmer, J., Roberts, M. E., & Stewart, B. M. (2022). _Text as data: A new framework for machine learning and the social sciences_. Princeton University Press.

### Para profundizar en los aspectos lingüísticos del análisis del discurso

* Gillings, M., Mautner, G., & Baker, P. (2023). _Corpus-Assisted Discourse Studies_. Cambridge University Press.
* Baker, P. (2023). _Using corpora in discourse analysis_. Bloomsbury Publishing.

### Para seguir aprendiendo sobre R

* Urdinez, F. & Cruz Labrín, A (Eds.): _AnalizaR datos políticos_. <https://arcruz0.github.io/libroadp/>
* Wickham, H. & Grolemund, G.: _R para Ciencia de Datos_. <https://es.r4ds.hadley.nz/>
* ¡Participar en la comunidad! Grupos de usuarios de R, capítulos de [R-Ladies](https://rladies.org/), eventos como [LatinR](https://latin-r.com/).

### Otras cosas

* Internet Archive: https://web.archive.org/. Sirve para buscar versiones anteriores de un sitio web, buscar sitios que ya no están disponibles y para archivar una versión de una página web que no queremos que se pierda en el futuro.
