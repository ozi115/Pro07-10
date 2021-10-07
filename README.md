# Pro07-10
Ejercicio 2 
1.	¿Qué es un servidor HTTP? 
es un conjunto de reglas para la comunicación entre el cliente y servidor el cual es responsable de procesar y responder solicitudes entrantes.

2.	¿Qué son los verbos HTTP? Mencionar los más conocidos
Son métodos de solicitud que implementan una semántica por individualidad entre los más usados y conocidos:
Get; Peticiones que recuperan datos.
Post: Envía una entidad a un recurso especifico y da un cambio de estado (modificación de los recursos existentes).
Put: Reemplaza representaciones actuales de los recursos del destino especificado.
Delete: Borra recursos específicos. 

3.	¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers? 
Request es un cliente comparable a una biblioteca de peticiones, mientras el request hace posible las solicitudes, el “response” da respuesta a tales peticiones, ambos consisten en una línea de salida dependiente a la solicitud del cliente o servidor. 
Headers son aquellos encabezados mostradas como etiquetas para su comprensión del usuario, también llevan relación o una similitud con los metadatos sobre el cuerpo del mensaje. 

4.	¿Qué es un queryString? (En el contexto de una url)
Son consultas dentro de una base de datos para simplificar el url dentro de las variables a buscar. Con ello es posible crear portales personalizables en función de las interacciones dentro de la página. 
5.	¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?
Es el estatus que devuelve la respuesta dentro del código de estado: 

100-199 Informativo - La solicitud fue recibida y se está procesando.
200-299 Éxito - La acción fue recibida con éxito, entendido y aceptado.
300-399 Redirección  - Otras peticiones hay que realizar para completar la petición.
400-499 Error en Cliente - La solicitud contiene mala sintaxis y no pueden llevarse a cabo.
500-599 Error de servidor - El servidor no pudo cumplir con una solicitud aparentemente válida.
6.	¿Cómo se envía data en un Get y cómo en un POST? 
Los datos enviados por un Get, son introducidos dentro de la url de la página mostrando los datos explícitamente separados por “?” y “&” simulando el cuerpo de la info. 
El método Post, solo muestra los apartados de los cuerpos dando la información con las especificaciones y no exactamente la información introducida. 

7.	¿Qué verbo http utiliza el navegador cuando accedemos a una página?
Verbo Post, muestra la versión de protocolo el código de estado y los encabezados para saber internamente donde se encuentra el usuario y las consultas realizadas. 

8.	Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.
Son formatos de datos para llevar a cabo una comunicación entre sistemas o servidores/clientes. Ej:
JSon:
“pieza”: {
        “tipo”: “A”
        “nombre”: “Tornillo”,
        “descripcion”: “Cilindro mecánico con una cabeza utilizado en la fijación temporal de unas piezas con otras”,
        “caracteristica”: {
            “tipo”: “metal”
            “tamanyo”: 10
        },
        “vacio”: “”
     }
XML:

<Pieza tipo=”A”>
<nombre>Tornillo</nombre>
    <descripcion>Cilindro mecanico con una cabeza  </descripcion>
    <caracateristica>
        <tipo>metal</tipo>
        <tamanyo>10</tamanyo>
    </caracateristica>
    <vacio></vacio>
</pieza>

9.	Explicar brevemente el estándar SOAP
Es un protocolo para el intercambio de información en entornos descentralizados y distribuidos, los mensajes SOAP son usados para crear patrones de petición/respuesta basados en XML.

10.	Explicar brevemente el estándar REST Full
Sistema de doble vía que consulta y da respuesta por métodos de comunicación a través de protocolo http (get, post, delete, put) y status code, también emplean parámetros de autenticación y validación.

11.	¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?
Dentro de un request, transmite la info. Del navegador del cliente en la pagina que esta siendo solicitada, del servidor y entre otras. Y se compone del método, la url solicitada y el protocolo http.
Un content-type dice al cliente el tipo de contenido a retornar por el tipo de medio, ya sea en base a imágenes o texto plano, entre otros. 
 

https://trailblazer.me/id/omonrreal

Ejercicio 5 

Lead: Cliente potencial sobre interés a la empresa.

Account: Datos de una cuenta con un seguimiento hacía una organización o cliente, ya sea el nombre, tel, dirección, entre otros registros automáticos.

Contact: Va ligada a las cuentas, guardan datos más personales sobre los clientes u organizaciones para su comunicación.

Opportunity: oportunidad de un cliente potencial, realizan seguimiento de acuerdos y pendientes de ventas. *

Product: Va ligado a las oportunidades, se definen en una lista de precios y es cualquier articulo en venta de la organización (o servicio).

PriceBook: Lista de precios de productos que la organización vende.

Quote: Cotizaciones de precios, un registro de productos y servicios que se crean a partir de oportunidades.

Asset: Es un apartado que posee un cliente dependiendo el tipo de organización y sus productos..

Case: Un caso es una forma de organización para resolver problemas, se identifican por que se guardan datos de prioridad, contacto y el estatus en que se encuentra.

Article: Capturan información de productos y/o servicios de la empresa deseada.

