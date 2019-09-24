# Google Cloud
[Console Google Cloud](https://console.cloud.google.com)

### eSource Capital
[eSource Capital](https://www.esourcecapital.com/)
Partner más grande de Google en Latinoamerica
mabcastillo@esourcecapital.com


## Ventajas de Google Cloud Plataform (GCP)

> El objetivo debe ser maximizar los recursos a utilizar por el tiempo que lo necesitemos solamente.
> El 20% de empresas a nivel mundial están haciendo algo por migrar a la nube.
> Los costos en la nube son bajísimos.

Crear datacenters es una idea retrasada. Es mil veces más seguro mantener nuestra data en nube por amenazas físicas.

* Future-Poof Infraestructure
* Powerful Data & Analytics
* Serverless (for devs)
* Pagar por lo que necesitamos. Crear una máquina pequeña exacta para lo que necesito aprovechando cada uno de sus recursos, con la capacidad de crecer con un par de clics.
* El internet es escencial. Una buena conexión a internet es necesaria para el funcionamiento. (100Mbps -> $1000)

## IaaS (Infraestructure as a service)  - Google Compute Engine

**¿Qué es Iaas?**
Los componentes básicos físicos que puede proveer la nube.
Creación de VM con diferentes características según la necesidad.

La creación de máquinas más grandes es utilizada en casos de Big Data.

_(Hadoop: Plataforma utilizada para big data)_ :mag:

### Dataproc
Creación de clusters para manejo de Big Data.

## PaaS (Platform as a service) - Google App Engine

App Engine es una plataforma sin servidores completamente administrada para desarrollar y alojar aplicaciones web a gran escala.

Crea instancias de VM necesarias y las pone a trabajar creando un ecosistema para el desarrollo (bases de datos, conexiones, etc.). La funcionalidad de cada una de las instancias no tiene nada que ver una entra otra.

Para resolver el problema de la persistencia entre instancias, se utiliza la BD o un File System. La idea básica es que la persistencia se haga remota, para que todas las instancias puedan acceder a ella.

> Google App Engine: Primer PaaS que apareció en la industria. Permitió el origen a Kubernets y Docker. App Engine es el PaaS completo.

_**¿Qué son los microservicios?** Son atómicos. Servicios pequeños e independientes acoplados de manera flexible._


Dos versiones: 

* Standard: 
    1. Desarrollar.
    2. Montar sobre la plataforma.
    3. Ponerla a correr.

* Flexible. 

### Ventajas de Google AE
- Alta disponibilidad: Siempre debe haber por lo menos una instancia trabajando.
- Elasticidad Horizontal: Si se cae una máquina, decirle al balanceador que tome en cuenta una máquina nueva para mantener el rendimiento. (Instancias de máquinas virtuales).

La primera versión de Kubernetes permite la elasticidad horizontal.
