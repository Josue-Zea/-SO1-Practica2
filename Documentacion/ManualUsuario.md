# Manual de Usuario

_Practica 2 - Sistemas Operativos 1_

### Josu茅 David Zea Herrera - 201807159馃殌

_En este proyecto podemos visualizar el paso de informaci贸n mediante un manejador de colas y la tecn贸logia grpc alojada dentro de clusteres de kubernetes._

# 馃搵 Detalle de cada Seccion

### Env铆o de informaci贸n mediante el uso de postman
![This is a alt text.](./images/Postman.png "Pagina Web- Funcionamiento.") 

_Aqu铆 podemos observar la manera de consumir la api alojada en kubernetes, el endpoint escrito en postman recibe un json con inormaci贸n que se necesita para llevar a cabo cada juego._

_El json que se debe enviar en el enpoint debe tener la siguiente estructura:_
```sh
{
    "players": Number //Indica la cantidad de jugadores a participar
}
```

#### Visualizacion de la data recibida en mongo
![This is a alt text.](./images/MongoLogs.png "Pagina Web- Funcionamiento.")
_Aqu铆 podemos observar el resultado final, una vez se haya enviado la petici贸n, esta genera cierta informaci贸n de inter茅s que se guardar谩 en mongo para su posterior uso._