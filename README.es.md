# PASS / Party Games

[中文](README.zh.md) · [English](README.en.md) · [Español](README.es.md) · [Inicio del proyecto](README.md)

**INNNX. · Un teléfono. Todos juegan.**

PASS reúne preguntas, retos, selección aleatoria de jugadores y respuestas contrarreloj en una colección de minijuegos de fiesta creada con Flutter. El grupo elige un juego, sigue las indicaciones y pasa el teléfono a la siguiente persona. La aplicación propone las actividades y organiza los turnos; la conversación y las reacciones las ponen quienes juegan.

## Vista de HOME en español

<a href="screenshots/home-es.png"><img src="screenshots/home-es.png" width="360" alt="Inicio completo de PASS en español con nueve entradas de juego" /></a>

Es una vista completa del inicio desplazable, compuesta a partir de capturas existentes de la interfaz Android; no es una única pantalla. Los nombres de los juegos y las instrucciones aparecen en español; la marca PASS y parte de su lema conservan el inglés. Pulsa la imagen para ampliarla. Las páginas en chino e inglés muestran sus respectivas interfaces.

## Diseño y navegación del inicio

El fondo oscuro, los colores fluorescentes, las ilustraciones de grafiti y las tarjetas numeradas organizan la colección. Labios, bomba, dedo, copa, rayo, tarta, ojo y llamas identifican las actividades. Las dos tarjetas grandes destacan Verdad o Reto y Bomba Numérica; las demás permiten cambiar de actividad rápidamente. Al desplazarte aparecen el Modo Mixto y el acceso para quitar anuncios. El botón superior derecho abre los ajustes.

## Las nueve entradas, explicadas

| Entrada | Cómo se juega | Qué aporta al grupo |
| --- | --- | --- |
| 01 Verdad o Reto | Añade jugadores, gira la ruleta para elegir a la siguiente persona, elige Verdad o Reto, responde o realiza el desafío y pasa el teléfono. | Preguntas y retos dentro de un mismo flujo de turnos. |
| 02 Bomba Numérica | Un número secreto es la bomba. Elegid números por turnos: los aciertos seguros reducen el intervalo y acertar la bomba activa un reto aleatorio. | Suspense al reducirse el intervalo disponible. |
| 03 ¿Quién es más probable que…? | Leed la pregunta, contad tres, dos, uno y señalad a quien mejor encaje. Continuad con otra pregunta. | Comparar impresiones y comentar vuestras elecciones. |
| 04 Yo Nunca | Leed la afirmación y responded con sinceridad si habéis vivido esa experiencia. Pasad a la siguiente. | Compartir experiencias y descubrir puntos en común. |
| 05 Reto de 5 Segundos | Lee el reto, inicia el temporizador y responde antes de que pasen cinco segundos. Pasa el teléfono para otra ronda. | Pensar rápido bajo la presión del tiempo. |
| 06 Fiesta de Cumpleaños | Elige a quien celebra su cumpleaños y seguid las propuestas temáticas con la participación del grupo. | Actividades centradas en la persona homenajeada. |
| 07 Verdad | Entra directamente en el modo de preguntas de verdad y responded por turnos. | Conversación y anécdotas personales. |
| 08 Reto | Entra directamente en el modo de retos y seguid las indicaciones de cada actividad. | Desafíos para animar la participación. |
| 09 Modo Mixto | Elige Chill o Wild; el juego selecciona desafíos al azar. Seguid las indicaciones y continuad pasando el teléfono. | Variedad sin elegir una actividad distinta en cada ronda. |

Las descripciones proceden de la ayuda y la implementación de la interfaz existentes. Los archivos de preguntas permanecen privados. Podéis saltar cualquier actividad que no queráis realizar y respetar los límites de los demás.

## Cómo empezar una sesión

1. Elige en el inicio un modo que encaje con el ambiente del grupo.
2. Sigue su preparación: añadir jugadores o elegir a quien cumple años. Usa la ruleta cuando haga falta seleccionar a alguien al azar.
3. Lee las instrucciones del modo y empieza con las preguntas, retos o temporizadores.
4. Completa o salta la actividad, pasa el teléfono y continúa con otra ronda.

## Idiomas, sonido y uso sin conexión

La aplicación dispone de interfaz y bancos de preguntas locales en chino, inglés y español. Los componentes locales gestionan el idioma, los jugadores, algunas preferencias y las opciones de audio. La música de fondo y los efectos acompañan las acciones y el ritmo del juego; sus opciones se encuentran en los ajustes.

El contenido principal funciona sin conexión. Las funciones publicitarias necesitan internet y el acceso para quitar anuncios incluye una integración de compra. Los €3.99 de la captura son texto de esa versión de la interfaz; no acreditan un precio actual de tienda ni que las compras estén activas.

## Implementación y estado actual

Flutter, Dart, localización de Flutter, SharedPreferences y audioplayers, con integraciones de Google Mobile Ads e in_app_purchase. El proyecto existente incluye compilaciones de depuración para Android y archivos de pruebas. Esta actualización utiliza capturas existentes y no vuelve a validar una compilación de distribución. Existe un proyecto iOS, pero aquí no se ha confirmado su funcionamiento.

Actualmente no hay un paquete jugable público. Una futura versión debe probarse en los dispositivos de destino y comprobar sus permisos de distribución antes de publicarse mediante GitHub Releases. Los archivos Source code automáticos solo contienen la documentación y las imágenes de esta presentación.

[Guía de publicación de una versión jugable](docs/PLAYABLE-RELEASE.md)

## Alcance público

Este repositorio publica la presentación y las vistas de interfaz. El código de la aplicación, los archivos de preguntas, los materiales de firma, los registros de desarrollo y la configuración local permanecen privados.
