# ¿Que son los paquetes RPM?

> Consisten en un conjunto de archivos que permiten la instalación de un programa y sus tareas relacionadas pensada para GNU/Linux. Es capaz de instalar, actualizar, desinstalar, verificar y solicitar programas. 
---
Desarrollado inicialmente por la empresa **Red Hat** por el fundador de la misma, Marc Ewing y el ingeniero Erik W. Troan para Red Hat Linux, es ampliamente utilizado en varias distribuciones como Fedora, Mageia, openSUSE y SuSE Linux.


Entre las características de **RPM** están:

1. Los paquetes pueden ser cifrados y verificados con GPG y MD5.
2. Los archivos de código fuente (por ejemplo .tar.gz, .tar.bz2) están incluidos en SRPMs [^1], posibilitando una verificación posterior.
3. PatchRPMs [^2] y DeltaRPMs [^3], que son equivalentes a ficheros parche, pueden actualizar incrementalmente los paquetes **RPM** instalados.
4. Las dependencias pueden ser resueltas automáticamente por el gestor de paquetes.

---
[^1]: Son paquetes que contienen el código fuente y la información de construcción necesaria para compilar e instalar un programa en un sistema basado en RPM.

[^2]: Son archivos que contienen actualizaciones para software en sistemas operativos basados en RPM.

[^3]: Los DeltaRPMs es un enfoque utilizado en sistemas basados en RPM para la gestión de paquetes y la aplicación eficiente de actualizaciones de software. En vez de descargar todos los paquetes nuevos más los que ya tienes, lo que hace es buscar las diferencias entre el antiguo y el nuevo y modificarlo, es decir, solo se transfiere lo que se haya modificado.
