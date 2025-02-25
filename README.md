##     Proyecto de automatización con Ansible

- Escenario:


![](https://github.com/joaz1985/ObligatorioTallerASLX/blob/main/images/diag.png)



Este repositorio contiene la configuracion y scripts necesarios para administrar servidores utilizando Ansible.

Estructura:

- inventory.ini: Archivo de inventario donde se definen grupos de servidores para Ubuntu y Centos
- webserver.yml: Playbook para instalar Apache, crear virtualhost (entre otras tareas)
- hardening.yml: Playbook para seguridad de los servidores ubuntu
- virtualhost.yml: Playbook especifico para la configuracion del virtualhost

> Los registros y capturas de pantalla 
> de las ejecuciones se encuentran en
> el directorio results.





## **Referencias**

Módulos y Colecciones Utilizados:

`ansible.builtin.lineinfile module` – Manage lines in text files.

 Authors
- Daniel Hokka Zakrissoni (@dhozac)
- Ahti Kitsik (@ahtik)
- Jose Angel Munoz (@imjoseangel)

Collection links

- [Issue Tracker](https://github.com/ansible/ansible/issues)
- [Repository (Sources)](https://github.com/ansible/ansible)
- [Communication](https://groups.google.com/forum/#!forum/ansible-project)

Documentation
- [Ansible Documentation – lineinfile module](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/lineinfile_module.html)

`ansible.builtin.template` lookup – Retrieve contents of file after templating with Jinja2 

Author
- Michael DeHaan
- Collection links
- [Issue Tracker](https://github.com/ansible/ansible/issues)
- [Repository (Sources)](https://github.com/ansible/ansible)
- [Communication](https://groups.google.com/forum/#!forum/ansible-project)


 `ansible.posix.firewalld module` – Manage arbitrary ports/services with firewalld
 
**Note**
This module is **not included in ansible-core** and is part of the **ansible.posix** collection.
- Author
- Adam Miller (@maxamillion)

Collection links
- [Issue Tracker](https://github.com/ansible/ansible/issues)
- [Repository (Sources)](https://github.com/ansible/ansible)
