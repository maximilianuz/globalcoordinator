<div align="center">
  <p>
    <a href="#english">English</a> | <a href="#español">Español</a>
  </p>
</div>

---

<h1 id="english">🌍 Global Time Coordinator</h1>

An ultra-simple, zero-friction single-page web application (SPA) designed to seamlessly coordinate schedules between community members (like Skool) living in different countries.

## 🚀 Project Philosophy
- **Zero Friction:** No sign-ups, no logins, and no databases.
- **Everything in the URL:** The state travels 100% in the URL parameters, making sharing instantaneous.
- **Visual Sharing Priority:** Built to display multiple timezones at once and easily capture them as an image.
- **Local Privacy:** No external API calls. Relies purely on [Luxon](https://moment.github.io/luxon/) and the built-in IANA database in modern browsers.
- **Auto-Localization (i18n):** Automatically translates the interface and country names based on the user's browser language.

## ✨ Core Features
1. **Creator View:** Set up an event with your date, time, and timezone. A magic link is generated instantly.
2. **Equivalence Dashboard (Guest View):** Guests opening the link will see:
   - The creator's original time.
   - Their **Local Time**, automatically detected.
   - A customizable grid to add schedules from multiple obscure or common countries simultaneously.
3. **Copy as Image for Skool:** A dedicated button that captures the schedule grid directly to the system clipboard using `html-to-image`. Just click, then `Ctrl+V` into your Skool comment!

## 🛠️ Tech Stack
- **React 18** (Via CDN, JSX transformed by standalone Babel on the client)
- **Tailwind CSS** (Via CDN for instant utility styling)
- **Luxon** (Precise timezone management)
- **html-to-image** (For clipboard screenshots)
---

<h1 id="español">🌍 Global Time Coordinator</h1>

Una aplicación web de una sola página (SPA) ultra-simple y directa, diseñada para coordinar horarios entre miembros de comunidades (como Skool) que viven en distintos países. 

## 🚀 Filosofía del Proyecto
- **Cero Fricción:** Sin registros, sin inicios de sesión y sin bases de datos.
- **Todo en la URL:** El estado viaja 100% en los parámetros de la URL, lo que lo hace instantáneo de compartir.
- **Pensado para Compartir:** La prioridad es visualizar múltiples países de una vez y capturarlo visualmente.
- **Privacidad Local:** Sin llamadas a APIs externas. Depende puramente de [Luxon](https://moment.github.io/luxon/) y la base de datos IANA integrada en los navegadores modernos.
- **Localización Automática (i18n):** Traduce automáticamente la interfaz y los nombres de los países según el idioma del navegador del usuario.

## ✨ Funcionalidades Principales
1. **Vista de Creador:** Configura un evento con fecha, hora y zona horaria. Se genera un enlace mágico al instante.
2. **Tablero de Equivalencias (Vista de Invitado):** Los invitados que abran el enlace verán:
   - La hora original del creador.
   - Su **Hora Local** detectada automáticamente.
   - Un tablero personalizable para añadir horarios de múltiples países simultáneamente.
3. **Copiar como Imagen para Skool:** Un botón dedicado que toma el tablero de horarios y lo copia al portapapeles del sistema operativo usando `html-to-image`. Así de simple: Click -> Ctrl+V en tu comentario de Skool.

## 🛠️ Tecnologías Utilizadas
- **React 18** (Vía CDN, JSX transformado por Babel en el cliente)
- **Tailwind CSS** (Vía CDN para estilos utilitarios instantáneos)
- **Luxon** (Gestión precisa de Zonas Horarias)
- **html-to-image** (Para la captura de pantalla al portapapeles)
