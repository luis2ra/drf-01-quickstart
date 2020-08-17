# Para hacer testing de usuarios / grupos


Opción 1: usando el comando curl desde consola

$ curl -H 'Accept: application/json; indent=4' -u admin:password123 http://127.0.0.1:8000/users/



Opción 2: usando el comando http (de httpie) desde consola:

$ http -a admin:password123 http://127.0.0.1:8000/users/



Opción 3: desde un navegador web:

http://127.0.0.1:8000/users/



Opción 4: Usando la aplicación Postman