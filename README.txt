DYSONCONTROL REPARACIÓN SERVICIO TÉCNICO EN BURGOS
==================================================

Web de una sola página (HTML/CSS/JS estático + función serverless en Vercel)
para DysonControl, servicio técnico y reparación de equipos Dyson con recogida
y entrega en Burgos y área metropolitana.

Dominio: https://burgosserviciotecnico.com.es/
Marca: DysonControl Reparación Servicio Técnico Burgos
Nombre corto (og:site_name): DyControl – Burgos
Ficha de Google: https://maps.app.goo.gl/Uo8BtkbicvR2yWBBA
Mapa: iframe de Google Maps de la ficha "DysonControl Reparación Servicio Técnico",
insertado tal cual en la sección de contacto (ancho 100% vía CSS).

DATOS DE CONTACTO
- WhatsApp: +34 649 97 01 28.
- Teléfono: +34 910 05 48 17.
- Recogida a domicilio: https://sis.redsys.es/tiendaWeb/item/NDk4OzI=
  (botón "Solicita tu recogida ahora" del hero, siempre en negro).
- Horario: lunes a viernes de 09:30 a 18:00.
- Política de privacidad: https://kelatos.com/privacy-policy/.

DIRECCIÓN: no se muestra dirección postal. La web indica "Burgos y área
metropolitana" y servicio de recogida y entrega; el taller está en Madrid.
Si se confirma una dirección en Burgos, añadirla al hero, footer y JSON-LD.

ESTRUCTURA
- index.html: toda la página (hero, ventajas, reparación rápida, confianza,
  servicios, por qué elegirnos, cómo trabajamos, contacto + mapa, FAQ, texto
  SEO, footer, cookies y JSON-LD).
- style.css: base de la plantilla.
- mobile-navigation.css, social-footer.css, cal-booking.css: ajustes compartidos.
- dysoncontrol.css: identidad visual de la marca (una sola capa, sin
  sobrescrituras en cascada).
- dysoncontrol-header-hero.css: cabecera grafito con logotipo blanco.
- dysoncontrol.js: menú móvil (se cierra al pulsar un enlace), formulario y
  preferencias de cookies (clave localStorage "dysoncontrol_cookie_preference").
- dysoncontrol-n8n-chat.js / .css: chatbot n8n con webhook compartido del grupo
  y botón de respaldo.
- api/contacto.js: envío del formulario por SMTP (variables SMTP_HOST,
  SMTP_PORT, SMTP_SECURE, SMTP_USER, SMTP_PASS y CONTACT_EMAIL en Vercel).
- img/: isotipo, patrón e ilustraciones SVG de la marca.
- robots.txt y sitemap.xml apuntan a https://burgosserviciotecnico.com.es/.

PALETA: cobre técnico, grafito y acero (el cobre de los bobinados de motor).
- Primario cobre #B4532A · oscuro #8C3E1D · muy oscuro #5A2712
- Grafito (cabecera, footer, cookies, tarjeta de Google) #16161A
- Cobre claro #F0955F para detalles sobre fondo oscuro (logotipo, destacados)
- Acero #B8BCC4 en ilustraciones · fondos #F6F5F7
Excepciones: WhatsApp conserva su verde y YouTube su rojo corporativo.
En móvil (≤720px) no se muestran las ilustraciones laterales del hero.
