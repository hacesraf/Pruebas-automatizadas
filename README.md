# Proyecto de Automatización de Pruebas

## Descripción

Proyecto de automatización de pruebas frontend utilizando Selenium IDE sobre una aplicación web pública y pruebas de backend utilizando Postman y Newman sobre una API pública.

### Aplicaciones probadas

- https://www.saucedemo.com
- https://jsonplaceholder.typicode.com

---

## Herramientas utilizadas

- Selenium IDE
- Selenium Side Runner
- Postman
- Newman

---

## Justificación de las herramientas

### Selenium IDE

Se utilizó para la automatización de pruebas frontend debido a que permite grabar y reproducir acciones realizadas por el usuario dentro del navegador, facilitando la creación de casos de prueba sin necesidad de desarrollar scripts complejos. Además, permite validar el funcionamiento de la interfaz de manera rápida y sencilla.

### Selenium Side Runner

Se utilizó para ejecutar los casos de prueba creados en Selenium IDE desde la línea de comandos. Esto permite automatizar la ejecución de pruebas y visualizar los resultados de manera eficiente, mostrando los casos aprobados o fallidos en la consola.

### Postman

Se utilizó para realizar pruebas sobre la API REST, ya que permite enviar solicitudes HTTP y validar las respuestas obtenidas. Su interfaz facilita la creación y organización de pruebas mediante colecciones.

### Newman

Se utilizó para ejecutar las colecciones de Postman desde la terminal. Esto permite automatizar las pruebas backend sin necesidad de abrir Postman, facilitando la integración con procesos automatizados y la obtención de resultados en consola.

---

## Ejecución de pruebas Frontend

Ejecutar el siguiente comando en la terminal:

```bas
selenium-side-runner Test_Frontend.side
