# A patiens_api

## Végpont

A végpontok indítás után így érhetők el:

* [http://localhost:8000/]

| Végpont | Metódus | Azonosítás | Leírás |
|-|-|-|-|
| patients | GET | nem | A páciensek listáját adja |
| patients | POST | nem | Új páciens vehető fel |
| patients | PUT | nem | Páciens adatainak módosítása |
| patients | DELeTE | nem | Páciens törlése |

Egy páciensről a következő adatok vannak tárolva:

* id – A páciens azonosítója
* name – A páciens neve
* age – A páciens életkora
* bodyWeight – A páciens testsúlya
* bloodPressure – A páciens vérnyomása
* pulse – A páciens pulzusa

## Páciensek lekérdezése

* [http://localhost:8000/patients](http://localhost:8000/patients)

| Végpont | Metódus | Azonosítás |
| patients | GET | nem |

Üres body kell küldeni.
