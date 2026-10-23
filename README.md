# Democratizando ESEROver 🚀
 
Rover lunar/marciano de bajo costo para centros educativos, basado en **micro:bit** y programado con **MicroBlocks**.
 
## 🌐 Ver la guía
 
👉 **[Abrir la guía de Democratizando ESEROver](https://material-robotica.github.io/democratizando_eserover/index.html)**
 
La guía incluye:
 
| Sección | Contenido |
|---|---|
| [Inicio](https://material-robotica.github.io/democratizando_eserover/index.html) | Justificación del proyecto |
| [Hardware](https://material-robotica.github.io/democratizando_eserover/hardware.html) | Componentes del robot |
| [Software](https://material-robotica.github.io/democratizando_eserover/software.html) | Entorno de programación MicroBlocks |
| [Librería](https://material-robotica.github.io/democratizando_eserover/libreria.html) | Bloques para controlar el movimiento |
| [Demo](https://material-robotica.github.io/democratizando_eserover/demo.html) | Control remoto por radio |
| [Librerías y programas](https://material-robotica.github.io/democratizando_eserover/libreras_y_programas.html) | Descarga de archivos |
 
## 🔧 Hardware
 
- Robot tipo oruga con tracción trasera.
- Dos servomotores de rotación continua.
- Placa **micro:bit** o **microSTEAMakers** con shield de conexionado.
- Batería Li-ion en formato pila de 9 V.
## 💻 Archivos de programación
 
Los archivos se abren en [MicroBlocks](https://microblocks.fun/), que funciona directamente en el navegador.
 
| Archivo | Descripción |
|---|---|
| `Eserover2M.ubl` | Librería con los bloques `Setup pins left _ right _` y `move action _ velocity _` |
| `rover_emisor.ubp` | Programa para la micro:bit que funciona como control remoto (por inclinación) |
| `rover_receptor.ubp` | Programa para la micro:bit montada en el robot |
 
### Bloque `move`
 
| Acción | Movimiento |
|---|---|
| `f` | Adelante |
| `b` | Atrás |
| `l` | Pivotar a la izquierda |
| `r` | Pivotar a la derecha |
 
La velocidad va de **0 a 10**. Con velocidad 0 el robot se detiene.
 
### Demo: control remoto
 
La placa emisora detecta su inclinación y envía una letra por radio (`f`, `b`, `l`, `r`, o `s` para detenerse). La placa receptora recibe la letra y mueve el robot. Ambas usan el **grupo de radio 5**. En el receptor, los servos se conectan en los pines **0 (izquierdo)** y **1 (derecho)**.
 
## 🙌 Créditos
 
Proyecto original del [Club de Robótica de Granada](https://github.com/clubroboticagranada/democratizando_eserover). Librería y programas de **Pedro Ruiz**. Sitio creado con [eXeLearning](https://exelearning.net/).
 
## 📄 Licencia
 
Obra publicada con licencia [Creative Commons Reconocimiento-CompartirIgual 4.0 (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/deed.es).
 
