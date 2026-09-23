# 💻 Portafolio Profesional — Carlos Oviedo

Portafolio web interactivo y moderno de **Carlos Andrés Oviedo**, Tecnólogo en Análisis y Desarrollo de Software (**ADSO**) en el **SENA**, desarrollador web y especialista en herramientas de Inteligencia Artificial aplicada.

🌐 **Demo en vivo**: [https://igorak404.github.io/Portafolio-Carlos-Oviedo/](https://igorak404.github.io/Portafolio-Carlos-Oviedo/)

---

## 🚀 Características

- **Diseño Cyberpunk / Terminal Moderno**: Tipografía `JetBrains Mono` e `Inter`, partículas de fondo interactivas y cursor estilo mira láser.
- **Tema Oscuro y Claro**: Switch dinámico de tema con persistencia en `localStorage`.
- **Efectos y Animaciones Fluidas**: Efecto de máquina de escribir (*typewriter*), tarjetas interactivas con resplandor (*glow*) y animaciones al hacer scroll (*reveal on scroll*).
- **Pitch Deck Interactivo — *Destiny Tower***: Presentación navegable del videojuego creado como proyecto ADSO en el SENA con estadísticas de personajes y arte en pixel art.
- **Visor Interactivo de Certificaciones**: Modal interactivo para visualizar los certificados oficiales en PDF (SENA, Scrum Fundamentals, SQL, Ciencia de Datos, PMI AI, Python, etc.) con previsualización embebida y descarga directa.
- **Proyectos Destacados**: Enlaces a demos en vivo y repositorios en GitHub (*Nativa Charles*, *Flowers 21*, *Game On*).
- **100% Compatible con GitHub Pages**: Rutas de recursos relativas y workflow automático de GitHub Actions.

---

## 🛠️ Stack Tecnológico

- **Framework**: [React 19](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- **Bundler**: [Vite](https://vitejs.dev/)
- **Estilos**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Iconos**: SVG inline optimizados y [Lucide React](https://lucide.dev/)
- **Despliegue**: GitHub Pages con GitHub Actions

---

## 📦 Instalación y Ejecución Local

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/iGoRak404/Portafolio-Carlos-Oviedo.git
   cd Portafolio-Carlos-Oviedo
   ```

2. **Instalar dependencias**:
   ```bash
   npm install
   ```

3. **Iniciar el servidor de desarrollo**:
   ```bash
   npm run dev
   ```
   Abre [http://localhost:3000](http://localhost:3000) o el puerto asignado en tu navegador.

4. **Compilar para producción**:
   ```bash
   npm run build
   ```
   Los archivos estáticos optimizados se generarán en la carpeta `dist/`.

---

## 🚀 Despliegue en GitHub Pages (3 Métodos Compatibles)

Este proyecto está configurado para que funcione con cualquiera de los métodos de GitHub Pages:

### Método 1: GitHub Actions (Recomendado y 100% automático)
1. En tu repositorio en GitHub, ve a **Settings** > **Pages**.
2. En **Build and deployment** > **Source**, selecciona **GitHub Actions** (en lugar de "Deploy from a branch").
3. Haz push a tu repositorio (`main` o `master`).
4. Ve a la pestaña **Actions** para ver la compilación. En menos de 1 minuto tu portafolio estará activo en `https://igorak404.github.io/Portafolio-Carlos-Oviedo/`.

### Método 2: Despliegue con un solo comando (`npm run deploy`)
1. En tu terminal local ejecuta:
   ```bash
   npm run deploy
   ```
2. Esto compila el proyecto y lo sube automáticamente a la rama `gh-pages`.
3. En **Settings** > **Pages**, asegúrate de que la rama seleccionada sea `gh-pages` y carpeta `/ (root)`.

### Método 3: Desde la carpeta `/docs`
1. Cada vez que ejecutas `npm run build`, se crea la carpeta `docs/` lista para producción.
2. Sube la carpeta `docs/` a tu repositorio.
3. En **Settings** > **Pages**, en **Source** selecciona **Deploy from a branch**, rama `main` (o `master`) y carpeta **/docs**.

---

## 📬 Contacto

- **Email**: [carlosandresoviedo21@gmail.com](mailto:carlosandresoviedo21@gmail.com)
- **LinkedIn**: [linkedin.com/in/carlos-oviedo-08a22b30a](https://www.linkedin.com/in/carlos-oviedo-08a22b30a/)
- **GitHub**: [@iGoRak404](https://github.com/iGoRak404)

---
© 2026 Carlos Oviedo. Construido con dedicación y código limpio.
