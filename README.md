# Desarrollo de un sistema de base de datos para la consulta de contenidos y servicios ofrecidos por un hospital.
_Proyecto integrador 8vo cuatrimestre, Universidad Politécnica de Juventino Rosas_

&nbsp;
### Integrantes del proyecto
* Sandra Ximena López Garcia.
* Brenda Sofía Cruz Mendoza.
* Hannia María Velásquez Gámez.
* Francisco Javier Vargas Conejo.
  
&nbsp;
## Problemática 
La administración eficiente de los servicios ofrecidos por un hospital en cuanto a el manejo adecuado de los medicamentos y la gestión de un control financiero de los servicios que este ofrece, es fundamental para garantizar la calidad de la atención a los pacientes. Sin embargo, en muchas instituciones de salud, la administración de estos aspectos se realiza de manera manual lo que permite que se presenten fallas sobre el control de los recursos utilizados en el hospital. Estos problemas pueden ocasionar la perdida de información, duplicación de registros, demoras en los procesos administrativos y dificultades para acceder a los datos en tiempo real; Los problemas se agravan cuando la cantidad de usuarios y el volumen de información aumentan, lo que por consecuencia puede llevar a errores humanos y crea retrasos o falta de control.

![2](https://github.com/user-attachments/assets/a03ee1cc-4106-4732-825d-ed11d0274b5f)

Para abordar esta problemática, se plantea el desarrollo de un sistema distribuido basado en una red local, con una página web alojada en un servidor Windows y una base de datos centralizada. Este sistema permitirá que el personal autorizado acceda a la plataforma mediante una dirección IP local, posibilitando la consulta y el registro de información desde cualquier dispositivo conectado a la red hospitalaria. De esta manera, se optimizará la gestión en tiempo real, garantizando que los datos sean precisos, accesibles y actualizados.

&nbsp;
## Desarrollo de la página web y base de datos
El proyecto se comenzó con diseñar un diagrama de Entidad - Relación tomando en cuenta las areas que el hospital contiene, en cuanto a la página se estreucturo desde un login para se correcto inicio de sesión que le permita el accesso al personal dependiendo el area al que este corresponda.

## Servidor en red local
Para esta actualización se opto por montar la página web en un servidor de windows para agrandar la posibilidad de visitar la página desde distintos dispositivos mientras esto se realice estando conectado a la red en la que se encuentre el servidor.

## Sin conexión a internet
Con el avance de investigación sobre las incognitas a mejorar se planeó la posibilidad de ofrecer la accesibilidad de la página aún si no habia seervicio a internet, reduciendo tiempos de espera para la actualización de registros o actualizaciones de datos.
