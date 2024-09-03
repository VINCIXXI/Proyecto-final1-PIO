# Proyecto-final1-PIO

## Sistema básico de venta de joyas y relojes en Python

Este sistema está diseñado para simular el proceso de compra en una tienda de joyas y relojes. El programa incluye varias funcionalidades clave, todas controladas a través de un menú principal que permite al usuario interactuar con el sistema de manera sencilla. A continuación, te explico cómo funciona:

1. Lista de Productos Disponibles
El programa comienza con una lista de productos disponibles, que incluye joyas y relojes. Cada producto tiene un nombre, un precio y una cantidad disponible en inventario. Esta lista actúa como el catálogo que se muestra al usuario para que pueda seleccionar los productos que desea comprar.

2. Carrito de Compras
El carrito de compras es una lista donde se almacenan los productos que el usuario decide comprar. Cuando un producto es agregado al carrito, se reduce la cantidad disponible de ese producto en el inventario.

3. Funciones del Programa
El programa se estructura en varias funciones que manejan las diferentes tareas necesarias para la compra:

Mostrar productos: Esta función muestra todos los productos disponibles en la tienda, junto con su precio y la cantidad en stock.
Agregar al carrito: Permite al usuario seleccionar un producto de la lista y especificar cuántas unidades desea comprar. La función verifica si hay suficiente stock antes de agregar el producto al carrito.
Mostrar carrito: Muestra los productos que el usuario ha agregado al carrito, junto con el precio y la cantidad seleccionada.
Calcular total: Esta función suma el precio de todos los productos en el carrito y muestra el total que el usuario tendría que pagar.
Finalizar compra: Permite al usuario revisar el contenido de su carrito y confirmar si desea finalizar la compra. Si el usuario confirma, el carrito se vacía y la compra se da por terminada.
4. Menú Principal
El programa opera a través de un menú principal, que se muestra repetidamente hasta que el usuario decide salir. El menú ofrece las siguientes opciones:

Mostrar productos
Agregar producto al carrito
Mostrar carrito
Finalizar compra
Salir del programa
El usuario selecciona una opción ingresando el número correspondiente. Según la elección, el programa ejecuta la función respectiva.

5. Manejo de Errores
El programa incluye mecanismos para manejar errores, como entradas inválidas por parte del usuario (por ejemplo, ingresar texto en lugar de un número). Esto se maneja mediante el uso de try-except, que permite capturar y manejar excepciones, evitando que el programa se detenga abruptamente por un error.

6. Finalización del Programa
El usuario puede salir del programa en cualquier momento seleccionando la opción "Salir" del menú. Esto termina la ejecución del programa de manera ordenada.