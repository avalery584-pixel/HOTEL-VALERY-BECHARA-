# Hotel Valery Bechara

Sitio web responsive para Hotel Valery Bechara, con habitaciones NK1, NQQ y Suite, concepto de experiencias inspirado en sabores de Latinoamérica, formulario de solicitud de reserva y concierge virtual 24/6.

## Publicación

El proyecto es estático: abre `index.html` directamente o publícalo con GitHub Pages:

1. En GitHub, entra a **Settings → Pages**.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Selecciona la rama **main** y la carpeta **/(root)** y guarda.
4. Espera a que GitHub Pages muestre la URL pública.

## Configuración obligatoria antes de recibir reservas

Abre `index.html` y busca:

```js
const HOTEL_WHATSAPP = "";
```

Reemplaza el valor vacío por el número oficial del hotel en formato internacional, solo números y sin `+`, espacios ni guiones. Para Colombia, comienza por `57`.

Ejemplo ficticio: `const HOTEL_WHATSAPP = "573001234567";`

No uses el ejemplo ficticio como número real.

## Antes de publicar

- Confirma el número oficial de WhatsApp.
- Reemplaza las fotografías de referencia por fotografías autorizadas del hotel.
- Confirma qué amenidades y servicios están realmente incluidos. Los sabores latinoamericanos están presentados como concepto de experiencia, no como servicios garantizados.
- Añade dirección, teléfono, redes sociales, tarifas, políticas y horarios reales.
- El concierge incluido es un prototipo conversacional con respuestas predefinidas en el navegador. No es todavía un chatbot conectado a IA ni a un sistema de reservas; el equipo confirma disponibilidad y tarifas por WhatsApp.

## Estructura

- `index.html`: sitio, estilos responsive, formulario, botón WhatsApp y concierge virtual.
