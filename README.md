# Binbash-exercices
# A little bit of script for practice
#########
#Programa:script2script
#Autor:Moi
#Fecha:26.08.18
#Descripcion: Script en bash que ayuda a crear encabezados para hacer scripts
########

#! /bin/bash
clear
echo "introduce nombre de programa" 
programa=$programa
read programa
echo "ejecutando script..."
touch /home/moi/$programa.sh
echo -e "############ \n#Programa:$programa \n#Fecha: `date +%d-%m-%y` \n#Autor: `whoami` \n#Descripcion: \n############ \n#! bin/bash" >> /home/moi/$programa.sh
nano /home/moi/$programa.sh
