<h1> Configurar un repositorio nuevo desde terminal </h1>
<ol>
    <li>git init</li> <!--Inicializar un repositorio vacio en nuestra carpeta-->
    <li>git add .</li> <!--Agregar archivos nuevos y con cambios a la version actual-->
    <li>git commit -m "Dejar un mensaje"</li> <!--Crea la version nueva con los cambios actuales-->
    <!--CADA VEZ QUE SE HACE UN COMMIT CREA UNA VERSION NUEVA PERO IGUAL MANTIENE LA VERSION ANTERIOR-->
    <li>Ir a github y crear un repositorio vacio</li> <!--INICIALIZA EL REPOSITORIO EN NUESTRA CUENTA DE GITHUB-->
    <li>git add remote origin rul-del-github-vacio</li> <!--ESTO SE HACE EN FUNCION DE LO QUE SE
    CREO EN EL PASO PREVIO
    Enlaza el repositorio de nuestra cuenta con el repositorio de nuestra carpeta-->
    <li>git push -u origin master</li> <!--Actualiza la version actual de nuestra carpeta en 
    el repositorio de nuestra cuenta
    Con esta version se sube al repositorio-->

</ol>

<h1>Modificando el archivo anterior para que sirva para lo que estoy haciendo en este momento</h1>
