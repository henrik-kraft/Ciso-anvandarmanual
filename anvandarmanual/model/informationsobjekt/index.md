---
templateKey: item-page
order: 2
title: Informationsobjekt
date: 2025-06-03
---

Informationsobjekt beskriver vilken information organisationen hanterar i sina processer. Ett informationsobjekt representerar en typ av information, till exempel ett register, en handling eller en informationsmängd.

Genom att modellera informationsobjekt blir det möjligt att analysera hur information används i verksamheten och i vilka system den behandlas.

## Informationsobjekt i modellen

Informationsobjekt kopplas till andra delar av modellen för att visa hur informationen används i verksamheten.

Exempel på relationer är:

- en **process** hanterar ett eller flera informationsobjekt  
- en **applikation** behandlar informationsobjekt  
- infrastrukturen och leverantörer som används av applikationen blir därmed indirekt kopplade till informationen  

På så sätt går det att se hur informationen rör sig genom organisationens verksamhet och teknik.

## Attribut

Informationsobjekt kan innehålla **attribut** som beskriver vilka uppgifter som ingår i informationen.

Exempel på attribut kan vara:

- namn  
- personnummer  
- adress  
- ärendenummer  

Attribut kan klassificeras separat och används för att beskriva informationen mer detaljerat.

Organisationen kan själv definiera vilka attribut som ska finnas för ett informationsobjekt.

## Informationsklassning

Informationsobjekt och dess attribut kan klassificeras utifrån organisationens krav på informationssäkerhet.

Klassningen sker enligt:

- **K** – konfidentialitet  
- **R** – riktighet  
- **T** – tillgänglighet  
- **S** – spårbarhet  

Klassningen används som underlag för riskanalyser, säkerhetskrav och andra säkerhetsåtgärder.

## Personuppgifter

Ett informationsobjekt kan markeras som innehållande **personuppgifter**. Detta används bland annat som underlag för organisationens **register över personuppgiftsbehandlingar enligt GDPR (artikel 30)**.

Informationen kan även användas för att styra säkerhetskrav, analyser och aktiviteter kopplade till personuppgiftshantering.

## Ägarskap

Informationsobjekt kan ha en **ägare**. Ägaren kan vara en person eller en befattning i organisationen.

Ägarskapet används för att tydliggöra ansvar för informationen och för att underlätta uppföljning och styrning.

## Handlingstyper

En **handlingstyp** är en form av informationsobjekt. Handlingstyper används ofta för att beskriva informationsmängder i dokument- och ärendehantering.

## Modellering i praktiken

Informationsmodellen i Ciso kan användas på olika nivåer av detalj.

I vissa delar av modellen kan organisationen beskriva information på en övergripande nivå, medan andra delar kan modelleras mer detaljerat. Båda angreppssätten kan användas samtidigt beroende på behov.

## Rekommenderad modellering av personrelaterad information

En vanlig och rekommenderad praxis är att modellera olika typer av personer som separata informationsobjekt.

Exempel på sådana informationsobjekt kan vara:

- kund  
- anställd  
- konsult  
- patient  
- medborgare  
- nära anhörig  

Genom att modellera dessa informationsobjekt och definiera deras attribut blir det enklare att identifiera vilka personuppgifter organisationen hanterar. Detta förenklar arbetet med dataskydd och GDPR.