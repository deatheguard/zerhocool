# ⚜ Primeras Contribuciones

Es complicado. Resulta difícil la primera vez que haces algo, especialmente cuando colaboras con otros, pues cometer errores no es nada agradable.

- Nuestro objetivo es simplificar la forma en la que los nuevos contribuidores de codigo abierto aprenden y contribuyen por primera vez.

- Leer artículos y ver tutoriales puede ayudar, pero, ¿Qué mejor que hacer las cosas en un entorno de prácticas?

- Este proyecto se enfoca en ser una guía y en simplificar la forma en la que los principiantes hacen su primera contribución.

- Si quieres hacer tu primera contribución, sigue los pasos que se muestran a continuación.

## ⚜ Si no estás familiarizado con la línea de comandos

Aquí hay tutoriales usando herramientas con Interfaz Gráfica (GUI) / (Tutoriales con otras herramientas)

- Si no tienes git en tu equipo, puedes encontrar instrucciones para instalarlo en [este enlace](https://docs.github.com/es/get-started/quickstart/set-up-git)

## ⚜ Bifurca (Fork) este repositorio

Haz un _fork_ de este repositorio haciendo click en el botón " _Fork_" en la parte superior derecha en esta página.
![fork de este repositorio](https://firstcontributions.github.io/assets/Readme/fork.png)

Si no tienes git en tu equipo, puedes encontrar instrucciones para instalarlo en [este enlace](https://docs.github.com/es/get-started/quickstart/set-up-git).

- Esto creará una copia de este repositorio en tu cuenta.

## ⚜ Clona (_Clone_) el repositorio bifurcado ![clonar este repositorio](https://firstcontributions.github.io/assets/Readme/clone.png)

- Ahora clona este repositorio en tu equipo. Dirígete a tu cuenta de GitHub, haz click en el botón " _clone or download_" y luego haz click en el icono para _copiar al portapapeles_.

- Abre tu consola o terminal y ejecuta el siguiente comando de git: `git clone "url que acabas de copiar"`

- Donde pone "url que acabas de copiar" (sin las comillas dobles) es la _url_ a este repositorio (tu _fork_ a este proyecto).

Mira los pasos previos para obtener la _url_. ![copiar URL al portapapeles](https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png)

La parte de `este-eres-tu` la reemplazarás con tu usuario de GitHub.

Aquí estás copiando los contenidos del repositorio _first-contributions_ en GitHub a tu equipo.

## ⚜ Crea una rama (_Branch_)

- Cambia al directorio del repositorio en tu equipo (si es que no estás ahí ya). `cd first-contributions`

- Ahora crea una rama (_branch_) usando el comando `git checkout`: `git checkout -b` Por ejemplo: `git checkout -b add-alonzo-church`

- El nombre de la rama no tiene por qué contener la palabra _add_, pero es razonable que lo tenga porque el objetivo de esta rama es añadir tu nombre a la lista.

## ⚜ Haz los cambios necesarios y confirma (_Commit_) esos cambios

- Abre el archivo `Contributors.md` en un editor de texto y añade tu nombre

- No lo añadas ni al principio ni al final del archivo, hazlo en cualquier otro sitio. Guarda el archivo. ![git status](https://firstcontributions.github.io/assets/Readme/git-status.png)

- Si vas al directorio del proyecto y ejecutas el comando `git status`, verás que hay cambios.

- Agrega esos cambios a la rama (_branch_) que creaste anteriormente usando el comando `git add`:`git add Contributors.md`

Ahora haz un _commit_ sobre estos cambios ejecutando el comando `git commit`:`git commit -m "Add to Contributors list"` cambiando con tu nombre.

## ⚜ Sube (_Push_) tus cambios a GitHub

- Haz _push_ de tus cambios usando el comando `git push`:`git push origin` `Reemplaza` con el nombre de la rama que creaste anteriormente

## ⚜ Envía (_Submit_) tus cambios para ser revisados

- Si vas a tu repositorio en GitHub, verás un botón `Compare & pull request`

Haz click sobre este botón. ![crea una pull request](https://firstcontributions.github.io/assets/Readme/compare-and-pull.png)

Ahora envía la _pull request_. ![enviar la pull request](https://firstcontributions.github.io/assets/Readme/submit-pull-request.png)

Pronto estaré fusionando tus cambios (haciendo _merge_) con la rama master de este proyecto. Recibirás una notificación por correo electrónico cuando los cambios hayan sido fusionados.

## ⚜ ¿Cuáles son los siguientes pasos?

- ¡Enhorabuena! ¡Has completado el flujo de trabajo fork -> clone -> edit -> PR que encontrarás habitualmente como contribuidor!

- Celebra tu contribución y compártela con tus amigos y seguidores.

## Licencia 📄

- Licencia GNU GPL V.3 Copyright (c) 2023 Andres Antonio Cardoso <https://github.com/zerhocool>
- Licencia Copyleft Copyright (c) 2023 Andres Antonio Cardoso <https://github.com/zerhocool>
- Licencia de Creative Commons Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional Copyright (c) 2023 Andres Antonio Cardoso <https://github.com/zerhocool>

**Diseño y Desarrollo por ZERHO COOL - Copyrigh © 1999-2023 ZERHO COOL - Todos los derechos reservados - Empresa en Tallinn, Estonia.**

---

<a rel="licencia" href="https://www.gnu.org/"><img alt="Licencia GNU General Publica " style="border-width:0" src="https://cdn.discordapp.com/attachments/1072960128820715602/1092305619681300520/gplv3-with-text-136x68.png" />⠀⠀⠀⠀<img alt="Software Freedom Conservancy " style="border-width:0" src="https://cdn.discordapp.com/attachments/1072960128820715602/1092474752779694181/conservancy-header.png" />⠀⠀⠀⠀⠀</a><br />Esta obra está bajo <a rel="licencia" href="https://www.gnu.org/licenses/gpl-3.0.html">Licencia GNU General Publica (GNU GPL v3.0) -</a>
<a rel="licencia" href="http://next.copyleft.org/pages/current-release.html">Software Freedom Conservancy.</a>
