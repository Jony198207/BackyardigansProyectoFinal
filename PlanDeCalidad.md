# Plan de Calidad

## 1. Identificador

**Versión**: 1.0   
**Autor**: Backyardigans

## 2. Referencias

* [Moqups] (pendiente)
* [Plantilla para plan de calidad](https://jmpovedar.files.wordpress.com/2014/03/ieee-829.pdf)

## 3. Introducción

Este plan, en su versión 1.0, tiene como motivo principal la entrega de un producto final que pueda cumplir con los distintos requerimientos de calidad. Nuestro primer punto
central es la seguridad, por lo cual se buscará garantizar la confidencialidad, integridad y disponibilidad de la información. Además, se implementarán servicios de autenticación.
En segundo término, se harán las pruebas necesarias para garantizar la fiabilidad y buen desempeño del software. Finalmente, es necesario que el producto sea fácil de mantener para
posibles actualización futuras.

## 4. Objetos de prueba

* Inicio de sesión de manera correcta: autenticación con base de datos 
* Filtros de búsqueda
* Personalización de bebidas: asegurar que las opciones disponibles cambien según la bebida
* Manejo correcto de carrito: añadir, eliminar, modificar productos
* Pago seguro y correcto
* Confirmación de pedido exitoso tras pago: seguridad
* Registro de valoración y/o comentarios de algún producto: almacenamiento correcto en base de batos y autenticar usuario

## 5. Eventos de riesgo

Áreas críticas:
* Compatibilidad con navegadores y dispositivos
* Documentación de código
* Horas de alta demanda: mañanas o periodos de exámenes
* Modificaciones para recompensas de tiempo limitado

Riesgos de Software:
* Regulaciones para venta de productos en México

## 6. Funcionalidades a Probar

* Iniciar sesión en la página
* Poder buscar una bebida y elegirla
* Añadir bebida personalizada a mi carrito
* Modificar elementos de mi carrito: borrar bebida, cambiar cantidad
* Elegir método de pago y completar transacción
* Usar programa de recompensas

## 7. Funcionalidades que no se probaran

* Observar puntos obtenidos

## 8. Estrategia

Dentro de las herramientas a usar tenemos *Selenium* para pruebas automatizadas y *Google Analytics* para observar el comportamiento de nuestros usuarios. Se implementarán cursos para los integrantes que no hayan manejado esas herramientas. Dentro de las métricas a recolectar tenemos: porcentaje de funcionalidades con tests correctos, desempeño de aplicación ante distintas cargas de usuarios, y pruebas completadas por usuarios de prueba.

Las pruebas finales involucrarán la simulación de escenarios frecuentes por usuarios nuevos para poder observar la facilidad de uso o intuitividad de nuestra aplicación.

## 9. Criterios de éxito/fallo

* Realización de pruebas con un 92% de éxito
* Todos los requerimientos de prioridad alta no presentan bugs significativos
* Satisfacción de 80% en las simulaciones hechas por usuarios
* Buen desempeño frente a la duplicación de la carga usual proyectada de usuarios

## 10. Criterios de suspensión

En el caso de que alguna de las pruebas lleve a un fallo completo de la página o comprometa la información de los usuarios, es imperante detenerlas. Ante estos eventos se debe regresar al código a hacer las correciones respectivas.

## 11. Entregables

* Plan de Calidad
* Resultados de las pruebas
* Reportes de problemas con sus respectivas soluciones

## 12. Entrenamiento y staff

Se implementarán cursos de *Selenium* y *Google Analytics* para los miembros del equipo sin experiencia con estas herramientas

## 13. Responsabilidades

- Definición de riesgos: Jonathan
- Funcionalidades a probar: Manuel
- Estrategia general: Fernanda
- Decisiones críticas para temas no presentes en el plan: Raúl
- Conflictos de horario: Camila
