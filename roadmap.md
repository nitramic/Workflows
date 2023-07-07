# Comenzando

## que pretende ser este repo?
En ppio busca demostrar la implementacion de una ifra, ya sea on-prem o en el cloud.
Esta infra estaria basada en el uso de docker, quizas luego subir a kubernetes u otro manager.
Dentro de esta infra se implementa un tomcat con el front-end en el mismo server de la app y luego tambien con un front escalable y el uso de load balancer junto con AJP.
La base sera un postgres y veremos si es posible el uso de MS-SQL.

## Implementacion de docker
En el repo de docker --> Link

Implementacion de Apache/ Load balancer / Tomcat / Postgres
Diagrama --> Link 
Wiki ? TBD


## Importante
MONITOREO: 
 - Usamos Grafana CLoud ? 
 - Zabbix?
 - Como Monitoreamos?
 - Que debemos monitorear?
    - CPU 
    - Uso de disco 
    - cantidad de sesiones en apache
    - revisa el log de cartalina out para ver si hay querys que cuelguen algo?
        EJ: Error on Export Registry 14.0 (Dato del evento ocurrido en ZENITH 20230706) --> [Link](https://vscode.dev/github/nitramic/Py/blob/main/catalina.out.old)


UPGRADES: Como se lleva adelante la implementacion de Upgrades del Soft?
DEVS: 
 - Usamos alguna herramienta de CI/CD? 
 - Como se implementan los desarrollos custom del cliente?
 - 
