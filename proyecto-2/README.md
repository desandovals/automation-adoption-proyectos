# Proyecto 2

## Documentación

### Repositorio

Para el presente documento deberán crear un repositorio **privado** en GitHub, con la siguiente nomenclatura: 

- grupo-##-equipo-proyecto-2
 
#### Permisos

Deberán añadir a todos los integrantes del equipo y al usuario `desandovals` y `dfmonjarazf`. Dado que será privado, no podrán verlo ni colaborar, hasta que no hayan aceptado la invitación para colaborar en el mismo. 

#### ¿Saben guardar un secreto? 

NO deberán compartir el repositorio con otros equipos ni permitir que nadie mas que sus compañeros de equipo puedan ver su contenido. 

#### ¿Quién debe crear el repo? 

Mi sugerencia es que el líder lo realice, pero puede hacerlo cualquier otro miembro del equipo. Tomen en cuenta que dependerá de que genere las invitaciones para que puedan comenzar a colaborar.

### README

- El readme deberá tener el título con formato. 
- Deberán indicar en una tabla los miembros del equipo que hayan participado en generar los commit e indicar el miembro del equipo que haya logrado realizar la actividad `Una aguja en un pajar`. 
- Si todos colaboraron en encontrarlo, en la tabla deberán describir cómo fue que llegaron en equipo a dar con la solución. 

## Una aguja en un pajar

En el bucket `gs://crp-dev-cloudsrv-test-bkt20` se encuentra una carpeta de nombre `proyecto-2` y dentro existen alrededor de `3000 archivos`. 

Todos los archivos tienen un cierto patrón. **Todos excepto 1.**

### Instrucciones

#### Bucket GCS

1. Encontrar el archivo intruso usando comandos. 
2. Mostrar el contenido del archivo intruso. 

#### Evidencias

Subir al readme las evidencias con imágenes de los dos puntos anteriores. 

## Para pensar

En el README, contestar las siguientes preguntas. Deberá ser una respuesta por equipo a cada una. 


### Problema 1

Se está desarrollando un nuevo sistema que almacenará información de los datos de facturas de clientes durante 7 años. Pasaron por la mesa de Diseño de Infraestructura y se llegó a la conclusión de que la tecnología que se debe usar es Google Cloud Storage. 

- El primer mes, los archivos no puedan ser eliminados y/o editados. 
- Al término del primer año, los archivos se consultarán una vez al año a lo sumo. 
- Se va a requerir que al término de los 7 años, el bucket sea destruido junto con toda la información contenida en él. (2 participaciones adicionales)
- Se requiere optimizar lo más posible el costo asociado al almacenamiento. 

```
¿Cómo deben ser configurados los bucket para cumplir con lo requerido? 
```

### Problema 2

Se requieren copiar alrededor de 10 mil archivos. Se usó el comando gsutil cp * gs://bucket para copiarlos, pero al parecer llevará semanas y el proyecto se libera en días. 

```
¿De qué forma podrían optimizar la copia de los archivos? 
```

### Problema 3

Nuestros compañeros de Seguridad están realizando una auditoría sobre la infraestructura y encontraron 10 buckets con las siguientes características: 

- **Ambiente:** PRO 
- **Region:** US
- **Tipo de acceso:** Uniforme
- **Tipo de almacenamiento:** Nearline
- **Llave de cifrado:** GMEK 

```
¿Cuál podría ser el motivo de que lo hayan encontrado como un hallazgo? 
``` 

## Forma de evaluación 

Para este proyecto se evaluará de la siguiente forma: 

- Repositorio: 1.5 puntos 
- Una aguja en un pajar: 6 puntos
- Problemas: 2.5 puntos

### Nota

- Para la actividad “una aguja en un pajar”, si encuentran el archivo de forma manual (sin usar comandos) será tomado en cuenta, pero habrá penalización. 


## El buen trabajo se recompensa

<div align="center">

| Rubro                 | Puntaje extra     |
| --------------------- | :---------------: |
| Cumplimiento 100%     | 3 |
| Una aguja en un pajar | 7 | 
| Creatividad           | 3 |
| Trabajo en equipo     | 5 |
 
 </div align="center">

### Notas

- Para el tema del trabajo en equipo, deberán compartir evidencia y anécdotas de los retos que enfrentaron. 
- Para la actividad de `una aguja en un pajar`, serán 7 puntos por lograr resolverla con comandos y 3 puntos si el comando que utilizan es creativo y/o complejo. 
- Para la actividad de `una aguja en un pajar` **sólo se darán participaciones al miembro del equipo que haya logrado resolverlo**. Se dará a todos si se comparte evidencia de la participación de todos para resolverlo. 
- Los puntos son adicionales al score que tengan en el proyecto.  

 

