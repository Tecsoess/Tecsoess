#  [Beneficiosi](http://tubeneficiosi.com/ "Beneficiosi.com")

[Tubeneficiosi.com](http://http://tubeneficiosi.com/ "Beneficiosi") es una plataforma tipo [marketplace](https://en.wikipedia.org/wiki/Marketplace "marketplace"), que cuenta con aplicación web y móvil desarrollada principalmente con [React.js](https://es.reactjs.org/ "React.js") Donde clientes y vendedores realizan transacciones de compra y venta de productos y eventos.

![](https://i.imgur.com/NCqhG5D.jpg)

## Videos Tutoriales 
- [Introducción a la aplicación Web ](https://www.youtube.com/watch?v=TzYGaBXAwQc "Introducción a la aplicación Web ")

------------

## Caracteristicas del Proyecto

------------
- Desarrollo de aplicaciones responsivas
- Desarrollo de aplicaciones administrativas (Tiendas y Administrador del markerplace). 
- RESTFUL APIs.
- Procesador de pago.
- Motor de búsqueda.
- Despliegue en servidor.

## Caracteristicas del Marketplace Beneficiosi
- Plataforma moderna para economía bajo demanda y mercados digitales
- ¡Todo reactivo, en tiempo real y ultrarrápido!
- Personalización del sitio web de comercio electrónico de compras para que los clientes realicen compras de alimentos, bienes o servicios a pedido en el navegador
- Sitio web de administración utilizado para administrar todas las funciones y configuraciones de la plataforma en una interfaz Web
- Catálogos de productos con múltiples imágenes de productos, variantes de productos, facetas y búsqueda de texto completo.
- Pasarela y procesamiento de pagos (Pasarela de pago admitida actualmente - Mercado libre)
- Integraciones de proveedores de envío de terceros





## Tecnologías 
------------
- [React.js](https://github.com/Tecsoess/Ebook-React-js/wiki) Actualmente una de las más empleadas para el desarrollo web y mantenida por Facebook.
- [React-Native](https://reactnative.dev/ "React-Native") Utilizasa para de desarrollar aplicaciones para Android. 
- [Node.js](https://github.com/Tecsoess/Node/wiki) De gran demanda actual, debido a que es considerada tecnología líder en desarrollo para servidores.
- [Tailwindcss](https://tailwindcss.com/ "Tailwindcss")  Framework de CSS que brinda los componentes basicos para crear diseños personalizados.
- [Material IU](https://mui.com/ "Material IU") Permite importar y usar diferentes componentes para crear una interfaz de usuario en nuestras aplicaciones React.
-  [NestJS](https://github.com/Tecsoess/NEST.JS "NestJS") Este framework para el desarrollo de aplicaciones en el lado del servidor, proporciona una arquitectura que permite un desarrollo más facil de mantener. 
- [TypeScript](https://github.com/Tecsoess/Typescript "TypeScript") Lenguaje superconjunto de Javascript que esencialmente añade tipos estáticos y objetos basados en clases. 
- [MySQL](https://www.mysql.com/ "MySQL") Sistema de gestion de base de datos relacionales que emplea un modelo cliente-servidor.



## Detalles del Desarrollo 
------------


###  Marketplace
- 100% responsiva, se adapta a los tamaños de pantallas más comunes.
- En comunicación con el backend se realizan envíos de correos electrónicos para casos como registro de usuario, olvido de contraseña entre otras opciones.
- Websocket para notificaciones y chat en tiempo real.

###  Panel de administración de las Tiendas 
- 100% responsiva, se adapta a los tamaños de pantallas más comunes.
- Control de parámetros y opciones relacionadas con las tiendas del Marketplace.
- En comunicación con el backend se realizan envíos de correos electrónicos para casos como registro de usuario, olvido de contraseña entre otras opciones.
- Websocket para notificaciones y chat en tiempo real.

###   Panel de administración general
- UI/UX empresarial.
- Control de parámetros y opciones del Marketplace.

###  Backend 
- Procesos programados para ejecuciones automáticas que requiera el cliente: envío de notificaciones, correos electrónicos entre otros.
- Websockets para comunicaciones en tiempo real.
- Procesador de pago y motor de búsqueda.







##  Perfiles: Cliente, Tienda y Administrador.

- ###  Cliente
                    
>Frontend principal para el marketplace [Beneficio Si](http://tubeneficiosi.com "Beneficio Si")

`<link>` : <https://github.com/Tecsoess/beneficiosi-clients-front>

### Instalación


```bash
git clone https://github.com/Tecsoess/beneficiosi-clients-front.git
cd beneficiosi-clients-front
npm install
cp .env-example .env
```

**Configurar variables de entorno en el archivo .env**
```bash
npm run start
```

- ### Tienda
                    
>Frontend de Tiendas para el marketplace [Beneficio Si](http://tubeneficiosi.com "Beneficio Si")

`<link>` : <https://github.com/Tecsoess/beneficiosi-stores-front>

### Instalación


```bash
git clone https://github.com/Tecsoess/beneficiosi-stores-front.git
cd beneficiosi-stores-front
npm install
cp .env-example .env
```

**Configurar variables de entorno en el archivo .env**
```bash
npm run start
```

- ### Administrador
                    
>Frontend de administración para el marketplace [Beneficio Si](http://tubeneficiosi.com "Beneficio Si")

`<link>` : <https://github.com/Tecsoess/beneficiosi-admins-front>

### Instalación


```bash
git clone https://github.com/Tecsoess/beneficiosi-admins-front.git
cd beneficiosi-admins-front
npm install
cp .env-example .env
```

**Configurar variables de entorno en el archivo .env**
```bash
npm run start
```

##  API de Beneficiosi

                    
>API de conexión  para el marketplace [Beneficio Si](http://tubeneficiosi.com "Beneficio Si")

`<link>` : <https://github.com/Tecsoess/beneficiosi-api>

### Instalación


```bash
git clone https://github.com/ICKillerGH/beneficiosi-api.git
cd beneficiosi-api
npm install
cp .env-example .env
```

**Configurar variables de entorno en el archivo .env**
```bash
npm run start:dev
```

#  App movil de Beneficiosi
Aplicacion móvil creada en [React-Native](https://reactnative.dev/ "React-Native") para el marketplace  [Beneficio Si](http://tubeneficiosi.com "Beneficio Si")

![](https://i.imgur.com/L3T8VX5.png)

### Requisitos 
- [NodeJs](https://nodejs.org/es/download/ "NodeJs")
- [Android Studio](https://developer.android.com/studio?gclid=Cj0KCQjw3v6SBhCsARIsACyrRAklAulHdNbnheg7R3yCB_NN0UqXP8V6W6mZn-bcmsYbdBbIUHNcsGcaAq09EALw_wcB&gclsrc=aw.ds "Android Studio")





### Instalación e Inicialización

> 1. Clonar el repositorio
>2. Cambiar a la rama develop
>3. Instalar las dependencias con node
>4. Iniciar el emulador android o conectar el dispositivo android a la pc por usb
>5. Iniciar la app
 >5.1  Iniciar el bundle
 > 5.2 Compilar la app
 
```bash
git clone https://github.com/JeyverVegas/BeneficioSiApp.git
git checkout develop
npm i
react-native
react-native run-android
```

## Seguridad

En una configuración de producción, todas las comunicaciones del lado del cliente al lado del servidor (backend, API) deben cifrarse mediante HTTPS/WSS/SSL (API REST, extremo de GraphQL, Socket.io WebSockets, etc.).

Si descubre algún problema relacionado con la seguridad, divulgue la información de manera responsable enviando un correo electrónico a atencionalcliente@beneficiosi.com



##   Indice de Ebooks
------------

* [React.js](https://github.com/Tecsoess/Ebook-React-js/wiki) 
	 - [React.js Essentials](https://github.com/Tecsoess/Ebook-React-js/wiki/CAPITULO-I:-REACT.JS-ESSENTIALS)
 	- [React by example](https://github.com/Tecsoess/Ebook-React-js/wiki/CAPITULO-II:-REACT.JS-BY-EXAMPLE)
	 - [React Cookbook](https://github.com/Tecsoess/Ebook-React-js/wiki/CAPITULO-IV:-FULL--STACK-REACT)
	 - [Full stack react](https://github.com/Tecsoess/Ebook-React-js/wiki/CAPITULO-IV:-FULL--STACK-REACT "Full stack react")
 	- [Introduction to react](https://github.com/Tecsoess/Ebook-React-js/wiki/CAPITULO-IX:-INTRODUCTION-TO-REACT "Introduction to react")
 	- [Learning react](https://github.com/Tecsoess/Ebook-React-js/wiki/CAPITULO-V:-LEARNING-REACT "Learning react")
	 - [Getting with react](https://github.com/Tecsoess/Ebook-React-js/wiki/CAPITULO-VI:-GETTING-WITH-REACT "Getting with react")
	 - [Design patterns and best practices](https://github.com/Tecsoess/Ebook-React-js/wiki/CAPITULO-VII:-DESIGN-PATTERNS-AND-BEST-PRACTICES "Design patterns and best practices")
 	- [Learning ext js](https://github.com/Tecsoess/Ebook-React-js/wiki/CAPITULO-VIII:-LEARNING-EXT-JS "Learning ext js")
 	- [React](https://github.com/Tecsoess/Ebook-React-js/wiki/CAPITULO-X:-REACT "React")
 	- [Full stack development with graph and react](https://github.com/Tecsoess/Ebook-React-js/wiki/CAPITULO-XI:-FULL-STACK-DEVELOPMENT-WITH-GRAPH-AND-REACT "Full stack development with graph and react")

* [React Native](https://github.com/Tecsoess/Ebook-React-Native/wiki)
	- [Getting started with react native](https://github.com/Tecsoess/Ebook-React-Native/wiki/CAPITULO-I:-GETTING-STARTED-WITH-REACT-NATIVE "Getting started with react native")
	-  [Practical react native](https://github.com/Tecsoess/Ebook-React-Native/wiki/CAPITULO-II:-PRACTICAL-REACT-NATIVE)
	- [React Native cookbook](https://github.com/Tecsoess/Ebook-React-Native/wiki/CAPITULO-III:-REACT-NATIVE-COOKBOOK "React Native cookbook")
	-  [30 Days of react](https://github.com/Tecsoess/Ebook-React-Native/wiki/CAPITULO-IV:-30-DAYS-OF-REACT "30 Days of react")
	-  [Progressive web apps with react](https://github.com/Tecsoess/Ebook-React-Native/wiki/CAPITULO-IX:-PROGRESSIVE-WEB-APPS-WITH-REACT "Progressive web apps with react")
	-  [Mastering react](https://github.com/Tecsoess/Ebook-React-Native/wiki/CAPITULO-V:-MASTERING-REACT "Mastering react")
	-  [Fullstack react](https://github.com/Tecsoess/Ebook-React-Native/wiki/CAPITULO-VI:-FULLSTACK-REACT "Fullstack react")
	-  [Getting started with react](https://github.com/Tecsoess/Ebook-React-Native/wiki/CAPITULO-VII:-GETTING-STARTED-WITH-REACT "Getting started with react") 
	- [Mastering react native](https://github.com/Tecsoess/Ebook-React-Native/wiki/CAPITULO-VIII:-MASTERING-REACT-NATIVE "Mastering react native") 
	- [React and react native](https://github.com/Tecsoess/Ebook-React-Native/wiki/CAPITULO-X:-REACT-AND-REACT-NATIVE "React and react native")
	-  [React native blueprints](https://github.com/Tecsoess/Ebook-React-Native/wiki/CAPITULO-XI:-REACT-NATIVE-BLUEPRINTS "React native blueprints")
	-  [React native tutorials point](https://github.com/Tecsoess/Ebook-React-Native/wiki/CAPITULO-XII:-REACT-NATIVE-TUTORIALS-POINT "React native tutorials point")
	-  [Android apps](https://github.com/Tecsoess/Ebook-React-Native/wiki/CAPITULO-XIII:-ANDROID-APPS "Android apps")

* [Node](https://github.com/Tecsoess/Node/wiki) 
	- [Node.Js Web Development](https://github.com/Tecsoess/Node/wiki/CAPITULO-I:-NODE.JS-WEB-DEVELOPMENT "Node.Js Web Development")
	-  [Node Applications](https://github.com/Tecsoess/Node/wiki/CAPITULO-III:--NODE-APPLICATIONS "Node Applications")
	- [Web Development With Mongodb And Node](https://github.com/Tecsoess/Node/wiki/CAPITULO-III:-WEB-DEVELOPMENT-WITH-MONGODB-AND-NODE "Web Development With Mongodb And Node")
	-  [Node](https://github.com/Tecsoess/Node/wiki/CAPITULO-IV:-NODE "Node")
	-  [A Progressive Node.Js Framework](https://github.com/Tecsoess/Node/wiki/CAPITULO-V:-A-PROGRESSIVE-NODE.JS-FRAMEWORK "A Progressive Node.Js Framework")
	-  [Node.Js In Practice](https://github.com/Tecsoess/Node/wiki/CAPITULO-VI:-NODE.JS-IN-PRACTICE "Node.Js In Practice")
	
	
* [NestJS](https://github.com/Tecsoess/NEST.JS/wiki) 
	- [Nest.Js: A Progressive Node.Js Framework](https://github.com/Tecsoess/NEST.JS/wiki/CAPITULO-I:-NEST.JS:-A-PROGRESSIVE-NODE.JS-FRAMEWORK "Nest.Js: A Progressive Node.Js Framework")
	-  [Nest.Js Build A Restful Crud Api](https://github.com/Tecsoess/NEST.JS/wiki/CAPITULO-II:-NEST.JS-BUILD-A-RESTFUL-CRUD-API "Nest.Js Build A Restful Crud Api")
	- [Application With Nestjs Framework](https://github.com/Tecsoess/NEST.JS/wiki/CAPITULO-III:-APPLICATION-WITH-NESTJS-FRAMEWORK "Application With Nestjs Framework")
	-  [Manual De Nest](https://github.com/Tecsoess/NEST.JS/wiki/CAPITULO-IV:--MANUAL-DE-NEST "Manual De Nest")
	
* [TypeScript ](https://github.com/Tecsoess/Typescript/wiki)
	- [Essential Typescript](https://github.com/Tecsoess/Typescript/wiki/CAPITULO-I:-ESSENTIAL-TYPESCRIPT "Essential Typescript")
	-  [The Typescript Workshop](https://github.com/Tecsoess/Typescript/wiki/CAPITULO-II:-THE-TYPESCRIPT-WORKSHOP "The Typescript Workshop")
	- [Efective Typescript](https://github.com/Tecsoess/Typescript/wiki/CAPITULO-III:-EFECTIVE-TYPESCRIPT "Efective Typescript")
	-  [Typescript Microservices](https://github.com/Tecsoess/Typescript/wiki/CAPITULO-IV:-TYPESCRIPT-MICROSERVICES "Typescript Microservices")
	-  [Advanced Typescript Programming Projects](https://github.com/Tecsoess/Typescript/wiki/CAPITULO-V:-ADVANCED-TYPESCRIPT-PROGRAMMING-PROJECTS "Advanced Typescript Programming Projects")
	-  [Angular Development Typescript](https://github.com/Tecsoess/Typescript/wiki/CAPITULO-VI:-ANGULAR-DEVELOPMENT-TYPESCRIPT "Angular Development Typescript")
	-  [Typescript Quikly](https://github.com/Tecsoess/Typescript/wiki/CAPITULO-VII:-TYPESCRIPT-QUIKLY "Typescript Quikly")
	

* [Metodología Ágil](https://github.com/Tecsoess/Metodologia-Agil/wiki)
	- [Scrum And Extreme Programming](https://github.com/Tecsoess/Metodologia-Agil/wiki/CAPITULO-I:-SCRUM-AND-EXTREME-PROGRAMMING "Scrum And Extreme Programming")
	-  [Project Managment](https://github.com/Tecsoess/Metodologia-Agil/wiki/CAPITULO-II:--PROJECT-MANAGMENT)
	- [Project Managment II](https://github.com/Tecsoess/Metodologia-Agil/wiki/CAPITULO-III:--PROJECT-MANAGMENT-II)
	-  [Agile Project Management With Scrum](https://github.com/Tecsoess/Metodologia-Agil/wiki/CAPITULO-IV:-AGILE-PROJECT-MANAGEMENT-WITH-SCRUM "Agile Project Management With Scrum")
	-  [Como Ser Un Srum Master Extraordinario](https://github.com/Tecsoess/Metodologia-Agil/wiki/CAPITULO-V:-COMO-SER-UN-SRUM-MASTER-EXTRAORDINARIO "Como Ser Un Srum Master Extraordinario")
	-  [Proyectos Agiles Con Scrum](https://github.com/Tecsoess/Metodologia-Agil/wiki/CAPITULO-VI:-PROYECTOS-AGILES-CON-SCRUM "Proyectos Agiles Con Scrum")
	-  [Head First Agile](https://github.com/Tecsoess/Metodologia-Agil/wiki/CAPITULO-VII:-HEAD-FIRST-AGILE "Head First Agile")
	-  [Great Big Agile](https://github.com/Tecsoess/Metodologia-Agil/wiki/CAPITULO-VIII:--GREAT-BIG-AGILE "Great Big Agile")
	

* [Jira software](https://github.com/Tecsoess/Jira/wiki)
	- [Jira Essentials](https://github.com/Tecsoess/Jira/wiki/CAPITULO-I:--JIRA-ESSENTIALS "Jira Essentials")
	-  [Jira Strategy Admin Workbook](https://github.com/Tecsoess/Jira/wiki/CAPITULO-II:-JIRA-STRATEGY-ADMIN-WORKBOOK "Jira Strategy Admin Workbook")
	- [Mastering Jira](https://github.com/Tecsoess/Jira/wiki/CAPITULO-III:-MASTERING-JIRA "Mastering Jira")
	-  [Practical Jira Pluggins](https://github.com/Tecsoess/Jira/wiki/CAPITULO-IV:-PRACTICAL-JIRA-PLUGGINS "Practical Jira Pluggins")
	-  [Jira Data Sanity Analyzer](https://github.com/Tecsoess/Jira/wiki/CAPITULO-V:-JIRA-DATA-SANITY-ANALYZER "Jira Data Sanity Analyzer")
	
* [Navicat](https://github.com/Tecsoess/Navicat/wiki)
	- [Navicat Version 11 User Guide](https://github.com/Tecsoess/Navicat/wiki/CAPITULO-I:-NAVICAT-VERSION-11-USER-GUIDE "Navicat Version 11 User Guide")
	-  [Navicat Version 12 User Guide](https://github.com/Tecsoess/Navicat/wiki/CAPITULO-II:-NAVICAT-VERSION-12-USER-GUIDE "Navicat Version 12 User Guide")
	-  [Navicat Version 15 User Guide](https://github.com/Tecsoess/Navicat/wiki/CAPITULO-III:-NAVICAT-VERSION-15-USER-GUIDE "Navicat Version 15 User Guide")
	



## [Componentes](https://github.com/Tecsoess/beneficiosi-clients-front)

------------

