# Jitsi-Meet-Installation

Este repositorio servirá para documentar la instalación y puesta en funcionamiento de Jitsi Server en una red local.

## Requerimientos iniciales

* **Ubuntu Server 24.04**
* **RAM:** more than 8GB
* **CPU:** Para un servidor básico, 4 núcleos sería suficiente
* **Espacio en disco:** al menos 20GB de espacio disponble en discos SSD.

## Pasos de preparación de requisitos
```bash
sudo apt update
sudo apt upgrade

sudo apt install apt-transport-https

sudo apt-add-repository universe
sudo apt update

sudo hostnamectl set-hostname meet.sansebastian.org
sudo nano /etc/hosts
Add 127.0.1.1 meet.sansebastian.org & save & exit
```

