# MME II - UE3

Aufgabe 1, Pflicht:
    
- neue Resourcensammlung (Accounts)

Aufgabe 1a, Pflicht:

- passende URL-Repr�sentation f�r die neue Ressourcensammlung
- min. eine Route mit Route-Handler in node.js anlegen

Aufgabe 1b, Pflicht:

- alle CRUD Operationen mit Route-Handlern erf�llen
  - Vorf�hrung mittels Postman Chrome-App
  
Aufgabe 2, Pflicht:

- lass die neue Ressourcensammlung eine 1:n oder n:1 Beziehung zu tweets haben

Aufgabe 2a, Pflicht:

- bei GET, das Attribut "href" in JSON Darstellung mitliefern
  - "href" enth�lt URL die das Obj. in der REST API repr�sentiert
  - wenn Array in response, auch ein "href" f�r das entsprechende Array
  
Aufgabe 2b, Pflicht:

- accounts : tweets = 1:n, ein account hat n tweets
  - HTTP GET http://localhost:3000/accounts/:id > Verweis auf tweets mitliefern

Aufgabe 3, Bonus:

- extend the api with a patch method for one of the collections
