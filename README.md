<p align="center">
  <img src="branding/elarcast_portada.png" alt="ELARCAST · Multimedia Player" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ElarCastro/ELARCAST/releases/latest"><img src="https://img.shields.io/badge/versión-1.5-2F6BFF?style=for-the-badge" alt="Versión 1.5"></a>
  <img src="https://img.shields.io/badge/Android-8.0%2B-00E5FF?style=for-the-badge&logo=android&logoColor=white" alt="Android 8.0 o superior">
  <img src="https://img.shields.io/badge/precio-gratis-9B4DFF?style=for-the-badge" alt="Gratis">
</p>

<p align="center">
  <a href="https://github.com/ElarCastro/ELARCAST/releases/latest"><b>⬇️ Descargar ELARCAST para Android</b></a>
</p>

<p align="center"><b>Música · Videos · TV en vivo · Radios</b> — todo en una sola app.<br>
<sub>Creación: Elar Castro con la IA</sub></p>

---

## ✨ Funciones

| | |
|---|---|
| 🎵 **Tu música** | La música del celular ordenada por artista y álbum, con listas de reproducción que puedes guardar. |
| 🔎 **Buscar** | Encuentra canciones y videos y añádelos a tu lista con un toque. |
| 📺 **TV en vivo** | Canales abiertos por internet de varios países, por idioma y categoría, con guía de programación. |
| 📻 **Radios** | Emisoras de todo el mundo por país y género; guarda tus favoritas con ☆. |
| 🌈 **Visualizaciones** | Efectos que bailan con la música y videos a pantalla completa (giran a horizontal). |
| 🎚️ **Ecualizador** | 10 bandas con ajustes para Rock, Pop, Latino, Más graves, Voz y más, y nivelador de volumen. |
| 🔒 **Segundo plano** | Sigue sonando con la pantalla apagada; controles en la notificación y la pantalla de bloqueo. |
| 🎨 **Temas** | Tema **Elarcast** en negro, azul eléctrico, cian y violeta, y otros siete temas de color. |

## 📱 Así se ve

<table>
  <tr>
    <td align="center"><img src="branding/capturas/01-inicio.png" width="190" alt="Pantalla de inicio"><br><sub>Inicio</sub></td>
    <td align="center"><img src="branding/capturas/02-lista.png" width="190" alt="Lista de reproducción"><br><sub>Lista de reproducción</sub></td>
    <td align="center"><img src="branding/capturas/03-buscar.png" width="190" alt="Buscar"><br><sub>Buscar</sub></td>
    <td align="center"><img src="branding/capturas/04-efectos.png" width="190" alt="Visualizaciones"><br><sub>Visualizaciones</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="branding/capturas/05-ecualizador.png" width="190" alt="Ecualizador"><br><sub>Ecualizador</sub></td>
    <td align="center"><img src="branding/capturas/06-radios.png" width="190" alt="Radios"><br><sub>Radios por internet</sub></td>
    <td align="center"><img src="branding/capturas/07-tv.png" width="190" alt="TV en vivo"><br><sub>TV en vivo</sub></td>
    <td align="center"><img src="branding/capturas/08-acerca.png" width="190" alt="Acerca de"><br><sub>Acerca de</sub></td>
  </tr>
</table>

## ⬇️ Instalación

1. En tu celular, abre **[Releases](https://github.com/ElarCastro/ELARCAST/releases/latest)** y descarga **`ELARCAST-1.5-android.apk`**.
2. Abre el archivo descargado.
3. Como no viene de Google Play, Android pedirá **«Permitir instalar apps de esta fuente»**: actívalo para tu navegador o explorador de archivos y vuelve atrás.
4. Pulsa **Instalar** y abre **ELARCAST**.

> **¿Ya tenías RetroAmp para Android?** Instala ELARCAST encima, sin desinstalar: es la misma app con nombre nuevo y **conservas tus listas, favoritos y ajustes**.

**Requisitos:** Android 8.0 o superior y conexión a internet para buscar, ver TV y escuchar radios.

## ❓ Preguntas frecuentes

<details>
<summary><b>¿Dónde quedan las canciones que descargo?</b></summary>

Los botones **MP3** y **MP3 TODO** guardan el audio en **Música › ELARCAST** y los videos en **Películas › ELARCAST**. Los encuentras con tu explorador de archivos o tu app de música.
</details>

<details>
<summary><b>Un canal de TV o una radio no se reproduce</b></summary>

Los canales y emisoras son transmisiones públicas de terceros y a veces dejan de emitir. ELARCAST te avisa cuando uno no está disponible; elige otro. En la Biblioteca, **REVISAR** marca cuáles están transmitiendo.
</details>

<details>
<summary><b>¿Necesito una cuenta?</b></summary>

No. ELARCAST funciona sin registrarte.
</details>

<details>
<summary><b>¿Cómo pongo un video a pantalla completa?</b></summary>

En la pestaña **Video**, pulsa **⛶ COMPLETA** o toca dos veces la pantalla. Para salir, usa **Atrás** o vuelve a tocar dos veces.
</details>

## 🛠️ Para desarrolladores

<details>
<summary>Estructura del proyecto y compilación</summary>

| Carpeta / archivo | Contenido |
|---|---|
| `android/` | Proyecto de Android (Gradle) |
| `elarcast.html` | Interfaz de la app (se copia al APK al compilar) |
| `lib/`, `VT323-Regular.ttf` | Reproductor HLS y fuente de la pantalla LCD |
| `branding/` | Logotipo, iconos, capturas y recursos para Google Play |
| `.github/workflows/android.yml` | Compilación automática del APK |

GitHub Actions compila la APK en cada cambio y la deja en **Releases › ELARCAST Android (pruebas)**.
A mano: JDK 17, Android SDK 35 y Gradle 8.10.2; copia `elarcast.html`, `lib/hls.min.js` y `VT323-Regular.ttf` a `android/app/src/main/assets/www/` y ejecuta `gradle assembleRelease` dentro de `android/`.
</details>

---

<p align="center">
  <img src="branding/elarcast_icono_1024.png" width="64" alt=""><br>
  <b>ELARCAST · MULTIMEDIA PLAYER</b><br>
  <sub>Creación: Elar Castro con la IA</sub>
</p>
