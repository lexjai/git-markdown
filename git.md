# GIT 
[Git]: https://git-scm.com/
[Git] es un sistema de control de versiones uno de los mas utilizados.

[Git], que presenta una arquitectura distribuida, es un ejemplo de DVCS (sistema de control de versiones distribuido, por sus siglas en inglés), en [Git], la copia de trabajo del código de cada desarrollador es también un repositorio que puede albergar el historial completo de todos los cambios.

 Ademas de contar con una arquitectura distribuida, [Git] se ha diseñado teniendo en cuenta el rendimiento, la seguridad y la flexibilidad

Acontinuacion podremos ver algunos de los comandos mas utilizados:

 >**Git config**

Establece valores de configuracion para tu usuario, email, gpg key, etc. Ejemplos:
 
```
git config --global user.name "Mi nombre"
```
```
git config --global user.email "usuario@dominio.com"
```

>**Git init**

Inicializa un repositorio git crea el dirextorio  ***.git*** inicial en un proyecto nuevo o existente. 
```
git init
```
```
Initialized empty Git repository in /RutaDelDirectorio/.git/
```
>**Git status**

Te muestra el estado de los archivos en el index en comparación con los del directorio de trabajo. Enumerará los archivos que no están rastreados (solo en su directorio de trabajo), modificados (rastreados pero aún no actualizados en tu index), y almacenados (añadidos a tu index y listos para comprometerse).Ejemplo:

```
git status
 
# On branch master #
# Initial commit #
# Untracked files: #
# (use "git add <file>..." to include in what will be committed) #
 
README
```
>**Git add**

Añade cambios de archivos en tu directorio de ensayo a tu index.

```
git add . 
```
Tambien podremos especificar que ficheros queremos agregar al repositorio.
```
git add NombreArchivo
```

>**Git commit**

Toma todos los cambios escritos en el index, crea un nuevo objeto de confirmación que apunta a él y establece la rama para que apunte a esa nueva confirmación. 
```
git commit -m ‘committing added changes’
```
```
git commit -a -m ‘committing all changes, equals to git add and git commit’
```


>**Git remote add origin**

Nos ayuda agregar el repositorio de destino al cual queremos subir nuestros archivos/ficheros.

```
git remote add origin  https://github.com/nombreUsuarioGit/nombedelrepositorio/
```

>**Git push **

Obtiene los archivos del repositorio remoto y los combina con el local.
```
git push -u origin NombreRama
```
>**git pull**

Obtiene los archivos del repositorio remoto y los combina con el loca
```
git pull origin
```


>**Git branch**

Podremos listar la ramsa existentes, incluyendo la remota

```
git branch
```
Si se proporciona '**-a**' creara una nueva rama proporcionando un nombre.

```
git branch -a * master
```

>**Git remote**

Muestra todas las versiones remotas de tu repositorio.

```
git remote origin
```

## **Referencias:**
- <https://git-scm.com/>
- <https://www.hostinger.es/tutoriales/comandos-de-git>





## [Git](https://github.com/lexjai/git-markdown)


Comandos | Función
----|-----
git init| Crea un nuevo repositorio git 
git add | 

```
git init
git add 
git commit -m
git remote add origin ...
git push -u origin 

```
