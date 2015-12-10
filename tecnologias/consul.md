

# Cónsul

Plataforma de Gobierno Abierto del Ayuntamiento de Madrid.

## Enlaces

|**URL** | https://decide.madrid.es |
| -- | -- |
| **Código** | https://github.com/consul/consul |

## Características

-   Permite a la ciudadanía realizar peticiones al Gobierno Vasco, así como votarlas (de manera positiva o negativa) y realizar comentarios. 
-   Cuenta con conexiones intercambiables para verificación con los usuarios a servicios externos en distintos grados (correo electrónico, SMS y API para conexión con el Padrón de la ciudad de Madrid).
-   Se encuentra en pleno desarrollo abierto y activo.
-   En su [hoja de ruta](https://github.com/consul/consul/blob/master/ROADMAP_ES.md) de funcionalidades técnicas se encuentran funcionalidades a estudiar para su implementación como los presupuestos participativos o la legislación colaborativa. 

## Argumentos

### A favor

* Licencia GPL Affero 3
* Tanto el lenguaje de programación (Ruby), el framework de desarrollo (Ruby On Rails), el sistema operativo (Linux) y la base de datos (PostgreSQL) son completamente libres. 
* Permite la colaboración externa en la rama principal de desarrollo.  
* * Cuenta tanto con suite de tests como servicios externos de control de calidad ya integrados.
* El desarrollo es completamente abierto y libre desde el primer momento. 
* Cuenta ya con internacionalización (en Castellano e Inglés), por lo que se ahorraría mucho tiempo en este trabajo que suele ser tedioso y llevar bastante tiempo durante el desarrollo.
* Tiene un sistema de registro de usuarios que permite su verificación a través de correo electrónico, así como de la API del padrón y a través de SMS. Cuenta con un sistema de permisos similar al necesario por las especificaciones. 
* Ya tiene un modelo base extensible de Propuestas, Comentarios, etc. 
* Aplica el principio de Kerckhoffs en materia de seguridad de configuraciones. Ya se encuentra revisada por la comunidad y no se han encontrado fallos de seguridad. 
* Cuenta con funcionalidades de denuncia y moderación de las propuestas y comentarios. 
* Tiene una comunidad de desarrollo cada vez más extensa 21 contribuidores.
* Lo están utilizando en Madrid y estudiando su uso en Zaragoza para los próximos meses, por lo que podemos aprovecharnos de la experiencia acumulada. 
* Ya lo están utilizando Ayuntamientos en España así que está en cierta medida asegurada su revisión técnica y legal. 

### En contra

* Su documentación es mejorable. Sólo tiene unas instrucciones muy básicas para hacerlo funcionar, pero sigue los estándares y convenciones de Ruby On Rails por lo que es prescindible.  
* Se encuentra en pleno desarrollo, por lo que será necesario coordinarse con los desarrolladores originales para ver la mejor forma de contribuir y cuales (y como) de nuestras funcionalidades se podrían subir a la versión del Ayuntamiento de Madrid. Esto podría evitarse esperando hasta que se consensue con Madrid  un modelo que facilite la colaboración aún más por parte de Madrid.
* La tecnología con la que está realizada, el lenguaje y framework de programación, no son unas en las que se encuentre familiarizados los programadores del IMI. Aunque se trate de tecnologías con conceptos similares a las que se utilizan internamente (Python y Django), aún así hace falta un tiempo de aprendizaje. 

## Pantallazos

![](consul01.png)
![](consul02.png)
![](consul03.png)
