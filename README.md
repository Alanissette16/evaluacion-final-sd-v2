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
![alt text](Imagen-fallosa.png)
Captura o registro que muestre si el build inicial valida o no las pruebas.
Captura o registro del Dockerfile final.
![alt text](Dockerfile-final.png)
Captura o registro de un build bloqueado cuando existe una prueba fallida.
![alt text](bloqueado.png)
Captura o registro de un build exitoso cuando las pruebas pasan.
Captura o registro del contenedor final respondiendo desde la máquina anfitriona.
![alt text](maquina-anfitriona.png)
## Evidencias Reto 3
Captura o registro del workflow inicial.
![alt text](workflow-inicial.png)
Captura o registro de una ejecución donde una prueba falla.
![alt text](falla-intencional.png)
Captura o registro que demuestre el comportamiento defectuoso inicial del pipeline.
![alt text](pipeline-fallido.png)
Captura o registro del workflow corregido.
![alt text](workflow-corregido.png)
Captura o registro de una ejecución donde el despliegue se bloquea por una prueba fallida.
![alt text](block-despliegue.png)
Captura o registro de una ejecución final donde las pruebas pasan y el despliegue continúa.

## Evidencias Reto 4