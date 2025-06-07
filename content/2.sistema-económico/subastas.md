---
title: Subastas
description: Cómo usar el sistema de subastas en Survival Custom 1.21

navTruncate: false

badges:
  - value: Sistema Económico
    to: /sistema-economico/como-ganar-dinero
    target: _self

authors:
  - name: Moha
    username: Kiramann__
    avatar: https://cdn.discordapp.com/avatars/300012418313224194/8210a33c2f974927b25d22a61dd58cd5.png?size=512
    to: https://github.com/mohaisreal
    target: _blank

---

¿Tienes objetos valiosos que ya no necesitas o quieres convertir tus hallazgos en una fuente de ingresos? ¡El sistema de Subastas (Auction House o "AH") es tu lugar ideal! Aquí podrás poner a la venta tus ítems para que toda la comunidad pueda verlos y adquirirlos.

### ¿Cómo Funciona la Casa de Subastas?

La Casa de Subastas te permite listar tus objetos de dos maneras principales: **Venta Directa** a un precio fijo o mediante una **Subasta Tradicional** donde los jugadores pujan por tu artículo.

**Límite de Publicaciones:** Para asegurar un mercado dinámico y justo para todos, cada jugador puede tener un máximo de **3 objetos listados simultáneamente** en la Casa de Subastas. ¡Administra bien tus espacios!

### Modalidades de Venta

1.  **Venta Directa (Precio Fijo):**
    *   **Concepto:** Si tienes un precio claro en mente para tu objeto y no quieres esperar a que finalice una puja, puedes listarlo para venta directa. Esto significa que cualquier jugador podrá comprar tu ítem instantáneamente pagando el precio que tú establezcas.
    *   **Comando:** Para poner un objeto en venta directa, sostén el ítem que deseas vender en tu mano principal y ejecuta el siguiente comando:
        ```
        /ah sell [PRECIO_FIJO]
        ```
        Reemplaza `[PRECIO_FIJO]` con la cantidad de monedas a la que deseas vender el objeto.
    *   **Ejemplo:** Si quieres vender una espada de diamante por 5,000 monedas, tomarías la espada en tu mano y escribirías: `/ah sell 5000`

2.  **Subasta (Sistema de Pujas):**
    *   **Concepto:** Si prefieres dejar que el mercado decida el valor de tu objeto o crees que puede generar interés y competencia, puedes iniciar una subasta. Establecerás un precio de puja inicial, y los jugadores interesados irán ofreciendo cantidades mayores. Al finalizar el tiempo de la subasta, el jugador que haya realizado la puja más alta se llevará el ítem.
    *   **Comando:** Para iniciar una subasta por un objeto, sostén el ítem en tu mano principal y ejecuta el siguiente comando:
        ```
        /ah bid [PRECIO_INICIAL_PUJA]
        ```
        Reemplaza `[PRECIO_INICIAL_PUJA]` con la cantidad mínima de monedas con la que deseas que comience la subasta.
    *   **Ejemplo:** Si quieres subastar un artefacto raro y deseas que la puja comience en 2,000 monedas, tomarías el artefacto en tu mano y escribirías: `/ah bid 2000`

::alert{type="info" icon="lucide:info"}
Para todas las ventas y subastas que realices en la Casa de Subastas, existe un **precio mínimo de listado de 1,000 monedas**. Esto significa que no podrás vender ni iniciar una subasta por un objeto por menos de esta cantidad.
::

---

¡Utiliza la Casa de Subastas para comprar esos ítems que tanto necesitas o para vender tus tesoros y hacerte rico! Para explorar los objetos actualmente en venta o subasta, generalmente usarás el comando `/ah` o `/auctionhouse` sin argumentos adicionales.
