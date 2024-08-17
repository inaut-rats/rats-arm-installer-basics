# Software básico de controlador de robots móviles

Software que integra: Controlador de motores y publicador de información de sensores básico para ROS2

## Tabla de Contenidos

1. [Requerimientos](#requerimientos)
2. [Instalación de herramientas necesarias](#instalación-de-herramientas-necesarias)
3. [Instalación del software](#instalación-del-software)
4. [Modo de uso](#modo-de-uso)
5. [Licencia](#licencia)

## Requerimientos

- **Hardware:** Arquitecturas basadas en ARM64 (Jetson Orin)
- **Sistema operativo:** Ubuntu 22.04
- **ROS humble:** La instalación se muestra en la sección de Herramientas necesarias


## Instalación de herramientas necesarias

### Instalación de ROS Humble Hawksbill

Seguir los pasos de instalación detallados en https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html.
Se asume que se verifica que la instalación sea correcta.


### Instalación de librerias adicionales:
```bash
# Actualizar el sistema
sudo apt-get update

sudo apt install ros-humble-nmea-*
sudo apt install ros-humble-mavros*

sudo apt-get install nlohmann-json3-dev
sudo apt-get install libssl-dev
sudo apt-get install libcurl4-openssl-dev
sudo apt install libssl-dev libjsoncpp-dev
sudo apt-get upgrade
```


## Modo de uso 
El instalador genera los directorios necesarios para su funcionamiento. Un servicio necesita ser ejecutado para correr los programas necesarios. Aquí se detalla la manera para ejecutar dicho servicio:



## Licencia 
Todo debe estar toda la licencia
