**¿Qué es Ansible y por qué es "sin agente" (agentless)?**  

_Ansible es un herramienta que se utiliza para la automatización de software, es sin agente porque no necesita que se instale ningun software adicional en los nodos que va a gestionar, en lugar de esto utiliza conexiones SSH_.

**Explica la diferencia entre un comando ad-hoc y un playbook.**

_Los comando ad-hoc son utilizados para operaciones puntuales, son comandos mas simples que se ejectuan de forma instantanea para tareas rápidas sin un archivo de configuración_

_Un playbook es un archivo YAML mas complejo, que contiene instrucciones o tareas para ejecutar en uno o mas hosts, permite automatizar procesos completos._

**¿Qué es la idempotencia y por qué es importante en Ansible?**

_La idempotencia significa que se puede hacer la misma acción varias veces y el resultado va a ser el mismo. En Ansible eso es importante ya que asegura que al repetir la tarea no se cambiará el estado final, los modulos salen sin realizar ninguna acción_.

**¿Cómo funcionan los handlers y cuándo deberías usarlos?**

_Son tareas especiales que se utilizan para realizar acciones solo si se ha realizado un cambio, como por ejemplo si se reinicia un servicio despues de modificar su configuración. En el playbook se llaman mediante la instrucción `notify`_

**¿Cómo verificas errores de sintaxis en un playbook de Ansible?**

_Para verificar errores de sintaxis se puede utilizar junto al comando `ansible_playbook`la opción `--syntax-check`. Este comando analizara el playbook y muestra si hay errores en la tarea sin ejecutarla.
Otra opción es la herramienta `ansible-lint` que analiza los módulos y controla las tareas de ansible._
