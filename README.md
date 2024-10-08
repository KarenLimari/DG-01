# Desafío - Creación de clases y objetos

## Descripción del proyecto

Este proyecto consiste en una aplicación simple en Python para gestionar pedidos de té. Permite a los usuarios ingresar información sobre el té que desean pedir y muestra los detalles del pedido, incluyendo el sabor, formato, precio, tiempo de preparación y recomendación de consumo.

## Archivos del Proyecto

1. **`te.py`**: Define la clase `Te` con métodos para obtener información sobre el té basado en el sabor y el formato.

   - **`retorna_tiempo_y_recomendacion(sabor)`**: Retorna el tiempo de preparación y la recomendación de consumo según el sabor del té.
   - **`retorna_precio(formato)`**: Retorna el precio del té según el formato (300 o 500 gramos).

2. **`instancias.py`**: Crea instancias de la clase `Te` con atributos específicos para dos tipos de té y muestra detalles sobre estos.

3. **`pedido.py`**: Permite a los usuarios ingresar datos para un pedido de té y muestra un resumen del pedido.
   - **Entradas requeridas**: Sabor del té (1: Té negro, 2: Té verde, 3: Agua de hierbas), formato (300 o 500 gramos).
   - **Salida**: Detalles del pedido, incluyendo sabor, formato, precio, tiempo de preparación y recomendación.

## Requisitos

Para ejecutar este proyecto, asegúrate de tener instalado:

- **Sistema Operativo:** Windows, Linux, macOS
- **Lenguaje de programación:** Python 3.12 o superior

## Instalación del Proyecto

1. **Clona el repositorio:**

   ```bash
   git clone git@github.com:KarenLimari/DG-01.git
   ```

2. **Accede al directorio del proyecto:**

   ```bash
   cd DG-01
   ```

## Instrucciones para Ejecutar el Proyecto

1. **Ejecuta el script principal:**

   ```bash
   pedidos.py
   ```

## Autores

- Ambar Zambrano
- Karen Limari
- Arlenis Gonzalez

## Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo `LICENSE.md` para más detalles.
