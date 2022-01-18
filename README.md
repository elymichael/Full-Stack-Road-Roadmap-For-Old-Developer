# Full-Stack-Road-Roadmap-For-Old-Net-Developer

### Algunos programadores me contactan para preguntarme como hice la transición de la antigua forma de programar al estilo de hoy en día.

Este repositorio tiene como finalidad a ayudar a programadores de la vieja escuela hacer la transición de la antigua metodología de trabajo a la nueva metodología, y dentro de este apartado, hemos querido mostrar las diferencias de las aplicaciones de manejo de versiones, nuevos patrones de diseño, cambios en los frameworks de backend y frontend.

**Atención:** La idea de este repositorio es aportar nuestras ideas de como romper esa barrera que no permite a algunos programadores hacer la transición a esta nueva metodología de trabajo. De igual manera, le puede servir a un nuevo programador que desea iniciar en este ámbito.

## Contenido

- [Inicio](##Inicio)
- [Prerequisitos](##Prerequisitos)
- [Editores de Programación](##EditoresdeProgramación)
- [Metodología](##Metodología)
- [Desarrollo](##Desarrollo)
- [Base de Datos](##BasedeDatos)
- [Manejo de Versiones](##ManejodeVersiones)
- [Construir tus Proyectos](##ConstruirtusProyectos)

## Inicio

Este tutorial está orientado principalmente a programadores FullStack Developer que trabajen con tecnología .Net y tengan conocimiento de Javascript. Vas a sentirte frustrado por momento, pero la idea es que puedas ir familiarizandote con algunas tecnologías que en un momento pueden ser un dolor de cabeza para ustedes. Hay un mercado lleno de oportunidades ahí afuera, y es una gran ventaja conocer las nuevas metodologías de trabajo que se usan hoy en día.

## Prerequisitos

- [x] **Inglés.** Gran parte de la información y documentaciones que podemos encontrar hoy se encuentra en inglés y las mayorías de las empresas tratan sus comunicaciones internas en inglés.
- [x] **Instalación Visual Studio y Visual Studio Code.** Como indiqué anteriormente, vamos a mostrar una ruta de programación para **Full Stack Net Developer**.
- [x] **Creación Cuenta Github.** Nuestro código debe guardarse en algún punto y para eso vamos a crear una cuenta GIT para crear los distintos repositorios que vamos a necesitar.
- [x] **Descarga Github Desktop.** Vamos a descargar github desktop para administrar los cambios en nuestro repositorios desde ahí.
- [x] **Instalación NodeJs**. Instalar NodeJS para trabajar con nuestras librerías de javascript.

## Editores de Programación

Si vas a trabajar a con tecnología .net vamos a entrar en contexto con las herramientas que se usan. Desde hace unos años, Microsoft ha liberado tanto sus frameworks como sus editores de programación. Microsoft ofrece dos frameworks principales, la versión conocida .Net que es el framework para desarrollo de aplicaciones que se van a ejecutar en sistemas operativos Windows y .Net core, que es la evolución de .Net, un framework open source que se puede ejecutar en cualquier sistema operativo. 

- **Visual Studio Code** es un editor gratis con una gran comunidad que le da soporte a esta herramienta y a las múltiples extensiones que se pueden integrar. <a href='https://code.visualstudio.com/download'>Descargalo aquí</a>
- **Visual Studio** tiene una versión community que permite realizar casi todas las operaciones básicas para desarrollar cualquier tipo de software.<a href='https://visualstudio.microsoft.com/es/vs/'>Descargalo aquí</a>
- **SQL Server.** Puede trabajar con su base de datos SQL directamente desde su editor de visual studio o si desea puede descargar la versión express que soporta base de datos hasta 4 GB de tamaño. - <a href='https://www.microsoft.com/es-es/sql-server/sql-server-downloads'>Descargalo aquí</a>. La herramienta de administración la puede descargar en el siguiente enlace: <a href='https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15'>Management Studio</a>
- **Github.** Crea tu cuenta de Git en la siguiente ruta: <a href='https://github.com/'>Github.com</a>. Aquí vas a guardar los distintos repositorios de tus proyectos. La administración de tus proyectos lo puedes hacer a través de <a href='https://desktop.github.com/'>Github Desktop</a> o usando las herramientas que vienen integradas tanto en Visual Studio como Visual Studio Code.
- **NodeJs.** Como vamos a ver como configurar algunos frameworks de javascript, necesitaremos de <a href='https://nodejs.org/es/download/'>NodeJs</a>. Los frameworks de javascript que vamos a mostrar son **VueJs** y **Angular CLI**.

## Metodología

Dependiendo de la tarea a realizar, debemos elegir una metodología de trabajo específica, las que trataremos desde el punto más general al mínimo detalle necesario para publicar una herramienta. Vamos a iniciar con la forma de trabajo de las compañías modernas:

Para trabajar en compañías de forma remota, es importante poner sobre la mesa que cosas debemos cuidar para realizar una buena labor. Lo primero, debemos respetar los horarios de trabajo y conocer las metodologías de trabajo <a href='https://www.atlassian.com/es/agile/manifesto'>agile</a> (<a href='https://www.atlassian.com/es/agile/scrum'>Agile Scrum</a> y <a href='https://www.atlassian.com/es/agile/kanban'>Kanban</a> principalmente) que utilizan muchas de estas empresas. Aunque esté trabajando remoto, debe respetar los horarios de trabajo, ser comunicativo, ser independiente y trabajar de forma organizada. Al trabajar remoto, se espera que el programador se encuentre capacitado para realizar sus tareas de la manera más independiente posible.

Para la programación de .Net existen diversos patrones que debe conocer antes de iniciar el desarrollo de su herramienta:

- **Monolithi:** toda la lógica de la aplicación se encuentra en un solo proyecto.
- **All In One:** toda la lógica se encuentra en un solo proyecto, dividido en diversos folder lógicos.
- **NLayer:** Toda la ógica se encuentra dividida por proyectos dividio en una capa de acceso a datos, una capa de negocios y una interfaz de usuario.
- **Clean Architecture:** como su nombre lo indica, es la arquitectura limpia, basada en el uso de interface e injección de dependencia.

Para extender más el contenido de los principales patrones de diseño en .Net, visita el siguiente <a href='https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/common-web-application-architectures'>enlace</a> para obtener más detalle.

En el caso de frontend, los patrones de diseños más utilizados son: <b>MVC</b> y <b>MVVM</b>, Vue tiene una interesante explicación en el siguiente <a href='https://012.vuejs.org/guide/'>enlace</a>.

Si estás trabajando con otras tecnologías distinto a .net, vamos a mostrarte como los nuevos desarrolladores tienen sub-divididos los fullstack de acuerdo a las tecnologías que trabajan:

- [x] MERN: MongoDB, Express, React, Node.Js.
- [x] LAMP: Linux, Apache, MySQL, PHP.
- [x] MEAN: MongoDB, Express, AngularJs, Node.Js.
- [x] LAAMP: Linux, Apache, Angular, MySQL, PHP.

## Desarrollo

Para iniciar a programar en .net core, es importante que visualice todos los cambios que ha sufrido <a href='https://docs.microsoft.com/en-us/dotnet/csharp/whats-new/csharp-version-history'>C#</a> en los últimos años para poder adaptarse a esta nueva forma de escribir el código. En .Net debe prestar atención a:

- <a href='https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/'>Linq</a>
- <a href='https://docs.microsoft.com/en-us/ef/core/get-started/overview/first-app?tabs=netcore-cli'>Entity Framework</a>
- <a href='https://dapper-tutorial.net/dapper'>Dapper</a>
- <a href='https://automapper.org/'>AutoMapper</a>
- <a href='https://swagger.io/'>Swagger</a>
- <a href='https://restfulapi.net/'>REST</a>

Para el desarrollo de frontend, ver los siguientes enlaces de algunos frameworks de javascripts que nos gustan: <a href='https://012.vuejs.org/guide/installation.html'>VueJS</a> y <a href='https://angular.io/'>Angular</a> con dos de las principales frameworks de desarrollo que se usan hoy en día. Otros frameworks de javascript importantes que puede considerar: ReactJs (el más popular) y Svelte. Importante indicar, que para la programación web basada en Javascript, debes prestar atención al NPM CLI para incluir paquetes de terceros en tus proyectos, así como ejecutar tu proyecto, compilar y construirlo. Buscar más información sobre:

- [x] NPM, Yarn.
- [x] Webpack, Gulp, Babel.

Para las herramientas que nosotros manejamos en desarrollo web, los fullstacks deben tener claro como debe estar diseñada la plataforma de desarrollo:
|Databases | Backend | Frontend|
| -------- | --------|-------- |
|Sql Server o MySQL|.net core api|angular, vue.js|
|CosmoDB, MongoDB|.net core api|angular, vue.js|

### Si deseas abundar más sobre programación, te dejo algunos enlaces donde he estudiado algunos cursos que me han interesado:
- [x] <a href='https://codewithmosh.com/p/asp-net-mvc'>Asp Net Core MVC</a>.
- [x] <a href='https://www.youtube.com/user/programmingwithmosh?app=desktop'>Diferentes cursos de Mosh Hamedami</a>.
- [x] <a href='https://www.vuemastery.com/courses'>Vue.Js</a>.
- [ ] En **pluralsight**, **Udemi** existen excelentes materiales si quieres seguir abundando sobre estos temas.

## Base de Datos

Al momento de elegir una base de datos, debemos saber el tipo de información que vamos a almacenar, cada que tiempo vamos a acceder a la misma y cual es la finalidad de la información que deseamos almacenar.

- Base de datos relacionar **(SQL):** La base de datos relacionar es idear para esos modelos de datos donde necesitas almacenar la información en un modelo entidad - relación. Algunos sistema que son un buen ejemplo de este modelo: ERP, CRM y POS. Más detalles <a href='https://www.oracle.com/database/what-is-a-relational-database/'>aquí</a>. Las base de datos que utilizamos principalmente son SQL Server, MySQL, MariaDB(basado en MySQL). Existen otras muy conocidas como PostgresSQL, Oracle, MaxDB por mencionar solo 3 más.
- Base de datos no relacionar **(NoSQL):** Este modelo es muy utilizado en algunos sistemas donde no se necesita un relación de datos padre-hijos. Por ejemplos: los post de un blog, una aplicación de CMS, un organizador de documentos y cualquier otro modelo que se base en almacenar documentos de datos. más información <a href='https://www.mongodb.com/es/nosql-explained'>aquí<a/>. La más popular es MongoDB, Microsoft tiene también CosmoDB que es muy buena.
- Blob de archivos **Blob Storage:** Modelo donde guardaremos archivos de datos, imagenes de alta calidad, etc. <a href='https://azure.microsoft.com/es-es/services/storage/blobs/'>Expanda</a>
- Tablas de datos **Table Storage:** Es un modelo NoSQL, pero que no va a tener muchos acceso a datos, un ejemplo, una aplicación para organizar libros digitales. <a href='https://docs.microsoft.com/en-us/azure/storage/tables/table-storage-overview'>Detalles</a>

## Manejo de versiones

Si tiene experiencia con otros sistemas de versiones, posiblemente el uso de GIT sea un poco intuitivo. Programadores que usaron algunos manejadores de versiones como: <b>SVN</b>, <b>Visual SourceSafe</b> y <b>Team Foundation Service</b> van a encontrar en git un herramienta parecido con un poco de exteroides para mejorar, explotar y proteger nuestro código. Para iniciar, le recomendamos usar la parte visual de GIT, ya sea GitHub Desktop o las integraciones que vienen con Visual Studio / Visual Studio Code. Además, Azure Devops está basado en GIT, por lo que si aprende uno, puede utilizar cualquiera de las versiones existente. Existe otras versiones menos conocidas, como Bonobo GIT Server, que te permite configurar tu propio servidor de GIT on premise.
  
- [x] <a href='https://codewithmosh.com/p/the-ultimate-git-course'>Curso de GIT</a>
  
## Construir Proyectos
  
Si quiere montar tu proyecto de forma sencilla en cualquier servidor en Azure o AWS, construyendo tu proyecto en docker te permite poder replicarlo fácilmente en cualquier ambiente con la configuración que necesitas sin tener que lidiar con las incómodas instalaciones. Luego que tienes tu aplicaciones "dockerizada", solo necesitas tus contenedores donde la vas a ejecutar. En Visual Studio es muy sencillo montar una aplicación en docker utilizando generando tu dockerfile y dockercompose con unos cuantos clic. Un ejemplo <a href='https://docs.microsoft.com/en-us/dotnet/architecture/containerized-lifecycle/design-develop-containerized-apps/visual-studio-tools-for-docker'>aquí</a>

No tenemos que ser un experto en docker para ser un buen fullstack developer, pero es importante que conozcamos los conceptos básicos y como funciona para saber para que plataforma estamos trabajando. Importante: al elegir tu tipo de imagen docker a usar, selecciona linux, ya que el docker se va creer con los mínimos requerimientos necesarios para correr tu aplicativo, distinto a uno basado en windows, donde prácticamente tienes el sistema completo.
  
- [x] <a href='https://codewithmosh.com/p/the-ultimate-docker-course'>Curso de Docker<a/>
  
## Agradecimientos
  
Te damos las gracias por pasar por este artículo con el que buscamos aportar nuestro granito de arena para que buenos programadores puedan mejorar la forma de trabajar y romper con las barreras que no le permiten moverse de las posiciones donde se encuentran. Si quieren aportar a este artículo, son bienvenidos a realizar un PR con información que le pueda sumar a otros programadores.
