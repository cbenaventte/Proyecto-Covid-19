# Proyecto-Covid-19
Sección que muestra el avance diario de la pandemia en Chile por medio de un gráfico
Para acceder a esta información será necesario obtener un JWT y
almacenarlo en el navegador con localStorage. Al finalizar este hito el usuario que visite el
sitio web deberá ser capaz de tener una visión general de cómo ha afectado el Covid-19 a
los diferentes países del mundo, saber cuál es el país con más casos y así mismo deberá
poder conocer cómo ha ido evolucionando el Covid-19 en Chile.

Requerimientos
1. Crear una barra de navegación en la parte superior con una opción que diga “Home”
y otra de “Iniciar sesión”.
2. Al hacer click en Iniciar sesión se debe levantar un modal con un formulario que le
pida al usuario ingresar un correo y una contraseña. 
3. Implementar la lógica para obtener el JWT cuando se ingrese el correo y contraseña
a través del formulario. 
● Llamar a la API para obtener el JWT.
● Persistir el JWT.
● Cuando exista un JWT, se debe ocultar la opción del menú que dice Iniciar
sesión, se debe agregar una que diga Situación Chile y otra de Cerrar sesión.
4. Al hacer click sobre la opción Situación Chile, se debe mostrar una nueva página
donde se añadirá un gráfico y se debe ocultar el gráfico de todos los países con la
tabla. 
5. Al hacer click en la opción Situación Chile, se debe llamar a las siguientes APIs.
(2 Puntos)
● http://localhost:3000/api/confirmed
● http://localhost:3000/api/deaths
● http://localhost:3000/api/recovered
6. En un sólo gráfico de línea se debe mostrar la información obtenida de las APIs del
punto 5. 
7. Al hacer click sobre el link Cerrar sesión del menú se debe volver al estado inicial de
la aplicación, eliminar el token y ocultar los link de Situación Chile y Cerrar sesión,
además de volver a mostrar Iniciar sesión.
