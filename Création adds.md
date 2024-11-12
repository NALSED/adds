### Mise en place d'un ADDS

1) ##### **INSTALATION DU SERVEUR ADDS**
* ##### Au sein du **Serveur manager**, cliquez sur **Manage** et **add roles and feature** .
  * ##### Choisissez l'option **Role-based or feature-based instalation** et poursuivez.
  * ##### Choisir Active Directory Domain Services
  * ##### Continuer l'installation, puis cliquer  sur **Add Features**
*********************************************************************************************************
2) ##### **CONFIGURATION DU SERVEUR ADDS**
   * ##### Procéder à l'installation, à la fin cliquer sur **Promote this server to a domain controller**
![adds1](https://github.com/user-attachments/assets/bc78a096-f64c-4ee1-bed9-d854ebe4b2f9)
 * ##### cocher Add new forest et Root domain name
![adds 2](https://github.com/user-attachments/assets/264e92a0-3881-4c32-b772-0fa2c0cbc31c)
* ##### renseigner le niveau de windows suporté **Forest functional level** et dans **Domain functional level**
* ##### entrer des **Password**  
* ##### Ne pas cocher Create DNS delegation
* ##### Renseigner **The NetBIOS domain name**
* ##### Laisser par défaut : "Database folder" Log files folder" "SYSVOL folder".
* ##### Un récapitulatif résume la configuration, faire next.
* ##### après une vérification le résultat :
 ![adds 4](https://github.com/user-attachments/assets/48233b21-c883-4eeb-b95a-8b5e209e27ec)
 * ##### **Install**
 * ##### L'opération peux durer et un redémarage est nécéssaire.
 *  #### Au redémmarage la **connection** se fait avec **DOMAINE** créer précédement et via le **Password** de A dministrator
![adds5](https://github.com/user-attachments/assets/1e75b322-17d4-4822-a698-2cbf8d84b234)


3) ##### création d'un Domain
* #####  Dans tool choisir Active directory Users and Computers
* ![adds 6](https://github.com/user-attachments/assets/d79a9043-5a3f-4cc4-857c-22090f87a46f)
* ##### Dans domain.local = > New => Organisations Unit
  ![adds 7](https://github.com/user-attachments/assets/06c7a72c-83dc-401a-80da-4213132ed2e8)
* ##### Donner un nom à ce domain puis créer un nouvel **User**
![adds8](https://github.com/user-attachments/assets/7dae6664-d50a-4b8f-b1df-66b5b23f82be)
* ##### Le renseigner 
![adds 9](https://github.com/user-attachments/assets/0378aca1-178e-426b-8f18-6f65bd5dc731)
