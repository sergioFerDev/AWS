<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Best-README-Template</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Intro What is Cloud Computing?

Es on-demand delivery de compute power, database storage, apps and others
pay as you go procing, provisionando exactamente el tipo correcto y el tamano adecuado de recursos que necesitas.
Se peude acceder a muchos servicios que se necesita al instante
Manera sensible de acceder a servidores, almacenamiento, database y un set de aplicaicones y servicios

AWS tiene y maniene una red conectada de hardware para todo tipo de aplcaciones, mientras nosotros provisionamos y utilziamos lo que se necesita a traves de la web app.

nos olvidamos de provlemas como el pago del lugar de data center, provision de energia enfriamiento mantenimiento , mantenimiento, escalamiento y manejo contra desastres

### Modelos de despliegues de la Nube

Private Cloud
* Usado por solo una org
* Control completo
* Securidad para apps sensitivas
* cumple necesidades especificas

Public Cloud
* cloud resources owned y operado por a 3rd party cloud service provider y entregado a travez de interner
* Six adventages

Hybrid Cloud
* Mantiene unos servers en las instalaciones y amplie algunas capacidades
* Control sobre activos sensibles en la infraestuctura privada
* Flexibilidad y rentabidildad en la nuve publica 


### Five characteristics of cloud computing

* On demand self service
* Broad network access  accessible by diverse client plataforms
* Multi-tenacy and resource pooling (Tenencia múltiple y agrupación de recursos)
* Rapid elasticity and scalability
* Measured service

### 6 adventages of Cloud computing
* Trade capital expense CAPEX for operational expense OPEX Pay on demand , reduce TCO total cost of ownership and operational expense
* Benefit from massive economies scale(prices reduced as aWS is more efficient)
* Stop guessing capacity (adivinar) Scale based on actual measured usage
* Increase speed and agility
* Stop spending money running and mainaining data centers
Go global in minutes (leverage-aprovecha-the AWS global infra)

### Problems Solved by the cloud
* Flexibility change the resource when you needed
* Cost*effectiveness pay as you go
* Scalability accomodate larger loads adding nodes or increase HW
* Elasticiy ability to scale out (horitzontal )and sacle in (vertical )when needed
* High availabiliy and fault-tolerance build acrross data center
* Agility rapidly develop test and launch apps


### Types of Cloud Computing
* IaaS 
    Provee componetes basicos para cludTI en la nube
    networking computeres data storage
    Hghest level of flex
* PaaS
    Removes la necesidad de adminitras la infraestructura subaciente enfocado en el despliegue de apps
* SaaS
    Cproducto ejecutado y manejado por el proveedor


On-premises propias instalaciones

![Types of Cloud Computing](/AWS/assets/IaaS-PaaS.png "Types of Cloud Computing")


### Ejemplos de tipos de Cloud computing

* IaaS
    EC2, Azure,Digital Ocean 
* PaaS
    Elastic Beanstalk, Heroku Google App Engie
* SaaS
    Rekoginition, Gmail, Zoom

### Pricing of the Cloud

AWS has 3 pricing fundamentals fllowing the pay-as-you go pricing model

* Compute : pay for compute time
* Storage: Pay for data stored in the Cloud
* Data transfer OUT of the Cloud: data in is free
 
### AWs cloud history
2002 intenally launched

47% of the market in 2019
9 years leader
+1.000.000 active users

### AWS Cloud Use Cases
AWS permite crear sophisticated scalable applications applicable a dicersas industrias

### AWS Global Infraestructure 

* **AWS Regions**:
AWS tiene el concepto de Región, que es una ubicación física en todo el mundo donde agrupamos los centros de datos. Llamamos a cada grupo de centros de datos lógicos una zona de disponibilidad. Cada región de AWS consta de zonas de disponibilidad múltiples, aisladas y separadas físicamente dentro de un área geográfica.
Cluster of data centers, los servicios estan focalizados en regiones ,Names can be us-east-1, eu-west-3 

Para elegir una region se debe toamr en cuenta Compliance with data governance, proximity, available services with a Region, Pricing pricing varies region to region


