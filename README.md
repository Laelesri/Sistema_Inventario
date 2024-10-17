# Sistema_Inventario
                                            ---Sistema de Facturación---

Este sistema de facturación es una aplicación de consola diseñada para facilitar la gestión de clientes, productos, inventario y la creación de facturas.Está escrito en Python y se puede ejecutar en cualquier sistema operativo que tenga Python 3.12.06 instalado.


Tabla de Contenidos📚

Requisitos
✅Python: Este sistema requiere Python 3.12.06. Puedes descargarlo desde python.org.
✅Sistema Operativo: Compatible con Windows, macOS y Linux. No se requieren dependencias externas.
✅Entornos de desarrollo: IDLE (viene con Python), PyCharm,Visual Studio Code.

Instalación🔧

Ir a python.org
Descargar la última versión estable de Python 3 (Importante: marcar la opción "Add Python to PATH").
Ejecutar el instalador.

Verificar la instalación:
Abrir la línea de comandos (cmd en Windows, Terminal en Mac/Linux)
Ejecutar python –versión
Ejecutar python para abrir el intérprete interactivo

Ejecución del Programa ▶️

Funcionalidades⚙️
El sistema permite realizar las siguientes acciones:

1.Gestión de Clientes 👥
Crear Cliente: Agregar un nuevo cliente proporcionando su información.
Modificar Cliente: Actualizar la información de un cliente existente.
Consultar Cliente: Buscar y mostrar la información de un cliente específico.
Eliminar Cliente: Eliminar un cliente del sistema tras confirmación.
Listar Clientes: Mostrar todos los clientes registrados en el sistema.

2.Gestión de Productos 🏷️
Crear Producto: Agregar un nuevo producto con detalles como tipo, nombre, marca, unidad de medida y precio.
Modificar Producto: Cambiar la información de un producto existente.
Consultar Producto: Buscar y mostrar la información de un producto específico.
Eliminar Producto: Eliminar un producto del sistema tras confirmación.
Listar Productos: Mostrar todos los productos registrados en el sistema.

3.Gestión de Inventario 📦
Agregar Stock a Producto: Aumenta la cantidad de un producto existente.
Restar Stock de Producto: Disminuir la cantidad de un producto en el inventario.
Consultar Stock de Producto: Ver la información detallada de un producto en el inventario.
Generar Reporte de Inventario: Listar productos con stock bajo (menos de 10 unidades).

4.Facturación 💳
Crear Factura: Generar una nueva factura asociando un cliente y seleccionando productos.
Consultar Factura: Buscar y mostrar detalles de una factura específica.
Listar facturas: Mostrar todos las facturas registrados en el sistema.

Interfaz de Usuario 🎨
El programa está diseñado para ser intuitivo. Aquí tienes una guía sobre cómo navegar por el sistema:
Menús: El menú principal y los menús de cada sección están estructurados con números. Selecciona una opción ingresando el número correspondiente.
Entradas: Proporciona los datos según se indica.
Confirmaciones: Responde con "S" para sí o "N" para no.
Errores: Si ingresas un dato inválido, el sistema mostrará un mensaje de error.


Notas Importantes ⚠️
Validaciones: El sistema incluye validaciones para asegurar que los datos ingresados son correctos.
Persistencia de Datos: Actualmente, los datos se guardan de manera persistente en archivos CSV.
Dependencias: No se requieren casi librerías externas.




¡Gracias por utilizar nuestro sistema de facturación! 
Pronto lo hare en Django y ampliaré la interfaz sea llamativa,agradable e intuitiva al usuario.
