# HANDYPIA IoT Platform 2.0 [![N|Solid](http://dev.handypia.co.kr/images/common/logo.gif)](http://dev.handypia.co.kr)
### Overview
HANDYPIA is an IoT Platform based on the [oneM2M](http://www.onem2m.org/)  standard. You need to understand the following standard documents to use our platform easily.


[![N|Solid](resources/images/HANDYPIA-architecture.png)]()
<p align="center">
  <b>[HANDYPIA IoT Platform Architecture]</b><br>
</p>

  - [oneM2M release1 specification, TS-0001-Functional Architecture(1.6.1)](http://www.onem2m.org/images/files/deliverables/TS-0001-Functional_Architecture-V1_6_1.pdf)
  - [oneM2M release1 specification, TS-0004-Service Layer Core Protocol Specification(1.6.0)](http://www.onem2m.org/images/files/deliverables/UpdateRelease1/TS-0004-Service_Layer_Core_Protocol-V1_6_0.zip)
  - [oneM2M release1 specification, TS-0009-HTTP Protocol Binding(1.5.0)](http://www.onem2m.org/images/files/deliverables/TS-0009-HTTP_Protocol_Binding-V1_5_1.pdf)

You can also refer to following related articles:
  - [oneM2M standard overview](slide/oneM2M(overview).pdf)
  - [oneM2M standard TS-0001 slides](slide/oneM2M(TS0001).pdf)
  - [oneM2M standard TS-0004 slides](slide/oneM2M(TS0004).pdf) 

### Platform Features

 Our platform technology makes it possible not only the integrated management in a single system via the web on any devices connected to the Internet in the Internet of Things circumstances, but also easy development of intelligent IoT convergence services through context-aware thing search / recommendation, connection and control. 
Specifically, our oneM2M standard based IoT platform provides the thing oriented information collection / analysis / control and has the following features. By supporting the interoperability of oneM2M standards and the flexible linkage with other devices, our platform can be utilized in the smart-object product development and take advantage of new service application development.

  - Compatible with oneM2M standards (oneM2M Release 1)
  - Interworking with HTTP, CoAP and MQTT message protocols
  - Multiple data repository (HBase, MongoDB, SQLite)
  - Support various proxy modules for interworking with other commercial devices
  - possible to mount various types of IoT devices (servers, gateways, etc.) SW

### APIs
Basically, our platform follows the mca interface of oneM2M standard. the mca interface defene message protocole between platform and application. The following API specification includes how to create and handle the major resource types such as AE(Application Entity), Container, ContentInstance, Subscription, Node, Group, etc.

* [HANDYPIA IoT Platform API](http://dev.handypia.co.kr/onem2m/doc/)

### Installation

You can find the installation and configuration guide from the following document.

* [HANDYPIA-Installation-configuration-guide](doc/HANDYPIA_Installation_Guide.pdf)

Briefly, Installtion, configuration  and running procedure are as followings.
##### Runtime Environment Setting

```sh
Install JVM(over 1.7)
Install Mongodb
Copy and Extact the HANDYPIA runtime modules
```

##### Configuration

```sh
> HANDYPIA CSE configuration
> Tomcat serve configuration
```

##### Running

```sh
> Mongodb deamon start
> Tomcat start
```

### Library : To be updated..
