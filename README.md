// Solicita el nombre del usuario y lo almacena en la variable 'nombre'
const nombre = prompt("¿Cuál es tu nombre?");

// Solicita la edad del usuario y la almacena en la variable 'edad'
const edad = prompt("¿Cuántos años tienes?");

// Solicita el lenguaje de programación que el usuario está estudiando y lo almacena en la variable 'lenguaje'
const lenguaje = prompt("¿Qué lenguaje de programación estás estudiando?");

// Crea un mensaje personalizado utilizando las variables 'nombre', 'edad' y 'lenguaje'
const mensaje = `¡Hola ${nombre}, tienes ${edad} años y ya estás aprendiendo ${lenguaje}!`;

// Muestra el mensaje personalizado en una ventana emergente
alert(mensaje);

// Solicita al usuario que indique si le gusta estudiar el lenguaje de programación, con opciones 1 para SÍ y 2 para NO
const gusta = prompt(`¿Te gusta estudiar ${lenguaje}? Responde con el número 1 - SÍ o 2 - NO`);

// Si el usuario responde con 1 (SÍ), muestra un mensaje de ánimo
if (gusta == 1){
    alert("¡Muy bien! Sigue estudiando y tendrás mucho éxito.");
}

// Si el usuario responde con 2 (NO), muestra un mensaje de aliento para intentar aprender otros lenguajes
if (gusta == 2){
    alert("Oh, qué pena... ¿Has intentado aprender otros lenguajes?");
}
