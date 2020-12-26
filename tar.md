- Créer tous ces fichiers et répertoires. Faire le nécessaire pour que l’affichage d’un
ls -l dans votre répertoire ressemble à cela :

%> ls -l
total XX
drwx--xr-x 2 XX XX XX Jun 1 20:47 test0
-rwx--xr-- 1 XX XX 4  Jun 1 21:46 test1
dr-x---r-- 2 XX XX XX Jun 1 22:45 test2
-r-----r-- 2 XX XX 1  Jun 1 23:44 test3
-rw-r----x 1 XX XX 2  Jun 1 23:43 test4
-r-----r-- 2 XX XX 1  Jun 1 23:44 test5
lrwxr-xr-x 1 XX XX 5  Jun 1 22:20 test6 -> test0
%>

[NB] Pour les heures, il sera toléré que ce soit l’année qui s’affiche si la date de l’exercice
(1 juin) est dépassée de six mois ou plus.
[NB] Les XX ne seront pas pris en compte.

- Une fois l’exercice résolu, vous exécuterez la commande tar -cf exo2.tar * pour
créer le fichier à rendre.