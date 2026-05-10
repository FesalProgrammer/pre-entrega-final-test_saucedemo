# Proyecto de Automatizacion QA - Fesal La Rosa.

# Proposito del proyecto:

Validar la estabilidad y funcionalidad de los módulos principales de la aplicación Swag Labs, asegurando que los usuarios puedan autenticarse, visualizar el catálogo de productos y gestionar el carrito de compras de manera correcta.

## Tecnologias usadas:

- Lenguaje principal: Python 3.13
- Estructura de testing: Pytest
- Automatización Web: Selenium WebDriver
- Control de Versiones: Git & GitHub
- Reportes: Pytest-HTML

## Instalación del repositorio

`git clone https://github.com/tu-usuario/nombre-del-repo.git`

## Instalación de las dependencias

`pip install -r requiremnts.txt`

## Ejecucion de las pruebas

o Comando para ejecutar las pruebas: py -m pytest

## Escenerarios Cubiertos

- Autenticación (test_login): Verifica que el usuario sea redirigido correctamente a la página de inventario tras un login exitoso.

- Validación de Inventario (test_inventory):

-- Verificación de títulos de página.

-- Confirmación de visibilidad de productos.

-- Validación de elementos de UI (menú hamburguesa y filtro).

- Gestión del Carrito (test_cart): Flujo completo de agregar un producto, verificar el incremento en el contador y validar que el ítem correcto aparezca en la vista del carrito.

• Pytest automaticamente genera un reporte HTML con resultados de la ejecución.
