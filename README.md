# bda-modulo-1-evaluacion-final-LaraDomenech
bda-modulo-1-evaluacion-final-LaraDomenech created by GitHub Classroom

Este repositorio contiene el proyecto correspondiente al **Examen Final** del Módulo 1, en él se crea la clase **TiendaOnline** siguiendo lo establecido por el enunciado.

## Descripción General

La clase `TiendaOnline` tiene como atributos:
- Un **inventario** (lista de diccionarios) con los productos, el precio que tienen y la cantidad de cada uno.
- Un **diccionario de clientes**, que incluye el email y un historial de compras.
- Un acumulador de **ventas totales** (float).

### Principales Métodos Implementados

1. **`agregar_producto(self, nombre, precio, cantidad)`**  
   - Añade un nuevo producto al inventario o actualiza su cantidad si ya existe.

2. **`ver_inventario(self)`**  
   - Muestra todos los productos del inventario con su nombre, precio y cantidad.

3. **`buscar_producto(self, nombre)`**  
   - Busca un producto específico en el inventario y muestra sus detalles.

4. **`actualizar_stock(self, nombre, cantidad)`**  
   - Suma o resta stock de un producto existente. Muestra un mensaje de error si no se encuentra el producto.

5. **`eliminar_producto(self, nombre)`**  
   - Elimina un producto del inventario por nombre.

6. **`calcular_valor_inventario(self)`**  
   - Calcula y muestra el valor total (en €) de todos los productos del inventario.

7. **`realizar_compra(self)`**  
   - Simula una compra interactiva, mostrando productos, permitiendo al usuario seleccionar, y actualizando el stock.

8. **`procesar_pago(self)`**  
   - Pide al cliente la cantidad con la que paga y calcula el cambio. Muestra error si el dinero es insuficiente.

9. **`agregar_cliente(self, nombre, email)`**  
   - Agrega un nuevo cliente al registro con su email y una lista de compras vacía.

10. **`ver_clientes(self)`**  
   - Muestra la información de todos los clientes registrados.