* **Availability Zones**
Una zona de disponibilidad (AZ) es uno o más centros de datos discretos con energía, redes y conectividad redundantes en una región de AWS. Los AZ brindan a los clientes la capacidad de operar aplicaciones y bases de datos de producción que tienen mayor disponibilidad, tolerancia a fallas y escalabilidad de lo que sería posible desde un solo centro de datos. Todas las zonas de disponibilidad en una región de AWS están interconectadas con redes de baja latencia y gran ancho de banda, a través de fibra metropolitana dedicada totalmente redundante que proporciona redes de alto rendimiento y baja latencia entre las zonas de disponibilidad. Todo el tráfico entre AZ está encriptado. El rendimiento de la red es suficiente para lograr la replicación síncrona entre zonas de disponibilidad. Las zonas de disponibilidad facilitan la creación de particiones para aplicaciones de alta disponibilidad
Usually 3 min 2 max 6 , each AZ is one or more discrete data center with redundant power networking and connectivity
Isolated for disaaster
* **Local Zones**
Las zonas locales de AWS colocan la computación, el almacenamiento, la base de datos y otros servicios selectos de AWS más cerca de los usuarios finales. Con AWS Local Zones, puede ejecutar fácilmente aplicaciones muy exigentes que requieren latencias de milisegundos de un solo dígito para sus usuarios finales, como creación de contenido multimedia y de entretenimiento, juegos en tiempo real, simulaciones de depósitos, automatización de diseño electrónico y aprendizaje automático.

* **AWS Wavelength**
AWS Wavelength permite a los desarrolladores crear aplicaciones que brindan latencias de milisegundos de un solo dígito a dispositivos móviles y usuarios finales. Los desarrolladores de AWS pueden implementar sus aplicaciones en Wavelength Zones, implementaciones de infraestructura de AWS que integran los servicios de computación y almacenamiento de AWS dentro de los centros de datos de los proveedores de telecomunicaciones en el borde de las redes 5G y acceder sin problemas a la variedad de servicios de AWS en la región. Esto permite a los desarrolladores ofrecer aplicaciones que requieren latencias de milisegundos de un solo dígito, como juegos y transmisión de video en vivo, inferencia de aprendizaje automático en el borde y realidad aumentada y virtual (AR/VR). AWS Wavelength lleva los servicios de AWS al borde de la red 5G, minimizando la latencia para conectarse a una aplicación desde un dispositivo móvil

* **AWS Outposts**
bring native AWS services, infrastructure, and operating models to virtually any data center, co-location space, or on-premises facility. You can use the same AWS APIs, tools, and infrastructure across on-premises and the AWS cloud to deliver a truly consistent hybrid experience

-------Page 35----

### How to choose AWS Region?

* Compliance with data governance and legal requirements
* Proximity to customers reduce latency
* Available services with a regio new services accordin region
* Pricing priceing varies region


### shared responsibility Model diagram

Customer Responsability for the security in the Cloud
AWS for the security of the cloud

### AWS acceptable use poicy

* No illegal harmful 
* No security violations
* No network abuse
* No e-mail or other message abuse


## IAM 

* IAM idendtiyy and access management, Global service
* Root  account created by default shuldn't used or shared
* User are peopol within your organization and can be grouped
* Groups only contain users no other groups

Users pueden pertenecer o no a un grupo o a multiples

### IAM permissions

* Users or groups can be assigned JSON documents called policies
* Policies define permissions of the users
* AWS apply least privilege principle , dont give more permissions than a user need


![IAM POlicies Structure](/AWS/assets/IAM_policies.png "IAM POlicies Structure")


* Strong passwords higher security for your account 
* in aws you can setup a password policy(length, include char, re-use, rquire change )

### Multi Factor Authentication MFA

protecto you account Root
MFA password +security device
DEvices:
* MFA virtual device (google auth , authy)
* Universal 2nd Factor (U2F) Securityy key (YubiKey)
* Hardware key gemalto
* hardware for AWS GovCloud SurePassID

### How can access users?

Access keys are generated through AWS Console, user can manage dont share , access key ID username Secret access key password

- CLI AWS command line interface -access keys

a tool enables you to interact with AWS services using commands in you command-line shell, direct access to the public APIs
Open source
Alternantive to using Console

- SDK Software Developer Kit -access keys
lenguage-specific APIs set of libreries, access AWS service programm, embedded with your app(JS, py,go)
CLI is built on aws sdk for py

