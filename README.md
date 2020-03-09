# Aprendiendo_Git
## Tutorial basado en Linux
==================================


<!-- START doctoc generado TOC por favor mantenga el comentario aquí para permitir la actualización automática ->
<!-- NO EDITE ESTA SECCIÓN, EN LUGAR RE-RUN doctoc PARA ACTUALIZAR -->

**Tabla de contenido**  *generado con: [DocToc](https://github.com/thlorenz/doctoc)*

- [Primeros pasos con Git](#primeros-pasos-con-git)
- [Crea un repositorio](#crea-un-repositorio)
- [Clona tu repositorio](#clona-tu-repositorio)
- [Cambios en tu repositorio](#cambios-en-tu-repositorio)

<!-- END doctoc generó TOC por favor mantenga un comentario aquí para permitir la actualización automática -->

# Primeros pasos con Git

## Instalacion de Git.

Si quieres instalar Git en Linux a través de un instalador binario, en general puedes hacerlo mediante la herramienta básica de administración de paquetes que trae tu distribución.
> $ apt-get install git

## Configuracion de usuario y direccion de correo.

podemos acceder a los ajustes de configuración de Git a través del comando git config.

> $ git config --global user.name "John Doe"

> $ git config --global user.email johndoe@example.com

# Crea un repositorio.

Dirigite a (https://github.com/) y registrate es totalmente gratis.

1. Una vez registrado dirigite a la parte superior derecha de la pagina de inicio y pulse el icono + el cual desplega la opcion de new repository

![Nuevo repositorio](Imagenes/newrepo.png)

2. Escribe un nombre corto y fácil de recordar para tu repositorio. Por ejemplo: "hola-mundo".

![Nombre repositorio](Imagenes/namerepo.png)

3. También puedes agregar una descripción de tu repositorio. Por ejemplo, "Mi primer repositorio en GitHub".

![Descripcion repositorio](Imagenes/descrepo.png)


4. Elija una visibilidad del repositorio.

![Visibilidad repositorio](Imagenes/visirepo.png)

5. Selecciona Inicializar este repositiro con un archivo README.

![readme repositorio](Imagenes/readrepo.png)

6. Haz clic en Crear repositorio.

# Clona tu repositorio.

1. Una vez creado el repositorio haga clic en Clonar o descargar.

![clonar repositorio](Imagenes/butclone.png)

2. Copia la url que se te muestra.

![url repositorio](Imagenes/urlclone.png)

3. Dirigete a la carpeta donde quieras que este tu repositorio y ejecuta el comando git clone y dale enter.

![clonar local repositorio](Imagenes/gitclone.png)

Felicidades ahora cuentas con tu repositorio de manera local en tu equipo.

# Cambios en tu repositorio.