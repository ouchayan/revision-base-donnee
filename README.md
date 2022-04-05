## Mysql : Moteurs de stockage :
- Les moteurs de stockage dans mysql : MyIsam (par defaut),InnoDB (le plus connu), ISAM, Heap, NBD, Berkeley DB ou encore Merge.
- Commande pour changer le moteur de stockage : ALTER TABLE `table` ENGINE=MYISAM;  ALTER TABLE `table` ENGINE=InnoDB;
- show databases; use databaseName; show engines; pour afficher les moteurs de stockage
- MyIsam : non transactionnel, non relationnel, pour des petit projet, bien pour des requetes d'affichage et création
- InnoDb : Transactionnel, Relationnel, Pour les grand projet.
- CREATE TABLE TOTO(.....)ENGINE=InnoDB; CREATE TABLE TOTO(.....)ENGINE=MyIsam; 
