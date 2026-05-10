# Diseno-de-Bases-de-Datos

# **CARRERAS**

## **Listado de Entidades**

### carreras (ED)
* carrera_id **(PK)**
* nombre
* tipo_carrera **(FK)**
* fecha
* tiempo
* mejor_tiempo
* altitud
* lugar
* pais **(FK)**
* foto
### tipos_carreras **(EC)**
* tipo_carrera_id **(PK)**
* descripcion
* distancia **(UQ)**
### paises **(EC)**
* pais_id **(PK)**
* nombre

## **Relaciones**
____________________________________________________________________________________________________________________________________
1. Una **carrera** pertenece a un **tipo de carrera** _(1 a M)._
2. Una **carrera** se corre en un **país** _(1 a M)._
   
## **Diagramas**
____________________________________________________________________________________________________________________________________
### Modelo Entidad - Reación

1[image](https://github.com/user-attachments/assets/06224038-091a-4af6-b509-d7f16f76fa55)

Modelo Entidad - Reación

Modelo Relacional de la BD
Modelo Relacional de la BD

Reglas de Negocio
carreras
Crear el registro de una carrera
Leer el registro de una(s) carrera(s) dada una condición en particular.
Leer todos los registros de la entidad carreras.
Actualizar los datos de una carrera dada una condición en particular.
Eliminar los datos de una carrera dada una condición en particular.
tipos_carreras
Todos los valores del atributo distancia, deberán estar expresados en km y no se podrán repetir.
Crear el registro de un tipo de carrera
Leer el registro de un(os) tipo(s) de carrera(s) dada una condición en particular.
Leer todos los registros de la entidad tipos carreras.
Actualizar los datos de un tipo de carrera dada una condición en particular.
Eliminar los datos de una tipo de carrera dada una condición en particular.
paises
Crear el registro de un país
Leer el registro de un(os) pais(es) dada una condición en particular.
Leer todos los registros de la entidad paises.
Actualizar los datos de un país dada una condición en particular.
Eliminar los datos de un páis dada una condición en particular.
