# fisi_2023_1_tribucumbia_armonia10_infra
- Creación del Grupo de Recursos.- Se cuenta con la creación de 4 principales grupos de recursos los cuales se definieron en la arquitectura física de nuestra aplicación, siguen el formato de nombre rg-servicio-bookaroom-prod-001 como se puede ver en la imagen
<img width="782" alt="Captura de pantalla 2023-07-09 065056" src="https://github.com/grupo2armonia10/fisi_2023_1_tribucumbia_armonia10_infra/assets/138836209/2cddcf3c-b218-4260-a1ac-992560d69522">

- Configuración Azure MySQL

Primero seleccionamos “Crear” en el recurso Servidores de Azure Database for MySQL

<img width="322" alt="Captura de pantalla 2023-07-16 100243" src="https://github.com/grupo2armonia10/fisi_2023_1_tribucumbia_armonia10_infra/assets/138836209/e88f3e64-3b13-4c5c-8bbe-885c275cb175">

Seleccionamos la opción de “Servidor Flexible”

<img width="353" alt="Captura de pantalla 2023-07-16 100322" src="https://github.com/grupo2armonia10/fisi_2023_1_tribucumbia_armonia10_infra/assets/138836209/851380e7-a393-45d6-b959-3be1009d1bc7">

Nos aparecerá una ventana donde estableceremos la configuración de la Base de Datos, el nombre de esta y el usuario con su contraseña.

<img width="482" alt="Captura de pantalla 2023-07-16 100721" src="https://github.com/grupo2armonia10/fisi_2023_1_tribucumbia_armonia10_infra/assets/138836209/c28d0f20-cedf-42e1-97d4-819c091e2e79">

Como requisito nos pedirá establecer Reglas de Firewall donde se dará acceso según ip

<img width="475" alt="Captura de pantalla 2023-07-16 101104" src="https://github.com/grupo2armonia10/fisi_2023_1_tribucumbia_armonia10_infra/assets/138836209/becacdbc-5565-4c4d-9430-99a1dc581d76">

Luego de unos minutos, Azure nos mostrará la ventana para visualizar el recurso y su estado

<img width="505" alt="Captura de pantalla 2023-07-16 101157" src="https://github.com/grupo2armonia10/fisi_2023_1_tribucumbia_armonia10_infra/assets/138836209/d03424a1-f9d8-4856-a9aa-7b9e3825a216">

- Configuración AKS
- Configuración API Management
- Configuración Azure Container Registry