![Procontact schema](https://user-images.githubusercontent.com/61712103/136431099-274b22e7-a0ac-49bf-99a4-7b96e004c442.jpg)


Ejercicio 7 

Soluciones de Salesforce
A.	¿Qué es Salesforce?
Plataforma con multifunciones en creación de pedidos para cualquier tipo de venta, diseño y demás. 
B.	¿Qué es Sales Cloud?
Es una relación con la gestión de datos y el cliente. 
C.	¿Qué es Service Cloud?
Plataforma personalizable para el servicio a atención al cliente.
D.	¿Qué es Health Cloud?
Plataforma de gestión entre médico y paciente.
E.	¿Qué es Marketing Cloud?
Proveedor de software y servicios de automatización de marketing digital. 

Funcionalidades de Salesforce
A.	¿Qué es un RecordType?
Creación de tipos de registros que permiten dar procesos comerciales, listas de selección y diseños de página personalizada según el registro. 
B.	¿Qué es un ReportType?
Tipos de reporte en Salesforce. Informes a partir de relaciones entre los objetos y los usuarios.
C.	¿Qué es un Page Layout?
Personalización de diseño, organización y edición de paginas de registros en Salesforce. Control de las páginas. 
D.	¿Qué es un Compact Layout?
Es un apartado de un objeto donde muestra toda la información relevante en campos clave. 
E.	¿Qué es un Perfil?
Es la forma de tener acceso a datos y objetos, un apartado personal para llevar a cabo acciones dentro de Salesforce. 
F.	¿Qué es un Rol?
Una asignación dentro de un conjunto de acciones, puede ser por parte de una jerarquía dentro de una organización.
G.	¿Qué es un Validation Rule?
Es el filtro que tiene de verificación para datos ingresados en algún campo que cumplen los estándares de mediación. 
H.	¿Qué diferencia hay entre una relación Master Detail y Lookup?
Una depende de derivaciones de la misma, como si fuera una clase controladora. Lookup, busca y relaciona datos con otro objeto completo. 
I.	¿Qué es un Sandbox?
Copia de seguridad de la organización, aislada para mantener un entorno seguro, con funciones de pruebas y capacitación.
J.	¿Qué es un ChangeSet?
Cambios de objetos que se envían de una organización a otra con una respectiva personalización. 
K.	¿Para qué sirve el import Wizard de Salesforce?
Importar datos, objetos entre otras cosas con mayor facilidad.
L.	¿Para qué sirve la funcionalidad Web to Lead?
Diseñar formularios con el objetivo de integrar datos de los usuarios al CRM, de modo que automatiza el proceso de capacitación a leads. 
M.	¿Para qué sirve la funcionalidad Web to Case?
Para crear una página web personal que genere casos nuevos de clientes para permitir enviar casos directamente a una instancia de la terminal de nuestro servicio.  Agiliza las respuestas a los clientes y mejora el soporte hacía ellos. 
N.	¿Para qué sirve la funcionalidad Omnichannel?
Distribuir canales de información y comunicación con los clientes, parte a través del servicio de nube (Service Cloud) el cual entrega objetos para enrutarse con sus agentes directos de los clientes (hasta haber disponibilidad). 
O.	¿Para qué sirve la funcionalidad Chatter?
Es una plataforma de chat donde los equipos de Salesforce pueden tener un seguimiento y comunicación de trabajos y tareas. 
Conceptos generales
A.	¿Qué significa SaaS? 
Desarrollo y mantenimiento de software a través de la nube. Se proporcionan actualizaciones y funciones completas por vía electrónica. 
B.	¿Salesforce es Saas?
Totalmente, es un software compartido en la nube, en la cual, sus clientes y organizaciones tienen comunicación a través de la web y desarrollan software para los mismos en la misma nube. 
C.	¿Qué significa que una solución sea Cloud?
Que tiene solución con objetos predeterminados que se encuentran a disposición en la nube. 
D.	¿Qué significa que una solución sea On-Premise?
Que la solución viene por “defecto” dentro del mantenimiento, seguridad y disponibilidad del software. 
E.	¿Qué es un pipeline de ventas?
Un modelo de etapas de una negociación, donde se identifican los clientes potenciales y los pasos a seguir de una estructura fija para aprovechar al máximo la forma de ventas y negociación de la empresa.
F.	¿Qué es un funnel de ventas?
Acciones que un vendedor comunica de forma visual a clientes potenciales. 
G.	¿Qué significa Customer Experience?
La experiencia que tiene el cliente con algún servicio, empresa en general o producto, la evaluación de satisfacción que tiene sobre ella. 
H.	¿Qué significa omnicanalidad?
Comunicación multiple entre un agente y un cliente a través de la web. 
I.	¿Qué significa que un negocio sea B2B?
Que el negocio como tal, promueve su servicio a otra empresa y no a un cliente en específico. 
J.	¿Qué significa que un negocio sea B2C?
Que su venta es al público. O sea, a un consumidor particularmente hablando. 
K.	¿Qué es un KPI?
Es un medido de rendimiento de un proceso, a medida que uno se acerca al objetivo el medidor muestra porcentualmente el avance. 
L.	¿Qué es una API y en qué se diferencia de una Rest API?
Api: Interfaz que conecta aplicaciones para la lectura y escritura de información. 
API Rest: Es la arquitectura que conecta por un protocolo HTTP que permite acceder a información e identificadores únicos. 
M.	¿Qué es un Proceso Batch?
Es la ejecución de un programa que se hace por partes para garantizar el desempeño y gestión de procesamiento dentro de la plataforma o sistema computacional
N.	¿Qué es Kanban?
Es una metodología ágil para la gestión general de un proceso o fabricación de un producto en el tiempo y forma deseado.
O.	¿Qué es un ERP? 
Conjunto de aplicaciones de software integradas que planifican la información de una empresa, la cual se centra en manejar de forma automatizada y fácilmente los recursos de ella. Modularidad. 

P.	¿Salesforce es un ERP?
Ciertamente, Salesforce utiliza y da la facilidad de crear tus propias facilidades de software para la creación e implementación en el desarrollo de software, un ejemplo serían lo que ellos llaman “sObject”.
