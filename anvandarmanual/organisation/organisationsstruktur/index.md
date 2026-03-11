---
templateKey: item-page
order: 0
title:Organisationsstruktur
date: 2026-03-01T21:42:14.193Z
---

# Organisationsstruktur

Organisationsstrukturen används för att beskriva **hur organisationer och verksamheter är uppbyggda i Ciso**.

Strukturen gör det möjligt att koppla ansvar, säkerhetskrav, risker och aktiviteter till rätt del av organisationen.

I Ciso består organisationsmodellen av två typer av objekt:

* **Organisationer (Org)**
* **Organisationsenheter (OU)**

Tillsammans används de för att modellera både **juridiska organisationer och den interna verksamhetsstrukturen**.

---

## Organisationer (Org)

Organisationer representerar **juridiska personer**.

Det kan till exempel vara:

* moderbolag
* dotterbolag
* kommunala bolag
* externa företag
* leverantörer

Varje Ciso-installation har normalt **en huvudorganisation (root-organisation)** som representerar organisationen som använder systemet.
Det går även att ha **flera parallella root-organisationer**.

Organisationer kan innehålla:

* andra organisationer
* organisationsenheter

Det gör det möjligt att modellera till exempel **koncernstrukturer** eller relationer mellan olika organisationer.

### Interna och externa organisationer

Organisationer kan klassificeras som **interna** eller **externa**.

Denna skillnad används bland annat för att:

* ställa olika **säkerhetskrav**
* skilja på **interna aktiviteter och leverantörsaktiviteter**
* genomföra **leverantörsgranskningar via leverantörsportalen**

---

## Organisationsenheter (OU)

Organisationsenheter används för att beskriva **hur en organisation är uppbyggd internt**.

Exempel på organisationsenheter kan vara:

* division
* avdelning
* team
* funktion

Varje OU har ett fält **Typ**, där man anger vilken typ av enhet det är.

Det gör att strukturen kan anpassas efter hur organisationen faktiskt är organiserad.

---

## Vad organisationsenheter används till

Organisationsenheter används i flera delar av Ciso. De kan till exempel:

* **äga andra objekt i systemet**
* användas som **tillgångar i riskanalyser**
* tilldelas **säkerhetskrav**

Det gör det möjligt att koppla säkerhetsarbete till **rätt del av verksamheten**.

---

## Regler i organisationsstrukturen

Det finns några grundläggande regler för hur strukturen byggs upp.

**Organisationer (Org)**

* kan ha andra organisationer som barn
* kan ha organisationsenheter som barn

**Organisationsenheter (OU)**

* kan endast ha andra OU som barn
* måste alltid ha en organisation som överordnad struktur

Det innebär att en OU alltid tillhör **en specifik organisation**.

---

## Exempel på struktur

Ett vanligt exempel kan se ut så här:

Organisation
└ Organisation (dotterbolag)
    └ OU – Division
        └ OU – Avdelning
            └ OU – Team

Det går att skapa **hur många nivåer av OU som helst**, beroende på hur detaljerad struktur organisationen vill ha.

---

## Relaterade artiklar

* Personer
* Befattningar
* Roller & behörigheter
