# Practica realizada por David Cordoba Ruiz 
# Orden de ejcución: 

1. AccesoAPI.py. Accede a la API de Spotify y crea un grafo que relaciona cantantes
con los que ha colaborado. Crea un fichero g_json.json con el grafo resultante para poder ejecutar 
el punto 2. Por defecto recoge la relación de artistas españoles.

2. AnalisisGrafo.py. Separa en componentes conexas el grafo obtenido en 1, incorpora información 
de las propiedades y adapta los grafos para su visualización. Crea dos ficheros .json para cada
componente. (Para que funcione para el grafo de cantantes de habla inglesa debe cambiarse la 
lectura del grafo de entrada por el fichero correspondiente.) Por defecto, lee el archivo g_json.json.
Si hay algún problema en su obtención en 1 se puede coger el que se encuentra en el directorio data.

3.1. VisComponente2.html. Visualiza la segunda componente del grafo de cantantes españoles (*) 

3.2. Vis_USA.html. Visualiza el grafo adaptado de cantantes estadounidenses (*)

(*) pueden usarse los ficheros .json creados en 2 pero por defecto coge los que hay en la carpeta 
data que deberían ser los mismos.

