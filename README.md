# ModaCentro, prototipo navegable

Prototipo de media fidelidad de una app de venta de ropa. Lo usamos en la evaluación integradora 6.1–6.2 (Validar y Comunicar) de Requerimientos y Prototipado en la ESEN.

**Demo:** https://vicrenlopez14.github.io/modacentro-prototipo/

## Flujo
Catálogo por categoría o búsqueda → producto (color, talla, cantidad) → carrito con cupón → pago → confirmación.

## Datos de prueba
- Cupones:
  - `MODA10`: 10% de descuento.
  - `BIENVENIDA5`: $5 de descuento en compras desde $30.
  - `ENVIOGRATIS`: envío gratis.
  - `VERANO20`: cupón expirado; muestra un error.
- Tarjeta: cualquier número de 16 dígitos, por ejemplo `4111 1111 1111 1111`, con vencimiento `12/28` y CVV `123`. Es ficticia: el prototipo no cobra ni envía nada.

## Panel del observador
Se abre con **Shift + O** o tocando tres veces el logo. Lleva el tiempo de la tarea y registra la navegación y los errores. También exporta los eventos en CSV y reinicia la app para el siguiente participante.

Todo está en un solo archivo, `index.html`, y no necesita instalar nada.
