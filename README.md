# Portafolio con Astro + Tailwind CSS v4

Proyecto creado con Astro, Vite y Tailwind CSS v4.

## 🚀 Stack Tecnológico

- **Astro** - Framework web moderno
- **Vite** - Build tool ultrarrápido
- **Tailwind CSS v4** - Framework CSS utility-first (última versión)
- **TypeScript** - Tipado estático

## 📦 Comandos Disponibles

```bash
# Instalar dependencias (ya instaladas)
npm install

# Iniciar servidor de desarrollo
npm run dev

# Compilar para producción
npm run build

# Vista previa de la build de producción
npm run preview
```

## 🎨 Tailwind CSS v4

Este proyecto usa Tailwind CSS v4 (versión next/beta) con las siguientes características:

- **Importación simplificada**: Solo necesitas `@import "tailwindcss"` en tu CSS
- **Tema personalizado**: Usa `@theme` para definir variables CSS personalizadas
- **Plugin Vite nativo**: Integración directa con Vite sin PostCSS
- **Mejor rendimiento**: Compilación más rápida

### Archivo CSS principal

El archivo `src/styles/global.css` contiene la configuración de Tailwind:

```css
@import "tailwindcss";

@theme {
  --color-primary: #3b82f6;
  --color-secondary: #8b5cf6;
}
```

## 🔧 Configuración de VS Code

El proyecto incluye configuración optimizada para VS Code:

- **Extensiones recomendadas**:
  - Astro (astro-build.astro-vscode)
  - Tailwind CSS IntelliSense (bradlc.vscode-tailwindcss)

- **Intellisense de Tailwind**: Autocompletado en clases de Astro y HTML
- **Validación CSS**: Configurada para Tailwind v4

## 🐛 Solución de Problemas con Tailwind v4

Si encuentras problemas:

1. **Asegúrate de usar `@import "tailwindcss"`** en lugar de las directivas antiguas
2. **Reinicia el servidor de desarrollo** después de cambios en la configuración
3. **Limpia la caché**: Elimina `node_modules/.vite` si hay problemas
4. **Verifica la versión**: `npm list tailwindcss` debe mostrar v4.x

## 📁 Estructura del Proyecto

```
/
├── public/          # Archivos estáticos
├── src/
│   ├── pages/       # Páginas de Astro
│   │   └── index.astro
│   └── styles/      # Estilos globales
│       └── global.css
├── .vscode/         # Configuración de VS Code
├── astro.config.mjs # Configuración de Astro
└── package.json
```

## 🚀 Empezar a Desarrollar

1. Abre el proyecto en VS Code
2. Instala las extensiones recomendadas cuando se te solicite
3. Ejecuta `npm run dev`
4. Abre http://localhost:4321 en tu navegador

¡Listo para crear tu portafolio! 🎉
