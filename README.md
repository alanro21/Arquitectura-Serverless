# Arquitectura-Serverless

<div style="text-aling: center;>
  <img src="imagen/Fondo.png" width="200">
</div>

## Introduccion
En este espacio les contaré qué es la Arquitectura Serverless, sus características principales y cómo se aplicó en nuestro trabajo de investigación. Exploraremos sus ventajas, casos de uso y las conclusiones obtenidas a partir de nuestra experiencia.

## Indice de contenidos
En este apartado, se visualizara la estructura del tema a abordar. Este indice servira como guia para navegar en por los distintos apartado de la explicacion.

1. [¿Que es la Arquitectura Serverless?](#¿Que-es-la-Arquitectura-Serverless?)
2. [Características principales](#Características-principales) 
3. [Ventajas y Desventajas](#Ventajas-y-Desventajas) 
4. [¿Que son las FaaS y BaaS dentro de la Arquitectura Serverless](#¿Que-son-las-Faas-y-Baas-dentro-de-la-Arquitectura-Serverless)
5. [Usos mas comunes](#Usos-mas-comunes)
6. [Proveedores de Arquitectura Serverless](#Proveedores-de-Arquitectura-Serverless)
7. [Aplicacion en el proyecto de investigacion](#Aplicacion-en-el-proyecto-de-investigacion)
8. [Glosario](#Glosario)

## ¿Que es la Arquitectura Serverless?
La Aquitectura Serverless es una computacion sin servidore (Serverless) un modelo de ejecucion en el que el proveedor en la nube es el responsable de ejecutar
un frgamento de codigo. El codigo se ejecuta dentro de contenedores sin estado puede ser activados por una variedad de eventos que incluyen solicitudes HTTP, base de datos,
servicios de colas, alertas de monitoreo, carga de archivos y eventos programados. El codigo que se envia al proveedor en la nube para la ejecucion es generalmete en forma de funcion.

## Caracteristicas Principales
text2

## Ventajas y Desventajas
Ventajas: 
* No hay necesidad de administrar infrastructura: Esto quiere decir que no hay necesidad de administrar servidores, manetener los sistemas opertativos o instalar y actualizar software, 
  ya que todo es responsabilidad del proveedor de la nube.
* Escalabilidad: Se escala de forma automatica y mantiene un equilibrio en cuanto a recursos, esto indica que se adapta a las necesidades del cliente.
* Ahorro de costos: Solo se paga lo que se usa, en este caso se paga por el tiempo que dura la ejecucion, en lugar de pagar por una instancia.
* Alta disponibilidad y tolerancia a falla: Sin necesidad de hacer algun proceso para replicar datos en diferentes zonas disponibles, ofrece una alta disponibilidad y tolerancia a 
  fallas de forma predeterminada. 

Desventajas:
* Dependencia de Proveedores: Puede implicar riesgo asociada con confiar en un unico proveedor, ya que puede haber cambios en servicios, precios o fallas del proveedor donde puede 
  impactar negativamente en la operacion.
* Menos control sobre la infraestructura: Los desarrolladores tienen limitado control sobre los servidores. Esto puede restringir la personalizacion y optimizacion de configuraciones 
  especificas.
* Procupaciones de Seguridad: Procupacion por la privacidad de los datos que se alojan en la nube de terceros. Esto aumenta el riesgo de seguridad cerbernetica.
 
## ¿Que son las FaaS y BaaS dentro de la Arquitectura Serverless?
Son dos tipos de servicios que utilizan la computacion sin servidor:
* FaaS(Functions as a Service - Funcion como Servicio): El modelo se basa en la tecnologias y arquitecuras informaticas sin servidores que permiten a los desarrolladores de software 
  implementar facilmente aplicaciones en la nube sin tener que administar servidores.

* BaaS(Backend as a Service - Backend como Servicio): Es un modelo de servicio en la nube en la que los desrrolladores subcontratan todos los aspectos detras de escena de una aplicacion
  web o movil para que solo tenga que escribir y mantener la interfaz. Los proveedores de BaaS proporcionan software prescrito para actividades como: Autenticacion de usuario, 
  Administracion de base de datos, Actualizacion remota y Notifiacionses push, Almacenamiento y Alojamiento en la nube.

   
## Usos mas comunes
La tecnologia serverless es ideal para microservicios, backend moviles, procesamiento de eventos y flujo de datos. Su uso mas comunes son:

1. Aplicaciones web o API backends: Esta orientado a la ejecucion de eventos, como por ejemplo en una aplicacion de tareas donde los usuarios pueden crear, actualizar ver y eliminar 
   elementos, por medio de funcion que puede convertirse en un endpoint HTTP.

2. Procesamiento de datos: Para trabajar con datos estructurados de texto, audio, imagen y video.

## Proveedores de Arquitectura Serverless

Los siguientes proveedores que utilizan Arquitectura Serverless son: 

* AWS Lambda: Permite ejecutar código automáticamente en respuesta a eventos generados por otros servicios de AWS (como S3, DynamoDB o API Gateway) o eventos personalizados, se cobra 
  únicamente por el tiempo de ejecución y la cantidad de invocaciones, eliminando costos fijos asociados a servidores tradicionales, admite varios lenguajes de programación, como
  Python, Node.js, Java, Go y Ruby, entre otros, funciona de manera eficiente con servicios como S3, DynamoDB, API Gateway, SNS y Kinesis, permitiendo construir arquitecturas altamente 
  distribuidas y escalables.
  
* Google Cloud: Permite respuesta a eventos de Google Cloud (como cambios en Cloud Storage, mensajes en Pub/Sub o solicitudes HTTP) o eventos personalizados, ejecucion basada en 
  eventos, admite JavaScript (Node.js), Python, Go, Java, .NET y Ruby, funciona con Firebase, BigQuery, Cloud Storage, Firestore y Pub/Sub, entre otros, 
  facilitando arquitecturas distribuidas.
     
* Azure Functions: Proporcionado por Microsoft Azure. Permite ejecutar código en respuesta a eventos sin necesidad de administrar servidores, facilitando la creación de aplicaciones 
  escalables y optimizadas en costos, se activa en respuesta a eventos generados por otros servicios de Azure (como Blob Storage, Event Grid, Cosmos DB) o mediante solicitudes HTTP, 
  soporta varios lenguajes de programación, incluyendo C#, JavaScript, Python, Java, TypeScript y PowerShell, funciona de manera nativa con otros servicios como Azure Storage, Service 
  Bus, Event Hubs y Logic Apps, facilitando arquitecturas serverless completas y permite desarrollar y probar funciones en entornos locales antes de desplegarlas en la nube.

* IBM Openwhisk

## Aplicación en el proyecto de investigacion.
Text6

##Glosario

* Solicitudes HTTP:
* Endpoint HTTP: 
* S3: 
* DynamoDB: 
* API Gateway: 
* SNS: 
* Kinesis:
* Firebase: 
* BigQuery: 
* Cloud Storage: 
* Firestore:
* Pub/Sub:

