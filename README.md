# FinalSoft · Portal de infraestructura telemática

Portal estático (HTML, CSS y JavaScript) del proyecto *Sistemas y Servicios Telemáticos*:
dos sedes, routers Debian, servicios corporativos y gateway con NAT y firewall, hechos en GNS3.

## Cómo abrir
Haz doble clic en `index.html` (Chrome, Firefox o Edge). No necesita instalar nada ni conexión a Internet.

## Publicar en Apache (Debian)
Copia `index.html`, `css/`, `js/`, `assets/` y `evidencias/` a `/var/www/html/`.
No hace falta publicar `docs/`, `extras/` ni los archivos `.md`.

## Capturas
Las imágenes viven en `evidencias/<servicio>/` y se muestran en cada espacio con el mismo nombre.
Si falta una, aparece un recuadro "Espacio para evidencia" con la ruta exacta que espera.
Al agregar un archivo con ese nombre y recargar, aparece solo; al hacer clic se amplía.

Capturas pendientes:
- routers/r1-config.png
- dhcp/cliente-principal.png
- dns/dns-secundaria.png
- web/portal-interno.png, web/portal-externo.png
- correo/squirrelmail-login.png, correo-enviado.png, correo-recibido.png, bloqueo-gmail.png
- gateway/reglas-iptables.png
- internet/google-principal.png, internet/google-secundaria.png

## Archivos
- `index.html`: estructura.
- `css/styles.css`: apariencia.
- `js/content.js`: contenido técnico (direcciones, comandos, pruebas, lista de capturas).
- `js/app.js`: navegación, páginas, galería y copiar código.
- `assets/video/router-hero.mp4` y `assets/img/router-poster.jpg`: video de la portada.
- `docs/Proyecto_Final_Routers_Sedes.docx`: documento fuente con las configuraciones completas.

## Advertencias
- Las pruebas son documentación histórica del laboratorio, no lectura en vivo.
- Algunos bloques de comandos son extractos; la configuración completa está en el documento.
- Dovecot sin TLS y SquirrelMail 1.4.22 son solo para laboratorio: no exponer a Internet pública.
- No publiques contraseñas ni claves privadas.
# a
