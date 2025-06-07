---
title: Venta de objetos
description: Cómo vender objetos en Survival Custom 1.21

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

Además de comerciar con otros jugadores a través de la Casa de Subastas, existe la posibilidad de vender muchos de tus objetos y recursos directamente al servidor para obtener dinero de forma instantánea. Esto es especialmente útil para deshacerte del exceso de materiales comunes, productos de granjas o cualquier ítem que tenga un valor de venta predefinido por el servidor.

Existen varios comandos para facilitar este proceso:

### 1. Venta Rápida: `/sellhand`

*   **Función:** Este comando te permite vender el objeto (o el stack de objetos) que tengas actualmente en tu **mano principal**.
*   **Uso:** Simplemente sostén el ítem que deseas vender y escribe en el chat:
    ```
    /sellhand
    ```
*   **Ideal para:** Ventas rápidas de un tipo específico de objeto que acabas de recolectar o fabricar. Si el objeto es vendible, recibirás el dinero correspondiente al instante.

### 2. Venta Masiva (¡Con Precaución!): `/sellall`

*   **Función:** El comando `/sellall` es una herramienta poderosa que venderá **todos los objetos vendibles que se encuentren en tu inventario principal** de una sola vez.
*   **Uso:** Escribe en el chat:
    ```
    /sellall
    ```

::alert{type="danger" icon="lucide:triangle-alert"}
  **¡CUIDADO AL USAR ESTE COMANDO!**
  
  `sellall` no discrimina entre los objetos que quieres vender y los que no, siempre y cuando sean vendibles al servidor.
  **Existe el riesgo de vender accidentalmente herramientas valiosas, armaduras, bloques de construcción importantes u otros ítems que preferirías conservar si estos tienen un precio de venta al servidor.**

  Recomendamos encarecidamente revisar tu inventario antes de ejecutar `/sellall` o utilizar el método `/sellgui` para una selección más controlada.
::


### 3. Venta Selectiva con Interfaz: `/sellgui`

*   **Función:** Para aquellos que prefieren tener un control más visual y selectivo sobre lo que venden, el comando `/sellgui` es la opción perfecta.
*   **Uso:** Ejecuta el comando en el chat:
    ```
    /sellgui
    ```
    Esto abrirá una **interfaz gráfica (GUI)** similar a un cofre.
*   **Proceso:**
    1.  Arrastra y suelta todos los objetos de tu inventario que deseas vender dentro de esta GUI.
    2.  Puedes llenar la GUI con diversos ítems.
    3.  Una vez que hayas colocado todo lo que quieres vender, simplemente **cierra la interfaz gráfica**.
    4.  Al cerrar la GUI, todos los objetos que depositaste en ella serán vendidos automáticamente al servidor y recibirás el pago total.
*   **Ventaja:** Este método te permite seleccionar cuidadosamente cada ítem, evitando ventas accidentales de objetos importantes.

---

Utiliza estos comandos de venta directa para gestionar tu inventario, convertir el exceso de recursos en dinero contante y sonante, y financiar tus próximos proyectos. ¡Recuerda siempre verificar qué objetos son vendibles y a qué precio para maximizar tus ganancias!
