# Web-API-de-Libro-con-control-de-excepciones-y-mejor-descripci-n-de-API
Manejo de excepciones en GET /libros/{id_libro}
Para manejar la excepción LibroException cuando no se encuentra un libro por ID, se deben realizar las siguientes modificaciones

1.	Crear la clase LibroException:
o	En el paquete com.tuuniversidad.exceptions,  se crea una clase llamada LibroException.java.
o	Extiende la clase RuntimeException y define un constructor con un mensaje de error personalizado.


![image](https://github.com/adelavargas/Web-API-de-Libro-con-control-de-excepciones-y-mejor-descripci-n-de-API/assets/49427124/b3b612ff-f3e4-42eb-b375-812d23e4b733)


Luego se modifica el método getLibroById() en LibroController.java


![image](https://github.com/adelavargas/Web-API-de-Libro-con-control-de-excepciones-y-mejor-descripci-n-de-API/assets/49427124/4e477c8e-89d6-429c-b60f-4c1be4db0d16)


3.	Modifiqué el método createLibro() en LibroController.java


   ![image](https://github.com/adelavargas/Web-API-de-Libro-con-control-de-excepciones-y-mejor-descripci-n-de-API/assets/49427124/81057509-61be-49a1-a00c-18c5c4c1965a)


Luego abrí Postman

![image](https://github.com/adelavargas/Web-API-de-Libro-con-control-de-excepciones-y-mejor-descripci-n-de-API/assets/49427124/1f549d18-e4ee-47e9-9517-a8d83a515727)

