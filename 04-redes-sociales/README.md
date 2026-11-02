# Una tarjeta con tus redes sociales

Crea una página de presentación con enlaces a las redes sociales de una persona. El HTML ya está preparado; escribe todas las reglas CSS dentro de `<style>` para conseguir una tarjeta similar a la captura.

## Tu tarea

1. Abre `index.html` con Live Server.
2. Personaliza el nombre, las iniciales, la ubicación y la descripción. Puedes utilizar tus datos públicos o inventar un personaje.
3. Sustituye los destinos de los enlaces por las direcciones de los perfiles elegidos. Los enlaces iniciales llevan a la portada de cada plataforma: todavía no son perfiles personales. Puedes cambiar también las plataformas y sus textos.
4. Escribe los selectores, propiedades y valores CSS para reproducir la tarjeta.
5. Comprueba que cada enlace abre el perfil correcto en una pestaña nueva.

## Diseño esperado

![Tarjeta con enlaces a redes sociales](disenoEsperado.png)

## Medidas y colores de referencia

| Parte | Indicaciones |
| --- | --- |
| Página | Arial o sans-serif, 16 px; margen de 30 px; fondo `#f5eee7`, texto `#30443b` |
| Tarjeta | 320 px de ancho de contenido; padding de 28 px; borde sólido de 2 px `#c9d9ce`; radio de 20 px; fondo `#ffffff`; texto centrado |
| Iniciales | Ancho de 64 px; padding de 16 px arriba y abajo y 0 px a los lados; margen de 0 px arriba, `auto` a los lados y 20 px debajo; radio de 40 px; fondo `#e4efe5`, texto `#426c53`; tamaño de 28 px y negrita |
| Nombre | 28 px; margen de 0 px salvo 10 px debajo |
| Ubicación | Color `#52735b`, negrita; margen de 0 px salvo 20 px debajo |
| Descripción | Margen de 0 px salvo 24 px debajo |
| Enlaces | Fondo `#edf3ef`, texto `#30443b` en negrita; borde sólido de 1 px `#c9d9ce`; radio de 10 px; padding de 14 px; margen superior de 12 px y 0 px en los otros lados |

La tarjeta queda a la izquierda de la página. El texto y las iniciales están centrados dentro de ella.

## Ayuda

Los enlaces son elementos en línea. Con `display: block` puedes hacer que cada enlace ocupe una fila y darle padding, borde y márgenes.

Puedes seleccionar los enlaces que están dentro de la clase de su contenedor. Por ejemplo, el selector `.redes a` aplica estilos a las etiquetas `<a>` que están dentro del elemento con clase `redes`.

Utiliza `text-decoration: none` para quitar el subrayado de los enlaces.

## Comprueba tu trabajo

- El padding separa el contenido del borde de la tarjeta.
- Hay espacio entre los textos y entre los enlaces.
- Los enlaces conservan etiquetas `<a>` y llevan a las redes elegidas.
- El resultado es aproximado. Tu solución debería verse bien con el navegador maximizado, pero es normal que no se vea bien en una pantalla pequeña.
