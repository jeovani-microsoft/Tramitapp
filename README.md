![Summer Hack (4)](https://user-images.githubusercontent.com/9124597/127756851-c8627116-f177-4198-966d-9003016d2060.png)

# Tramitapp

## Descripción:

TramitAPP es una web app que busca arrorar tiempo en los trámites gubernamentales y reducir el risgo de contagios por COVID19 en los tiempos de espera para esos trámites. Como equipo notamos que mucho del tiempo de espera segenerá en la revisiónde documentos, por lo que proponemos una web app que permita subir los documentos para su revisón previo a la cita. De esta manera tu acudes a al cita solo por el tiempo justo que necesitas reduciendo el tiempo de espera, así como el riesgo de contagio.

La plataforma esta en mantenimiento por el momento.

https://lemon-dune-0d9eb8310.azurestaticapps.net/

### Link al Tiktok
https://vm.tiktok.com/ZMd3JNVeN/

### Diagrama de Azure
![alt text](https://github.com/jeovani-microsoft/Tramitapp/blob/main/diagrama.png)



### SLA Compuesto
![SLA](https://user-images.githubusercontent.com/86895225/127779895-56f78167-c2bf-4311-aee1-3e978c6cf11b.png)

### TCO 3 años y Precio Total por mes

TCO a 3 años
Nuestra propuesta al ser una Web app, no consideramos el uso de maquinas virtuales como tal. Para los workloads definimos:
* *Database:* My SQL en una maquina virtual con Windows Standar de 2 cores y 4Gb de Ram. Destinada a 200 usuarios en concurrencia. Consideramos que aunque muchos ciudadanos pueden solicitar trámites, no todos lo harán al mismo tiempo.
* *Storage:* Un disco SSD con capacidad de 1 TB, al igual en Bakup y Archive 
* *Networking:* Consideramos un ancho de banda de 2Gb ya que las operaciones que se realizaran en la plataforma no requieren demsiado tiempo, salvo al subir archivos, pero el resto es de lectura de información.

Con estas consideraciones obtenemos que al utilizar Azure durante 3 años en la región del Este de Estados Unidos, nos ahoraríamos la nada despreciable cantidad de USD 3,206 ($63,740.73 MXN) como se puede apreciar en las siguientes imágenes.



![image](https://user-images.githubusercontent.com/86895225/127781106-a4228145-933b-4119-b77a-51ada42dc4be.png)

![image](https://user-images.githubusercontent.com/86895225/127781113-3af0dfa5-fa7a-4e11-b3f0-c764a6b9c843.png)

![image](https://user-images.githubusercontent.com/86895225/127781140-e5704970-7bca-4b9e-aad4-d3ddc7d3d35c.png)

![image](https://user-images.githubusercontent.com/86895225/127781149-72f8aee5-0b89-4508-beca-fdbaa2d72c51.png)


Por otra parte, el cálculo mensual se obtuvo de al cotizar los siguientes productos:

* *Cuenta de Lamcenamiento*: En la región este de Estados Unidos de tipo File Storage con un alamcenamiento de 1000 GB y un Servidr para sincronización.
* *APP Service:* Una instancia B1 para 730 Horas, utilizando Windows en la región del Este de Estados Unidos.
* *Azure SQL Database:* Una instancia aprovisionada para 730 Horas en la region del Este de Estados Unidos de tipo Single Database y de proposito general 5ta Generacion con redundancia local. Se reservo por 3 años con una licencia de Azure Hybrid Benefit y un almacenamiento de 1 Tera, un respaldo de 256gb y %gb para la retención.

Bajo estas circunstancias el gasto mensual es de USD 748.76 ($14,886.62 MXN) lo cual lo podemos ver en este informe.

![image](https://user-images.githubusercontent.com/86895225/127781674-f21ba4da-a374-49b5-a245-15a030587e90.png)



### Tiempo sin disponibilidad a un año

![TIA](https://user-images.githubusercontent.com/86895225/127780016-4cac88d2-6bcd-40e1-98b9-d9c112348192.png)

----
### Qué te pareció el evento

Es un evento bastante interesante , que te permite desarrol habilidades y ampliar conocimientos en el ambito tecnológico.
----

Fue una exelente oportunidad para convivir con la comunidad técnológica. Estuvo llena de retos tanto tecnológicos como personales. HAce poco me di cuenta de lo desfasado que me encuentro en cuanto a las nuevas tecnologías y estoy haciendo un esfuerzo por ponerme al día. Esta experiencias me agradables momentos y estresantes como estos últimos días pero de todo se aprende. Me llevo una excelenete experiencia y me quedo con ganas de seguir participando en estos eventos. Ojalá en algún punto pueda estar del otro lado. Gracias a todos los del Staff y a mis compañeros. Jeovani Morales.
