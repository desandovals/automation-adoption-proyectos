# Proyecto Golondrinas

Este será el último proyecto que trabajemos durante este curso. Les deseo éxito y que por sobre todo se puedan divertir. 

## Repositorio

Este proyecto será GRUPAL a diferencia de los demás, por lo que el equipo único que trabajará en él es el grupo en el que se encuentren actualmente. 

Por cada grupo, deberán crear un repositorio público donde irán depositando el desarrollo de su proyecto. 

Nomenclatura de nombre del repositorio: 

```
proyecto-final-grupo-## 
```

## ¿Líderes?

Como grupo, deberán designar un único líder, que será el responsable de lo siguiente: 

- Organizar actividades (salas de chat, meets, etc).  
- Hacer la entrega formal del proyecto en tiempo y forma. 
- Punto de contacto con el profe Dan. 

## ¡¡A programar!!

Deberán crear un programa, haciendo uso de variables, funciones, condicionales y ciclos, que realice lo siguiente: 

1. Crear un bucket de GCS que tenga un rango de nombre del 04 al 07. Recuerden que no deben repetirse, por lo cual el líder tendrá que comunicarse con líderes de los otros 3 grupos para elegir cada uno el bucket que creará. 

**Nota:** Si adjuntan evidencia de la comunicación que hubo, los líderes serán acreedores a 3 participaciones adicionales. 

**Características del bucket:**

<div align="center">

| Rubro             | Valor                 |
| :---------------: | :-------------------: |
| Store             | Multiregional         |
| Storage Class     | Acceso frecuente      |
| Tipo de acceso    | Uniform               |
| Etiqueta 1        | grupo:grupo-##        |
| Etiqueta 2        | proyecto:golondrinas  |

</div align="center">

2. Dentro del GCS, crear una carpeta con la nomenclatura `grupo-##`. 
3. Crear dentro 100 carpetas con la nomenclatura `carpeta-###`. 
4. Crear en cada carpeta un archivo de texto vacío de nombre `sinceramente.txt`. 
5. Seguir las instrucciones del `Proceso manual` detallado más adelante. 

**Proceso manual:**

Cada integrante del equipo deberá elegir una carpeta de forma totalmente aleatoria y reemplazar el archivo `sinceramente.txt`, con uno del mismo nombre que tenga contestadas la siguientes preguntas:

- ¿Te gustó el curso?
- ¿Te divertiste?
- ¿Qué cosas NO te gustaron? 
- ¿Vovlerías a tomar un curso similar? 
- Comentario de libre elección. 

La intención de esta sección es que puedan compartir sus comentarios de forma anónima, por lo que queda **PROHIBIDO** compartir con otros compañeros qué carpeta eligieron. 

6. Crear una función que indique en qué carpetas están los archivos no vacíos de nombre `sinceramente.txt`.
7. La ejecución del programa debe generar un log, con el siguiente formato de nombre: 

```
grupo-##-fecha-hora.log
```

### Logging del programa

El log generado por el programa, debe contener la siguiente información: 

- Grupo ## 
- Distribución de Linux en la que se está ejecutando el programa. 
- Usuario que ejecutó el programa. 

## Documentación 

1. El script que desarrollen deberá estar almacenado en una carpeta de nombre `script` dentro de su repositorio. 
2.  Deberán crear un README en la raíz de su repositorio, que contenga la siguiente información: 

&emsp;&emsp; - **Título:** Proyecto final <br>
&emsp;&emsp; - **Tabla con dos columnas:** La primer columna deberán listarse quienes participaron en el proyecto y la segunda columna la descripción de su participación en el mismo. <br>
&emsp;&emsp; - **Los líderes** deberán estar en el último renglón. <br>
&emsp;&emsp; - **Evidencias:** Pantallazos de todo aquello que se solicite tener evidencia como sustento.  

3. TODOS, sin excepción, deberán tener registrados commit en el repositorio de github para tener participación en el proyecto. No importando si aportaron al readme o al script. 

## Consintiendo al profe (opcional)

Generar una función del programa, que permita decidir al usuario si quiere o no que se muestren en pantalla el contenido de los comentarios que se encuentran dentro de los archivos `sinceramente.txt`. 

En caso de que el profe eliga que si, ir mostrando el contenido de los archivos uno a uno, con intervalos de 15 segundos entre uno y otro. En caso de que se eliga que no, simplemente salir del programa. 

## Forma de evaluación: 

Para este proyecto se evaluará de la siguiente forma: 

- Repositorio: 15 % 
- ¡¡A programar!!: 65 %
- Logging: 10 %
- README: 10 %

## El buen trabajo se recompensa

<div align="center">

| Rubro                 | Puntaje extra     |
| --------------------- | ----------------- |
| Cumplimiento 100%     | 9 participaciones |
| ¡¡ A programar !!     | 7 participaciones | 
| Consintiendo al profe | 6 participaciones |
| Trabajo en equipo     | 10 participaciones|
| Evidencia líderes     | 3 participaciones |
 
 </div align="center">

### Notas

- Para el tema del trabajo en equipo, deberán compartir evidencia y anécdotas de los retos que enfrentaron. 
- Para la actividad de `¡¡A programar !!`, serán 7 participaciones para las personas que hayan participado en el desarrollo del script, no importando la función que hayan desarrollado. 
- Para la actividad de `Consintiendo al profe` **sólo se darán participaciones a los miembros del equipo que hayan desarrollado esa función**, para lo cual se deberá adjuntar evidencia de su participación. 
- Las participaciones son adicionales al score que tengan en el proyecto.  
