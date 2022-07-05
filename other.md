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
Se peude acceder a muchos servicios que se necesita al isntante
Manera sensible de acceder a servidores, almacenamiento, database y un set de aplicaicones y servicios

AWS tiene y maniene una red conectada de hardware para todo tipo de aplcaciones, mientras nosotros provisionamos y utilziamos lo que se necesita a traves de la web app.

nos olvidamos de provlemas como el pago del lugar de data center, provision de energia enfriamiento mantenimiento , mantenimiento, escalamiento y manejo contra desastres

### Modelos de despliegues de la Nube

Private Cloud
* Usado por solo una org
* Control completo
* Securidad para apps sensitivas
* cumple necesidades especificas

Public Ckiyd
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
Flexibility change the resource when you needed
Cost*effectiveness pay as you go
Scalability accomodate larger loads adding nodes or increase HW
Elasticiy ability to scale out (horitzontal )and sacle in (vertical )when needed
High availabiliy and fault-tolerance build acrross data center
Agility rapidly develop test and launch apps


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


* **Abailability Zones**
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