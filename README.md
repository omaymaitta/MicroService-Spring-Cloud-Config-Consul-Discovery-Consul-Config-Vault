# MicroService-Spring-Cloud-Config-Consul-Discovery-Consul-Config-Vault

Installer et Démarrer Consul

![image](https://user-images.githubusercontent.com/62363101/209483980-660fde50-0455-4a84-9622-20a683546ad2.png)

![image](https://user-images.githubusercontent.com/62363101/209483984-5905ece2-f293-4c95-9dce-383935662aa9.png)

Création d’une repository git pour que le config service connaître le changement 

![image](https://user-images.githubusercontent.com/62363101/209484000-3bb25406-39e4-46ef-af59-62ab5cb02736.png)

Executer config-service classe

![image](https://user-images.githubusercontent.com/62363101/209484006-6a5908ed-1ffa-499f-9caa-2e0537e68d95.png)

Acceder aux configurations par défaut de customer-service

![image](https://user-images.githubusercontent.com/62363101/209484014-d8ab320f-7456-4bb4-a67c-fd82820f26d5.png)

Acceder au environnement dev 

![image](https://user-images.githubusercontent.com/62363101/209484020-d020dfbb-25d5-49b6-8d17-b87e4b3d9817.png)

Accéder au environnement prod

![image](https://user-images.githubusercontent.com/62363101/209484029-9463d924-29a7-414d-9327-80d25fe80221.png)

Démarrer customer service

![image](https://user-images.githubusercontent.com/62363101/209484038-d77595a2-1a19-4b08-8bd3-4e5d302809cb.png)

Tester le testController

![image](https://user-images.githubusercontent.com/62363101/209484042-d04f995a-5a55-4982-b4e5-79a2caddd749.png)

Reconfiguration sans besoins de redémarrer 
http client request client en utilisant Actuator

![image](https://user-images.githubusercontent.com/62363101/209484048-2e14a959-61b7-4e72-8864-3d0955f2da2f.png)

Résultat

![image](https://user-images.githubusercontent.com/62363101/209484055-544243af-e318-4a94-b184-aacf4e9cfd7d.png)

Tester le service gateway

![image](https://user-images.githubusercontent.com/62363101/209484061-4d379125-df25-495c-9fb3-6638b1552d15.png)

![image](https://user-images.githubusercontent.com/62363101/209484063-e36fe661-b883-4d94-8386-d4f3b51500e3.png)

Démarrer le service inventory

![image](https://user-images.githubusercontent.com/62363101/209484068-ea6c4ed7-3bab-4e97-80b1-fb27fe1046f0.png)

![image](https://user-images.githubusercontent.com/62363101/209484072-ea1592ed-32e0-4cd2-881e-b4b9e907e368.png)

Tester la projection

![image](https://user-images.githubusercontent.com/62363101/209484074-abfe29a9-e256-411d-81dd-8aba40f24ac0.png)

![image](https://user-images.githubusercontent.com/62363101/209484076-f687e60b-803a-4517-9864-4d9b986470bc.png)

Pour que le service order peut communiquer avec les autres services (inventory et customer) il faut ajouter un client Rest : Openfeign
Insertion des dépendances au pom de order service
-Hateoas 
-Openfeing

![image](https://user-images.githubusercontent.com/62363101/209484084-2cfad49d-f5f0-4d04-96fc-22a163b4e0c4.png)

Tester le service order

![image](https://user-images.githubusercontent.com/62363101/209484098-c48ba6c1-d59e-4fc0-97a2-bf82bf4fda79.png)

![image](https://user-images.githubusercontent.com/62363101/209484102-36ae0ca9-549c-4e94-95b3-05fef2c639f6.png)

Tester OrderRestController

![image](https://user-images.githubusercontent.com/62363101/209484107-56fa7b74-57eb-44b3-8e3c-5e8fbceda4f7.png)

## Vault
#### SERVER
![image](https://user-images.githubusercontent.com/62363101/209484122-1cb22589-600d-459f-9aee-f59dbafbfcae.png)

![image](https://user-images.githubusercontent.com/62363101/209484126-d36cb893-b03f-4ef5-b3a0-9e537d59c5f9.png)

#### CLIENT

![image](https://user-images.githubusercontent.com/62363101/209484134-75d862fa-e8c8-43aa-af5a-19ce44a7a47f.png)

![image](https://user-images.githubusercontent.com/62363101/209484136-1a6dd22b-95e6-4a33-ad7c-dbb109ed55a7.png)

![image](https://user-images.githubusercontent.com/62363101/209484139-0fe97e7b-a352-4d5a-8647-e041c7ef7da2.png)

![image](https://user-images.githubusercontent.com/62363101/209484143-4b728a91-31ea-445a-8d0d-4b2303a34213.png)

Private et public key

![image](https://user-images.githubusercontent.com/62363101/209484150-9924cafc-183b-43f0-ab88-1f3ee9b92a04.png)

![image](https://user-images.githubusercontent.com/62363101/209484158-547a59d1-b949-4eb4-abaf-8231b3974a23.png)

## Front end
Creation de projet Angular
![image](https://user-images.githubusercontent.com/62363101/209484165-d3b7d308-a78e-448d-acf6-cc64089f9f5e.png)
