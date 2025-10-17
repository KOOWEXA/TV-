# 📺 TV_RM – Descubre contenido aleatorio de películas y series

**TV_RM** es una aplicación web ligera y moderna que te ayuda a resolver la eterna pregunta:  
> _«¿Qué veo hoy?»_

Con un solo clic, obtén una **película estrenada este año** o una **serie en emisión o próximamente estrenada**, seleccionada al azar desde la base de datos de [The Movie Database (TMDb)](https://www.themoviedb.org/). Ideal para quienes buscan inspiración sin perder tiempo navegando.

---

## 🌟 Características

- **Contenido actualizado en tiempo real**:
  - Películas estrenadas en el año actual.
  - Series **en emisión** (`On the Air`) y **próximas a estrenarse** (`Upcoming`).
- **Interfaz minimalista y oscura**: diseñada para reducir la fatiga visual.
- **Actualización automática**: cada hora, la app puede notificarte una nueva sugerencia (con permiso).
- **Sin registro ni cookies**: 100% cliente, sin recopilación de datos.
- **Totalmente responsiva**: funciona en móviles, tablets y escritorio.
- **Soporte offline parcial**: si falla la conexión, muestra la última sugerencia válida.
- **Notificaciones inteligentes**: solo si hay un nuevo contenido distinto al anterior.

---

## 🚀 Cómo usarlo

1. Abre la aplicación en tu navegador.
2. Elige entre:
   - **Películas (este año)**
   - **Series (en emisión y próximas)**
3. Haz clic en el botón **«¿QUÉ VER? +»** para obtener una sugerencia aleatoria.
4. (Opcional) Permite notificaciones para recibir actualizaciones automáticas cada hora.

¡Listo! Disfruta de tu próxima película o serie sin esfuerzo.

---

## 📡 Fuente de datos

Esta aplicación consume datos públicos de la API de **[The Movie Database (TMDb)](https://www.themoviedb.org/documentation/api)**, específicamente:

- Películas: endpoint `discover/movie` filtrado por año actual.
- Series:
  - `/tv/on_the_air` → series actualmente en emisión.
  - `/tv/upcoming` → series anunciadas para estreno futuro.

> ℹ️ TMDb es una base de datos colaborativa de cine y televisión. No está afiliada a esta aplicación.

---

## 🛡️ Privacidad y seguridad

- **No se almacenan datos del usuario**.
- **No se usan cookies ni rastreadores**.
- Toda la lógica se ejecuta en el navegador (**frontend puro**).
- Las peticiones a la API se realizan directamente desde tu dispositivo.
- Las notificaciones son opcionales y gestionadas por el navegador.

---

## 📱 Compatibilidad

Funciona en cualquier navegador moderno que soporte:
- Fetch API
- ES6+ (async/await, destructuring, etc.)
- CSS moderno (variables, `aspect-ratio`, etc.)

Probado en:
- Chrome / Edge / Firefox / Safari (últimas versiones)
- Dispositivos móviles (iOS y Android)

---

## 🎨 Diseño

- Paleta de colores inspirada en plataformas de streaming (rojo oscuro, negro, blanco).
- Tipografía clara y legible.
- Transiciones suaves y microinteracciones para mejorar la experiencia.
- Marca de agua sutil para identificación visual.

---

## 🙌 ¿Por qué TV_RM?

Porque a veces, lo más difícil no es encontrar algo bueno…  
es decidir **qué** ver.  
Deja que el azar elija por ti.

🎬 ¡Feliz visionado!