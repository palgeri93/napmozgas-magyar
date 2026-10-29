# Napmozgás – magyar szimulátor

A `sunmotions.swf` (sunMotions068, 2010. szeptember 24.) magyar adaptációja. A HTML-oldal a helyi Ruffle JavaScript/WebAssembly lejátszóval futtatja az eredeti szimulációt; nem teljes JavaScript-újraírás.

## Használat

A GitHub Pages oldalon közvetlenül fut. Helyben Windows alatt az `inditas.cmd` indítja (Python 3 szükséges). Másik lehetőség: `python -m http.server 8000`, majd `http://localhost:8000/`. A HTML közvetlen, fájlként történő megnyitása helyett HTTP-kiszolgáló kell.

Állítsd be a földrajzi szélességet, a dátumot és az időpontot az Idő és hely panelen. Az Indítás gombbal futtatható az animáció. A folyamatos mód az idő múlását, a naponkénti mód ugyanazon napszak éves változását mutatja. A sebesség külön állítható. A Nap húzásakor a kiválasztott beállítástól függően az időpont vagy a dátum változik. A horizontábra háttere húzással forgatható.

Bekapcsolható az égi egyenlítő, az ekliptika, a napi út, az éggömb alsó fele, a megfigyelő és árnyéka, valamint az analemma. A részletes adatok között napmagasság, azimut, deklináció, rektaszcenzió, óraszög, csillagidő és időegyenlet is szerepel.

## Magyar adaptáció és forrás

Magyar feliratok, súgó, névjegy, hónapnevek, égtájak, vezérlők és dinamikus kijelzések. É = észak, D = dél, K = kelet, Ny = nyugat. A sebesség egységei perc/mp, óra/mp vagy nap/mp. Az eredeti 12 órás kiegészítő időformátum AM/PM jelölése megmarad; a beállítható idő 24 órás.

Eredeti: [Nebraska Astronomy Applet Project](https://astro.unl.edu/). A támogatási adatok és az eredeti engedély magyar szövege a névjegyben megtalálható. Az eredeti engedély nem kereskedelmi, változatlan felhasználást említ; a fordítás nem terjeszti ki az eredeti engedélyt. Az eredeti program jogai az eredeti jogosultaknál maradnak. Ez nem az eredeti alkotók hivatalos magyar kiadása.

A modell szemléltető tananyag. Az eredeti csillagászati számításokat és kezelési módokat megtartottuk. A fordítási jegyzéket a `forditas.json` tartalmazza.

Ruffle: MIT / Apache-2.0; a licencek a `ruffle` mappában találhatók.
