<div align="center">

[English](README.md) · [Português (Brasil)](README.pt-BR.md) · **Español**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="media/aioncore-logo-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="media/aioncore-logo-light.svg">
  <img alt="AionCore" src="media/aioncore-logo-light.svg" width="340">
</picture>

### Mira el DPS de tu grupo, encuentra el Cubo Oculto y contrólalo todo desde una barra sobre el juego.<br>Una app gratis para Aion 2 en Windows.

[![Versión](https://img.shields.io/github/v/release/filvoch/AionCoreUpdate?label=versi%C3%B3n&color=1a9bbd)](https://github.com/filvoch/AionCoreUpdate/releases/latest)
![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows&logoColor=white)
![Gratis](https://img.shields.io/badge/precio-gratis-2ea44f)

<a href="https://github.com/filvoch/AionCoreUpdate/releases/latest/download/AionCore-Setup.exe"><img alt="Descargar AionCore para Windows (AionCore-Setup.exe)" src="https://img.shields.io/badge/Descargar_para_Windows-AionCore--Setup.exe-1a9bbd?style=for-the-badge&logo=windows&logoColor=white"></a>

<sub>Instalador de unos 195 MB · se actualiza solo · Windows 10 u 11, 64 bits · [Todas las versiones](https://github.com/filvoch/AionCoreUpdate/releases) · [Sitio web](https://aioncore.app/es) · [Discord](https://aioncore.app/discord)</sub>

<img alt="Captura de pantalla del Radar de Cubos con norte fijo: tú en el centro con una flecha hacia donde miras, tres Cubos Ocultos alrededor, el más cercano destacado con una línea, y el texto &quot;Cube 38 m northeast&quot; y &quot;+2 more · ahead, to the right&quot; (app en inglés, datos de ejemplo)" src="media/shot-radar.jpg" width="820">

</div>

> [!NOTE]
> El medidor necesita [Npcap](https://npcap.com) (el instalador lo comprueba y avisa si falta), y Aion 2 debe estar en modo **Ventana sin bordes** o **Ventana**. Mira [Instala en 3 pasos](#instala-en-3-pasos).

## Por qué descargarlo

- **Descubre quién cargó el combate.** Daño, DPS y porcentaje de cada jugador del grupo, habilidad por habilidad.
- **No pierdas ningún combate.** Cada combate queda en el historial de tu PC, para compararlo con el siguiente intento.
- **Encuentra el Cubo Oculto.** El radar se abre solo cuando el juego muestra un cubo cerca y te dice adónde ir.
- **Todo en una barra sobre el juego.** Un botón para cada ventana, un candado que deja pasar el clic y nada delante cuando abres el mapa o el inventario.

## Novedades desde la 1.20

- **PvP automático y gratis, con Abyss Rank:** una tarjeta sobre el juego se activa sola en un combate PvP o en el Abismo/Grieta, con K/D/A, historial de partidas y tu Abyss Rank, sin necesitar apoyo.
- **AionCore 2.0, el nuevo aspecto predeterminado:** panel del medidor rediseñado, con imágenes de portada, color y animación del nick, y modo Entrenamiento para quienes apoyan.
- **Avisos de mecánica del jefe con las líneas del propio juego**, una tarjeta de Amenaza para quienes apoyan, y un resumen del jugador al pasar el mouse, con habilidades, buffs y el golpe más grande.
- **Medidor más fluido:** barras continuas, el número de DPS se desliza y las filas que cambian de lugar se deslizan hasta el nuevo puesto.
- **Pantalla de plugins rediseñada:** activa, desactiva u oculta cada overlay desde una sola pestaña, con vista de Lista o Cuadrícula.

[Todo lo que cambió](https://github.com/filvoch/AionCoreUpdate/releases/latest) · [Las pantallas nuevas en el sitio](https://aioncore.app/es/features)

## Medidor de DPS del grupo

- **Todo el grupo de un vistazo:** una fila por jugador con daño, DPS y porcentaje. Pestañas **HPS**, **APS** (golpes por segundo) y **Recibido** para la curación, los golpes y el daño recibido. Alcance **Yo**, **Grupo**, **Raid** o **Automático**.
- **Cada habilidad al detalle:** haz clic en un nombre y mira golpes, críticos, golpes por la espalda, multigolpes, promedio, mínimo y máximo, gráfico y registro.
- **Tiempos del jefe:** HP del jefe en números, **Derrota en** (estimación según lo rápido que baja el HP) y **Furia en** para jefes con tiempo de furia conocido.
- **Cada combate guardado en tu PC:** **Historial**, resumen de cada combate, **Comparar combates**, **Runs de jefes**, resumen de tu muerte y exportar a JSON, CSV o PNG.
- **Grupo flotante:** la vida de tu grupo en una ventana pequeña.
- **Cinco visuales gratis:** Franjas, Clásico, Denso, Panel y Cristal, y el **acabado Cristal** sobre Denso, Panel y Franjas.
- **Barra de abajo, gratis en todos los visuales:** copiar el DPS del grupo al chat (AionCore solo copia; quien pega eres tú) y captura solo del medidor.

<p align="center"><img alt="Captura de pantalla de AionCore Meter en el visual Franjas durante un combate contra un jefe: arriba el HP del jefe con Derrota en y Furia en, y debajo una fila por jugador, seis jugadores, con daño, DPS y porcentaje (app en inglés, datos de ejemplo, nombres inventados)" src="media/shot-meter.jpg" width="400"></p>

## Radar de Cubos Ocultos

Una ventanita que se abre sola cuando el juego muestra un Cubo Oculto cerca de ti y desaparece cuando no hay ninguno.

- **Automático:** se abre cuando aparece un cubo aún cerrado y se oculta unos 3 segundos después de que desaparece el último. ¿Prefieres verlo siempre? Activa **Mantener el radar siempre visible**.
- **Norte fijo**, como el minimapa del juego, o **Gira contigo**.
- **Varios cubos:** el cubo actual tiene el punto más grande y la línea; el texto muestra «+N más».
- **Altura, zoom y tamaño:** un cubo a 3 m o más por encima o por debajo de ti recibe una marca ▲ o ▼ y el texto dice cuántos metros. Desbloquea el radar para acercar con la rueda del mouse y arrastrar los bordes.
- **Avisos que te dicen adónde ir:** a menos de 80, 50, 25 y 10 m, si el cubo está a tu derecha, delante o detrás, y cuando otro jugador ya lo abrió.

El radar muestra solo los cubos que envía el juego. El juego solo informa tu posición cuando usas una habilidad o un dash; sin una posición reciente, el radar muestra «Cubo detectado» y te pide que te muevas. Todo está en **Configuración › Avisos y eventos**.

<p align="center"><img alt="Demostración animada del Radar de Cubos: un Cubo Oculto al noreste, delante de ti, se acerca mientras caminas hacia él, de 85 m a 18 m (app en inglés, datos de ejemplo)" src="media/demo.gif" width="720"></p>

## Barra superior y ventana principal

- **Barra superior:** un botón para el medidor, el grupo flotante, el checklist, los temporizadores, el radar de mascotas, los avisos de mecánica, la guía de mazmorras y YouTube. El candado bloquea todo y el clic pasa directo al juego. Opacidad de 20 % a 100 % y modo contraído.
- **Ventana principal:** Inicio con la cuenta regresiva para el reinicio diario y semanal, tus personajes, los próximos eventos y tu último combate; Ctrl+K busca pantallas y comandos. Se abre desde la barra, la bandeja de Windows o con Ctrl+Alt+A.
- **Sin estorbar:** la barra y los overlays se ocultan cuando otro programa está delante y cuando se abre un menú del juego (Esc, mapa, inventario). Con **Abrir AionCore como administrador** activado, AionCore solo comprueba si las teclas Alt y Esc están pulsadas, solo con el juego en primer plano; ninguna otra tecla, y no se graba ni se envía nada. Sin el modo administrador, se guía por el cursor del juego. Se desactiva en **Configuración › En el juego**.
- **Atajos Ctrl+Alt** que funcionan sobre el juego (M medidor, G grupo, H contraer la barra, L bloquear, K clic transparente, D ocultar todo). Si otro programa ya usa uno, AionCore te ofrece cambiarlo.
- El PvP automático es gratis; Amenaza es para quienes apoyan; Objetivo PvP está en Acceso Anticipado de apoyo. El **Mapa** es una pestaña gratis de la ventana principal.

<p align="center"><img alt="Captura de pantalla de la barra de AionCore: el nombre a la izquierda, una fila de botones con iconos, el control de opacidad en 100 %, el candado y los botones de contraer, ajustes y cerrar (app en inglés)" src="media/shot-bar.jpg" width="880"></p>

<p align="center"><img alt="Captura de pantalla de la ventana principal en Inicio: menú lateral con Inicio, Checklist, Medidor, Mazmorras, Agenda y Mascotas, la cuenta regresiva de los reinicios diario y semanal, lo que no debes perderte, dos personajes, los próximos eventos y el último combate (app en inglés, datos de ejemplo, nombres inventados)" src="media/shot-home.jpg" width="820"></p>

## Mecánicas de jefe

- **Panel de mecánicas:** lo que hace el jefe y lo que debes hacer tú, por mazmorra. Gratis. La cobertura crece con cada versión, y las mecánicas aún no comprobadas en el juego vienen marcadas.
- **Avisos de mecánica en pantalla:** de una a tres palabras en la parte superior de la pantalla antes del golpe. Primero para quienes apoyan; para todos a partir del **10 de noviembre de 2026**.

## En validación

Ya vienen en el instalador y pasaron las pruebas automáticas, pero todavía no se comprobaron en vivo en el juego:

- **Checklist:** tareas diarias y semanales por personaje. Las Misiones del Deber, el límite de Kinah del día, los Puntos del Abismo de la semana y la Energía de Od se leen del juego; el resto lo marcas tú.
- **Agenda y Temporizadores:** los eventos de la semana con cuenta regresiva y los jefes de campo leídos del juego al abrir el mapa del mundo.
- **Mascotas:** tu colección por familia, las almas que te faltan y dónde farmearlas. El **radar de mascotas** muestra los monstruos cercanos que dan un alma que te falta; viene desactivado.

<table>
  <tr>
    <td width="50%"><img alt="Captura de pantalla del Checklist de un personaje: Energía de Od, límites de ganancia, tareas diarias y semanales, unas leídas del juego y otras marcadas a mano (app en inglés, datos de ejemplo, nombres inventados)" src="media/shot-checklist.jpg"></td>
    <td width="50%"><img alt="Captura de pantalla de la Agenda: los eventos de la semana con horarios y cuenta regresiva, y el bloque de jefes de campo esperando a que se abra el mapa del juego (app en inglés, datos de ejemplo)" src="media/shot-agenda.jpg"></td>
  </tr>
  <tr>
    <td align="center"><sub>Checklist</sub></td>
    <td align="center"><sub>Agenda</sub></td>
  </tr>
  <tr>
    <td width="50%"><img alt="Captura de pantalla de la pestaña Mascotas: la colección por familia, el mapa de farmeo con los puntos de cada familia y las mascotas más cerca del siguiente nivel (app en inglés, datos de ejemplo)" src="media/shot-pets.jpg"></td>
    <td width="50%"><img alt="Captura de pantalla del radar de mascotas: monstruos cercanos que dan un alma que te falta, con distancia aproximada y un minirradar (app en inglés, datos de ejemplo)" src="media/shot-petradar.jpg"></td>
  </tr>
  <tr>
    <td align="center"><sub>Mascotas</sub></td>
    <td align="center"><sub>Radar de mascotas</sub></td>
  </tr>
</table>

¿Viste algo raro? Cuéntanoslo en [Discord](https://aioncore.app/discord) o abre un [issue](https://github.com/filvoch/AionCoreUpdate/issues).

## Instala en 3 pasos

Requisitos: Windows 10 (1809 o más nuevo) u 11, 64 bits.

1. [Descarga el instalador](https://github.com/filvoch/AionCoreUpdate/releases/latest/download/AionCore-Setup.exe) y ejecútalo. Se instala solo para tu usuario. Si Windows muestra «Windows protegió su PC», haz clic en **Más información** y luego en **Ejecutar de todas formas** ([por qué](#preguntas-frecuentes)).
2. Instala [Npcap](https://npcap.com) una vez, marcando *Install Npcap in WinPcap API-compatible Mode* y *Support loopback traffic*. Si falta, el instalador de AionCore avisa y abre el sitio de Npcap al final.
3. Abre AionCore desde el acceso directo. En Aion 2, usa **Ventana sin bordes** o **Ventana**: Windows no deja que nada aparezca sobre la pantalla completa exclusiva.

La primera vez eliges el idioma y la región y lees el aviso de uso y datos. Conectar tu cuenta de Discord es opcional. App y sitio web en 6 idiomas: español, inglés, portugués, alemán, francés y ruso (alemán, francés y ruso son traducción automática revisada, aún sin revisión de hablantes nativos).

AionCore se actualiza solo: comprueba la firma digital del instalador y no se instala por sí solo mientras Aion 2 está abierto (si haces clic en **Actualizar** con el juego abierto, te pregunta antes, y el medidor pierde el combate en curso). Tu configuración y tu historial de combates se conservan entre versiones.

## Para quienes apoyan

AionCore es gratis. Si quieres ayudar a mantenerlo, puedes apoyar en Ko-fi con cualquier monto. Un pago único de **US$ 15 o más, en dólares** (el artículo de la tienda de Ko-fi o una donación única) te convierte en **persona que apoya durante 12 meses**, **sin renovación automática**. Los montos menores son un agradecimiento, sin ventajas. **Todo lo que ya salió gratis sigue gratis para siempre.**

Lo que tiene hoy quien apoya:

- **AionCore Theme:** el nuevo visual del medidor, con parte superior en dos líneas, flecha de tendencia en cada jugador, hasta 4 columnas por rol (Tanque, DPS y Sanador) y **Solo yo** con tus mejores habilidades.
- **Avisos fuera del juego:** ¿hiciste alt-tab o minimizaste el juego? Las invitaciones de grupo y de Expedición, las llamadas para entrar y las solicitudes de entrada aparecen sobre cualquier ventana. Haz clic y AionCore trae el juego al frente; nunca hace clic ni acepta nada por ti. Gratis para todos desde el 11/01/2027.
- **Panel de sala:** quién está en la sala, el GS y el poder de combate de cada uno y quién está listo. Gratis para todos desde el 11/02/2027.
- **Tarjeta del candidato:** quien pide entrar en tu sala aparece en una ventanita con clase, nivel, GS y los combates que ya jugaron juntos, y puedes consultar el resumen de su perfil público en el sitio.
- **Temas de color** del medidor.
- **Análisis de habilidades:** una pestaña en los detalles de cada jugador, en vivo y en el Historial, con usos estimados, daño por uso, DPS activo, picos y línea de tiempo de cada habilidad.
- **Sello de apoyo:** un sello en tu fila del medidor con gema, estilo y movimiento, y una barra de éter del color de tu barra. Solo tú lo ves en tu medidor.
- **Informe de la Arena:** en el Resumen de un combate de Arena, una tarjeta con resultado, puntuación, duración, bajas y muertes (lo que el juego aún no informó queda en blanco; hoy solo se reconoce la victoria).
- **Antes que nadie:** avisos de mecánica de jefe (hasta el 10/11/2026) y avisos de la barra de guardia del jefe (hasta el 11/11/2026).

<table>
  <tr>
    <td width="50%"><img alt="Captura de pantalla de tres avisos fuera del juego apilados: llamada para unirse, invitación de Expedición e invitación de grupo, cada uno con la clase, el nivel, el GS, el poder de combate y el servidor del jugador (app en inglés, datos de ejemplo, nombres inventados)" src="media/shot-alerts.jpg"></td>
    <td width="50%"><img alt="Captura de pantalla del Panel de sala: cuatro miembros con GS, poder de combate, nivel y quién está listo, una plaza libre y dos solicitudes para unirse (app en inglés, datos de ejemplo, nombres inventados)" src="media/shot-room.jpg"></td>
  </tr>
  <tr>
    <td align="center"><sub>Avisos fuera del juego</sub></td>
    <td align="center"><sub>Panel de sala</sub></td>
  </tr>
</table>

[Apoya a AionCore](https://aioncore.app/es/apoie)

<sub>Sin publicidad pagada. En Inicio y en Configuración › Acerca de hay una tarjeta de socio (enlace de afiliado), avisada en pantalla: AionCore puede recibir una comisión sin costo extra para ti.</sub>

## Tus datos

Tus combates se quedan en tu PC. Sin conectar una cuenta, ningún combate sale de él. Conectar la cuenta (con Discord) es opcional; al conectarla, un aviso muestra lo que va a [aioncore.app](https://aioncore.app/es) y se activa el envío de los combates de jefe y de las inspecciones. Se desactiva con un clic en **Configuración › Cuenta y envío**. Detalles en la [política de privacidad](https://aioncore.app/es/privacidade).

## Preguntas frecuentes

<details>
<summary><b>¿Me pueden banear?</b></summary>

AionCore lee el tráfico de red de tu PC y el título de la ventana del juego. No cambia archivos ni la memoria del juego. No envía teclas ni clics al juego: copiar el DPS al chat solo copia, quien pega eres tú. Aun así, ninguna herramienta de este tipo puede garantizar lo que decida la política del juego: el riesgo de usarla es tuyo.
</details>

<details>
<summary><b>¿AionCore lee lo que escribo?</b></summary>

No. Con **En los menús del juego** activado y AionCore ejecutándose como administrador, solo comprueba si las teclas Alt y Esc están pulsadas, y solo con Aion 2 en primer plano, para saber si se abrió un menú del juego. No lee ninguna otra tecla, y no se graba ni se envía nada. Se desactiva en **Configuración › En el juego**.
</details>

<details>
<summary><b>¿Qué servidores y regiones funcionan?</b></summary>

Hecho y probado en Aion 2 Global (servidores de Sudamérica). En otras regiones (Taiwán, Corea) puede funcionar, pero aún no está garantizado.
</details>

<details>
<summary><b>¿El medidor es preciso?</b></summary>

Cuenta lo que envía el juego. En algunos casos el medidor no ve todo, y avisa cuando no está leyendo el juego. El sitio explica cómo mide: [precisión](https://aioncore.app/es/precisao).
</details>

<details>
<summary><b>¿Hay que ejecutarlo como administrador?</b></summary>

No por defecto: AionCore se instala solo para tu usuario y se abre sin pedir permisos de administrador. Tres casos lo cambian:

- Si tu Npcap se instaló con la opción *Restrict Npcap driver's access to Administrators only*, el medidor muestra el botón **Reabrir como administrador** (vale solo esa vez). Para no necesitarlo nunca, reinstala Npcap sin marcar esa opción.
- **En los menús del juego** (ocultar la barra y los overlays cuando se abre un menú del juego): para ver si Alt y Esc están pulsadas con el juego en primer plano, AionCore tiene que ejecutarse como administrador. Sin eso, se guía por el cursor del juego.
- Si Aion 2 se ejecuta como administrador, el clic en un aviso fuera del juego solo trae el juego al frente si AionCore también se ejecuta como administrador.

Para estos casos existe **Configuración › General › Abrir AionCore como administrador**, desactivado por defecto. Al activarlo, Windows pide el permiso (UAC).
</details>

<details>
<summary><b>La barra o el medidor desaparecen cuando el juego está al frente.</b></summary>

El juego está en **Pantalla completa** exclusiva, y Windows no muestra ventanas encima. En las opciones de video de Aion 2, cambia a **Ventana sin bordes**.
</details>

<details>
<summary><b>Windows o el antivirus avisó al instalar.</b></summary>

El instalador no tiene un certificado de firma de código de pago, así que Windows no conoce al editor y muestra «Windows protegió su PC». Haz clic en **Más información** y luego en **Ejecutar de todas formas**. Un antivirus puede pedir confirmación por el mismo motivo. Para comprobar que el archivo es el original, compara el valor `sha256` de `latest.json` (en los Assets de la [versión más reciente](https://github.com/filvoch/AionCoreUpdate/releases/latest)) con el resultado de:

```powershell
Get-FileHash .\AionCore-Setup.exe
```
</details>

<details>
<summary><b>¿Qué sale de mi PC?</b></summary>

Sin una cuenta conectada, ningún combate sale de tu PC. AionCore descarga los iconos de las habilidades desde la CDN del juego y consulta este repositorio para saber si hay versión nueva. Con la cuenta conectada, van a aioncore.app los combates de jefe y las inspecciones, como dice el aviso antes de activarse; se desactiva en **Configuración › Cuenta y envío**. La consulta del perfil en la tarjeta del candidato envía solo nombre y servidor (se desactiva en **Configuración › Avisos y eventos › Invitación de grupo**).
</details>

<details>
<summary><b>¿Cómo lo desinstalo? ¿Pierdo mis datos?</b></summary>

*Configuración de Windows › Aplicaciones instaladas › AionCore*. El desinstalador pregunta si también borra tus datos (historial, configuración); por defecto los conserva. Instalar una versión nueva encima también conserva todo.
</details>

<details>
<summary><b>¿Es oficial? ¿El código es abierto?</b></summary>

No y no. AionCore es un proyecto independiente, hecho por un jugador, sin vínculo con NCSOFT. El código fuente no es público: este repositorio guarda los instaladores publicados, esta página y los archivos de traducción, abiertos a contribuciones.
</details>

## Contribuir

- **Errores e ideas:** abre un [issue](https://github.com/filvoch/AionCoreUpdate/issues/new/choose) y elige una plantilla (informe de error, solicitud de función o sugerencia de traducción). Nunca pegues nombres de personajes, registros ni paquetes sin quitar antes los nombres.
- **Traducciones:** los textos de la app están en la carpeta [`i18n/`](i18n/README.md). Para corregir una palabra, abre un issue con la plantilla *Translation suggestion*; para un idioma completo, envía un pull request.
- **Seguridad:** comunica las vulnerabilidades en privado, escribiendo a contato@aioncore.app, y no en un issue público. Consulta el [SECURITY.md](SECURITY.md).

## Comunidad y contacto

- **Discord:** [aioncore.app/discord](https://aioncore.app/discord)
- **Errores:** abre un [issue](https://github.com/filvoch/AionCoreUpdate/issues) o escribe a contato@aioncore.app.
- **En la app:** **Configuración › Ayuda y diagnóstico**.

## El proyecto en cifras

[![Estrellas en GitHub](https://img.shields.io/github/stars/filvoch/AionCoreUpdate?style=flat&color=1a9bbd)](https://github.com/filvoch/AionCoreUpdate/stargazers) [![Descargas del instalador](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ffilvoch%2FAionCoreUpdate%2Fstats%2Finstaller-downloads.json&style=flat)](https://github.com/filvoch/AionCoreUpdate/releases) [![Última versión](https://img.shields.io/github/v/release/filvoch/AionCoreUpdate?label=version&style=flat&color=1a9bbd)](https://github.com/filvoch/AionCoreUpdate/releases/latest)

<sub>Descargas del instalador cuenta las instalaciones y las actualizaciones automáticas de todas las versiones y se actualiza una vez al día. Las cifras vienen de los contadores del propio GitHub: AionCore no rastrea a quien visita esta página.</sub>

## Créditos

AionCore por **Guilherme Filvoch (Simavi)**.
Proyecto independiente de fans, sin vínculo con NCSOFT. Aion 2 y sus iconos, nombres y artes pertenecen a NCSOFT y a sus licenciantes.
