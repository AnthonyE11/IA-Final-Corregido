# IA-Final-Corregido
Cómo utilizarlo:

Descargar el repositorio:
Descarga el repositorio en tu computadora desde el enlace proporcionado.

Iniciar un servidor en la carpeta:
Este proyecto utiliza un modelo de Tensorflow.js, el cual se carga a través de una conexión HTTP/HTTPS. Para visualizar la aplicación, se requiere un servidor local. Sigue estos pasos:

Descarga Python en tu computadora (si aún no lo tienes).
Abre una línea de comandos o terminal.
Navega hasta la carpeta donde descargaste el repositorio.
Ejecuta el comando python -m http.server 8000.
Abre un explorador web y ve a http://localhost:8000.
Utilizarlo en un celular:
Si deseas abrir la aplicación en tu celular, es necesario establecer una conexión HTTPS para acceder a la cámara del dispositivo. Puedes seguir estos pasos para hacerlo:

Descarga ngrok en tu computadora y descomprímelo.
Abre una línea de comandos o terminal.
Navega hasta la carpeta donde descargaste ngrok.
Ejecuta el comando ngrok http 8000.
Aparecerá un enlace HTTPS en la línea de comandos. Accede a este enlace desde tu celular (no importa si no estás en la misma red local).
El túnel de ngrok expirará después de 2 horas. En caso de que necesites más tiempo, simplemente reinicia ngrok.
Uso:

Al acceder a la aplicación desde un explorador web, podrás ver un botón "Cambiar cámara". Puedes utilizarlo para alternar entre la cámara delantera y trasera de tu celular.

Apunta la cámara hacia un perro o gato. La aplicación realizará una predicción y mostrará los resultados en la parte inferior de la pantalla.

Ten en cuenta que este clasificador no es perfecto y podría cometer errores en la clasificación.

¡Disfruta utilizando la aplicación para identificar perros y gatos con la cámara de tu celular! Si tienes alguna pregunta o sugerencia, no dudes en hacerla. Recuerda que este proyecto fue realizado con fines educativos por un estudiante y está en constante mejora.
