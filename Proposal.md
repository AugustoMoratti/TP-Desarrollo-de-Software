# TP-Desarrollo-de-Software
## Grupo
### Integrantes
* Cossia Colagioia, Lucas - 52777
* Soto, Nahir Yania - 47103
* Moratti, Augusto Franco - 52555
* Bertuccelli, Valentin - 52809

### Repositorios
* [BackEnd](https://github.com/AugustoMoratti/TP-Desarrollo-de-Software/tree/main/Backend)

* [FrontEnd](https://github.com/AugustoMoratti/TP-Desarrollo-de-Software/tree/main/Frontend)

## Tema

### Descripción
Nuestra propuesta se basa en una aplicacion online que logre conectar dos personas, un primer usuario que requiere de un servicio (como puede ser un electricista) y otro tipo de usuario que ofrezca sus servicios, en la cual los usuarios puedan encontrar, postular y puntuar profesionales que estén ofreciendo sus servicios. estos servicios están orientado a oficios como electricista, plomero o carpintero, todos con su debida acreditación y con reseñas de usuarios. La idea es crear un lugar donde se pueden encontrar profesionales con validaciones de usuarios previos con sus experiencia.

### Modelo

## Alcance Funcional

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Provincia<br/>2. CRUD Profesion<br/> |
|CRUD dependiente|1. CRUD Perfil *{depende de}* CRUD Provincia y Profesion<br/>2. CRUD Localidad *{depende de}* CRUD Provincia<br/>|
|Listado + detalle|1. Listado de perfiles filtrado por Profesion, Localidad, Provincia Y Valoracion, muestra Nombre y Valoracion => detalle CRUD Perfil<br/>2. Listado de Profesion, muestra Nombre => detalle CRUD Profesion |
|CUU/Epic|1. Realizar Solicitud<br/>2. Tomar solicitud|

Adicional para Aprobación:
|Req|Detalle|
|:-|:-|
|CRUD ||
|CUU/Epic|1. Realziar pago<br>2. Solicitar profesion<br>3. Realizar reseña<br/>4. Agendar trabajo (pregunta)|
