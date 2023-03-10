# Curso de Flask (Platzi)
[Clase 1 Introducción](#Clase-1-Introducción)

[Clase 2 ¿Cómo funcionan las aplicaciones web?](#Clase-2-Cómo-funcionan-las-aplicaciones-web)

[Clase 3 ¿Qué es Flask?](#Clase-3-Qué-es-Flask)

[Clase 4 Instalación de Python, pip y virtualenv](#Clase-4-Instalación-de-Python-pip-y-virtualenv)

[Clase 5 Hello World Flasj](#Clase-5-Hello-World-Flask)

## Clase 1 Introducción
Conoce todo el potencial de Flask como framework web de Python, integraciones con Bootstrap, GCloud, What The Forms y más.

Flask es sencillo de aprender, tiene una documentación clara y práctica, es rápido a la hora de renderizar puede ser hasta tres veces más rapido que Django. También es fácil de realizar una API REST, la estructura de un proyecto es flexible y es ideal para aprender desarrollo web con un framework de Python.

## Clase 2 ¿Cómo funcionan las aplicaciones web?
Cuando utilizas una aplicación web puedes interactuar con ella desde una computadora hasta un dispositivo móvil, pero esto no quiere decir que consume el procesamiento de tu dispositivo. Todo lo contrario, se hace en una red de servidores.

Estos servidores unen su poder de procesamiento con el fin transmitir solicitudes a todo el mundo, a su vez utilizar servidores especializados para almacenar los datos con los cuales se está trabajando, así como los datos de los demás usuarios. Como todo esto sucede sin demora alguna, parecerá que la aplicación se está ejecutando de forma nativa en tu dispositivo.

El servidor procesa la información obtenida por el navegador, luego se realizan los procedimientos necesarios de acuerdo a la lógica de negocio de la aplicación para regresar la información solicitada al cliente.

**Ejemplo:**  
Cuando utilizamos Google Drive el cual es una aplicación web y abrimos un documento con Google Docs, el navegador se comunica con los servidores para ver y editar el documento.  
A medida que vayas editando el documento, tu navegador trabajará de la mano con los servidores para asegurarse que todos los cambios se estén guardando.

**Ventajas:**  
- Muchas de las aplicaciones web que existen son gratuitas.  
- Puedes acceder a tu información en cualquier momento y lugar.  
- No dependes de un dispositivo en específico ya que la aplicación se encuentra almacenada en la web.

## Clase 3 ¿Qué es Flask? 
Flask es un framework minimalista escrito en Python que permite crear aplicaciones web rápidamente y con un mínimo de líneas de código, busca que su infraestructura inicial sea lo mas simple posible y pueda personalizarse fácilmente, no depende de un sistema de autenticación especifico o base de datos especifica, puedes extender sus funcionalidades llamadas Flask Extensions http://flask.pocoo.org/extensions/

**Algunas diferencias con Django son:**  
- Utiliza un template llamado Jinja2 que está inspirado en los templates de Django.  
-	Django trae todo incluido mientras que flask es lo más simple posible.  
- Django tiene in modelo MVC mientras que Flask no tiene in modelo especifico.  
-	Django tiene ORM mientras que Flask es más personalizable al trabajar con bases de datos.

## Clase 4 Instalación de Python, pip y virtualenv
**Esta es la guía para configurar nuestro ambiente con Python 3.**  
Por lo general Mac ya incluye una instalación de Python, la puedes verificar ejecutando los siguiente comandos en una terminal
```
python --version
```
```
python3 --version
```

Debemos asegurarnos de tener **python 3**. Para instalar Python puedes seguir el siguiente enlace y después regresar a esta lectura

https://platzi.com/clases/1378-python/14289-guia-de-instalacion-y-conceptos-basicos/

**Instalación en Windows**  
Una vez que instalaste python 3 desde python.org vamos a verificar que también incluimos pip en esta instalación. Después debes correr el siguiente comando para instalar virtualenv:
```
pip install virtualenv
```

El sistema debe haber instalado virtualenv y ahora podemos comenzar con el curso.

**Instalación en Mac**  
Si ya instalaste python 3 ahora corre el siguiente comando para instalar pip:

```
sudo easy_install pip
```

Para install virtualenv de manera global corre:

```
pip install virtualenv
```

El sistema debe haber instalado virtualenv y ahora podemos comenzar con el curso.

## Clase-5-Hello-World-Flask  
**Creación del ambiente virtual**  
Una vez que ya instalamos virtualenv con pip, nos dirigimos a la carpeta en la que deseamos crear el proyecto, una vez ahi, mediante el cmd o powershell estando en la ruta deseada, creamos un nuevo directorio con el siguiente comando
```
mkdir nombre_del_directorio
```
Nos movemos al nuevo directorio, creamos en ambiente virtual
```
virtualenv venv
```
y lo activamos
```
venv/Scripts/activate
```
En este ambiente virtual es donde nosotros vamos a instalar Flask, esto se hace mediante pip
```
pip install flask
```
Si todo salio correctamente deberiamos tener instalado flask con sus dependencias, esto lo podemos ver realizando un freeze
```
pip freeze
```
Lo que nos tendria que devolver los siguiente datos  
- click==8.1.3
- colorama==0.4.6
- Flask==2.2.2
- itsdangerous==2.1.2
- Jinja2==3.1.2
- MarkupSafe==2.1.2
- Werkzeug==2.2.2





