- Console pass+MFA

### IAM Roles for Services

Some AWS service will need to perform actions on your behalf(en mi nombre), to do so, we'll assign permision to AWS services with IAM Roles Common roles(EC2 instance rroles;lambda, Cloudformation)

### Tools
 * credentials Report account-level Report that lists all accounts and users status

 * access advisor user-level Access advisor shows the service permissions and when those services were last accessed

 ### best Practices

 * Don't use the root account except for AWS account setup
 * One physical user = One AWS user
 * Assign users to groups and permission to croups
 * Create a strong pass policy
 * Use and enforce MFA
 * Create and Roles for giving permissions
 * Use Access keys for prog access (CLI/SDK)
 * Audit permissions of your account wiht IAM cred Report
 * Neverr share IAM users and access keys

### shared responsavility

* AWS infra, config and vulnerability, compliance
* YOU User, groups,MFA, rotate allf your keys, use IAM tools to apply permisions, analyse access patterns 

--P57---
## AMAZON EC2 

one of the mos popular, Elastic compute cloud IaaS
* Renting virtual machines EC@
* Storing data EBS
* Distribuiting load ELB
* Scaling the service auto-scaling group ASG
* EC@ is fundamental to undestand how cloud works
 
 ### Options
 * Operating System OS, CPU,RAM, 
 * Storage SPACe (-networ attached EBS EFS -hardware EC2 isntance store)
* Network card(speed of the card)
* Firewall rules(security group)
* Bootstrap script

* Its possible to boot our intance using a EC2 userd data script (lunch commands when machine start) only run one time when starts
* Used to automate tasks as update isntall softwaare download file
* Runs with the root user

### EC2 Instances Types Overview
Instances can be optimased for diferente use cases
AWS has this convention:

M5.2xlarge

m:instance class
5:generation
2xlarge: size within the insance class

* T (T2,t3,t4g,m5,m5a,m4) gernal pupose EC2 instance balance in compute memory and networking
* C (c6g,c5,c5a)computed Optimzed used for compute-intensive tasks that require hig preformace processos
* R (r6g,r5,r5n,x1,x1e)Memory Optimized fast performance for workloads that process large data sets in memory (hig perfomance for realtional no relational databeses optimez for by)
* I I3 D2 D3 Storage Optimized great for storage intensive task (high freq online transaction, cache for in-memory databases data warehousing)

### Security groups

Sec groups are the fundamental of network security in AWS, control how traffic is allowin into our EC2 instance, only contain allow rules, and can reference by IP or by security group.
Acting as a firewall on EC@ instances , regulate Access ports, authorised Ip ranges, control of inbound net and outbound

* Security groups can be attached to mulple insances, locked down to a region/
* Lives putside the EC2 intances, iof is blocked EC2 dont see it
* Good to maintaina separate SSH group to access
* If your app is not accessible (time out)its a sec group issue
* Connection refused its a app error 
* All inbound blocked by default
* All outbound authorised by default

Ports to remember SSH(secure shell) 22 FTS 21 SFTP (upload using secure ftp)22 HTTP 80 HTTPS 443 RDP remote desktop3389 


EC2 instance connect can be used to connect to EC2 , no need key file, port 22 is open amazon linux 2 only allow

### EC2 Purchasing Options

On Demand Instances

Pagas por lo que usas, Highest cost but no upfront payment
no long-term commitment sin compromiso a largo plazo
recomendado para short term y cargas interrumpidas

Reserved Instances

* Reserved specifi instance attibutes for one time
* 72% discount compared on demand
* time reservation period 1 year+ 3year+++
* Payment options no upfront + partial upfront ++ all upfront +++
* Scope regional or Zonal, recommed seatdy state apps thik database
* Convertible reserved isntance

Saving Plans

* based on long term usage, commit to a certain type of usage $10 hour for 1 or 3 years
* billed on demand
* locked to a specific isntance family & region
* Flexible acrooss size OS tenancy

Spot instances

* Can have 90% discount compared on demand
* Intances that you can lose at any point of time
* Most cost efficient insances
* Useful for workloads that are reslite to failues(batch joves ,data analysis, image processing, workloads with flexible time)
* no for critical jobs or databases

