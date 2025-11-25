# 🚕 Proyecto Urban-Routes Automatizacipón  

Este proyecto contiene un conjunto de pruebas de automatización de interfaz de usuario (UI) para la aplicación web de taxi **Urban-Routes**.  
El objetivo es validar el flujo de un pedido, desde el establecimiento de la ruta hasta la confirmación de la orden con el conductor.  

---

## 📌 Tecnologías y herramientas utilizadas  

- **Lenguaje:** Python 🐍  
- **Framework de pruebas:** Pytest  
- **Automatización Web:** Selenium WebDriver  
- **Entorno de desarrollo:** PyCharm  

---

## ✅ Lista de comprobación  

El conjunto de pruebas automatizadas valida los siguientes pasos en la aplicación:  

| № | Descripción de la Prueba |
|---|---------------------------|
| 1 | `test_set_route`: Establecer la dirección de recogida y el destino. |
| 2 | `test_select_comfort`: Seleccionar el tipo de tarifa **"Comfort"**. |
| 3 | `test_fill_number`: Rellenar el número de teléfono y confirmar el código. |
| 4 | `test_add_new_card`: Agregar un nuevo método de pago con tarjeta. |
| 5 | `test_add_message`: Agregar un mensaje para el conductor. |
| 6 | `test_add_blanket`: Seleccionar la opción de **"Manta y pañuelos"**. |
| 7 | `test_add_ice`: Agregar dos unidades de **"cubeta de hielo"**. |
| 8 | `test_order_taxi`: Hacer clic en el botón para pedir un taxi. |
| 9 | `test_get_driver`: Verificar que la información del conductor se muestra en la pantalla. |

---

## 📊 Resultado de las pruebas  

A continuación, se muestra el resultado completo de la ejecución de pruebas, donde todas las validaciones han sido exitosas:  

============================= test session starts =============================
collecting ... collected 9 items

main.py::TestUrbanRoutes::test_set_route PASSED [ 11%]
main.py::TestUrbanRoutes::test_select_comfort PASSED [ 22%]
main.py::TestUrbanRoutes::test_fill_number PASSED [ 33%]
main.py::TestUrbanRoutes::test_add_new_card PASSED [ 44%]
main.py::TestUrbanRoutes::test_add_message PASSED [ 55%]
main.py::TestUrbanRoutes::test_add_blanket PASSED [ 66%]
main.py::TestUrbanRoutes::test_add_ice PASSED [ 77%]
main.py::TestUrbanRoutes::test_order_taxi PASSED [ 88%]
main.py::TestUrbanRoutes::test_get_driver PASSED [100%]

============================= 9 passed in 34.87s ==============================



---

## 🎉 Conclusiones

Todas las pruebas automatizadas pasaron exitosamente, lo que indica que el flujo de pedido en la aplicación **Urban-Routes** funciona como se espera.
El conjunto de pruebas valida correctamente las interacciones del usuario, la entrada de datos, la selección de opciones y la confirmación final de la orden.

---

## 🚀 Ejecución de pruebas

Clona el repositorio:

```bash
git clone https://github.com/usuario/Urban-Routes.git
cd Urban-Routes

pip install -r requirements.txt


pytest
