Yarn es un gestor de paquetes para tu codigo. Se le permite usar y compartir
codigo con otros desarrolladores de todo el mundo. Yarn hace todo manera rapida,
segura y fiable por lo que no vas a tener que preocuparte.

---¿Cual es la diferencia con NPM(Node Package Manager)?

	Yarn es mucho más rapido, lo que hayamos hecho con npm en minutos.
	Yarn lo hace en segundos.

---Ventaja

	Puedes trabajar de manera offline, ¿ esto que quiere decir ? Yarn crea una cache global en el equipo, cosa 
	que cuando quieras instalar alguna dependencia en tu proyecto, Yarn lo que va hacer es buscar si tienes ya ese 
	dependencia instalado en tu equipo y lo unico que va hacer es traerlo.

	Otra ventaja de trabajar con yarn es que puedes traer todos esas dependencias de desarrollo de npm. 
	Exacto yarn te da la facilidad de traer todas esas dependencias con lo que trabajabas anteriormente con 'npm', 
	de igual forma con 'bower'.

Para tener que usar 'Yarn' tienes que tener NodeJS instalado.
	
	https://nodejs.org/es/

Para instalar 'Yarn' solo debes de dirigirte a tu consola y poner lo siguiente:

	npm install yarn -g

-g quiere decir que lo vamos a instalar de forma global.
Para saber que lo instalamos correctamente escribimos en la consola lo siguiente:

	yarn --version

Para iniciar un nuevo proyecto con yarn, vamos a escribir lo siguiente:

	yarn init

De la misma que hacias con npm te va a preguntar el nombre del proyecto, su version y otras
cosas mas.

Para traer una dependencia de desarrollo, escribimos lo siguiente:

	yarn add bootstrap
	yarn add pug

Para instalar un devDependencies de desarrollo:
	
	yarn add --dev gulp gulp-sass gulp-concat gulp-uglify browser-sync autoprefixer

Por utlimo al instalar los paquetes de desarrollo para nuestro proyecto, nos genera
un archivo "yarn.lock"
Ese archivo es muy importante, porque lo que te sugiero que no lo añadas al gitignore
para que no te genere conflictos mas adelante.