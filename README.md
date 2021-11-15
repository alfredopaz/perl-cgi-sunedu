# Laboratorio de PERL-CGI sobre archivo de datos de la SUNEDU
En esta tarea usted pondrá en práctica todo lo aprendido en el curso, para resolver un problema de programación en un periodo de tiempo limitado.

## Archivos proporcionados
- `index.pl`, este archivo generar el código HTML del formulario. La intensión de que haya un CGI que genere el formulario, es para que el formulario muestre opciones disponibles a partir de un análisis previo del conjunto de datos.
- `css/mystyle.css`, aquí deberá incluir el estilo de su página, este estilo no tiene que ser complejo.
- `licenciamiento.csv`, archivo con codificación UTF-8, que contiene los datos sobre los que se hará la consulta.
|CODIGO\_ENTIDAD|NOMBRE|TIPO\_GESTION|ESTADO\_LICENCIAMIENTO|PERIODO\_LICENCIAMIENTO|DEPARTAMENTO\_LOCAL|PROVINCIA\_LOCAL|DISTRITO\_LOCAL|LATITUD\_UBICACION|LONGITUD\_UBICACION|
- `README.md`, estas instrucciones.

## Etapas
0) Estudie el código del archivo index.pl, ante cualquier duda, pregunte al profesor, esto debería tomarle unos 10 min.
1) Cree el archivo CGI que el formulario espera, de modo que este responda a la consulta dada. La respuesta a la consulta, sólo deberá mostrar el nombre de las universidades en un tabla. Deberá usar los estilos definidos en su archivo CSS.
2) Modifique el archivo `index.pl` para que el formulario permita elegir adicionalmente el departamento al que pertenece la universidad, use `select` para proporcionar la lista de departamentos disponibles; esta lista debe ser generada al estilo del programa original, haciendo un análisis previo del conjunto de datos.

