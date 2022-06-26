# <b>¿Qué es WSL2?</b>

<cite style="display:block; text-align: justify">
El subsistema de Windows para Linux 2 (WSL2) es la solución más sencilla y eficiente para utilizar aplicaciones Linux en Windows. WSL2 permite el acceso a las herramientas y aplicaciones Linux directamente desde el entorno Windows habitual y, por ello, es especialmente interesante para programadores. Gracias a la arquitectura completamente revisada respecto a la versión anterior, WSL2 ofrece un mayor rendimiento que los planteamientos comparables que existen.

WSL2, que fue lanzado en la primavera de 2020, es un perfeccionamiento de [Windows Subsystem for Linux (WSL1)][1_0]. Linux es un sistema operativo de [código abierto][1_1] que se diferencia fundamentalmente de Windows, que se desarrolla y distribuye como un producto comercial. Linux convence especialmente por su amplia variedad de herramientas de programación y otros paquetes de software disponibles libremente.</cite>

![Arquitectura WSL2](img_Arq/img_1.jpg) 

[1_0]:https://www.ionos.es/digitalguide/servidores/know-how/windows-subsystem-for-linux-wsl/

[1_1]:https://www.ionos.es/digitalguide/servidores/know-how/que-es-el-open-source-o-codigo-abierto/

[1_2]:https://www.ionos.es/digitalguide/servidores/configuracion/virtualizacion/

[1_3]:https://www.ionos.es/digitalguide/servidores/know-how/maquina-virtual/

[1_4]:https://www.ionos.es/digitalguide/servidores/know-how/que-es-hyper-v/

# <b>Comparación de WSL1 y WSL2</b>

<cite style="display:block; text-align: justify">La diferencia fundamental entre WSL2 y su versión anterior se encuentra en la arquitectura del software. Mientras que WSL1 cuenta con una capa de compatibilidad para la transferencia de la ejecución del código entre Windows y Linux, WSL2 está basado en la [virtualización][1_2] de un sistema operativo Linux. [La máquina virtual][1_3] que se utiliza se ejecuta en el hipervisor nativo de Windows [Hyper-V][1_4], que ofrece un rendimiento especialmente alto.</cite>
