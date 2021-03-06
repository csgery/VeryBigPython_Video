# Követelmény specifikáció

## Áttekintés
A fejlesztés célja egy vizuálisan részletes, átlátható alkalmazás készítése, amely képes a bemeneti videókból egy személyre szabott hosszúságú, együttes videó állományt készíteni, aminek a letöltésére is lehetősége van a felhasználónak. Fontos a program egyszerű áttekinthetősége, ami a felhasználó munkáját könnyíti meg.

## Jelenlegi helyzet
- A megrendelőnek szüksége van egy átlátható, könnyen kezelhető és korszerű szoftverre, ami (akár a jelenlegi biztonsági kamerák vagy) akármilyen kamera által készített különböző nézetű felvételeket képes egy nézetben megjeleníteni. 
- Nehezebb nyomon követni a felvételeket ha külön-külön vannak, valamint ha arra lenne szükség, összehasonlítani is nehezebb

## Kívánt rendszer
A megrendelő vágyik egy programra, aminek célja több videó állományt összeilleszteni. A videó fájlokat a felhasználó tetszés szerint kiválaszthatja és megadhatja a kezdő és végpontjaikat, valamint, hogy melyik hangcsatorna legyen aktív. Miután minden kész van, a felhasználónak lehetősége van letölteni az összeállított állományt.

## Elvárt működés
A felhasználó előtt a program elindítása után négy kattintható felület jelenik meg, amelyek segítségével ki tudja választani, hogy a képernyő melyik részén milyen videó jelenjen meg. Ezek alatt pedig egy-egy csúszka az összes videóhoz, amin a felhasználó a kezdő és végpontokat tudja beállítani. Minden csúszka mellett egy-egy checkbox, amikkel meg lehet adni, hogy melyik videó hangja hallatszódjon. A képernyőn található még egy exportálás gomb is, amivel az összeszerkesztett videó állományt lehet letölteni.

## Funkcionális követelmények
A felhasználónak legyen lehetősége videókat kiválasztani valamint a kezdő és végpontokat beállítani az összesnél és méretet beállítani, valamint aktív és passzív hangsávokat tudjon megadni. Legyen még lehetőség a szerkesztett videó állomány letöltésére.

## A rendszer futása
Asztalról megnyitható program, futtatásához mindössze egy számítógépre van szüksége a felhasználónak. Platformfüggetlen(windows/ linux/ mac).

## Szükséges funkciók listája
| Modul | ID |Név | Leírás |
|---|---|---|---|
| Frontend| F1 | Videók hozzáadása| A felhasználó által kiválasztott videók hozzáadása|
| Frontend| F2 | Videók kezdetének és végének beállítása| A felhasználó által kiválasztott videók kezdő- és végpontjának beállítása |
| Frontend| F3 | Aktív és passzív hangsávok beállítása| A felhasználó által kiválasztott videók hangsávjának a beállítása checkboxokon keresztül | 
| Backend| F4 | Létrehozott videó állomány letöltése| Az összeolvasztott videó fájlt le lehessen tölteni |

## Rendszerre vonatkozó törvények, szabványok, ajánlások
- AZ EURÓPAI PARLAMENT ÉS A TANÁCS (EU) 2016/679 RENDELETE (2016. április 27.) a természetes személyeknek a személyes
adatok kezelése tekintetében történő védelméről és az ilyen adatok szabad áramlásáról, valamint a 95/46/EK irányelv 
hatályon kívül helyezéséről (általános adatvédelmi rendelet).


- 2011.évi CXII. törvény az információs önrendelkezési jogról és az információszabadságról.

- 1.§2 E törvény célja a hatálya alá tartozó tárgykörökben az adatok kezelésére vonatkozó alapvető szabályok 
meghatározása annak érdekében, hogy a természetes személyek magánszféráját az adatkezelők tiszteletben tartsák,
valamint a közügyek átláthatósága a közérdekű és a közérdekből nyilvános adatok megismeréséhez és terjesztéséhez
fűződő jog érvényesítésével megvalósuljon.
