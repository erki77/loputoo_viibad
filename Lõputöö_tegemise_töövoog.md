Lõputöö tegemise töövoog
===

# 1. Agendipõhine (Agentic AI) töövoog lõputöö koostamiseks

Alljärgnev juhis kirjeldab efektiivset töövoogu, kus lõputöö luuakse tervikuna tehisintellekti agentide poolt. Inimese roll selles protsessis on seada piirid, määrata valmisoleku kriteeriumid, tagada sisendandmete kvaliteet ning valideerida lõpptulemus.
**Eeldus:** Teil on olemas toorkujul tulemused, mida tahate töös esitleda (nt puhastatud koodibaas, küsitluste andmestikud, metoodika märkmed).

## Tööprotsess

**1. Ettevalmistus ja repositooriumi seadistamine**
Kloonige lõputöö viipade ja kontrollide Giti repositoorium oma arvutisse.

**2. Agentse arendusvahendi seadistamine ja oskuste loomine**
Käivitage kaasaegne failisüsteemile ligipääsu omav agentse arenduse vahend (nt OpenAI Codex, Claude Code või Antigravity). Laske vahendil töötada kloonitud repositooriumi viibad ümber oma spetsiifilisteks oskusteks / pistikuteks / laiendusteks. Need uued oskused annavad agendile võimekuse muuta otse Teie lõputöö faili, lähtudes akadeemilistest nõuetest.

**3. Dokumendi baasstruktuuri loomine**
Looge ise lõputöö dokumendi põhi, mis sisaldab muuhulgas esialgset sisukorda. Kuna kaasaegsed agendid suudavad edukalt lugeda ja muuta erinevaid formaate, võite kasutada endale sobivaimat lahendust, olgu selleks `.docx` (Microsoft Word) või LaTeX (`.tex`).

**4. Konteksti ja andmete sidumine**
Tagage, et agent saab lugeda ja muuta loodud dokumendi põhja ning pääseb ligi loodud koodibaasile või mis tahes muudele toortulemustele, mida soovite töös esitleda (nt küsitluste tulemused).
Sisestage viibas (või agendi seadistustes) järgmised Teie tööd suunavad algparameetrid:
*   **Õppetase:** [SISESTA ÕPPETASE (nt Bakalaureus / Magister)]
*   **Lõputöö maht (EAP):** [SISESTA EAP-de ARV, nt 12, 15, 30]
*   **Lõputöö põhiosa maksimaalne pikkus lehekülgedes:** [SISESTA PÕHIOSA MAX LK ARV]
*   **Ülikool ja teaduskond:** [SISESTA ÜLIKOOL JA TEADUSKOND]
*   **Õppekava ja kood:** [SISESTA ÕPPEKAVA JA KOOD]
*   **Õppekava eesmärgid:** [SISESTA ÕPPEKAVA EESMÄRGID]
*   **Cum laude võimalus:** [JAH / EI]

**5. Autonoomne genereerimine ja automaatkontroll**
Andke agendile käsk täiendada ja kirjutada lõputöö dokumenti nii kaua, kuni dokument on terviklikult valmis ning ükski repositooriumi kataloogis "04" olevatest kontrollviipadest ei leia tekstis enam ühtegi viga. Agent itereerib ja parandab tööd iseseisvalt vastavalt nendele kontrollidele.

**6. Inimpoolne valideerimine ja ristkontroll**
Kui agent raporteerib, et töö on valmis, on Teie kohustus tulemus valideerida:
*   Loete tulemuse ise mitu korda põhjalikult läbi.
*   Kontrollite RANGELT üle kõik viited ja allikatele omistatud väited.
*   Lasete valminud tulemust hinnata ja auditeerida erinevatel teistel keelemudelitel, kasutades selleks kataloogis "04" leiduvaid kontrollviipasid, et tagada maksimaalne kvaliteet ja objektiivsus.



# 2. Töö loomine väikeste sammudega

> 💡 **Märkus:** Käivitage siin toodud järjekorras viipasid, mis on nimetatud vastavates kataloogides.

## Kataloog 01: Ideede genereerimine
* **Ideede_genereerimine**
* **Uurimisküsimuste_genereerimine** *(sisend: parimaks peetud idee)*

## Kataloog 02: Ülesandepüstitus
* **Ülesandepüstituse_genereerimine** *(sisend: idee ja uurimisküsimused)*

## Kataloog 03: Töö struktuur ja planeerimine
* **Sissejuhatus** *(sisend: ülesandepüstitus)*
* **Sisukord** *(sisend: ülesandepüstitus)*
* **Eksperimendi_plaan** *(sisend: ülesandepüstitus)*
* **Valideerimise_plaan** *(sisend: ülesandepüstitus)*
* **Seotud tarkvara** *(sisend: ülesandepüstitus)*

---

### ✍️ Töö sisu osa tegemine (kirjutamise faas)

**Vajadusel rakendatavad viibad:**
* **AHP_kriteeriumid_alternatiivid** *(sisend: ülesandepüstitus)*
* **Suured_keelemudelid** *(sisend: lõputöö mustand)*
* **Riskid** *(sisend: lõputöö mustand)*
* **Veebiküsitlus_intervjueerimine** kataloogi viibad *(sisend: lõputöö mustand)*

### 📝 Mustandi täiendamine ja kohustuslikud osad
*(Kõigi alljärgnevate viipade sisendiks on lõputöö mustand, välja arvatud juhul kui on märgitud teisiti)*

* **Uudsus** – *Alus töö edasiseks täiendamiseks.*
* **Töö struktuur** – *Tulemus lisatakse sissejuhatusse.*
* **Huvitatud osapooled** – *Tulemus lisatakse analüüsi peatükki.*
* **Piirangud** – *Tulemus lisatakse analüüsi peatükki.*
* **Arengusuunad** – *Tulemus lisatakse analüüsi peatükki.*
* **Litsenseerimine** – *Tulemust tuleks kajastada tulemuste peatükis, et tuua välja, millised töö tulemused tehakse kõigile avalikuks, millise litsentsiga ja miks just sellisega.*
* **Lühendite ja mõistete sõnastik**
* **Annotatsioonid**
* **Kokkuvõte**
* **Lõputöö pealkiri**
* **TI kasutuse deklaratsioon** *(sisend: info TI abil genereeritud töö osadest)* – *Tulemuse võiks panna metoodika peatükki tööriistade kasutuse juurde.*

## Kataloog 04: Kontrollimine
1. Kõigepealt kontrolli tööd **kõigi** viipadega kataloogist **"Konkreetsed vead"**.
2. Kataloogist **"Üldisem tagasiside"** kasuta **vähemalt** järgmisi viipasid:
   * **Eelkaitsmise täiendused**
   * **Retsensent kompaktne**
   * **Kõrvaltvaataja pilk**