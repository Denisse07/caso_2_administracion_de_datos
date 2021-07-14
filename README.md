# caso_2_administracion_de_datos

Este repositorio contiene información de muestras de Github

Las subcarpetas contienen la siguiente información: 

/datos_sin_procesar: Se encuentran todos los datos sin procesar en formato json

/datos_sin_procesar/response.json: Usuarios que se tengan más de 2100 followers pero que
además tengan repositorios en R.

/datos_procesados: Se encuentran todos los datos procesados en formato csv

/datos_procesados/response.csv: Usuarios que se tengan más de 2100 followers pero que
además tengan repositorios en R.

Se busco en el sitio web de Github (https://docs.github.com/es/rest/reference/search) el link para la estración de API

Se ingreso a la aplicación del Postman con el link del API para realizar la extración de los datos por medio de un json (https://api.github.com/search/users?q=followers:%3E2100+language:r)

Despues de que se busco el archivo json se guardo en una carpeta de datos_sin_procesar

Se realizo la conversión del documento json en un archivo cvs por medio de la pagina (https://www.convertcsv.com/json-to-csv.htm)

Despues de que se paso el archivo a cvs, se guardo en la carpeta de datos_procesados

Se subio los archivos a GitHut atravez de la aplicación GitKraken.

Se edito el documento README

Compañeros:
Denisse Fajardo
Andres Flores
Alexander Gonzalez
Andres Masis



