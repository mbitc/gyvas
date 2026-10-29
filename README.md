# GYVAS — P2P Tinklo Intelektas & CID Variklis

> Decentralizuotas, lengvas ir poetiškas prototipas, jungiantis P2P mazgus per Nostr protokolą su deterministiniu CID (Content Identifier) skaičiavimo varikliu naršyklėje.

---

## 🌌 Apie Projektą

**GYVAS** — tai eksperimentinė erdvė, kurioje įrenginiai jungiasi be centrinių serverių. Kiekvienas mazgas talpina savo „atminties fragmentą“ (poeziją, kadro indeksą, dažnius), iš kurio naršyklės standartinė Web Crypto API (`SHA-256` + `Base58`) deterministiškai sugeneruoja unikalų **CID**. 

Sujungus mazgus per Nostr relę ar P2P interfeisą, sukuriamas gyvas rezonanso ir fragmentų mainų laukas.

---

## ⚙️ Technologinė Architektūra

- **Zero-Dependency Core:** Jokių išorinių sunkių NPM bibliotekų — viskas veikia grynuoju JavaScript, HTML5 Canvas ir Web Audio API.
- **Deterministinis CID:** Kanonizuoti JSON objektai keičiami į `SHA-256` baitų srautą ir užkoduojami IPFS stiliaus `z...` prefiksu.
- **Nostr Protokolas:** Pasaulinis arba lokalus įvykių mainų srautas per WebSocket reles (`kinds: 31337`).
- **Mobili Estetika:** Optimizuota pirštui, tamsi, analoginė-mistinė sąsaja su interaktyviu rezonanso lauku.

---

## 🚀 Paleidimas Kituose Įrenginiuose

Kadangi visa aplikacija sukoncentruota viename faile, ją paleisti kitoje naršyklėje ar mobiliajame telefone itin paprasta:

1. **Atsisiųsk arba nukopijuok** `index.html` failą į savo įrenginį.
2. **Atidaryk** jį bet kurioje šiuolaikinėje naršyklėje (Chrome, Safari, Firefox, Edge).
3. **Naudojimas:**
   - Spustelėk **„Simuliuoti Kaimyną“**, kad išbandytum tinklo sujungimo būseną.
   - Atidaryk **„Parametrus“**, redaguok poezijos fragmentą, stebėk realiu laiku generuojamą **CID** arba įvesk Nostr relės adresą (pvz., `wss://relay.damus.io`) ir transliuok savo genomišką žinutę kitiems mazgams.

---

## 📜 Licencija
Atviro kodo eksperimentas (MIT). Kurk, laužk ir augink tinklą toliau

git add README.md
git commit -m "docs: pridėtas išsamus README.md failas kitų įrenginių testavimui"
git push origin main.