EC2 dedicated Hosts

* physical server fully dedicated for your use
* allows you address compliance req and use your existing server bound sof licenses
* Purchase on-demand reseved
* Most expensive
* Useful for soft that have complicated licensing model or companies with strong regulatory 

EC2 dedicated instances

* instances run on hardware dedicated
* may share hardware wit other instances
* no control over instances placement(puede moverse de hardware cuando se detiene o continua)

EC2 Capacity Reservations

* Reserved On-demand isnances capacity in a specific AZ for any duration
* Sin contrato, sin descuentos, 
* Se tiene una capacidad reservada, no importa si no se usa se cobrara, se recomienda combinar con otros planes


Which purchasing?
* On demand:entrar y salir cuando quieras del resort pagando fuull
* Reserved: si planeamos estar por buen tiempo, buen descuento
* Saving plan: paga a cierto tipo de cantidad por hora y quedate en cualqueir tipo de room (se tiene planeado gastar una cantidad por mes)
* Spot instances: el hotel permite usar las camas vacias , puedes ser botado en cualqueir momento
* Dedicated hosts we book a entire building
* Capacity reservations book a room for a period with full price even you don stay


## Shared resp

* AWS infra, isolation , replacing faulty hardware, compliance validation
* ME security groups ,OS patches and updates,sof installed,IAM roles and user acces, data security

---92---

## EC2 Instance Storage Section

### EBS
 Elastik block Store volume is a network drive you can attach to your instances
 Allows persist data, one per instance at time, bound to specifiz AZ (like a network usb stick)

Its a network drive (no phisical drive), uses network to communicate he isnance ,+ latency, 
 HAve provisioned capacity GBs 

 * Delete on termination attribute
 when EC2 instance terminates EBS volume is deleted (controle by AWS console)
 Preserve root volume when instance terminated

 ### EBS snapshot

 Backup of EBS at a point in time
 not necessary buit recommended
 can copy acroos the regions

 EBS snapshot archive - move to an archive 75% more cheaper
 Takes 24-72 hours for restoring
 Recicly BIN for EBS-recover after accidental deletion (need to specify the amount of time)

 ### AMI

 Amazon Machine Image (customaitazion of EC2 isntance) add your software config operating system monitoring faster boot

 built for a specific region(can be copied across the regions)
 You can lunc EC@ isntaces from 

 Public AMI, OWN AMI, AWS marketplace AMI

 To create you need to start a EC@ instance and customize it, stop instance , build an AMI, lunch instances from oher AMIs

can not used for add your own IP addresses
### EC2 image builer

Used to autmate the creation of virtual machiner or container images
Automate the creation, maitain validate and test EC2 AMIs
can be scheduled
free services

### EC2 Instance Store

EBS are network drives withh limited performance, if you need hig performance need EC2 instance Store

Better i/o performace
Instance Store lose their storage if is stopped
Good for buffer/cache/scratch data/temporary content
risk to loss data
Backups and replication are your resp

IOPS input output peer second

### EFS Elastic File System

managed network file system can be mounten on 100 EC2
works with linux EC2 instances in multi AZ
High available scalable expensive ,pay peer use, no capacity planning
CAn be shared accross AZ 

EFS IA infrecuent access is a cost optimzed for files not accessed every day.92 lower cost compared con standar
EFS will automatically move you file to EFS IA based on the last time they were accessed
Enable with a lifecycle policy(ex move files not used after 60 days)

### Shared respon for EC2 storage

AWS:infraestrucute, replciation for data for EBS volumes & EFs, replace fault hardware, ensure their employes can not acces your data.

YOU:Setting backup/snapshot, data encryption, responsability on any data on drives, undestan the risk of using EC2 instance store


### FSX overview

launch 3rd pary high performance file system on AWS
Fully managed service
(for lustre, windows file server, NEtAPP ONTAd)if you dont want to use S3 or EFS 
* Windows fully managed , highly reliable and scalable windows native shared FS, build on Windows FS
* Lustre: fully mange, hig performace scalable file storage for HIGH PERFORMANCE COMPUTING, name from linux and cluster, used for ML, analytics video processing,sacles to 100s GB millon of IPs

voc Tied atado


--page 112--