# Introducción

## ¿Qué es este documento?

Este documento es un primer acercamiento a las especificaciones de una plataforma participativa (tanto en su faceta de espacio de participación a través de Internet como en su rol de interfaz con procesos presenciales), en la que la ciudadanía de Barcelona podrá proponer, debatir y evaluar medidas y objetivos para el Programa d'Actuació Municipal (PAM) del Ajuntament de Barcelona en el periodo 2016-2019.

El documento quiere ser un espacio vivo de debate participativo y producción colectiva. Para ello estamos usando la tecnología de [git](https://git-scm.com/) a través del [Gitbook](http://gitbook.com), lo que permite la edición colaborativa, el control de versiones, la cuantificación de las contribuciones y la creación de obras derivadas, todo ello de manera automática. También puedes contribuir editando directamente el documento desde gitbook o desde tu repositorio git local.

## Meta-datos 

### Autoría

Este borrador está siendo desarrollado por Andrés Pereira de Lucena, Antonio Calleja-López y Arnau Monterde. Puedes consultar la lista de contribuciones al documento directamente en [la sección de Detalles de gitbook](https://www.gitbook.com/book/andreslucena/specs-pam/details). Todos los autores son, a su vez, los editores del texto. Las contribuciones de terceras personas serán aceptadas o rechazadas y, en su caso, reconocidas, en este apartado.

### Resumen  

Este documento busca describir las especificaciones que tendrá una plataforma participativa (tanto en su faceta de espacio de participación a través de Internet como en su rol de interfaz con procesos presenciales), en la que la ciudadanía de Barcelona propondrá, debatirá y evaluará medidas y objetivos para el Programa d'Actuació Municipal (PAM) del Ajuntament de Barcelona en el periodo 2016-2019. 

Se trata de una aplicación web responsiva y multi-idioma, orientada a facilitar la participación de la ciudadanía de Barcelona por medio de un registro de usuarios con confirmación vía correo electrónico, posibilidad de verificación a través de conexión al padrón municipal y SMS, así como otros mecanismos. La ciudadanía podrá proponer, modificar, discutir y votar medidas y objetivos relativos al Programa d'Actuació Municipal (PAM) y a los Planes de Acción por Distrito (PAD) a partir de Febrero del 2016. 

Este primer proceso participativo se organizará en distintas fases, por lo que es necesario que la aplicación cumpla con unos requisitos iniciales de funcionalidad. En este desarrollo inicial deben tenerse en cuenta las funcionalidades futuras ya planificadas, favoreciéndose una versatilidad que permita su modificación posterior sin provocar retrasos en el calendario propuesto para el desarrollo de funcionalidades.

### Palabras clave

Democracia participativa, ciudad democrática, conocimiento abierto, democracia deliberativa, democracia directa.

### Estructura

* [Introducción](README.md)
* [Objetivo](objetivo.md)
* [Períodos o fases](fases.md)
* [Requisitos técnicos](requisitos.md)
* [Funcionalidades](funcionalidades.md)
   * [Portada](funcionalidades/portada.md)
   * [Propuesta](funcionalidades/propuesta.md)
   * [Listado de propuestas](funcionalidades/listado.md)
   * [Registro y verificaciòn de usuarias](funcionalidades/usuarias-registro.md)
   * [Tipos de usuarias](funcionalidades/usuarias-tipos.md)
   * [Acciones de una usuaria](funcionalidades/usuarias-acciones.md)
   * [Panel de administración y moderación](funcionalidades/admin.md)
   * [Encuentros presenciales (Calendario, mapa de eventos y autoorganización de encuentros presenciales)](funcionalidades/calendario.md)
   * [Sistema de transparencia, monitorización y visualización de participación ciudadana](funcionalidades/transparencia.md)
* [Tecnologías útiles y/o parecidas](tecnologias.md)
   * [Cónsul - Gobierno abierto del Ayuntamiento de Madrid](tecnologias/consul.md)
   * [Open Irekia](tecnologias/open-irekia.md)
   * [Your Priorities](tecnologias/your-priorities.md)
   * [e-Petitions Gov.UK](tecnologias/e-petitions.md)
   * [Desarrollo propio a medida](tecnologias/development.md)

### Fuentes 

Este documento está escrito en lenguaje Markdown, está dividido en diferentes archivos (uno por cada sección), puedes encontrar los archivos para descarga o copia en:  https://github.com/XXX

### Cómo citar este documento

Especificaciones Plataforma de Participación Ciudadana para la elaboración del PAM 2016 de la ciudad de Barcelona (2015) *Andrés Pereira de Lucena, Antonio Calleja-López y Arnau Monterde.*. https://www.gitbook.com/book/andreslucena/specs-pam

### Licencia

Copyleft 2015 bajo las licencias Creative Commons BY-SA (Reconocimiento compartir Igual) y GFDL (Licencia de Documentación Libre de GNU):

#### CC BY-SA: Creative Commons Reconocimiento Compartir Igual 4.0 Internacional

Usted es libre de copiar y redistribuir el material en cualquier medio o formato, remezclar, transformar y crear a partir del material, para cualquier finalidad, incluso comercial. El licenciador no puede revocar estas libertades mientras cumpla con los términos de la licencia. Bajo las siguientes condiciones: a) Reconocimiento: debe reconocer adecuadamente la autoría, proporcionar un enlace a la licencia e indicar si se han realizado cambios. Puede hacerlo de cualquier manera razonable, pero no de una manera que sugiera que tiene el apoyo del licenciador o lo recibe por el uso que hace. b) Compartir Igual: Si remezcla, transforma o crea a partir del material, deberá difundir sus contribuciones bajo la misma licencia que el original. No hay restricciones adicionales, no puede aplicar términos legales o medidas tecnológicas que legalmente restrinjan realizar aquello que la licencia permite. Puede encontrarse la licencia completa en: https://creativecommons.org/licenses/by-sa/4.0/deed.es_ES

#### GFDL: Licencia de Documentación Libre de GNU

Se concede permiso para copiar, distribuir y/o modificar este documento bajo los términos de la licencia de documentación libre GNU, versión 1.3 o cualquier otra versión posterior publicada por la Free Software Foundation; sin secciones invariantes ni textos de cubierta delantera, tampoco textos de contraportada. Puede encontrar una copia de la licencia en http://www.gnu.org/copyleft/fdl.html
