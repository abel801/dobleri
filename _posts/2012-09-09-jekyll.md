---
title: Sistema de Control de Versiones 
layout: post
---
¿Qué es un sistema de control de versiones?, es un sistema que registra los cambios realizados de una carpeta o cunjunto de carpetas a lo largo del tiempo, de manera que es posible recuperar versiones especificas de los cambios realizados cuando lo requieras, cualquier tipo de carpetas o documentos pueden someterse a este sitema de control de versiones.

## Sistema de Control de Versiones Centralizado (CVSs)
El Sitema de Control de versiones centralizado fue desarrollado motivado por la necesidad de colaborar  con desarrolladores  de otros sitemas. Entonces se creó el Control de Versiones Centralizado(CVCSs). Estos sistemas tales como Subversion, Perforce y otros, se caracterizan por tener un único servidor que contiene todas las versiones de todas las carpetas, y un numero de clientes que verifican las carpetas del lugar central.

Sin embargo, este sistema tuvó una seria desventaja, el más importante fue: (1) Que cualquier problema que presentaba el servidor central ninguno podía colaborar ni guardar cambios.(2) Si el disco duro de la central de base de datos sufría algún desperfecto ningún backups podia ser guardado. Es decir, se perdía todo, exepto los snapshots que los usuarios guardaban en sus computadoras.

## Sistema de Control de Versiones Distribuido (DVCSs)

En éstos sistemas como: Git, Mercurial, Bazzar o Darcs; los clientes no solo pueden verificar los últimos snapshots de los directorios, sino que pueden verificar todo el repositorio, y si el servidor colapsa y estuvieron colaborando por este sitema, cualquiera de los repositorios clientes pueden ser copiados al servidor para restaurarlos.




