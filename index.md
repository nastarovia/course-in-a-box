---
layout: index
published: true
---

## Edita y publica un libro con un workflow sostenible y automatizado

la idea es editar un libro. Pero también evitar todos los problemas que nos pueden causar el uso de software propietario y la falta de un sistema coherente de control de versiones. Y todavía más interesante, utilizando una plataforma que nos permite colaborar sin conflictos con nuestros colegas. 

El propósito de este tutorial será mostrar desde un punto de vista práctico como combinar herramientas para crear un libro multiformato, de una mera sostenible y automatizada, y que, de paso, resuelve punto por punto nuestro problema..

Este es únicamente un posible *workflow* y desde luego que existen muchas otras herramientas y combinaciones. El punto que espero demostrar es únicamente la cantidad de herramientas que existen a nuestra disposición, que pueden transformar el proceso de producción de un libro hasta el punto de permitirnos automatizar todas las tareas, ganando en eficiencia y al mismo tiempo en control sobre nuestros proyectos.

Para mostrar esto, voy a replantear mi proyecto (la edición de *Mío cid campeador* de Vicente Huidobro) y rehacerlo desde el principio. Para ello:

- Crearemos, a partir de los archivos que tenemos, un set de archivos fuente en markDown (texto plano con la extensión ``.md``)
- Luego crearemos un repositorio para albergar los archivos necesarios
- Crearemos un archivo formateado en ``yaml`` para almacenar la metadata del libro
- Pondremos este repositorio (el directorio donde vive nuestro proyecto) bajo control de versiones con ``git``
- Sincronizaremos este repositorio local con un repositorio remoto en GitHub
- Utilizando pandoc, crearemos nuestro Epub, y crearemos un archivo ICML para importarlo en inDesign
- Crearemos desde InDesign el PDF final de imprenta
- Veremos como hacer correcciones, manteniendo un único set de archivos fuente y guardando un registro histórico de correcciones.
- y por último, crearemos una página web con los archivos de nuestro libro.

## Reach new audiences

Online courses take a big step forwards in the sharing of knowledge around the world. However, your course is only ever as good as the people it reaches. To help reach new audiences with online courses, P2PU developed learning circles: groups for people who take online courses together, in local libraries or community spaces.

Once you create a course, you can add it to P2PU’s learning circle [course page](http://p2pu.org/en/courses/), a growing database of online courses that people are using to facilitate learning circles around the world. You can also check out our [facilitator page](https://www.p2pu.org/en/facilitate/) to learn how to run your own learning circle.


