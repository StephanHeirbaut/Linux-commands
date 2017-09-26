# Linux-commands
|Commando|Parameters|Uitleg|
|--------|----------|-----------------------------------------------------------------|
|KeePassX|/|Genereren sterk passwoord|
|ls [directory]|-lahRS |Weergeven (current) directory |
|stat [directory]|/|Betere versie van ls -l|
|history|[number]|Weergeven welke commando's er ingegeven geweest zijn|
|!!|/|Vorig commando nog eens uitvoeren|
|!-5|/|Het commando uitvoeren dat op de 5de plaats van vanonder in de uitvoergeschiedenis zit|
|![commando]|/|Meest recente versie van het commando uitvoeren|
|echo "tekst"|/|Boodschap naar de console sturen|
|$var|/|Lokale variabele genereren|
|export var|/|Globale variabele genereren|
|which [commando]|/|Opzoeken locatie commando|
|type [commando]|-at|Geeft informatie over een commando|
|man [commando]|-fk|Volledige uitleg over een commando|
|[commando] --help|/| " |
|whatis [commando]|/| = man -f|
|whereis [commando]|/|Geeft locatie commando|
|info|/| " |
|less|/|Verkort de uitvoer van een commando tot het leesbaar is op één venster|
|more|/| " |
|passwd|/|Aanpassen wachtwoord|
|locate [string]|-c -b|Weergeven alle directories met de string erin|
|pwd|/|Toont huidige working directory|
|cd [directory]|/|change directory|
|cp [directoryA] [directoryB]|-virn|Kopieren A naar B|
|mv [directoryA] [directoryB]|-vin|Verhuizen of hernoemen A naar B|
|touch [string]|/|Aanmaken bestand|
|rm [file/directory]|-irf|Verwijderen bestand|
|rmdir [directory]|-irf|Verwijderen directory|
|mkdir [directory]|/|Aanmaken directory|
|gzip/bzip2/|-l|Comprimeren bestanden|
|tar|-czf -tjf -xjf -v|Archiveren bestanden|
|zip|-f -r|Bestanden toevoegen aan een archief|
|unzip|-l|Extraccting bestanden|
|find [directory]|-size|Zoeken achter een bepaalde directory|
|cat|/|Inlezen bestand|
|sort|-t -n -k|Sorteren output commando|
|wc|-l -w -c|Wordcount|
|cut|-d -f -c|Bepaalde kolommen selecteren uit een bestand|
|grep|-c -n |Filteren van lijnen uit een file of output|
|arch/lscpu|/|Toont type cpu|
|cat /proc/cpuinfo|/|Toont info cpu|
|lspci|-nn -d -v -vv -vvv|Toont info pci|
|lsusb|-v|Toont alle usb apparaten|
|lshal|/|Informatie hardware|
|apt-get [package]| update install upgrade [--purge] remove|Packet manager voor Debian-derived|
|yum| update install upgrade [--purge] remove|Package manager Red Hat-derived|
|ps|--forest aux -ef|Toont active processen|
|pstree|/| " |
|top|/| " |
|syslogd/klogd/rsyslogd/systemd-journal|/|Log files|
|dmesg|/|Kernl buffer ring|
|cat [/etc/sysconfig/network-scripts/ifcfg-eth0
/etc/hosts
/etc/sysconfig/network
/etc/nsswitch.conf]|/|Genereren sterk passwoord|
|ifconfig|/|Algemene info netwerk config|
|ip addr show|/|Netwerkkaart config|
|route|-n|Toont routering tabel|
|ping [address]|-c|Contact opnemen met adres|
|netstat|-i -r -tln|Netwerkverkeer tonen|
|dig [address]|/|DNS|
|host [address]|-ta|Opzoeken aan welk IP/naam het adres gekoppelt is|
|ssh [naam@naam.naam]|/|Remote verbinding aangaan via ssh|
|id [user]|-g -G|Toont uid/gid/groups van de user|
|who|/|Toont alle ingelogde gebruikers|
|w|/|Uitgebreide who|
|chgrp [groupname] [file]|-R|Wijzigen groepeigenaar van file|
|grep [user] /etc/group|/|Toont alle lokale groepen|
|getent|/|Net zoals grep, maar zowel local als netwerkgroepen|
|groupadd [naam]|-g -r|Groep creëren|
|groupmod [naam]|-n -g|Aanpassen groepnaam of GID|
|find / -nogroup|/|Zoeken files zonder groupparent|
|groupdel [naam]|/|Verwijderen groep|
|useradd [naam]|-D -g -f -b|Nieuwe user toevoegen (vb.: useradd -u 1000 -g users -G wheel,research -c 'Jane Doe' jane)|
|usermod [user]|-u -g -aG|Aanpassen gebruiker instellingen (vb.: usermod -aG development jane)|
|userdel [naam]|/|Verwijderen user|
|passwd [user]|/|Aanpassen wachtwoord user|
|chage|/|Aanpassen wachtwoord vereisten|
|chown [file]|user:group|Laat root-user toe om group- en userownership aan te passen|
|chmod [permission] [file]|/|Aanpassen permissies van file|
|umask [permission]|/|Bepalen default permissies|
|chmod g+s [file/directory]|/|Aanpassen setgit|
|chmod o+t [directory]|/|Sticky bit instellen|
|ln [file] [link]|/|Hardlink naar file|
|ln -s [file] [link]|/|Softlink naar file|
