# app-ejemplo-evaluacion

Aplicacion base para evaluacion de Docker, Kubernetes y CI/CD.

## Comandos utiles

```sh
npm install
npm test
npm start
```

La aplicacion escucha en el puerto `8080` y expone `GET /`.

## Evidencia inicial obligatoria
Captura o registro de la aplicación ejecutándose localmente.
![alt text](/evidencias/app-local.png)
Captura o registro de una petición local a GET /.
![alt text](/evidencias/Get-inicial.png)
Captura o registro de la ejecución inicial de npm test.
![alt text](/evidencias/npm-test-inicial.png)

## Evidencias Reto 1
En el 1er Reto las variables ya estaban establecidas
Captura o registro de la aplicación respondiendo manualmente.
![alt text](/evidencias/Get-inicial.png)
Captura o registro del fallo inicial de la prueba.
![alt text](/evidencias/npm-test-inicial.png)
Captura o registro que compare la respuesta real de la aplicación con la expectativa del test.
![alt text](/evidencias/resp-real-resp-exp.png)
Captura o registro del archivo de prueba corregido.
![alt text](/evidencias/server.test-corregido.png)
Captura o registro de npm test ejecutándose correctamente después del ajuste.
![alt text](/evidencias/npm-corregido.png)

## Evidencias Reto 2

Captura o registro de la construcción inicial de la imagen.
![alt text](/evidencias/Imagen-fallosa.png)
Captura o registro que muestre si el build inicial valida o no las pruebas.
Captura o registro del Dockerfile final.
![alt text](/evidencias/Dockerfile-final.png)
Captura o registro de un build bloqueado cuando existe una prueba fallida.
![alt text](/evidencias/bloqueado.png)
Captura o registro de un build exitoso cuando las pruebas pasan.
Captura o registro del contenedor final respondiendo desde la máquina anfitriona.
![alt text](/evidencias/maquina-anfitriona.png)
## Evidencias Reto 3
Agregar el build-test
Captura o registro del workflow inicial.
![alt text](/evidencias/workflow-inicial.png)
Captura o registro de una ejecución donde una prueba falla.
![alt text](/evidencias/falla-intencional.png)
Captura o registro que demuestre el comportamiento defectuoso inicial del pipeline.
![alt text](/evidencias/pipeline-fallido.png)
Captura o registro del workflow corregido.
![alt text](/evidencias/workflow-corregido.png)
Captura o registro de una ejecución donde el despliegue se bloquea por una prueba fallida.
![alt text](/evidencias/block-despliegue.png)
Captura o registro de una ejecución final donde las pruebas pasan y el despliegue continúa.
![alt text](/evidencias/despliegue-pipeline.png)
## Evidencias Reto 4
Captura o registro de la aplicación del manifiesto.

Captura o registro de los pods en ejecución.
Captura o registro del Service y sus endpoints asociados.
Captura o registro de una petición exitosa a la aplicación a través del servicio.
Captura o registro de una modificación controlada del test o de la app que demuestre que el pipeline detecta fallos reales.