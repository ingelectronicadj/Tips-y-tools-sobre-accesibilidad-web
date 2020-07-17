# Para auditar accesibilidad web
Este sitio pretende compartir un set de herramientas que ayudan a la automatización de algunas pruebas para accesibilidad web en entornos virtuales.

## Aspectos Generales

Cuando se realizan pruebas de Accesibilidad utilizando herramientas, es muy pero muy importante, tener en cuenta que las herramientas como tal, son una ayuda grande en términos de determinar qué podría estar pasando con la accesibilidad de nuestro código y cómo podríamos hacer para solucionarlo.

Ahora bien, que utilicemos estas herramientas es bueno sin embargo no debemos depender enteramente de los resultados de estas pruebas y mucho menos que todo nuestro trabajo en términos de remediation dependa de estas herramientas.

## ¿Qué queremos decir con esto?
Se debe dominar o tener un conocimiento elevado sobre los criterios de accesibilidad (WCAG 2.1, Section 508, EU 3149, UAAT, ATAG, ACAA, NTC-5854, etc.) para poder determinar si los resultados obtenidos por estos tools son en realidad, defectos de accesibilidad y si infringe alguna regla (Sucess Criteria).

## ¿Por qué mencionamos esto?
Muchos profesionales tienden a depender de ciertas herramientas para resolver los problemas de sus sitios y no hacen análisis concientes sobre los resultados obtenidos.
Recuerden que las herramientas de automatización son poderosas pero dependen del análisis y conocimiento de las normativas de accesibilidad para determinar su validez.
## ¿Qué recomendamos?
Acá algunos puntos:
* Diseñe una estrategia que combine habilidades de varios tools. Investigue cuales les funcionan en términos de funcionalidades complejas de sus sitios así como de tipo de resultados que arrojan las mismas.    
* Integre pruebas manuales y automatizadas. 70% del esfuerzo de validación depende de esta relación: USUARIO + TECNOLOGÍA DE ASISTENCIA + SITIO    
* No dependa solo de herramientas open source o plugins, sabemos que dependiendo de la estrategia de desarrollo así como el presupuesto, a veces no se puede, sin embargo en caso de que pueda invertir, ¡hágalo!    
* Si usa tools open source, revise cuando fue la última vez que se hizo un cambio-update del tool esto para validar vigencia y si incluye los WCAG 2.1. como base.    
* Cree "combos" de validación. Por ejemplo: NVDA funciona muy bien con Chrome y Firefox e Internet Explorer con JAWS. ChromeVox con Chrome en macOS y Windows.    
* Defina rutas críticas o "happy paths" que pueda considerar primero en términos de usuario.    
* Cree un buen sistema de control de bugs-defectos para llevar el progreso de los mismos.    

Esto es importante mencionarlo porque en términos de demandas, al depender enteramente de los tools, puede que no nos estemos dando cuenta que están faltando situaciones de solucionar.

## Herramientas de apoyo a la auditoría de accesibilidad web
A continuación algunos tools que sirven para el escaneo automático de accesibilidad, definitivamente hay otros, la lista es grande, pero al menos para iniciar, recomiendo estos:
- https://www.deque.com/axe/devtools/
- https://www.ibm.com/able/
- https://accessibilityinsights.io/ 
- https://www.paciellogroup.com/products/accessibility-resource-center-arc/ 
- https://wave.webaim.org/ 
- https://www.ssa.gov/accessibility/andi/help/howtouse.html 
- https://validator.w3.org/ 
- https://www.w3.org/WAI/test-evaluate/ 
- https://www.w3.org/WAI/test-evaluate/preliminary/
