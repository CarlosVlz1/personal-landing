# 🚀 Landing Page Personal

Una landing page moderna y responsive construida con AstroJS, lista para desplegar en Vercel.

## ✨ Características

- 🎨 Diseño moderno con gradientes y animaciones
- 📱 Totalmente responsive
- ⚡ Optimizada para rendimiento
- 🎯 SEO-friendly
- 🌈 Colores atractivos y bien combinados
- 📦 Lista para desplegar en Vercel

## 🛠️ Tecnologías

- [Astro](https://astro.build) - Framework web moderno
- TypeScript - Para type safety
- CSS3 - Animaciones y estilos personalizados

## 📋 Secciones

- **Hero** - Presentación inicial con call-to-action
- **Acerca de mí** - Información personal y highlights
- **Stack Tecnológico** - Skills con barras de progreso
- **Experiencia** - Timeline de experiencia profesional
- **Contacto** - Enlaces a redes sociales (LinkedIn, GitHub, WhatsApp)
- **Footer** - Con botón de scroll to top

## 🚀 Instalación y Uso

### Prerequisitos

- Node.js 18+ instalado
- npm, yarn o pnpm

### Pasos

1. **Instalar dependencias**

```bash
npm install
# o
yarn install
# o
pnpm install
```

2. **Ejecutar en desarrollo**

```bash
npm run dev
# o
yarn dev
# o
pnpm dev
```

La aplicación estará disponible en `http://localhost:4321`

3. **Construir para producción**

```bash
npm run build
# o
yarn build
# o
pnpm build
```

4. **Vista previa de la build**

```bash
npm run preview
# o
yarn preview
# o
pnpm preview
```

## 📝 Personalización

### 1. Información Personal

Edita los siguientes archivos para personalizar tu información:

- **`src/components/Hero.astro`** - Tu nombre y título
- **`src/components/About.astro`** - Biografía y estadísticas
- **`src/components/Stack.astro`** - Tus tecnologías y nivel de experiencia
- **`src/components/Experience.astro`** - Tu experiencia laboral
- **`src/components/Contact.astro`** - Enlaces a tus redes sociales
- **`src/components/Footer.astro`** - Tu nombre en el copyright

### 2. Colores

Los colores se definen en `src/layouts/Layout.astro` en las variables CSS:

```css
:root {
  --primary: #6366f1;      /* Azul índigo */
  --secondary: #ec4899;    /* Rosa */
  --accent: #14b8a6;       /* Turquesa */
  --bg-dark: #0f172a;      /* Fondo oscuro */
  --bg-darker: #020617;    /* Fondo más oscuro */
}
```

### 3. Meta Tags y SEO

Edita en `astro.config.mjs`:

```javascript
site: 'https://tu-sitio.vercel.app'
```

Y en `src/layouts/Layout.astro` para descripción y título.

## 🌐 Desplegar en Vercel

### Opción 1: Desde GitHub (Recomendado)

1. Sube tu código a GitHub
2. Ve a [Vercel](https://vercel.com)
3. Haz clic en "Import Project"
4. Selecciona tu repositorio
5. Vercel detectará automáticamente que es un proyecto Astro
6. Haz clic en "Deploy"

### Opción 2: Usando Vercel CLI

```bash
# Instalar Vercel CLI
npm i -g vercel

# Desplegar
vercel

# Para producción
vercel --prod
```

### Configuración de Vercel

El proyecto ya está configurado con `@astrojs/vercel` adapter. No necesitas configuración adicional.

## 📱 Enlaces Sociales

Actualiza tus enlaces en `src/components/Contact.astro`:

```javascript
const socialLinks = [
  {
    name: "LinkedIn",
    url: "https://linkedin.com/in/TU-USUARIO", // ← Cambia aquí
  },
  {
    name: "GitHub",
    url: "https://github.com/TU-USUARIO", // ← Cambia aquí
  },
  {
    name: "WhatsApp",
    url: "https://wa.me/TU-NUMERO", // ← Cambia aquí (formato: código país + número)
  },
  {
    name: "Email",
    url: "mailto:tu-email@example.com", // ← Cambia aquí
  }
];
```

## 🎨 Buenas Prácticas Implementadas

- ✅ Código semántico HTML5
- ✅ Accesibilidad (aria-labels, roles)
- ✅ Performance optimizada
- ✅ Responsive design mobile-first
- ✅ Animaciones suaves y no invasivas
- ✅ SEO optimizado
- ✅ TypeScript para type safety
- ✅ Código modular y reutilizable

## 📄 Licencia

Libre de usar para tus proyectos personales.

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Siéntete libre de hacer un fork y mejorar el proyecto.

---

Hecho con ❤️ usando Astro

