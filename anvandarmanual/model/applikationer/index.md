---
templateKey: item-page
order: 4
title: Applikationer
date: 2025-09-03
---

Applikationer representerar de system och tjänster som används i organisationens verksamhet. En applikation kan till exempel vara ett verksamhetssystem, en molntjänst eller en teknisk komponent i ett större system.

Applikationer används i modellen för att visa **i vilka system information behandlas och vilka system som stödjer organisationens processer**.

## Applikationer i modellen

Applikationer kopplas till andra objekt i modellen för att beskriva hur verksamheten stöds av teknik.

Exempel på relationer är:

- en **process använder en applikation**
- en applikation **behandlar informationsobjekt**
- en applikation **driftsätts i en teknisk miljö**
- en applikation **tillhandahålls av en leverantör**

Genom dessa kopplingar kan organisationen se hur verksamhet, information och teknik hänger ihop.

## Struktur och komponenter

Applikationer kan organiseras hierarkiskt. Det innebär att en applikation kan bestå av flera underliggande komponenter eller delsystem.

Det gör det möjligt att modellera till exempel:

- ett övergripande system
- flera moduler eller tjänster
- tekniska komponenter

Organisationen kan själv välja hur detaljerad strukturen ska vara.

## Infrastruktur

Applikationer kan kopplas till den tekniska miljö där de körs. I Ciso modelleras infrastrukturen genom **platser och enheter**.

### Enheter

En enhet representerar en teknisk komponent, till exempel:

- klient  
- server  
- nätverksenhet  
- annan teknisk enhet  

### Platser

En plats beskriver var infrastrukturen finns och kan vara:

- en fysisk plats  
- en virtuell plats  
- ett nätverk  

Genom att koppla applikationer till platser och enheter kan organisationen beskriva sin tekniska miljö.

## Informationsklassificering

Applikationer kan klassificeras utifrån informationssäkerhet enligt:

- konfidentialitet  
- riktighet  
- tillgänglighet  
- spårbarhet  

Klassningen kan sättas direkt på applikationen eller härledas från informationsobjekt som behandlas i applikationen.

## Verksamhetskritikalitet

Applikationer kan också få en **verksamhetskritikalitet** genom de processer där applikationen används.

På så sätt går det att identifiera vilka system som är kritiska för verksamheten.

## Leverantörer

Applikationer kan kopplas till en **leverantör**. Leverantören kan till exempel vara systemleverantör, driftleverantör eller molnleverantör.

Genom kopplingen mellan applikation och leverantör blir det möjligt att analysera organisationens beroenden till externa parter.

## Ägarskap

Applikationer kan ha en **ägare**. Ägaren kan vara en person eller en befattning i organisationen.

Ägarskapet används för att tydliggöra ansvar för systemet och underlätta uppföljning och styrning.

## Modellering i praktiken

Applikationer kan modelleras på olika sätt beroende på organisationens behov. Vissa organisationer beskriver sina system på en övergripande nivå, medan andra delar upp systemen i flera komponenter.

Modellen i Ciso stödjer båda arbetssätten och gör det möjligt att beskriva både verksamhetens system och den tekniska miljön de körs i.