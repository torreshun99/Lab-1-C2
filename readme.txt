----------------ENUNCIADO--------------------------------
En muchos restaurantes de El Salvador, el proceso de toma de pedidos aún se realiza de forma manual con papel y lápiz. 
Esto genera errores en la comunicación con cocina, lentitud al calcular el total de la cuenta y dificultades para modificar pedidos en tiempo real. 
Se propone una interfaz web sencilla donde el personal pueda registrar productos, ver el resumen de la orden y calcular el total automáticamente.

---Sectores enfocados---

Sector de gastronomia

Sector de servicio al cliente

---------------Funciones del programa --------

Registro de productos: Permite ingresar el nombre del plato y su precio.

Validación de datos: Evita que se agreguen productos sin nombre o con precios negativos.

Cálculo automático: Suma los precios de los productos agregados mediante variables reactivas.

Control de visibilidad: Muestra un mensaje especial si la cuenta está vacía o si supera un monto determinado.


-----------Preguntas--------------------------

1. ¿Qué es Vue.js y para qué sirve?
Es un marco de trabajo (framework) de JavaScript que sirve para crear páginas web interactivas de forma más fácil. 
Su función principal es conectar los datos que tenemos en el código con lo que el usuario ve en la pantalla para que 
todo se actualice automáticamente sin recargar la página.

2- ¿Qué significa que una variable sea "reactiva"?
Significa que la variable está "viva" o conectada a la vista. Si el valor de esa variable cambia en el código (por ejemplo, al sumar un precio), 
el texto en el navegador cambia al instante sin que nosotros tengamos que escribir código extra para refrescar la pantalla.

3- ¿Para qué sirven las directivas v-model y v-on (o @)?

v-model: Sirve para amarrar lo que el usuario escribe en un cuadrito de texto (input) con una variable. 
Es como un puente de dos vías.

v-on / @: Sirve para detectar cuando el usuario hace algo, como un clic en un botón 
y decirle al programa que ejecute una función en respuesta.

4. ¿Cuál es la utilidad de v-for y v-if?

v-for: Es como un ciclo que se usa para mostrar una lista de cosas (como los productos de la orden) repitiendo la misma estructura HTML varias veces.

v-if: Es una condición. Solo muestra una parte de la página si se cumple algo (por ejemplo, mostrar un mensaje de error solo si los campos están vacíos).

5. ¿Por qué es importante validar las entradas de datos?
Porque evita que el programa falle o de resultados locos. Si no validamos, alguien podría dejar el nombre vacío o poner un precio negativo, lo que haría que 
la cuenta total esté mal calculada o que la lista se llene de basura.


Alumno: Josue Alexander Turcios Quintanilla
Alumno: Jose Aristides Torres Ramos

