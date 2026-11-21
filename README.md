# seminario_dsga
Trabajo práctico: Aplicación web CRUD desarrollada con IA
prompts utilizado
1.  Hola, necesito hacer una aplicación web CRUD para un trabajo de la universidad. Quiero que sea un inventario para una tienda de barrio, donde cada producto tenga nombre, categoría, precio en pesos colombianos y cantidad. Todo tiene que estar en un solo archivo index.html: el CSS dentro de una etiqueta <style> y el JavaScript dentro de una etiqueta <script>. Los datos se deben guardar en localStorage. Por ahora dame solo la estructura HTML con un formulario para agregar productos y una tabla para mostrarlos.
2.  Ahora agrégale dentro del <script> las funciones para crear, listar, editar y eliminar productos guardándolos en localStorage. Comenta el código en español explicando qué hace cada parte
// como el diseño estaba muy simple y es lo normal para que vaya añadiendo desde una hoja en blanco hasta un diseño profesional decidi hasta el segundo añadirle mas ux para mayor calidad///
3.  Agrégale estilos CSS dentro del <style>. Quiero un diseño moderno y limpio, con color principal verde azulado, el formulario y la tabla en tarjetas blancas con sombra, botones redondeados y que se vea bien en celular.
tambien en las escepciones quiero que no uses alert, muestra el mensaje de error en rojo debajo del formulario. añade validaciones al formulario: el nombre debe tener mínimo 2 letras, hay que elegir una categoría, y el precio y la cantidad no pueden ser negativos.
4.  mejora la tienda de manera que tenga un menu de bienvenida en la parte superior y al bajar el pedido del producto: pidiendo los requisitos tales como: (nombre completo, cedula, numero celular, categoria y que en vez de colocar el precio uno mismo, que ya vengan pre establecidos, pide cantidad dependiendo de que tantas cosas lleve y si lleva mas de una en un solo producto,  direccion y si paga en efectivo o transferencia)
5.  Refactoriza el código para usar el mismo formulario tanto para crear como para editar, usando un campo oculto con el id del producto. Cuando esté editando, el botón debe decir "Actualizar" y debe aparecer un botón para cancelar la edición.
// a este punto, era muy simple y solo podia colocar informacion,pero no subirla//
6.  si es necesario añadirle otra tecnologia como por ejemplo, HTML, CSS, JavaScript, Node.js, React) utilizala para que podamos almacenar la informacion del pedido y la edicion de  los otros
7.  Agrega un buscador arriba de la tabla que filtre por nombre o categoría. Muestra los precios con formato de pesos colombianos (ejemplo: $4.500) y agrega un resumen con el total de productos y el valor total del inventario.
   // ahora le pedimos clacificar la cantidad de stock//
8.  Haz que los productos con menos de 5 unidades se vean en naranja con un ícono de advertencia, y agrega un mensajito flotante en la esquina que aparezca cuando se agregue, edite o elimine un producto.
9.  como es un proyecto de prueba al colocar efectivo o transferenci y confirmar pedido quiero que lo subas de una ves a la ventana de pedidos registrados(es solo un prototipo de prueba)
