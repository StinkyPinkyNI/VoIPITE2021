# CJDB ITE2021
Proyecto de Finalizacion de Curso ITE Feb.2021.
En este abordaremos el tema de **"Servidor VoIP"** o tambien conocido como
**Central Telefonica**; Terminologia, usos, instalacion e implementacion
en **LAN**.

## Que es VoIP?
Es un conjunto de recursos que hacen posible que la señal
de voz viaje a travès de internet empleando el protocolo **IP** (Protocolo de Internet).

```
            -->             -->
Softphone        Servidor        Tel IP
            <--             <--
```
## Equipo para su implementacion
* Telefonia con Software (Softphone)
* Adaptador para tajeta telefonico
* Servidor VoIP
* VoIP Switch
* Terminales VoIP

## Requisitos de Servidor
| Proposito | Numero de canales | Minimo Recomendado |
| ---------- | ---------- | ----------|
| Hobby | No mas de 5 | 400MHz x86, 256 MB RAM |
| SOHO | 5 a 10 | 1 GHz x86, 512 MB RAM |
| Mediano | Hasta 25 | 3 GHZ x86, 1 GB RAM |
| Grande | Mas de 25 | CPUs Dual, Posibilidad de servidores multiples en una arquitectura distribuida |
* SOHO (Pequeña oficina/ oficina casera - menor que tres lineas y cinco sets)

## Carga del Sistema
|Recurso |     |     |      |
|----------------------- | ---------- | ---------- | ---------- |
| Llamadas Simultaneas | 330 | 330 | 550 |
| Utilizacion del CPU | 149% | 14.8% | 57.6% |
| Carga Promedio | 49 | 25 | 60 |
| Almacenamiento | HDD | RAM | RAM |

## Calidad del Servicio
| Servicio | Caracteristica |
| ---------- | -------------------- |
| Mejor Esfuerzo | No ofrece garantias
| Asegurar el Re-envìo (AF) | Asegura un trato prefenten, si los valores DSCP son màs altos, tendrà mayor prioridad el tràfico y disminuye la posibilidad de ser eliminado por congestiòn
| Re-envìo Acelerado | Utilizada para dar el mayor servicio, por ende, es la que brinda mas garantìas (utilizada para tràfico de voz o video)

### Links de Utilidad
* [Presentaciòn](https://view.genial.ly/60e3d13a5cd8670d349cf2df/presentation-voip)
* [VoIP - Wikipedia](https://es.wikipedia.org/wiki/Voz_sobre_protocolo_de_internet)
* [Asterisk](https://www.asterisk.org/)
* [Issabel](https://www.issabel.org/)
* [Zoiper](https://www.zoiper.com/)
* [3CX](https://www.3cx.es/voip-telefono/softphone/)
