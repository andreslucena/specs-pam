Requisitos técnicos

La aplicación debe contar con unas características básicas técnicas a seguir en materia de liberación de código, estándares de calidad, seguridad, documentación, :
* La plataforma que se desarrolle debe tener licencia abierta desde el primer momento, utilizando una licencia GPL Affero V3 o similar. Su código fuente debe estar publicado desde antes de su puesta en producción, idealmente desde el primer commit. Debe estar disponible en una plataforma como Github y, a ser posible, además en otro repositorio-plataforma no privativo y/o del propio Ayuntamiento.
* Debe contarse con la posibilidad de poder comprobar los cambios antes de desplegar a todos los usuarios en servidores de staging (beta), preproduction (preproducción) y production (producción). 
* A nivel de seguridad se deben cumplir unos requisitos básicos mínimos estándares de la industria:
 * debe ir configurado con un certificado SSL válido en todos los navegadores principales (Firefox, Chrome, IE, Safari, etc).
 * nunca se deben guardar las contraseñas en claro en la base de datos
 * tener en cuenta protecciones para ataques de tipo XSS
 * protecciones frente ataques de inyecciones SQL
* Se deben seguir unos estándares mínimos de documentación para facilitar su reutilización por otras entidades o personas: 
 * Instalación inicial de la plataforma en desarrollo. Qué pasos deben seguirse para tener una instalación mínima funcionando. 
 * Explicación de parámetros de configuración: conexiones a bases de datos, servicios externos que se requieran. 
 * Instalación y configuración en staging (beta) y producción. 
 * Instalación y configuración de servicios asociados (bases de datos).
* El lenguaje de programación con el que está desarrollado debe ser 100% libre, a su vez. No se deben usar componentes privativos ni pagar licencias ni servicios externos privativos. Lo mismo con el Sistema Operativo y otros componentes que se utilicen (por ejemplo bases de datos, colas de trabajo, etc). Esto debe cumplirse por seguridad (al ser el código libre es auditable y hay menos probabilidades de que haya programas espias implementados por gobiernos extranjeros), por economía (el costo de las licencias), por soberanía tecnológica (permite modificaciones en caso de ser necesarias).
* Debe utilizarse un framework de desarrollo web moderno MVC (Modelo Vista Controlador) o similar, así como preferirse la utilización de librerías abiertas siempre que corresponda y tenga sentido. Esto facilita tanto el mantenimiento, como la seguridad y la colaboración por otros desarrolladores. Recomendaciones: Ruby On Rails (Ruby), Django (Python), Laravel (PHP), etc. 
* Debe tener una suite de tests extensiva, con tests unitarios (de modelo) y de integración, utilizarse un sistema de Integración Continua, y servicios externos automáticos para control de calidad. Esto debe realizarse para mantener un alto grado de calidad y mantenibilidad, permitiendo realizar cambios con seguridad de que no se produzcan errores en otras partes de la aplicación, algo crítico cuando se colabora en equipos abiertos. Hay diversos ejemplo de servicios externos, en su mayoría disponibles de forma gratuita a proyectos de software libre.
* Debe permitirse y documentarse como se prefiere realizar la participación de otros programadores durante el desarrollo. A su vez los desarrolladores iniciales de la plataforma deben mantener un diálogo fluido con los otros. Los tickets y el roadmap del desarrollo deben estar en abierto.
* A nivel de diseño la web debe ser responsiva y cumplirse criterios de accesibilidad. 
Seguridad de las configuraciones: siguiendo las prácticas de seguridad de la industria, todo lo que sean configuraciones específicas de la aplicación se encontrarán en ficheros de configuración o similar fuera del repositorio en el que se encuentra el código, aplicando el principio de Kerckhoffs en materia de seguridad (el adversario conoce el sistema, pero la clave 
es secreta).
* Internacionalización: la aplicación debe permitir que su interfaz se vea en varios idiomas, el Catalán y el Español. 
* A nivel de estándares de calidad, documentación, asi como una explicacion exahustiva de la mayor parte de los puntos tecnicos tratados en esta sección, asi como su aplicación y justificación en materia de gobierno, el modelo a seguir es el propuesto por gov.uk. 
* Se deberá permitir el acceso de robots de búsqueda y dispositivos de lectura para personas con discapacidades diferentes. Hay que tenerlo en cuenta si se decide utilizar algún framework Javascript del tipo Ember, Angular, Backbone, etc. 