# Arôme V4

Catálogo profesional de perfumes + panel privado de administración.

## Incluye
- Catálogo responsive.
- Buscador y categorías.
- Productos, precios y stock.
- Carga y reemplazo de imágenes.
- Productos destacados/ocultos.
- WhatsApp por producto.
- Configuración de marca, Instagram y textos.
- Imagen principal editable.
- Login de administrador.
- SQLite para guardar datos.

## Ejecutar
Requiere Node.js 18+.

```bash
npm install
npm start
```
Abrir `http://localhost:3000`.

Panel: `http://localhost:3000/admin.html`

Usuario inicial: `admin`
Contraseña inicial: `arome2026`

Antes de publicar, cambiá las credenciales usando `AROME_ADMIN_USER`, `AROME_ADMIN_PASSWORD` y `AROME_SESSION_SECRET`.

El hosting debe soportar Node.js y almacenamiento persistente para SQLite y uploads.
