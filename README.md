# MVC
# Modelo Vista Controlador (MVC)


MVC se encarga de separar la lógica de negocio de la interfaz de usuario y es el mas utilizado en aplicaciones web, framework, ya que facilita 
la funcionalidad, mantenibilidad, y escalabilidad del sistema, de forma cómoda y sencilla, a la vez que ayuda a no mezclar lenguajes de 
programación en el mismo código, el conocido “código espagueti”.

## ¿Cómo funciona el MVC?

1. El usuario realiza una petición.
2. El controlador captura la petición.
3. Hace la llamada al modelo correspondiente.
4. El modelo será el encargado de interactuar con la base de datos.
5. El controlador recibe la información y la envía a la vista.
6. La vista muestra la información al usuario.

## Partes del Mpodelo Vista Controlador

+ El modelo: Es la parte que se encarga de interactuar directamente con la base de datos, es decir, todo el código PHP que hará las inserciones, selecciones, actualizaciones o eliminaciones de datos.
+ La vista: En esta parte se encuentra toda la interfaz gráfica de la aplicación con la cual el usuario interactúa. Es decir, se encuentra el código CSS, HTML y JavaScript, además todos los recursos como las imágenes, fuentes tipográficas, iconos etc.
+ El controlador: Es el que interactúa como intermediario entre el modelo y la vista. Es decir, es el que recibe las peticiones enviadas desde la vista para enviárselas al modelo para luego enviar la respuesta del modelo hacia la vista.


## ¿Como implementar el Modelo Vista Controlador (MVC) en PHP?

+ Creando una estructura de carpetas parecida a estas:

```bash
tresCapasPhp
├── credenciales.php
└── index.php
	├─modelo
	├─controlador
	└─vista

Diagrama 1. Estructura monolítica.

```
</br>

![capasModeloVistaControlador](/img/capasModeloVistaControlador.JPG "modelo en capascon Php")
</br>
					Figura 1. Capas en aplicación web.
</br></br>
Se muestra que en la parte superior de la Figura 1, existe una petición de un recurso electrónico, integrada por un tercia de elementos 
constructivos de un direción web. 
Así también, se presenta la iteración entre _objetos_Interfaz_  (conn, result, row[]), interactuando solicitudes _request_ de 
datos entre las capas de: vista↔controlador↔modelo. Caracterizado en la Tabla 1.

| _objetos_Interfaz_ | Caracterización | 
|:-------------- |:----------:| 
| conn           | Es un objeto del tipo mysql. Vincula una conexión al servidor MySQL.|
| result         | Retorna un arreglo asociativo de registros de una base de datos.    | 
| row[]          | Es un deserealizador de objetos. | 

Tabla 1. Objetos tipo _request_.
</br>
# Instalación.

Se recomienda dar lectura al documento de instalación y configuración del software para desarrollo de aplicaciones web
XAMPP.   

https://github.com/miRepositorioGit/tresCapasPhp/blob/main/Referencias/instalacionConfiguracionXampp_V120.pdf

El Diagrama 2, mustra la ruta lógica de instalación local del proyecto:
https://github.com/miRepositorioGit/tresCapasPhp/archive/refs/heads/main.zip


```bash
C:\xampp
└──htdocs					← Carpeta global archivos.
	└─proyectos				← Carpeta de proyectos.
		└─tresCapasPhp			← Carpeta de aplicación.
			├─index.php
			├─credenciales.php
			└─submodulo_uno.sql
	
Diagrama 2. Árbol de dependencia.
```
</br>

# Glosario. 

## Actividad.  
Desarrollar el contenido de un glosario de palabras técnicas y un resumen de las mismas.
https://github.com/miRepositorioGit/tresCapasPhp/blob/main/Referencias/palabrasClave.txt

# Referencias.

[1]: https://es.wikipedia.org/wiki/SOLID 

     [1]: Ingeniería de software.
     Disponible en:<https://https://es.wikipedia.org/wiki/SOLID/> "Título"
     Consultado:04Jun24.
	 
[2]: https://reactiveprogramming.io/blog/es/estilos-arquitectonicos/capas 
	
	[2]: Blancarte, O. (2020). Introducción a la arquitectura de Software. 
	Ciudad de México: Oscar Javier Blancarte Iturral.
