# JavaScriptExam-A 🔱
Yellow Flower's Bloom 🟡 Welcome! This is my first uploaded JavaScipt exam for education. ⚡️
Made by Koni. 
![image](https://github.com/nikkeisadev/JavaScriptExam-A/assets/137056695/05cc4e3a-49a2-4460-a4b5-a9b938426e9d)
## The Exam's Description 🌟
The description is writen in Hungarian, so if ya can't read it, just use Google.
Also it's possible that the translation will contain missunderstandings too...
### 1. Game Recommender 
![Screenshot from 2023-11-29 20-25-25](https://github.com/nikkeisadev/JavaScriptExam-A/assets/137056695/a7526925-b8f5-4408-9e08-4c13eb5431e7)
Több ismerősöd is megkeresett azzal, hogy játékokat ajánlj neki. Mivel most már annyi kérést kaptál, hogy nehéz átlátni. Ennek segítésére azt találtad ki, hogy összedobsz egy gyors weblapot, amely a következők szerint működik:
• Lehessen egy legördülő listával (vagy bármilyen más módszerrel) választani játékok listájából (legyen legalább 5 játék)!
• A megfelelő elem kiválasztása után (lehet gombra kattintás után vagy rögtön a listaelem kiválasztása után) a játék címe, rövid leírása töltődjön be egy div-ben, és lehessen választani 2 lehetőség közül: ajánlott vagy nem ajánlott. Ha időd marad a végén a dolgozatnak, akkor a játék borítóját is beleteheted, de ezt hagyd a végére, csak ha időd marad!
• A játék címét, és adatait próbáld meg úgy megoldani, hogy nem statikusan helyezed el az oldalra, hanem pl. listába tárolod el az adatokat, és onnan olvasod ki!
• A megfelelő értékelés kiválasztása esetén mentsd el, hogy ha a listából más elemet választasz ki, és visszatérsz hozzá, megmaradjon a döntés!
### 2. Snowfall
![image](https://github.com/nikkeisadev/JavaScriptExam-A/assets/137056695/2dafb4a5-81ac-4e86-8af1-0063652f656d)
Több külföldi városban is télen problémát okoz az óriási havazás. A hómennyiség mérésére a későbbiekben lesznek majd eszközök, amelyek valós információt szolgáltatnak, de most jelenleg még a módszer kidolgozását véletlen számok generálásával fogod szimulálni.
Feladatod a következő:
• Legyen az oldalon egy „generálás” gomb, amelyre kattintva Bootstrap rács segítségével kis kijelzőn 4 oszlopban, közepes vagy nagyobb kijelző esetén 4 oszlopban a program generál 20 város jelenlegi hómennyisége mm-ben. A mennyiségek értékei 40 és 120 cm között legyenek!
• Az értékek kiírásánál a 100 cm feletti mérések pirossal jelenjenek meg, a többi érték az alapértelmezett színnel (vagy amit választasz).
• Legyen egy másik gomb is, amelynek hatására a hómennyiségek a [-10,10] zárt intervallum értékei között változnak véletlen szám generálásával, amely a növekedés mértékét jelenti! Tehát ha pl. -10-et kapsz, akkor a hómennyiség mértéke 10-zel csökken. Minden városnál külön értéket generálj! A generálás után ugyanazzal a szabállyal írd ki újra az értéket, mint az előbb!
### 3. Roguelite Game
![Screenshot from 2023-11-29 22-52-25](https://github.com/nikkeisadev/JavaScriptExam-A/assets/137056695/d7f9e657-6ab3-4972-8fa7-7769cded38d2)
Manapság népszerűek a „Roguelite” típusú játékok, amely azt jelenti, hogy a játék szereplőivel minél tovább próbálod a játékot elvinni, és ha legyőzik a főszereplőket, akkor az elejétől kell kezdeni a játékot. Itt azonban mindig valamit átviszel az előző végigjátszás alkalmával, hogy könnyebb legyen a következő. Ki szeretnéd próbálni, hogy milyen kihívásokkal jár ilyen játék készítése, de ehhez még az első lépést kell megtenned, ahol a következőket kell megoldanod:
◦ A játékban van a játékos és van az ellenfél, akit le kell győzni. A játékos és az ellenfél életereje (HP) 200-ról indul, a játékos ereje 20-ről indul, az ellenfél ereje fixen mindig 40.
◦ A weblapon legyen egy gomb, „játék indítása”, aminek segítségével az életerők az alapértelmezett 200-ra, és a játékos ereje 20-ra lesz állítva.
◦ Legyen egy másik gomb, „támadás”, aminek hatására a játékos és ellenfél is támad. Mind a játékos és az ellenfél sebzése véletlen számmal lesz generálva erő és erő*2 között (határokat beleértve). A sebzés értékét le kell vonni az életerőből.
◦ Ha a játékos életereje 0, vagy 0-nál kevesebb, akkor új kör indul, aminek hatására a játékos és ellenfél életereje újra 200 lesz, DE itt a játékos előző erő értéke 10-zel növekszik a játék elején (tehát pl. a második végijátszásnál már 20). Ezzel nyilván a sebzése is megnövekszik.
◦ Ha az ellenfél életereje 0 vagy kevesebb, a játék vége. Írd ki a végén, hogy mennyi kör volt szükséges, hogy legyőzd az ellenfelet!
