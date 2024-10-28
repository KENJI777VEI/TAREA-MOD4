# TAREA-MOD4

* Maestria en ingeninieria y tecnologia hospitalaria
* Practica 1 y 2
* Estudiante: Kenji Gonzalo Veizan Lopez
* M.Sc Ing. Edwin Calle Condori


# PRACTICA 1

- Se descargaron imagenes llamada de emergencia y detectores de incendios 
- Se crearon los repositorios para las imagenes y los labels, distribuyendo 200 imagenes para el entrenamiento y 96 para la validacion
- Con la  herramienta https://www.makesense.ai/ se realizaron las etiquetas
![](https://github.com/KENJI777VEI/TAREA-MOD4/blob/main/etiqueta.jpg)
- Se guardaron y exportaron las anotaciones en formato YOLO
- Al estructurar la carpeta data se realizo la transformacion en formato zip


# PRACTICA 2

- Se utilizao el archivo data.zip creado en la practica 1 para el entrenmiento del modelo
- Se siguieron las isntrucciones: [https://github.com/KENJI777VEI/TAREA-MOD4.git](https://geonort.blogspot.com/2024/10/identificacion-de-sistemas-de-seguridad_17.html)
- Se utilizo la plataforma de colab, se importo el docuemnto comprimido y se creo el archivo custom.yaml considerado las etiquetas y los nombres de cada uno de los archivos y se importo para su utilizacion.
- Se ralizaron las configuraciones con 20 lotes y 100 epocas como se muestra en la imagen
![](https://github.com/KENJI777VEI/TAREA-MOD4/blob/main/entrenamiento.jpg)
- El entrenamiento fue terminado correctamte y se procedio a la descarga del archivo best.pt
![](https://github.com/KENJI777VEI/TAREA-MOD4/blob/main/respuestaentreno.jpg)
- Para verificar el correcto funcionamiento se realizaron pruebas con diferentes imagenes obeteniendo resultados aceptables para las dos etiquetas
![](https://github.com/KENJI777VEI/TAREA-MOD4/blob/main/Deteccion.jpg)
- Se termino correctamente la practica comprendiendo el entramiento de cualquier tipo de imagenes haciendo uso de YOLO, aprochando sus ventajas para el reconocimiento de imagenes
