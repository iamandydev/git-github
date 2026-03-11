```
git init
```
Inicializa el proyect y crea el subdirectorio /.git, que contiene los archivos necesarios para el repositorio.

```
git fetch
```
Descarga los cambios realizado en el repositorio remoto, de modo que permite actualizar el repositorio local con la información del repositorio remoto.

```
git merge <nombre_rama>
```
Trae a la rama actual, los cambios realizados en la rama especificada.

```
git pull
```
Unifica los comandos `fetch` y `merch` en uno solo.

```
git commit -m "<mensaje>"
```
Confirma los cambios realizados. El “mensaje” generalmente se usa para asociar al commit una breve descripción de los cambios realizados.

```
git push origin <nombre_rama>
```
Sube la rama “nombre_rama” al servidor remoto.

```
git add <nombre_archivo>
```
Comienza a trackear el archivo “nombre_archivo”.
