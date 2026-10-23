# Sitio web de MayLo Devs

Sitio estatico (HTML + CSS, sin servidor ni frameworks) con 4 paginas, en ingles y espanol (boton EN/ES):
- `index.html` inicio del estudio y lista de juegos
- `akeme/index.html` pagina del juego
- `privacy/index.html` politica de privacidad (requerida por las tiendas)
- `support/index.html` soporte y preguntas frecuentes (requerido por la App Store)

## Antes de publicarlo
1. Reemplaza `contact@maylodevs.com` por tu correo real en los 4 archivos HTML (buscar y reemplazar).
2. Lee la politica de privacidad: refleja la version 1.0 SIN anuncios ni compras. Antes de lanzar anuncios o Premium hay que actualizarla.
3. Cuando existan, cambia el boton "Proximamente" por los enlaces a la App Store y Google Play.
4. Anade capturas de pantalla del juego en `akeme/index.html` cuando las tengas.

## Publicarlo gratis (GitHub Pages)
1. Crea un repositorio y sube el CONTENIDO de esta carpeta (`index.html` debe quedar en la raiz). No hay datos secretos, asi que puede ser publico.
2. Settings > Pages > "Deploy from a branch" > `main` / `(root)`.
3. Dominio propio: crea un archivo `CNAME` con el dominio (por ejemplo `maylodevs.com`), configura los DNS como indica la guia de GitHub para dominios propios y activa "Enforce HTTPS".
Alternativas igual de simples: Cloudflare Pages o Netlify (arrastrar la carpeta).

## Dominio y correo
- Comprueba que `maylodevs.com` este libre (si no, prueba `.dev`, `.games` o `.studio`). Un dominio cuesta aproximadamente entre 10 y 15 USD al ano.
- Correo `contact@tudominio`: puedes reenviarlo a tu correo personal con Cloudflare Email Routing (gratis) y configurar "enviar como" en Gmail para responder.

## URLs para las tiendas (con tu dominio)
- Politica de privacidad: `https://TUDOMINIO/privacy/`
- URL de soporte: `https://TUDOMINIO/support/`
- URL de marketing: `https://TUDOMINIO/akeme/`
