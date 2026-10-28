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

## Enlaces de las tiendas (cuando la app este publicada)
En `index.html` y `akeme/index.html` busca el comentario `STORE-LINKS`. Cambia cada `<span class="btn off">` por `<a class="btn" href="ENLACE">` con el enlace de la App Store o de Google Play (o pasame los enlaces y te devuelvo el sitio listo). Para usar las insignias oficiales, descargalas de Apple y de Google y sigue sus guias de uso.

## Anuncios: app-ads.txt
El sitio no lleva anuncios. Si la app usa AdMob, hace falta un archivo `app-ads.txt` en la raiz del sitio (`https://maylodevs.com/app-ads.txt`) con una linea como:
`google.com, pub-XXXXXXXXXXXXXXXX, DIRECT, f08c47fec0942fa0`
donde `pub-XXXXXXXXXXXXXXXX` es TU identificador de editor de AdMob (lo da tu cuenta de AdMob). No lo crees antes de tener ese identificador.

## Boton "ir al inicio"
Cada pagina termina con un boton "Ir al inicio" y, al bajar, aparece un boton flotante "Inicio" abajo a la derecha.

## Novedades de esta version
- Politica de privacidad actualizada para un juego CON anuncios de AdMob. Publicala solo junto con la version que lleva anuncios (o antes, no pasa nada). Cuando el juego tenga el boton de consentimiento en Ajustes, la politica ya lo menciona.
- Pagina de prensa (`press/`) con ficha tecnica e imagenes descargables, `404.html`, `robots.txt` y `sitemap.xml` (puedes enviar el sitemap en Google Search Console).
- Menu con enlace a Prensa; textos de Sprint (150 m) y reto diario (100 m) al dia.

## Pagina de prensa
Por ahora la pagina de prensa solo tiene la ficha tecnica y un correo de contacto; se quitaron las descargas de imagenes. Cuando el juego este publicado, anade capturas y un trailer, indica en la pagina para que se pueden usar (cobertura, resenas, videos) y no subas archivos originales de trabajo, solo versiones listas para publicar.
