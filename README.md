# Reconocedor de Emociones 😊
Hemos decidido realizar un trabajo que consiste en entrenar y reconocer 5 emociones: Enojo, Felicicdad, Neutral, Tristeza y Sopresa. Para ello, usaremos nuestra cámara web y la libreía OpenCV para capturar imágenes y entrenar el modelo.  

## Instalación del Entorno en Anaconda🐍
Teniendo Anaconda Navigator instalado, podemos importar el <code>conda_enviroment.yaml</code> ubicado en "./Ficheros", de esta forma podremos tener el Enviroment con las librerías necesarias para ejecutar cada uno de los 3* ficheros necesarios (* Si hay suerte puede que sean 4). Si todo ocurre de forma correcta, podemos pasar al siguiente apartado.

## Captura de Imágenes 📷
El primer paso será abrir "./captura.ipynb", e ir paso a pasos por cada celda. Este fichero se tendrá que **ejecutar 5 veces, 1 por cada emoción**.

La primera celda importa las librerías necesarias para este fichero.

La segunda celda implica la emoción que va a capturar la cámara, esta es la celda que hay que cambiar para cada emoción, 5 veces en total.

La tercera celda es para crear las carpetas donde se guardará las fotos, en caso de querer tener un sentimiento nuevo, solo habrá que añadirlo en la celda 2 y ejecutar la celda 3 para que se cree la carpeta.

La última celda es donde se capturan las fotos y se insertan en la carpeta correspondiente, justo antes de la celda viene explicado los cambios que hay que hacer


tienes que ir descomentando cada emoción de las 5 para que se vayan guardando. Aquí también tienes que cambiar en la última celda los números count es el número de la última foto que haya en cada carpeta, y dentro del if del final de la celda, cambiar el coun >= al número que tu quieras (te sacará fotos desde count hasta coun >= x)


## Entrenamiento del modelo 🧠
Luego cuando hayas sacado las fotos vas al ficheor de entrenamiento.ipynb, literalmente vas ejecutando celda por celda, y todo debería ir guay, la última tarda fleje porque es el entrenamiento, pero me quedé con el más rapido, que sigue yendo de puta madre, solo tarda 19 segundo (los otros 2, que ya no están, tardaban 10 minutos y 25 minutos respectivamente)

## Reconocimiento de Emociones 🤖
Y por último vas al fichero de reconocimiento, vas ejecutando celda por celda, y en la última se te debería abrir la cámara y aparecerte lo de las emociones