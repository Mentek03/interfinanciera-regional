# Interfinanciera Regional — sitio web

Sitio estático (HTML, sin dependencias ni instalación).

```
index.html          Página completa
assets/logo.png     Logo
assets/intro.mp3    Audio de la animación del banner
```

## Subir a GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `interfinanciera-regional`).
2. Sube el CONTENIDO de esta carpeta a la raíz del repositorio: `index.html` y la carpeta `assets`
   (en GitHub: Add file > Upload files; arrastra `index.html` y `assets`). `index.html` NO debe quedar dentro de otra carpeta.
3. En el repositorio: Settings > Pages > Build and deployment:
   Source = "Deploy from a branch", Branch = `main`, Folder = `/ (root)`. Guarda.
4. Espera 1 a 3 minutos y abre `https://TU-USUARIO.github.io/interfinanciera-regional/`.

Si ves 404: confirma que el archivo se llama exactamente `index.html` (minúsculas) y que está en la raíz.

## Pasar a hosting propio (dominio)

- Hosting tradicional (cPanel, FTP): sube `index.html` y la carpeta `assets` a la carpeta `public_html` del dominio.
- Netlify, Cloudflare Pages o Vercel: crea un proyecto nuevo, arrastra esta carpeta y listo.
- GitHub Pages con dominio propio: Settings > Pages > Custom domain, y apunta el DNS (CNAME) a `TU-USUARIO.github.io`.

Los enlaces del sitio son relativos, así que funciona igual en cualquier ruta o dominio.

## Pendientes de contenido (buscar los corchetes [ ] en index.html)

- Cifras: clientes atendidos, créditos activos, monto colocado y fecha de corte.
- Autoridad que regula a la financiera.
- Dirección, teléfono y correo del pie de página.
- Datos de la UNE y horario de atención.
- Fecha de cálculo del CAT.
- Sección de Facebook: insertar el plugin de publicaciones o quitar el recuadro.
- Aviso de privacidad, términos y condiciones y buzón de transparencia (hoy son enlaces sin página).
