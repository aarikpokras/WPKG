Avant de d�ployer Office 365 il est n�cessaire de modifier quelques param�tres dans x86 et x64.xml : lignes 3, 15 et 19 il faut modifier l'endroit o� sont stock�s les fichiers d'Office 365.

Il faudra ensuite lancer la ligne de commande suivante : 

\\server\path\setup.exe /download \\server\path\x86.xml pour la version 32 bits

\\server\path\setup.exe /download \\server\path\x64.xml pour la version 64 bits

Le d�lai d'installation moyen est d'environ 15 minutes.