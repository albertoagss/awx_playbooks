# awx_playbooks

Playbooks para ser lanzadas en AWX:

-Se han realizado dos playbooks: una para analizar el espacio de 
	volúmenes, y otra para actualizar paquetes.

-Se han adaptado las playbooks de creación e instalación del
	LAMP realizadas anteriormente para que puedan ser lanzadas
	desde AWX. Estas playbooks son compatibles tanto en CentOS como en Debian.

-Se ha creado un 'Workflow Template' en AWX para automatizar 
	el lanzamiento de todas las playbooks necesarias para 
	instalar el LAMP, dejándolo completamente operativo.
