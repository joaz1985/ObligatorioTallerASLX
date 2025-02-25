#       Descripcion del proyecto
## Escenario:


![](https://github.com/joaz1985/ObligatorioTallerASLX/blob/main/images/diag.png)



Este repositorio contiene la configuracion y scripts necesarios para administrar servidores utilizando Ansible.

Estructura:

- inventory.ini: Archivo de inventario donde se definen grupos de servidores para Ubuntu y Centos
- webserver.yml: Playbook para instalar Apache, crear virtualhost (entre otras tareas)
- hardening.yml: Playbook para seguridad de los servidores ubuntu
- virtualhost.yml: Playbook especifico para la ocnfiguracion del virtualhost

> Los registros y capturas de pantalla 
> de las ejecuciones se encuentran en
> el directorio results.
