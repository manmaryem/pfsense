
# Installation du firewall pfSense

![image](https://github.com/manmaryem/pfsense/assets/137881827/54936358-5c0c-442c-b5ae-28b2b6b1615d)


•	Créez une règle de filtrage pour empêcher la machine client de sortir du réseau interne :
•	Allez dans "Firewall" > "Rules" > "LAN".
•	Cliquez sur "Add" pour créer une nouvelle règle.
•	Configurez la règle en spécifiant l'adresse IP de la machine cliente comme source et "LAN net" comme destination.
•	Définissez l'action de la règle sur "Block" pour bloquer le trafic sortant de la machine cliente.
•	Enregistrez la règle.


![image](https://github.com/manmaryem/pfsense/assets/137881827/12991200-956f-4d33-85d5-24cd23263e81)

### je bloque le trafic vers l'extérieur 

•	Source : Adresse IP de la machine cliente
•	Destination : LAN net
•	Action : Block

![image](https://github.com/manmaryem/pfsense/assets/137881827/560182c7-697c-4b07-98ed-48e79411ce44)

- plus d'accès a internet 


