# Cost-effective Cognitive City (CeCC)

## Descripción

Proyecto con el que participo en el Hackaton interno de IBM. El objetivo fundamental es desarrollar una aplicación de forma rápida y sencilla con los servicios de [Bluemix](https://bluemix.net) y [NodeRed](https://nodered.org/).

A la hora de realizar este proyecto, se ha pensado en ciudades, pero podríamos pensar también en parques empresariales, empresas con recintos con varios edificios.

## Caso de negocio

Hoy en día podríamos pensar en sensorizar cada una de las farolas con
y cada uno de los parques. Eso conllevaría un gasto muy elevado.
Sin embargo con este proyecto podemos ahorrar en costes teniendo en cuenta el tiempo.

### Funcionalidades

- **Agente Virtual para aviso de contaminación**: 
- **Detección de día/noche**: utilizando el servicio de The Weather Channel, el sistema obtiene la hora exacta de amanecer, atardecer y anochecer en la localización exacta. Esto permite saber cuando encender/apagar el alumbrado.
- **Detección de climatología**: utilizando el servicio de The Weather Channel, el sistema obtiene la temperatura y el clima exácto de la zona. Esto permite la activación de los sistemas de riego de los parques en los momentos más adecuados. Igualmente este dato también se utiliza 


## Prototipo

El prototipo de ha probado con una Raspberry PI y unos LEDs para poder hacer una simulación real delante de un cliente.

Esta conexión ha sido muy fácil gracias a **IBM IoT**. 


## ROI

El ROI de este proyecto es inmediato si pensamos en términos **económicos**.

Por una parte encontraremos el ahorro de no alumbrar las calles de las ciudades en horas que no sea necesario o en condiciones climáticas determinadas. Igualmente tendremos un ahorro claro con el riego de los parques siempre que las condiciones climáticas sean las adecuadas.
 

## Enlaces

#### Consola de NodeRed
El flujo de NodeRed está desplegado en: [hackarriquitaun.mybluemix.net](https://hackarriquitaun.mybluemix.net/)

#### Servicio de The Weather Channel
The Weather Channel: [https://console.bluemix.net/docs/services/Weather/index.html?pos=2](https://console.bluemix.net/docs/services/Weather/index.html?pos=2)


## Capturas

La siguiente captura de pantalla muestra el flujo de NodeRed implementado para hacer el prototipo del proyecto:

![Flujo NodeRed](img/flujo-node-red.png)

## Futuras extensiones

