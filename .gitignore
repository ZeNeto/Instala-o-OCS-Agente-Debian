#Criador por José Neto
#25/10/2016
#!/bin/bash

clear
while true; do

echo "---------------------------------------------------
	Instalação do OCS Inventory Linux - Debian/Linux Educacional 
	1 - Instalar
	2 - Sair
   "
read choice

if [ -z $choice ]; then
	echo "Erro: Escolha uma opção"
	exit
fi

case $choice in
	1) 
	apt-get install dmidecode libxml-simple-perl libnet-ip-perl libwww-perl libdigest-md5-perl libnet-ssleay-perl
	wget https://launchpadlibrarian.net/175892335/Ocsinventory-Unix-Agent-2.1.1.tar.gz
	tar -xvf  Ocsinventory-Unix-Agent-2.1.1.tar.gz
	cd Ocsinventory-Unix-Agent-2.1.1
	perl Makefile.PL
	make
	make install
	exit;;

	2)
	echo "Saindo"
	exit;;

	*)
	echo "Erro: Opção Inválida"
	echo;;

esac
done
