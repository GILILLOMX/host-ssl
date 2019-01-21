...............................
#Nombre del script: host-ssl
.........................

#Domingo 09/12/2018
#Martes 15/01/2019
#by: gilillo / rwam

#Script diseñado para la extracción de url de páginas web, Mostrar los estatus que arrojan cada uno de dichos host y analizar los servicios que brinda con un scan usando nmap 

PASO N°1

#Instalar paquetes para el buen inicio del script

apt update && apt upgrade -y

pkg install nmap

pkg install wget

pkg install curl

pkg install git


PASO N°2

#Instalar el script host-extractor-v2

git clone https://github.com/GILILLOMX/host-ssl.git

cd host-ssl

chmod +x real-host.sh

bash real-host.sh



MOD GILILLOMX



PRESIONA UNA ENTER PARA CONTINUAR...
