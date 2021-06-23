# Comandos básicos de Git:

## Clonar repositorio
`git clone https://github.com/ivigilante/curso-python-itba`

Este comando crea el repositorio git en tu computadora.

## Actualizar repositorio local
``git pull``

Este comando actualiza el repositorio local (en nuestra computadora) con el remoto (el que esta online)

## Subir cambios a repositorio remoto
``git add NOMBRE_DEL_ARCHIVO``

Este comando agrega el archivo a la lista de cambios que haremos

``git commit -m "MENSAJE PARA NUESTRO CAMBIO"``

Este comando agrega un mensaje al cambio que haremos para que sea más entendible que hicimos

``git push``

Este comando sube los cambios al repositorio remoto

## Cambiar rama de trabajo
``git checkout RAMA``

Este comando nos permite cambiar a otra rama de trabajo, útil cuando queremos trabajar con varias personas a la vez.

## Crear una nueva rama de trabajo
``git checkout -b RAMA_NUEVA``

Este comando crea una rama nueva de trabajo

## Ver ramas de trabajo actuales en el repositorio local
``git branch``

Este comando muestra las ramas que tenemos en nuestro repositorio local, si queremos una que está en el remoto, deberemos hacer:

``git checkout RAMA_QUE_QUEREMOS``

## Ver estado de nuestro repositorio local
``git status``

Útil para ver diferencias y cambios con el repositorio remoto

# Empezar a trabajar!

Primero debemos instalar Git si estamos usando Windows, luego:

````
git clone https://github.com/cescalada-lab/Comandos_Basicos_Git
````

``cd Comandos_Basicos_Git``

``git checkout -b primerletradelnombreapellido`` 

Esto es para crear una rama. Si me llamo Christian Boanerges sería cboanerges

## Empezamos a trabajar y subimos los cambios:

``git status`` 

``git add LosArchivos``

``git commit -m "MensajeParaElCambio"``

``git push``

