# Uso de los conceptos aprendidos sobre cómo usar la consola para navegar y crear directorios y archivos

Se deben aprender unos comandos esenciales para saber navegar correctamente en la consola, crear directorios y archivos.

Primero, se deben ingresar nuestros datos en Git; lo que es el nombre y el email con los siguientes códigos:

git config --global user.name "nombre completo"
git config --global user.email "email"

<img width="892" height="133" alt="Registro" src="https://github.com/user-attachments/assets/7bc968fb-afd0-4b8c-9120-caeb3806b7b7" />

Luego ingresamos el código *git status* para ver dónde estamos ubicamos. Una vez sepamos ingresamos a la carpeta que necesitamos con el código *cd (nombre de la carpeta)*. 

Si aún no hemos creado un repositorio, con el código *git init* se puede crear, así podemos ingresar con el código anteriormente visto que es *cd (nombre de la carpeta).

Para crear un directorio usamos el código *mkdir (nombre que le vayas a colocar)*, una vez creada la carpeta, si queremos comvertirla 
en un repositorio ingresamos en comando *git init*; enseguida eso crea un carpeta oculta *.git*.

Para crear un archivo dentro del directorio ingresamos el comando *touch nombre que le vayas a colocar.extension*
