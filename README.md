# Limonaia · Catálogo de Verano

Catálogo digital de bouquets de vela artesanales (limones de cera, peonías y rosas sobre jarrones de cerámica). Sitio estático de una sola página, sin dependencias ni build: HTML + CSS + JS vanilla.

## Ver el sitio

Abre `index.html` en el navegador, o sirve la carpeta:

```bash
npx serve .
```

## Estructura

- `index.html` — toda la página (hero, colección, proceso, pedidos, galería, footer)
- `uploads/` — fotografías del catálogo

## Configuración

El número de WhatsApp del botón de pedidos está al inicio del `<script>` en `index.html`:

```js
var WHATSAPP_NUMBER = '5215500000000'; // solo dígitos, con código de país
```

## Créditos

Tipografías: [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) y [Karla](https://fonts.google.com/specimen/Karla) (Google Fonts).

© 2026 Limonaia · Velas artesanales
