
# Polyrepo Designe Doc
##### Last updated:
El título de su documento de diseño, el/los autor/es (debería/n ser los mismos que la lista de personas que planean trabajar en este proyecto), el/los revisor/es del documento (hablaremos más sobre eso en la sección Proceso a continuación) y la fecha de la última actualización de este documento.


## Authors
- [Sabin Areiza](https://github.com/sareiza)


## Overview / Descripcion General
Un resumen de alto nivel que todos los ingenieros de la empresa deberían comprender y utilizar para decidir si les conviene leer el resto del documento. No debe exceder los 3 párrafos.
## Context
Una descripción del problema en cuestión, la necesidad de este proyecto, la información que deben tener las personas para evaluarlo y cómo se integra en la estrategia técnica, la estrategia de producto o los objetivos trimestrales del equipo.
## Goals and No Goals
La sección de Objetivos debe:

Describe el impacto de tu proyecto impulsado por el usuario, donde tu usuario podría ser otro equipo de ingeniería o incluso otro sistema técnico.
Especifica cómo medir el éxito utilizando métricas; obtendrás puntos extra si puedes enlazar a un panel de control que haga un seguimiento de esas métricas.
Los objetivos secundarios son igualmente importantes para describir qué problemas no se van a solucionar, de modo que todos estén en sintonía. 

Las no metas o no objetivos es sumamente importante definirlos para que en la postreridad no vaya a incrementarse el proyecto, que no se resulten ahciendo cosas de mas. 

Decido que se va a poner en un aapartado diferente abajo, las no metas. 
## No Goals
## Milestones
Una lista de puntos de control medibles, para que tu jefe de proyecto y el superior de tu jefe puedan consultarla rápidamente y saber aproximadamente cuándo se completarán las diferentes partes del proyecto. Te recomiendo dividir el proyecto en hitos principales orientados al usuario si dura más de un mes.

Utiliza fechas del calendario para tener en cuenta retrasos no relacionados, vacaciones, reuniones, etc. Debería verse algo así:

Start Date: June 7, 2018
Milestone 1 — New system MVP running in dark-mode: June 28, 2018
Milestone 2 - Retire old system: July 4th, 2018
End Date: Add feature X, Y, Z to new system: July 14th, 2018

Si cambia la fecha estimada de finalización de alguno de estos hitos, añada [Update]aquí una subsección para que las partes interesadas puedan consultar fácilmente las estimaciones más actualizadas.

Nota: Un hito en programación es un punto de control clave en el tiempo que marca el fin de una fase importante o el logro de una meta grande, sin tener una duración propia. Funciona como una señal para medir el avance del software.


## Existing Solution
Además de describir la implementación actual, también debería explicar el flujo de ejemplo de alto nivel para ilustrar cómo interactúan los usuarios con este sistema y/o cómo fluyen los datos a través de él.

Una historia de usuario es una excelente manera de plantear esto. Ten en cuenta que tu sistema podría tener diferentes tipos de usuarios con distintos casos de uso.

Dice acerca del sistema que ellos ya tengan en caso de que esten migrando para otro lado, esto es solo cuando ya hay algo y se va a migrar. no habria caso de uso ahora. 

Pero tambien se me ocurre a mi que si ya existe eso que estamos planeando, identificar cuales son sus funcionalidades, que funciona muy bien, que no funciona y que podria faltarle.
## Proposed Solution
Algunos la denominan sección de Arquitectura Técnica . De nuevo, intenta desarrollar una historia de usuario para ilustrarlo. Puedes incluir numerosas subsecciones y diagramas.

Primero, ofrece una visión general y luego añade muchos detalles. Imagina un mundo donde puedas escribir esto, irte de vacaciones a una isla desierta y que otro ingeniero del equipo simplemente lo lea e implemente la solución tal como la describiste.
## Alternative Solutions
¿Qué otros aspectos tuviste en cuenta al idear la solución anterior? ¿Cuáles son las ventajas y desventajas de las alternativas? ¿Has considerado comprar una solución de terceros —o usar una de código abierto— que resuelva este problema en lugar de desarrollar la tuya propia?

### Aqui se pone la alternativa:
 - Pros:
     -
     -
     -
-Cons:
    -
    -
    -
    
## Testability, Monitoring and Alerting

Me gusta incluir esta sección porque la gente suele pasarla por alto o directamente la omite, y casi siempre les pasa factura más adelante cuando las cosas se estropean y no tienen ni idea de cómo ni por qué.
## Cross-Team Impact
¿Cómo afectará esto al aumento de la carga de trabajo en guardia y de desarrollo/operaciones? ¿
Cuánto costará?
¿Provoca alguna disminución de la latencia en el sistema?
¿Revela alguna vulnerabilidad de seguridad?
¿Cuáles son algunas consecuencias negativas y efectos secundarios?
¿Cómo podría el equipo de soporte comunicar esto a los clientes?
## Open Cuestion
Cualquier cuestión pendiente sobre la que no esté seguro, decisiones polémicas sobre las que le gustaría que los lectores dieran su opinión, sugerencias para futuros trabajos, etc. Un nombre irónico para esta sección es «las incógnitas conocidas».
## Detailed Scoping and Timeline/Alcance detallado y cronograma
Esta sección la leerán principalmente los ingenieros que trabajan en este proyecto, sus jefes de equipo y sus gerentes. Por lo tanto, se encuentra al final del documento.

Básicamente, este es el desglose de cómo y cuándo planeas ejecutar cada parte del proyecto. Definir el alcance con precisión implica muchos aspectos, así que puedes leer esta publicación para obtener más información al respecto.

Suelo usar esta sección del documento de diseño como un registro continuo de tareas del proyecto, así que la actualizo cada vez que cambia mi estimación del alcance. Pero eso es más bien una preferencia personal.

Aqui se puede desgrozar mediante apartados cada cosa que se va a realziar. 
   -
   -
   -
   -
   - 
Es de manera libre la manera en que presentas las fechas, las partes del proyecto y las tareas. 

## Discussions
Por último, si hay mucha controversia entre usted, el revisor y otros ingenieros que lean el documento, le recomiendo encarecidamente que consolide todos los puntos de desacuerdo en la sección de Discusión . Luego, programe una reunión con las partes involucradas para hablar sobre estas discrepancias en persona.

Cuando un hilo de discusión tiene más de cinco comentarios, suele ser mucho más eficiente pasar a una conversación presencial. Recuerda que sigues siendo responsable de la decisión final, incluso si no todos logran llegar a un consenso.

Hablando recientemente con Shrey Banga sobre este tema, me enteré de que Quip tiene un proceso similar, con la diferencia de que, además de contar con un ingeniero o líder técnico experimentado del equipo como revisor, también sugieren que un ingeniero de otro equipo revise el documento. No lo he probado, pero sin duda creo que esto ayudaría a obtener comentarios de personas con diferentes perspectivas y a mejorar la legibilidad general del documento.
## Notas Finales para Cuando se vaya a comenzar con la implementación.

Por último, si hay mucha controversia entre usted, el revisor y otros ingenieros que lean el documento, le recomiendo encarecidamente que consolide todos los puntos de desacuerdo en la sección de Discusión . Luego, programe una reunión con las partes involucradas para hablar sobre estas discrepancias en persona.

Cuando un hilo de discusión tiene más de cinco comentarios, suele ser mucho más eficiente pasar a una conversación presencial. Recuerda que sigues siendo responsable de la decisión final, incluso si no todos logran llegar a un consenso.

Hablando recientemente con Shrey Banga sobre este tema, me enteré de que Quip tiene un proceso similar, con la diferencia de que, además de contar con un ingeniero o líder técnico experimentado del equipo como revisor, también sugieren que un ingeniero de otro equipo revise el documento. No lo he probado, pero sin duda creo que esto ayudaría a obtener comentarios de personas con diferentes perspectivas y a mejorar la legibilidad general del documento.

https://www.freecodecamp.org/news/how-to-write-a-good-software-design-document-66fcf019569c/

## Nota parte no queda en el documento final, es solo para que tenga idea de lo que se deberia hacer. 