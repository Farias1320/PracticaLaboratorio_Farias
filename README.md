# Menú Interactivo de Restaurante

Este proyecto es un **Jupyter Notebook** en Python que simula el menú de un restaurante. Permite a los usuarios seleccionar platos, ver los ingredientes y calcular el total a pagar.

## ¿Cómo funciona?

1. **Visualización del menú:**  
   El notebook muestra una lista de platos disponibles, sus precios y sus ingredientes.

2. **Selección de platos:**  
   El usuario puede ingresar el nombre de los platos que desea pedir.  
   Puede seguir agregando platos hasta que escriba `fin` para terminar.

3. **Cálculo del total:**  
   El programa suma automáticamente el precio de cada plato seleccionado.

4. **Resumen del pedido:**  
   Al finalizar, se muestra un resumen con los platos elegidos y el total a pagar.

## Manipulación avanzada del menú

- **Modificar un precio:**  
  Puedes actualizar el precio de cualquier plato directamente en el diccionario. Por ejemplo, se aplica un 10% de descuento a la "Fritada" y se muestra el menú actualizado.

- **Añadir un nuevo plato temporal:**  
  Se puede agregar un "Plato del Día" al menú, con su propio precio e ingredientes, y luego mostrar el menú completo con este nuevo plato.

## Exploración de errores y depuración

- **Error de índice (IndexError):**  
  El notebook incluye ejemplos donde se intenta acceder a un elemento fuera de rango en una lista o tupla, lo que genera un IndexError.  
  Estas líneas están comentadas, pero puedes descomentarlas para ver el error y aprender cómo ocurre.

- **Inmutabilidad de tuplas (TypeError):**  
  También se muestra qué ocurre si intentas modificar un elemento de una tupla de ingredientes.  
  Esto genera un TypeError porque las tuplas no se pueden modificar después de ser creadas.

## Ejemplo de uso

```
MENÚ DEL RESTAURANTE

Plato: Arroz con Pollo
Precio: $8.50
Ingredientes: arroz, pollo, guisantes, zanahoria, pimiento

...

Ingresa tu plato favorito o 'fin' para terminar: fritada
'Fritada' añadido al pedido
Ingresa tu plato favorito o 'fin' para terminar: fin

RESUMEN DE TU PEDIDO
Platos seleccionados:
   1. Fritada

TOTAL A PAGAR: $8.10
¡Gracias por tu pedido!
```

## Requisitos

- Python 3.x
- Jupyter Notebook (puedes instalarlo con Anaconda o usando `pip install notebook`)

## Ejecución

1. Abre el archivo `menu.ipynb` en Jupyter Notebook.
2. Ejecuta las celdas una por una siguiendo el flujo del menú interactivo.
3. Puedes probar los ejemplos de errores descomentando las líneas indicadas para ver cómo funcionan los errores en Python.

---

¡Disfruta usando el menú interactivo
