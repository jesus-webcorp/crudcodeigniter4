CRUD hecho con Codeigniter 4 proporcionado por Facultad Autodidacta, canal de youtube

Instrucciones o pasos a seguir:

1. Instalar Composer-Setup.exe de este enlace: https://getcomposer.org/download/
2. En xampp configurar el intl quitandole el ; que aparece al principio de la linea extension=intl.
Para esto hay que entrar a Config en la parte de apache y buscar dicha línea (Ctrl + B y poner extension). Cerrar xampp para reiniciar y que se configure correctamente.
3. Estando en htdocs desde la terminal poner
 composer create-project codeigniter4/appstarter crudcodeigniter4 , donde crudcodeigniter4 es el nombre del proyecto que se le dio
4. Posteriormente del archivo env que aparece en la carpeta del proyecto creado descomentar la línea que dice CI_ENVIRONMENT y cambiar su valor por development
5. Ir a app->Config->App.php y cambiar $baseURL por la ruta local donde vamos a probar dicho proyecto, que en este caso es http://localhost/crudcodeigniter4/public/
6. Posteriormente podemos poner en el navegador la misma ruta de la baseURL que es http://localhost/crudcodeigniter4/public/ para comprobar que ya este funcionando codeigniter4 y no mande ningún error.