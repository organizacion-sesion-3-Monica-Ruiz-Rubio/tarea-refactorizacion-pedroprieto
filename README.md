[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/R8hEAr68)
# sesion7-tarea-individual
Crea un proyecto de consola llamado EjercicioRefactorizacion y copia las siguientes clases con el código correspondiente:

## Configuración
Clona el repositorio: `git clone https://github.com/MonicaRuiz/EjercicioRefactorizacion.git`

## Ejercicio
1. Renombra los siguientes elementos, comprobando que se han modificado sus referencias en todas las clases:
• Clase Class1 por Operaciones
• Método Or2Nms por Ordenar2Numeros
• Parámetro a por numero2
• Parámetro b por numero1
2. Reordena los parámetros del método Ordenar2Numeros de forma que quede numero1 primero y numero2 segundo.
3. Encapsula el campo radio por una propiedad con los descriptores de acceso get y set.
4. Reemplaza todas las referencias del valor 3,14159 en la clase Operaciones por una constante simbólica llamada PI.
5. Extrae el código PI * radio * radio de los métodos VolumenEsfera y AreaEsfera por un método llamado AreaCirculo. Modifica este último método para que sea público.
6. Elimina el parámetro radio del método PerimetroCirculo. Comprueba que continua funcionando igual y razona porqué. Razona también si se puede aplicar esta herramienta de refactorización en cualquier caso.
7. Crea una nueva interfaz llamada IOrdenacion con el método Ordenar2Numeros de la clase Operaciones. Usa la herramienta de refactorización Extraer interfaz.

## Entrega el código refactorizado
