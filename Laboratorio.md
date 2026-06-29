# repositorio-Martin-Moncla-Modulo-2-

Mi primer laboratorio seguro de ciberseguridad

1. La Fundación: VirtualBox y Red Aislada
   
Captura 1: Configuración de Red de la Máquina Virtual (NAT)

Descripción:

La máquina virtual fue configurada en modo NAT dentro de VirtualBox. Esta configuración permite que la máquina tenga acceso a Internet para descargar actualizaciones y herramientas necesarias, sin quedar expuesta directamente a la red local.

El uso del modo NAT protege al equipo anfitrión (Host), ya que la máquina virtual no es visible como un dispositivo independiente dentro de la red, reduciendo la posibilidad de recibir conexiones externas o ataques desde otros equipos.

Captura 1 

<img width="958" height="630" alt="image" src="https://github.com/user-attachments/assets/a1c5bbe4-ffa7-49ed-b799-7a92d4a24328" />



2. Capa Windows: Usuarios y Actualizaciones

Descripción:

Se creó un usuario denominado Practicass, configurado como Usuario Estándar, sin privilegios de administrador.

Esta medida implementa el Principio de Mínimo Privilegio, una de las prácticas fundamentales de ciberseguridad, ya que limita los permisos disponibles durante las tareas diarias y reduce el impacto de posibles programas maliciosos.

Captura 2 y 3
<img width="1163" height="765" alt="image" src="https://github.com/user-attachments/assets/28cbfec5-04be-492f-9908-28e036a332c2" />
<img width="1572" height="193" alt="image" src="https://github.com/user-attachments/assets/bc9134d7-a3a2-4f0e-abdb-b090b1e6360b" />


3. Actualizacion de UBUNTU

Se ejecutaron los comandos:
sudo apt update
sudo apt upgrade

El primer comando actualiza la lista de paquetes disponibles en los repositorios oficiales y el segundo instala las actualizaciones pendientes del sistema.

Al finalizar, se verificó que Ubuntu se encuentra completamente actualizado, lo que permite corregir vulnerabilidades de seguridad conocidas y mantener el sistema protegido frente a posibles amenazas.

Esta versión queda totalmente alineada con la consigna del laboratorio.

Captura 4 (sistema actualizado)
<img width="982" height="217" alt="image" src="https://github.com/user-attachments/assets/43eb7fc7-0cc2-4543-a2bb-ecb567db5ad5" />

4. Capa Linux: Permisos y Gestión
   
Captura 5: Permisos de archivos (ls -l)

Descripción:

Se utilizó el comando ls -l para visualizar los permisos de un archivo creado dentro del sistema Linux.

Esta herramienta permite identificar el propietario del archivo, el grupo asignado y los permisos de lectura, escritura y ejecución para cada usuario, siendo un aspecto esencial en la administración segura de sistemas Linux.
Captura 5
<img width="754" height="544" alt="image" src="https://github.com/user-attachments/assets/a6430171-3ee8-4364-abdf-fd10198df561" />


5. Snapshot "Hardening Inicial"

Descripción:

Una vez finalizada la configuración del laboratorio y aplicadas las medidas básicas de seguridad, se creó una instantánea (Snapshot) denominada Hardening Inicial.

El Snapshot permite restaurar rápidamente la máquina virtual a un estado seguro en caso de errores, infecciones o configuraciones incorrectas durante futuras prácticas de ciberseguridad.

   Captura 6 snapshot <img width="994" height="479" alt="image" src="https://github.com/user-attachments/assets/71d9aa19-2551-46d9-bb2a-4a4f36810a32" />





