# React + Vite — Starter ⚛️
Estructura inicial creada con **Vite** para mis proyectos en React.

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=FFD62E)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

---

## 📋 Requisitos
- Node.js 18+ (LTS recomendado)
- npm 9+ o equivalente (pnpm, yarn)

---

## 🚀 Ejecución

### 1️⃣ Descargar y usar el repositorio por primera vez
```bash
git clone https://github.com/hjoven15/react-vite-starter.git
cd react-vite-starter
npm install
npm run dev
```

### 2️⃣ Actualizar el proyecto local si lo descargaste con otro nombre

- Opción A — Renombrar la carpeta local
  ```bash
  mv my-app-react react-vite-starter
  cd react-vite-starter
  ```
- Opción B — Cambiar el remoto de Git
  ```bash
  cd my-app-react
  git remote set-url origin https://github.com/hjoven15/react-vite-starter.git
  git pull origin main
  ```

---

## 📂 Estructura de carpetas
```bash
src/             # Código fuente de la aplicación
 ├── components/ # Componentes reutilizables
 ├── pages/      # Vistas o páginas principales
 ├── assets/     # Imágenes, fuentes y recursos estáticos
 └── styles/     # Archivos CSS/SCSS globales o módulos

public/          # Archivos públicos que no pasan por el bundler
package.json     # Dependencias y scripts npm
vite.config.js   # Configuración de Vite
```

---

## 🛠️ Scripts principales

```bash
npm run dev     # Ejecuta la app en modo desarrollo
npm run build   # Genera la versión optimizada para producción
npm run preview # Previsualiza el build de producción en local
```
  
