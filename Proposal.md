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
|CRUD simple|1. CRUD Ubicacion<br/>2. CRUD Profesion<br/>3. CRUD Asignacion<br/>4. CRUD Administrador|
|CRUD dependiente|1. CRUD Reseña *{depende de}* CRUD Profesional<br/>2. CRUD Cliente *{depende de}* CRUD Ubicacion<br/>3. CRUD Profesional *{depende de}* CRUD Ubicacion<br/> 4. CRUD Pago *{depende de}* Asignacion<br/>5. CRUD Solicitud {depende de} Profesion |
|Listado + detalle|1. CRUD Reseña => <br/>2. CRUD Cliente => <br/>3. CRUD Profesional => <br/> 4. CRUD Pago => <br/>5. CRUD Solicitud => |
|CUU/Epic||

### ***DUDAS***: 

* CRUD 5 CALENDARIO
