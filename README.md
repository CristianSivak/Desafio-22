# Desafio-22
Programacion Backend - Coderhouse

>> Consigna:
Sobre el desafío entregable de la clase número 20, crear una ruta 'productos/vista-test' que permita mostrar productos generados al azar en forma de tabla (similar a lo realizado sobre la ruta 'productos/vista').
Los productos se generarán utilizando Faker.js como generador de información aleatoria de test (en lugar de tomarse desde la base de datos). Elegir apropiadamente los temas para conformar el objeto ‘producto’: nombre, precio y foto.
Considerar pasar por query params la cantidad de productos a generar: 
Ej. 'productos/vista-test?cant=5'. De no pasar ningún valor, producirá 10 objetos.
Verificar la generación de productos aleatorios utilizando distintas cantidades. Comprobar que para cantidad 0 indique que no hay productos.
