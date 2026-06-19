# Global Time Coordinator

Una aplicación web de una sola página (SPA) ultra-simple y directa, diseñada para coordinar horarios entre miembros de comunidades (como Skool) que viven en distintos países. 

## 🚀 Filosofía del Proyecto

- **Cero Fricción:** Sin registros, sin inicios de sesión y sin bases de datos.
- **Todo en la URL:** El estado viaja 100% en los parámetros de la URL, lo que lo hace instantáneo de compartir.
- **Pensado para Compartir:** La prioridad es visualizar múltiples países de una vez y capturarlo visualmente.
- **Privacidad Local:** Sin llamadas a APIs externas. Depende puramente de [Luxon](https://moment.github.io/luxon/) y la base de datos IANA integrada en los navegadores modernos.

## ✨ Funcionalidades Principales

1. **Vista de Creador:** Configura un evento con fecha, hora y zona horaria. Se genera un enlace mágico al instante.
2. **Tablero Equivalencias (Guest View):** Los invitados que abran el enlace verán:
   - La hora original del creador.
   - Su **Hora Local** detectada automáticamente.
   - Un tablero personalizable para añadir horarios de múltiples países simultáneamente.
3. **Copiar como Imagen para Skool:** Un botón dedicado que toma el tablero de horarios y lo copia al portapapeles del sistema operativo usando `html-to-image`. Así de simple: Click -> Ctrl+V en tu comentario de Skool.

## 🛠️ Tecnologías Utilizadas

- **React 18** (Vía CDN, JSX transformado por Babel en el cliente)
- **Tailwind CSS** (Vía CDN para estilos utilitarios instantáneos)
- **Luxon** (Gestión precisa de Zonas Horarias)
- **html-to-image** (Para la captura de pantalla al portapapeles)
- **Lucide Icons** (SVGs en línea para UI moderna)

## 📦 Despliegue Rápido

Como toda la aplicación vive en un solo archivo `index.html` estático, puedes desplegarla de forma gratuita en segundos:

1. **GitHub Pages:** Sube `index.html` a un repositorio y habilita Pages.
2. **Vercel / Netlify / Surge:** Arrastra la carpeta que contiene el `index.html` a tu cuenta de Vercel o Netlify para obtener una URL al instante.

¡No requiere `npm install`, ni procesos de build!
