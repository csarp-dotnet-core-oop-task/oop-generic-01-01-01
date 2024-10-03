Generikus osztályok - gyakorlás
1. feladat  
Készítsen üzenet tárolót amely bármilyen típusú ünezetet képes tárolni és kiiírni a képernyőre. Az üzenet küldés legyen az üzenet kiírása a képernyőre!
2. feladat  
Készítsen szerver választ (Response) osztályt, amely tárolja, hogy a művelet sikeres volt-e, és tárolja a szerver válaszát amely egy tetszőletes típus! Kiíráskor, vagy az üzenetet írja ki, vagy azt, hogy a művelet sikertelen volt!
3. feladat  
Készítsen különböző típus párokat tároló osztályt! Lehesen új párt felvenni! Lehessen őket módosítani! Legyenek olyan metódusok amelyel lekérdezhető a pár egyik vagy másik tagja! Legyen olyan metódus, amely a két párt megcseréli! Lekérdezhető legyen, hogy a pár két típusa megegyezik vagy nem! Lekérdezhető legyen, hogy a két pár megegyezik-e (ha megegyeznek a típusaik)!

~~~
public class Pair<Tipus1,Tipus2> {} 
~~~
5. feladat  
Tegyük fel, hogy egy webáruház rendszerében rendeléseket kezelünk. A rendelés eredménye különböző típusú adatok lehetnek, például sikeres megerősítés (számla), vagy hibaüzenet. Készítsünk osztály különböző típusú visszajelzések tárolására. Készíts egy OrderResult<T> osztályt, amely rendelési eredményeket tárol, függetlenül attól, hogy sikeres-e vagy hibás. Lehessen lekérdezni a generikus segítségével a rendelés sikerességét! Készítsünk ToString metódust amely vagy azt írja ki, hogy a rendelés hibás, vagy kiírja a rendelés eredményét (a T típushoz tartozó adatot)
6. feladat  
Fejlessze tovább az órai Storage osztályt, hogy csak akkor lehesen belerakni elemet a Storage-ba ha üres, és csak akkor lehesen kivenni belölle, ha van benne valami!
