# Instalar Wine + Lutris

## 1. Instalar Wine

(https://linuxconfig.org/install-lutris-on-ubuntu-20-04-focal-fossa-linux)

1. Habilitar arquitectura de 32 bits (asumiendo que tu sistema es de 64 bits) esto sirve para añadir compatibilidad:

    ``
    sudo dpkg --add-architecture i386
    ``

2. Luego, descargar la clave del repositorio de Wine:

    ``
    wget -nc https://dl.winehq.org/wine-builds/winehq.key
    ``

3. A continuación, agregar la clave del repositorio al sistema:

    ``
    sudo apt-key add winehq.key
    ``

4. Finalmente añadir el repositorio de Wine con el siguiente comando:

    ``
    sudo apt-add-repository 'deb https://dl.winehq.org/wine-builds/ubuntu/ focal main'
    ``
5. Actualizar repositorios e instalar Wine:

    ``
    sudo apt update ``
    
    ``
    sudo apt install --install-recommends winehq-stable
    ``  

---

## 2. Instalar Lutris

(https://lutris.net/downloads/)

1. Añadir el repositorio PPA de Lutris:

    ``
    sudo add-apt-repository ppa:lutris-team/lutris
    ``

2. Actualizar repositorios e instalar Lutris:

    ``
    sudo apt update ``

    ``
    sudo apt install lutris
    ``

---

## 3. Instalar soportrte para Vulkan
(https://github.com/lutris/docs/blob/master/InstallingDrivers.md)

en el caso de AMD/Intel:

1. Añadir los repositorios mesa:

    ``
    sudo add-apt-repository ppa:kisak/kisak-mesa
    ``

2. Actualizar el sistema:

    ``
    sudo apt update
    sudo apt upgrade
    ``

3. Instala soporte para juegos de 32 bits:

    ``
    sudo apt install libgl1-mesa-dri:i386
    ``    

4. Instala soporte para Vulkan:

    ``
    sudo apt install mesa-vulkan-drivers mesa-vulkan-drivers:i386
    ``

