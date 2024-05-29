# Maven with dependency - Spring Angular JWT de Digital Banking

## Partie Backend
* ###### entités JPA : Customer, BankAccount, Saving Account, CurrentAccount, AccountOperation
* ###### Repositories
* ###### interfaces JPA Repository basées sur Spring Data
* ###### Mapper, Service, RestControllers

## Tâches Accomplies
##### Screenshot :
!![img.png](img.png)

**- Tâche 1 : Exec & App.properties**
![img_1.png](img_1.png)

**- Tâche 2 : Exec Ebanking APP**
![img_2.png](img_2.png)

**- Tâche 3 : Exec PresSpringAnnot**
![S4presAnnot.png](Screen4github%2FS4presAnnot.png)

**- Tâche 4 : Dependency (Spring Core/Context/Beans-Junit)**
![S5dependency1.png](Screen4github%2FS5dependency1.png)

**- Tâche 5 : Config.txt**
![S6config.png](Screen4github%2FS6config.png)

**- Tâche 6 : Test with JunitAssert**
![S7testJunit.png](Screen4github%2FS7testJunit.png)

## Notions et réference : 

###### @OneToMany:  utilisée pour définir une relation "un-à-plusieurs" entre deux entités.
###### @Data : provient de la bibliothèque Lombok, utilisée pour simplifier le code Java en générant automatiquement des méthodes courantes comme les getters, setters, toString, equals, et hashCode.
###### @Id : utilisée pour spécifier le champ d'une entité qui sera utilisé comme clé primaire. Chaque entité doit avoir une clé primaire, qui identifie de manière unique chaque instance de cette entité dans la base de données.
###### @GeneratedValue : utilisée en conjonction avec @Id pour indiquer que la valeur de la clé primaire sera générée automatiquement. Cette génération peut se faire de différentes manières, spécifiées par la stratégie (strategy) utilisée.
###### @DiscriminatorColumn : utilisée dans le contexte de l'héritage des entités. Elle est particulièrement utile lorsqu'on utilise la stratégie d'héritage SINGLE_TABLE, où toutes les classes d'une hiérarchie d'héritage sont mappées sur une seule table dans la base de données.
###### Inheritance : utilisée pour définir la stratégie d'héritage pour les entités dans une hiérarchie d'héritage. JPA propose plusieurs stratégies pour mapper les hiérarchies d'héritage aux tables de la base de données.
###### @Entity : marquer une classe Java comme une entité persistante, ce qui signifie que ses instances peuvent être stockées dans une base de données relationnelle. 
###### @Bean : utilisée pour indiquer qu'une méthode produit un bean à gérer par le conteneur Spring. Cette annotation est généralement utilisée dans les classes de configuration marquées avec @Configuration.
###### @Transactionnal : utilisée pour gérer les transactions de manière déclarative. Elle permet d'appliquer la gestion des transactions à des méthodes ou des classes sans avoir à écrire du code de gestion des transactions de bas niveau.
###### @Service : utilisée pour marquer une classe comme un composant de service dans l'application.
