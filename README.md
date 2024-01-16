![FoxServer](https://github.com/VFPLegacy/FoxServer/raw/main/images/foxserver-logo.png)
# FoxServer

## Simple and flexible library for building VFP based Web Applications

|Resource|Location|Description|
|---|---|---|
|Runtimes|[See Manifest](https://github.com/VFPLegacy/MagicMenu/raw/master/native/fox-server.manifest)|All runtimes needed by FoxServer
|MagicMenu|[Download](https://github.com/VFPLegacy/MagicMenu/raw/master/magicmenu.app)|The Project Manager

# Contents

- [Welcome to FoxServer](#welcome-to-foxserver)
- [Get Excited!](#get-excited)
- [Batteries Included](#batteries-included)
- [Practical](#practical)
  * [Wep Application](#web-application)
  * [Web Site](#web-site)
  * [API RESTful](#api-rest-ful)
- [Why FoxServer?](#why-foxserver)
  * [Designed For a Clear Goal](#designed-for-a-clear-goal)
  * [Simple](#simple)
  * [Uses Macros For Redability](#uses-macros-for-redability)
- [Implementation](#implementation)
  * [MagicMenu](#magicmenu)
  * [Multi-threaded](#multi-threaded)
  * [Fast Enough For Many Applications](#fast-enough-for-many-applications)
- [Features](#features)
  * [Syntax](#syntax)
  * [Powerful Implementation](#powerful-implementation)
  * [Simple](#simple)
  * [Dynamic](#dynamic)
  * [Builtins](#builtins)
  * [Examples](#examples)
  * [Support And Donations](#support-and-donations)
  * [License](#licence)

# Welcome to FoxServer
FoxServer is a web server implementation developed in **C#** that acts as a container to execute logical code written in **Visual FoxPro (VFP)** through a *Wrapper*. The main idea behind this project is to allow developers to write their service logic using VFP and expose this logic as *web service* through a modern web server.

# Get Excited

Each FoxServer project comes with a set of macros that simplify writing code and improve readability, this way the code becomes more idiomatic since the macros abstract all the syntax of object-oriented programming.

## Licencia

Este proyecto se distribuye bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

## Uso con MagicMenu

Puedes utilizar la herramienta MagicMenu para simplificar el proceso de creación de servicios web utilizando esta plantilla. MagicMenu automatiza la descarga y uso de estas mismas plantillas, permitiéndote concentrarte en el desarrollo de tu aplicación.
  
Para obtener más información sobre MagicMenu, visita el repositorio: [MagicMenu en GitHub](https://github.com/VFPLegacy/MagicMenu).

## Documentación
[ControllerHelper](ControllerHelper.md)

## Contribuciones

¡Siéntete libre de contribuir y mejorar esta plantilla! Si tienes sugerencias, mejoras o correcciones, ¡no dudes en hacer un pull request!

## Agradecimientos

Este proyecto utiliza las siguiente librerías de terceros, y quiero expresar mi agradecimiento a los autores y mantenedores de las mismas:

- [wwDotNetBridge](https://github.com/RickStrahl/wwDotnetBridge): Una librería esencial para la interoperabilidad entre Visual FoxPro y .NET.
- [WinSW](https://github.com/winsw/winsw): WinSW es una herramienta que permite ejecutar cualquier aplicación como un servicio de Windows.
- [MagicMenu](https://github.com/VFPLegacy/MagicMenu): Es una herramienta nativa para VFP que permite crear proyectos especiales como Aplicación de Consola, Servicio de Windows, Aplicaciones Web, entre otros.
- [JSONFox](https://github.com/Irwin1985/JSONFox): JSONFox es una herramienta para VFP que permite codificar y decodificar objetos JSON entre otras funciones.
- [FoxyPreviewer](https://www.foxypreviewer.com/): Imprimir reportes FRX a PDF.

---

**SIN GARANTÍA**

EL SOFTWARE SE PROPORCIONA "TAL CUAL", SIN GARANTÍA DE NINGÚN TIPO, EXPRESA O IMPLÍCITA, INCLUYENDO PERO NO LIMITADO A LAS GARANTÍAS DE COMERCIABILIDAD, IDONEIDAD PARA UN PROPÓSITO PARTICULAR Y NO INFRACCIÓN. EN NINGÚN CASO LOS AUTORES O TITULARES DE DERECHOS DE AUTOR SERÁN RESPONSABLES DE NINGÚN RECLAMO, DAÑO U OTRA RESPONSABILIDAD, YA SEA EN UNA ACCIÓN CONTRACTUAL, AGRAVIO O DE OTRA MANERA, QUE SURJA DE, FUERA DE O EN RELACIÓN CON EL SOFTWARE O EL USO U OTRAS NEGOCIOS EN EL SOFTWARE.
<!--stackedit_data:
eyJoaXN0b3J5IjpbOTE4NTE3OTM2LC0xMjc4MzM1MDMwLC0yMT
E4MTIzNTU2LDYyODYyMDQ2Nyw3MzQxNjM5MjMsLTE4NTA2MDI4
ODMsLTc5MDEwNjUyNF19
-->