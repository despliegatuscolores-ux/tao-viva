# TAO · WU WEI | El Curso Espontáneo (無為)

### Zìrán & Pǔ · La Vía de la No-Fuerza y el Desaprendizaje

> *Herramienta contemplativa de código abierto para encarnar el fluir natural y la no-coacción: capítulos vivos del Daodejing y Zhuangzi, laboratorio de la mirada del agua, respiración de marea Zìrán con ondas concéntricas en Canvas, síntesis acústica de arroyo de montaña en tiempo real y diario del bloque sin tallar (Pǔ).*

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-blue.svg)](index.html)
[![Offline First](https://img.shields.io/badge/Architecture-Offline--First-orange.svg)](#arquitectura-t%C3%A9cnica)
[![Deploy with GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-violet.svg)](#despliegue-en-github-pages)
[![Collection: Pentalogía Contemplativa](https://img.shields.io/badge/Collection-Pentalog%C3%ADa%20Contemplativa-teal.svg)](#la-pentalog%C3%ADa-contemplativa)

---

## 🌊 Visión Filosófica: El Arte de No Empujar el Río

Mientras que el esfuerzo moral busca controlar la conducta y el entrenamiento ascético disciplina la voluntad, el Taoísmo clásico de Laozi y Zhuangzi propone un movimiento radicalmente inverso: **el retorno a la espontaneidad original (*Zìrán*) a través del desaprendizaje continuo (*Wéi dào rì sǔn*)**.

> *«El agua no compite con la roca: la rodea, la abraza y con paciencia infinita desgasta sus aristas. Nada en el mundo es más dócil, y nada puede vencerla. Empujar el río solo cansa los brazos; el río ya sabe cómo llegar al mar.»*

**tao-viva** es el quinto volumen de la serie contemplativa de código abierto. Desarrollada bajo la premisa estricta de **cero dependencias externas**, privacidad absoluta en el dispositivo y arquitectura desconectada (*offline-first*), la aplicación funciona como un santuario digital para desmantelar la fatiga del sobreesfuerzo moderno y reposar en el orden orgánico de la vida.

---

## ✨ Módulos Principales

### 1. El Capítulo Vivo (Integración Diaria)
* **Textos canónicos directos:** Pasajes esenciales del *Daodejing* (Laozi) y parábolas maestras del *Zhuangzi* (El Bote Vacío, El Cocinero Ding, El Árbol Nudoso).
* **Caracteres tradicionales y Pīnyīn:** Preservación de la raíz gráfica y fonética china original.
* **Clave Wu Wei:** Interpretación psicológica lúcida orientada a desactivar la compulsión de imponer la voluntad personal.
* **Micro-Práctica de Acción Espontánea:** Una acción conductual concreta para aplicar en el día a día (renunciar a tener la última palabra, habitar un vacío de 15 minutos, suspender una corrección ajena).
* **Contador de Gotas en el Flujo (💧):** Registro simbólico persistente en `localStorage` que honra la continuidad de la presencia sin esfuerzo.

### 2. Laboratorio Wu Wei (El Arte de No Forzar)
Espacio interactivo de discernimiento para desatar nudos sin romper la cuerda:
1. **Identificar la Coacción:** Registrar dónde se está intentando empujar los acontecimientos o forzar el cambio de otra persona.
2. **La Mirada del Agua (*Shuǐ*):** Consultar las tres respuestas naturales del agua:
   * *Rodear (Ceder el paso):* Encontrar el intersticio libre sin chocar contra la dureza.
   * *Sedimentar (Esperar quietud):* Dejar de agitar el fango mental para que el agua se aclare por sí sola.
   * *Descender (Ocupar el lugar bajo):* Renunciar a la superioridad moral para convertirse en océano receptor.
3. **La Resolución del No-Hacer:** Formulación de un compromiso de no-intervención deliberada por 24 horas.

### 3. Ayuno del Corazón (*Xīnzhāi*) & Marea Zìrán
* Ejercicio contemplativo de respiración coherente orgánica (marea de 5.5s inhalación / 5.5s exhalación).
* **Lienzo dinámico de ondas concéntricas en HTML5 Canvas:** Representación visual de ondas de agua que se expanden y contraen sincrónicamente con el ciclo respiratorio.
* Toques de campana pentatónica de jade en los puntos de inflexión del aliento para asentar la mente en el vacío receptivo.

### 4. Motor Acústico Procedural: Arroyo de Montaña y Campana de Jade
* **Síntesis nativa en tiempo real (Web Audio API pura):** Cero archivos `.mp3` ni enlaces a librerías externas.
* **Murmullo de Arroyo y Cañaveral:** Generación algorítmica continua basada en buffer de ruido blanco procesado por dos filtros resonantes pasa-banda modulados por osciladores de baja frecuencia (LFOs), emulando el borboteo errático y sereno del agua sobre las piedras.
* **Campana de Jade / Guqin:** Síntesis armónica con decaimiento natural y afinación pentatónica china clásica.

### 5. Diario del Bloque sin Tallar (*Pǔ - 樸*)
* Bitácora contemplativa de desaprendizaje: registrar aquello que hoy se ha dejado de controlar o fingir.
* Clasificación por sellos taoístas: *Dejar de Controlar*, *Ceder sin Resentimiento*, *Quietud ante la Provocación (La Barca Vacía)* y *Simplicidad & Moderación*.
* Exportación y copia de seguridad en un solo clic en formatos estructurado **JSON** y texto plano legible **TXT**.

### 6. Compendio del Manantial Original
* Biblioteca temática organizada por dimensiones: *El Poder del Agua*, *La Paradoja del No-Hacer*, *La Vacuidad Útil*, *La Risa de Zhuangzi* y *El Bloque sin Tallar*.
* Buscador en tiempo real por caracteres chinos, pīnyīn o conceptos en español con botón para fijar cualquier capítulo como práctica del día.

---

## 🏛️ Arquitectura Técnica

Diseñado para perdurar sin requerir actualización de dependencias, compilación ni conexión a servidores externos:

| Capa | Implementación | Propósito |
|---|---|---|
| **Estructura** | HTML5 Semántico Puro | Accesibilidad universal y renderizado instantáneo en cualquier navegador. |
| **Estética Shanshui** | Tailwind CSS CDN + Variables CSS | Paleta de tinta oscura (`#0a0d10`, `#11161d`), jade imperial suave (`#10b981`, `#34d399`), papiro beige (`#f7f4ed`) y niebla. |
| **Tipografía** | Cormorant Garamond + Cinzel + Noto Serif SC + Inter | Fusión clásica occidental y caracteres chinos tradicionales con respaldos de sistema (`Georgia`, `SimSun`, `sans-serif`). |
| **Animación Gráfica** | HTML5 Canvas 2D API | Ondas de agua concéntricas reactivas calculadas proceduralmente a 60 FPS sin librerías pesadas. |
| **Motor Sonoro** | Web Audio API Nativa | Síntesis acústica procedural en tiempo real del murmullo del agua y resonancias de campana de jade. |
| **Persistencia** | Web Storage API (`localStorage`) | Datos 100% aislados en el dispositivo del usuario. Sin cookies, servidores remotos ni telemetría. |

---

## 🚀 Puesta en Marcha

### Uso Local Inmediato
No requiere Node.js, npm, compilación ni configuración de servidor:

```bash
# 1. Clonar el repositorio
git clone https://github.com/<tu-usuario>/tao-viva.git

# 2. Entrar en la carpeta
cd tao-viva

# 3. Abrir en cualquier navegador moderno
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

### Despliegue en GitHub Pages (Gratuito y Permanente)

1. En tu cuenta de GitHub, crea un nuevo repositorio público o privado llamado `tao-viva`.
2. Sube el archivo de la aplicación renombrado como `index.html` en la raíz del repositorio, junto con este `README.md` y el archivo de licencia `LICENSE`.
3. Ve a la pestaña **Settings** del repositorio.
4. En el menú lateral izquierdo, haz clic en **Pages**.
5. En **Build and deployment > Branch**, selecciona la rama `main` (o `master`) y la carpeta `/ (root)`.
6. Haz clic en **Save**. En un par de minutos tu aplicación estará publicada globalmente en:
   ```text
   https://<tu-usuario>.github.io/tao-viva/
   ```

---

## 📜 La Pentalogía Contemplativa

Este proyecto constituye el quinto volumen de la serie contemplativa abierta, completando un mapa integral del despertar de la consciencia humana:

```text
┌────────────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                        PENTALOGÍA CONTEMPLATIVA                                        │
├─────────────────────┬────────────────────┬───────────────────┬────────────────────┬────────────────────┤
│ Vol. I · SŪTRA YOGA │ Vol. II · DHARMA   │ Vol. III · TANTRA │ Vol. IV · BHAKTI   │ Vol. V · TAO       │
├─────────────────────┼────────────────────┼───────────────────┼────────────────────┼────────────────────┤
│ Repo: sutra-yoga    │ Repo: sutra-dharma │ Repo: tantra-viva │ Repo: bhakti-viva  │ Repo: tao-viva     │
│ Raja Yoga           │ Budismo Canónico   │ Śaivismo no dual  │ Mística devocional │ Taoísmo clásico    │
│ El Hilo de la Calma │ El Sendero Lúcido  │ El Tejido Vivo    │ El Fuego del Amor  │ El Curso del Agua  │
│ Cese y disciplina   │ Vacuidad y atención│ Energía y asombro │ Rendición interior │ No-acción (Wu Wei) │
└─────────────────────┴────────────────────┴───────────────────┴────────────────────┴────────────────────┘
```

---

## 🛡️ Privacidad y Ética Digital

1. **Cero Rastreo:** Sin analíticas de terceros, sin píxeles de seguimiento publicitario y sin telemetría oculta.
2. **Cero Conexiones Salientes:** Una vez descargado el archivo, el código opera de forma local e independiente de la red.
3. **Respeto a la Quietud:** Sin banners invasivos ni mecánicas de retención compulsiva. La herramienta fomenta cerrar la pantalla para reintegrarse con el mundo físico.

---

## 📄 Licencia

Publicado bajo la Licencia **MIT**. Consulta el archivo `LICENSE` para conocer los términos completos de uso, bifurcación y redistribución abierta.