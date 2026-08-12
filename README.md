# Napi Kivitelezési Asszisztens – V2 javított

A működő V1 alapjára épített, szélesebb szakmai munkafolyamat-listát tartalmazó prototípus.

## Mit tud?
- Több munkafolyamat egy napon.
- Nincs időpont- vagy időtartam-megadás.
- A kiválasztott munkák szerszám- és anyagjavaslatai összevonódnak.
- Ismétlődő tételek csak egyszer jelennek meg.
- Minden tétel külön kipipálható.
- Saját szerszám és saját anyag hozzáadható.
- Regisztráció nélkül használható.
- A napi kiválasztások a böngészőben helyben mentődnek.
- Saját ikon és webapp manifest is van benne.

## Munkafolyamatok
Falazás, Vakolás, Betonozás, Zsaluzás, Bontás, Szigetelés, Hőszigetelés, Vízszigetelés, Burkolás, Padloponozás / aljzatkiegyenlítés, Glettelés, Festés, Színezés, Profilozás, Gipszkartonozás, Állványozás, Térkövezés, Aljzatbetonozás, Betoncsiszolás, Fúrás / vésés, Nyílászáró körüli javítás, Kőműves javítások, Tereprendezés, Anyagmozgatás, Takarítás / munkaterület-rendezés.

Az egyes listák szakmai alapjavaslatok; nem kötelező előírások. A felhasználó dönt minden tételről.


## Ikonok
A projekt saját kivitelezési asszisztens ikont használ: `icons/favicon.svg` a böngészőfülhöz, `icon-192.png` és `icon-512.png` a telefonos/PWA telepítéshez. A `manifest.webmanifest` és az `index.html` ezekre közvetlenül hivatkozik.
