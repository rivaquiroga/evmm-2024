# evmm-2024
Materiales del módulo "Minería de texto para el trabajo con archivos" (también conocido como "Archivos, web scraping y análisis de contenido") de la [Escuela de Verano de Métodos Mixtos](https://cienciapolitica.uc.cl/escuela-de-metodos-mixtos/emm-2024) organizada por el Instituto de Ciencia Política UC. 


El tema es muy amplio como para mostrar todo lo que se puede hacer durante 90 minutos, así que en el taller nos enfocaremos en la fase de adquisición de datos, es decir, en cómo extraer datos textuales para constituir un corpus de documentos para analizar en el futuro.


## Preparación

Durante la sesión utilizaremos {rvest} y otros paquetes que son parte de lo que se conoce como [Tidyverse](https://www.tidyverse.org/), un conjunto de paquetes diseñados para el trabajo en ciencia de datos. Probablemente ya lo tengan instalado de la sesión del lunes. Además, es necesario instalar {janitor}, un paquete que nos servirá para formatear nombres de archivos. Puedes instalarlo con la siguiente línea de código:

```
install.packages("janitor")
```

## Atajos de teclado útiles

Los siguientes atajos de teclado serán útiles al explorar las páginas web que _escrapearemos_.

| Acción | Windows / Linux | Mac |
|---|---|---|
| Abrir el panel de desarrollo | F12<br/>ctrl + shift + i | F12<br/>option + command +i |
| Abrir el panel de desarrollo con la opción de selección activada | ctrl + shift + c | option + command + c |

## Ejercicio práctico: extracción de texto de un sitio web

🔗 [Página web que _escrapearemos_](https://prensa.presidencia.cl/discurso.aspx?id=278977)

:page_facing_up: [Código escrito en clases]()

## Materiales de apoyo

La lectura central del módulo: Nguyen et al., 2020: ["How We Do Things With Words: Analyzing Text as Social and Cultural Data"](https://www.frontiersin.org/articles/10.3389/frai.2020.00062/full).

