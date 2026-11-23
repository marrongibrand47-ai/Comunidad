# GAMS Comunal — Despliegue en Vercel

Proyecto web PWA + Offline-First conectado en tiempo real a Firebase (`gams-sc`), con identidad visual negro carbono y dorado metálico de **GAMS Company**.

## Archivos incluidos
- `index.html`: Aplicación completa (Censo, Comercios, Constancias PDF/QR, Contabilidad, CLAP/Gas, Proyectos, Dashboard y Roles).
- `vercel.json`: Configuración de rutas limpias, rewrites y cabeceras PWA para Vercel.
- `manifest.json`: Manifiesto instalable en Android, iOS y PC como aplicación nativa.
- `sw.js`: Service Worker para abrir la web incluso cuando no hay señal de internet en la comunidad.

## Pasos para subir a Vercel
1. Descomprime este archivo `.zip` en una carpeta nueva.
2. Súbelo a un repositorio en tu cuenta de **GitHub** (o arrastra la carpeta directamente en **Vercel → Add New Project**).
3. En Vercel, deja **Framework Preset** en `Other` (sitio estático sin build command) y presiona **Deploy**.
4. En **Firebase Console (`gams-sc`) → Authentication / Firestore → Configuración**, agrega tu dominio `.vercel.app` en **Dominios autorizados** y verifica las reglas de Firestore.
