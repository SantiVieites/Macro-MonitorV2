# MACRO MONITOR — Panel Macroeconómico

Dashboard interactivo con datos macroeconómicos de 17 países.

## Países incluidos
Argentina, Estados Unidos, Brasil, Uruguay, Chile, México, Paraguay, Alemania, Francia, Reino Unido, España, Suiza, Rusia, China, Japón, Australia, Nueva Zelanda.

## Cómo deployar en Vercel (gratis)

### Paso 1 — Subir a GitHub
1. Creá una cuenta en github.com si no tenés
2. Creá un repositorio nuevo (ej: macro-monitor)
3. Subí todos los archivos de este proyecto al repositorio

Desde la terminal:
```bash
cd macro-monitor
git init
git add .
git commit -m "Macro Monitor v1"
git remote add origin https://github.com/TU-USUARIO/macro-monitor.git
git push -u origin main
```

### Paso 2 — Deployar en Vercel
1. Andá a vercel.com y creá una cuenta (podés usar GitHub)
2. Click en "Add New Project"
3. Importá tu repositorio macro-monitor
4. Vercel detecta que es Vite automáticamente
5. Click en "Deploy"
6. En ~60 segundos tenés tu URL: tu-proyecto.vercel.app

### Alternativa: Netlify
1. Andá a netlify.com
2. Arrastrá la carpeta dist (después de npm run build) a Netlify
3. Listo

## Desarrollo local
```bash
npm install
npm run dev        # http://localhost:5173
npm run build      # genera carpeta dist/
```

## Cómo actualizar datos
Editá src/App.jsx — los datos están en el array COUNTRIES al inicio.

## Fuentes
FMI (WEO Oct 2025), OECD, Trading Economics, Bancos Centrales.
