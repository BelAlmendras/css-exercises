# El Santo Grial del Maquetado

En este último ejercicio de flexbox vas a recrear una maquetación de sitio web increíblemente común. Es tan habitual que a menudo se la llama diseño [Holy Grail](https://www.google.com/search?q=holy+grail+layout&tbm=isch&sclient=img)... y con flexbox en realidad es bastante fácil de lograr.

Como en el ejercicio anterior, hemos dejado un poco más para que hagas tú.

### Pistas
- Necesitarás cambiar la `flex-direction` para empujar el footer hacia abajo.
- Tendrás que añadir algunos divs como contenedores para que las cosas se alineen correctamente.
- `flex-wrap` ayudará a que las tarjetas se alineen de forma adecuada.
- Asegúrate de definir cuánto espacio deben ocupar las tarjetas para que `flex-wrap` funcione como se espera.

## Resultado deseado

![desired outcome](./desired-outcome.png)

El número de tarjetas que aparecen en esa sección cambiará según el ancho de tu pantalla, así que no te preocupes por obtener exactamente una cuadrícula 2x3 o 3x2.

En una pantalla más pequeña se verá así:

![smaller](./desired-outcome-smaller.png)

Nota: Los emojis pueden aparecer como uno o varios símbolos de texto (p. ej. &#9734;&#9794;) si no tienes instalada una familia tipográfica basada en emoji en tu sistema operativo. Esto no afecta al ejercicio y puede ignorarse.

### Comprobación
- El texto del header tiene tamaño 32px y peso 900.
- El texto del header está centrado verticalmente y a 16px del borde de la pantalla.
- El footer está empujado hacia la parte inferior de la pantalla (el footer puede ir por debajo de la parte inferior de la pantalla si el contenido de la sección de 'cards' desborda y/o si tu pantalla es más corta).
- El texto del footer está centrado horizontal y verticalmente.
- La barra lateral (sidebar) y las tarjetas ocupan todo el espacio disponible por encima del footer.
- La sidebar tiene 300px de ancho (y no se encoge).
- Los enlaces de la sidebar tienen tamaño 24px, son blancos y no tienen la decoración de subrayado.
- La sidebar tiene 16px de padding.
- Hay 48px de padding alrededor de la sección de 'cards'.
- Las tarjetas se disponen horizontalmente, pero se ajustan a varias líneas cuando se quedan sin espacio en la página.
