# IEE240 - Laboratorio 4 - 2021-1

## Instrucciones:
- Para clonar el repositorio y trabajar de forma local, realizar lo siguiente en un Terminal de Linux. Dentro de `<carpeta-del-repositorio>` encontrará todos los archivos necesarios para el desarrollo del laboratorio.
```
$ git clone <link-repositorio-alumno>
$ cd <carpeta-del-repositorio>
```
- Cada carpeta contiene un archivo `README.md` con el enunciado de la pregunta. Puede visualizarlo directamente en su repositorio en el explorador web.

- Recordar que para poder ejecutar los archivos con extensión `.sh` debe realizar lo siguiente:
```
$ chmod 777 nombre_de_achivo.sh
```

- **La prueba inicia a las 8:00 pm y termina a las 10:00 pm. El sistema (GitHub Classroom) cierra a las 10:10pm, no se calificarán entregas (`push`) luego de esa hora.**

- **En caso se detecte plagio en alguno de sus códigos, se iniciará el proceso correspondiente definido por la Facultad de Ciencias e Ingeniería.**

## Subir solución a GitHub Classroom para revisión.
Al terminar el laboratorio y luego de validar localmente la correcta ejecución de su programa, realizar un `push` de su solución a su laboratorio para su corrección. Para ello ejecute los siguientes comandos en un Terminal de Linux. **NOTA:** Los comandos a continuación debe ejecutarlos dentro de la carpeta `<carpeta-del-repositorio>`.

- Verificar con el siguiente comando que se han modificado los archivos correctos. Debería aparecer en rojo los archivos modificados durante el laboratorio.
```
$ git status
```
- Para añadir los archivos a git:
```
$ git add .
```
- Para subir sus códigos al repositorio remoto (GitHub):
```
$ git commit -m "<ponga-aqui-un-comentario-util>"
$ git push
```
- Cualquier consulta comuníquese con su JP.