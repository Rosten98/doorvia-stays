# Doorvia Stays
Landing de rentas vacacionales en Vite + React. Proyecto independiente del sitio principal de Doorvia.

## Desarrollo
`npm install` y `npm run dev`.

## Producción
`npm run build` genera `dist/`. Se puede servir desde cualquier hosting estático. Configurar el subdominio elegido (`stays.doorvia.com.mx` o `rentals.doorvia.com.mx`) en el proveedor de hosting y su DNS.

## Contenido
Cambiar propiedades y referencias fotográficas en `src/data.js`. Las fotografías actuales son imágenes de referencia de Unsplash, cargadas remotamente. No representan propiedades reales de Doorvia. Los textos y el flujo son una propuesta para revisión. Las consultas son demostrativas: no se envían datos, no se comprueba disponibilidad y no se aceptan reservas ni pagos.

Antes del lanzamiento público: incorporar inventario/fotografías reales, canal de contacto, tarifas, políticas y aviso de privacidad aplicable. El subdominio todavía no está configurado.
