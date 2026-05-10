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
### Modelo Entidad - Relación

![image](https://github.com/user-attachments/assets/06224038-091a-4af6-b509-d7f16f76fa55)

____________________________________________________________________________________________________________________________________
### Modelo Relacional de la BD

![image](https://github.com/user-attachments/assets/a4a5cd71-d932-4f9e-a100-7ff03c690c18)

____________________________________________________________________________________________________________________________________
## Reglas de Negocio
____________________________________________________________________________________________________________________________________
### carreras

1. Crear el registro de una carrera.
2. Leer el registro de una(s) carrera(s) dada una condición en particular.
3. Leer todos los registros de la entidad carreras.
4. Actualizar los datos de una carrera dada una condición en particular.
5. Eliminar los datos de una carrera dada una condición en particular.
   
### tipos_carreras

1. Todos los valores del atributo distancia, deberán estar expresados en km y no se podrán repetir.
2. Crear el registro de un tipo de carrera.
3. Leer el registro de un(os) tipo(s) de carrera(s) dada una condición en particular.
4. Leer todos los registros de la entidad tipos carreras.
5. Actualizar los datos de un tipo de carrera dada una condición en particular.
6. Eliminar los datos de una tipo de carrera dada una condición en particular.

### paises

1. Crear el registro de un país.
2. Leer el registro de un(os) pais(es) dada una condición en particular.
3. Leer todos los registros de la entidad paises.
4. Actualizar los datos de un país dada una condición en particular.
5. Eliminar los datos de un páis dada una condición en particular.
