# fic-websites
Múltiples sitios web en un mismo servidor, servidos con HTTPS a través de nginx:

<img src="https://miro.medium.com/max/3000/1*rnzxfcy2N_ffJPnBundJQw.jpeg"
     alt="architecture-nginx-websites"
     style="float: left; margin-right: 10px;" />


Los sitios que quedaron configurados son los siguientes:

- ZAD: ```zad.uaysen.cl```
- IMTA: ```imta.uaysen.cl```
- MEWEP: ```mewep.uaysen.cl ```

Cada sitio se encuentra dentro de la capeta ```/websites``` y contiene su respectivo ```docker-compose.yml``` con la configuración de Wordpress y mysql correspondiente. 



# Actions

When push on main branch, automatic build on the server 
