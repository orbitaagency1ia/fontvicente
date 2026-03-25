# Fontanería Vicente - Animación Scroll

Sitio web con animación de scroll controlada por frames.

## Despliegue en Vercel

### Opción 1: Desde GitHub (RECOMENDADO)

1. **Crea un repo en GitHub**
   - Ve a github.com y crea un nuevo repo
   - Sube esta carpeta completa

2. **Importa en Vercel**
   - Ve a [vercel.com](https://vercel.com)
   - Click en "Add New Project"
   - "Import Git Repository"
   - Selecciona tu repo
   - Click en "Deploy"

### Opción 2: Desde Vercel CLI

1. Instala Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Desde esta carpeta:
   ```bash
   cd /Users/kevinubeda/Desktop/fontaneria-vicente-vercel
   vercel
   ```

### Opción 3: Drag & Drop

1. Ve a [vercel.com](https://vercel.com)
2. Logueate con tu cuenta de GitHub
3. Click en "Add New Project"
4. Arrastra esta carpeta al área de upload

## Estructura

```
├── index.html       # Página principal
├── vercel.json      # Configuración de Vercel
├── frames/          # 302 frames de video
│   ├── frame_0001.png
│   ├── frame_0002.png
│   └── ...
└── README.md
```

## Dominio Personalizado

Después del despliegue, en Vercel:
1. Ve a Settings → Domains
2. Añade tu dominio personalizado
3. O usa el dominio gratuito: tu-proyecto.vercel.app
