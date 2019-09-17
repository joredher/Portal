# Portal - casanare.dev

Portal Web de los Desarrolladores de Software de Casanare.

¡Bienvenid@ a **[casanare.dev](https://casanare.dev)**!

Esta es un espacio construido por nosotros y que busca compartir nuestro conocimiento y crecer profesionalmente de manera colaborativa.

## Que es casanare.dev

Es una plataforma que nos permite compartir nuestro portafolio, experiencia, lenguajes y plataformas, escribir sobre software (o cualquier cosa geek que se nos venga a la cabeza), discutir sobre diferentes asuntos y crecer profesionalmente y personalmente.

Casanare.Dev busca ser un espacio de contacto entre desarrolladores, empresas y entidades, permitiendo con esto visibilizar el sector en la región.

Creemos que compartir nuestro conocimiento no hace otra cosa que aumentarlo ¡Transparencia y colaboración!

### Por qué crearlo si podemos usar wix

Porque si :) . La idea es crear algo en común, que salga del esfuerzo de todos y que mostremos lo que sabemos hacer.

### En que plataforma

La idea es que nos organicemos y hagamos una vaina como en el mundo real, multiplataforma, php, .net, nodejs, java o cualquier tecnologia que cumpla el objetivo que buscamos (y que soporte mi hosting  linux, o el que alguien quiera aportar).

Propongo el uso de la arquitectura basada en microservicios, de tal manera que podamos determinar servicios en diferentes plataformas y crear pequeños equipos por cada uno.

### Como contribuir

La idea es que juntemos lo que sabemos, en backend, frontend, diseño, redes sociales, con cerveza, pizza, gestionando el hosting o simplemente ayudando a probar y dando ideas.

### Quien se lleva el crédito

Todos y ninguno, la idea es crear comunidad, independientemente de la empresa o equipo en el que estemos trabajando y como se registrará en github, el crédito se verá reflejado en la reputación y contribuciones.

### Cuanto tiempo me llevará

Lo que cada quien pueda, yo personalmente, voy a usar el proyecto para aprender algunas cositas que estoy sintiendo necesarias (Clean Arquitecture, TDD, DDD y microservicios).

### Cuando lanzariamos el producto

La idea es reunirnos (asi sea virtualmente) y hacer una pequeña planeación de sprints y determinar que vamos lanzando en el tiempo, registrar estas tareas en un tablero y cuando cumplamos un primer sprint lanzar el producto.

### Como vincularme

Usaremos [El Grupo de Slack](https://join.slack.com/t/casanaredevs/shared_invite/enQtNzU1OTA1MzczNTIxLTFhYTc5ZjQ1MTdiM2I5MGJlMzZiZWY2ZjQ1MTc5Mjc4MGQ4ODhiMzU2N2FhYmYyYWQ1NWJmOGEwZDdlNWYxNGM) como herramienta de comunicación del grupo, el objetivo es que cada quien pueda usarlo cuando pueda y según su tiempo.

## Tabla de Contenido

- [Contribuciones](#contribuir)
- [Introducción](#codigo)
  - [Arquitectura](#arquitectura)
  - [Tecnologías usadas](#tecnologia)
- [Instalación](#instalacion)
  - [Prerequisitos](#prerequisitos)
  - [Guia de Instalación](#guia)
  - [Como ejecutar](#ejecucion)
- [Participantes del desarrollo](#participantes)
- [Licencia](#licencia)

## Contribuciones

Si quieres participar del desarrollo de **[casanare.dev](https://casanare.dev)** verifica esta **[guia para contribuir a la iniciativa](CONTRIBUTING.md)**

## Introducción

### Arquitectura

La arquitectura propuesta es la siguiente

![Diagrama de Arquitectura](https://github.com/casanaredevs/Portal/blob/master/Casanare%20Devs-Page-2.png)

De manera general el objetivo es crear microservicios, donde cada uno de manera independiente pueda ser desarrollado en una plataforma diferente, con un repositorio de datos diferente y unicamente bajo la premisa de exponer un web api, basado en OpenApi con Swagger.

La autenticación se realizará desde un servicio externo, usando cualquier servicio Auth (OpenId) o similar

El FrontEnd lo separarémos en dos uno para el Portal y otro para gestión (Creación de perfiles, publicaciones, etc).

Como en todo proyecto, no se que vaya a salir y como cambie en el futuro pero la idea es partir de estas premisas, alimentarlo con las ideas de todos y ver como fluye la idea.

### Tecnologías usadas

Según la arquitectura propuesta tenemos las siguientes tecnologias:

- BackEnd
  - Servicio Portafolio: Pendiente
  - Servicio Blog: Pendiente
  - Servicio CMS: Pendiente
  - Servicio Auth: Pendiente
  - Servicio Monitoreo: Pendiente
- FrontEnd: Pendiente
- Api Gateway: Pendiente
- Infraestructura: Docker para cada servicio y UI.
- CI/CD: Azure DevOps nos da la oportunidad de usarlo grátis para proyecto (Propongo usarlo)

## Instalación

Pendiente

### Prerequisitos

Pendiente

### Guia de Instalación

Pendiente

### Como ejecutar

Pendiente

## Participantes del desarrollo

- Juan David Pareja Soto **[parejajd](https://github.com/parejajd)**
(Poner nombres acá)

## [Licencia](LICENSE)
