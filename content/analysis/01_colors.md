---
Title: Färganalys
Description: Sida för redovisning av Färganalys
---

Utvärdera webbplatsers färgval
=======================

I dennra rapport undersöks färgval och typografi för olika webbplatser.

Urval
-----------------------

Jag valde att undersöka webbplatserna för tre av de mest populära JavaScript-baserade SPA-ramverken, vilket är React, Angular och Vue. Valet av webbplatser baserades bland annat på att jag finner webbplatsernas innehåll väldigt intressant i sig men utöver det så ville jag även jämföra hur sidorna väljer att representera och kommunicera kring sin produkt ur typografi- och färgschemeperspektiv.

Metod
-----------------------

För denna analys så har jag använt mig av Chrome Developer Tools för att ta reda på vilka färger samt vilken typografi som webbplatserna använder sig av. Jag använde mig även av verktyget Adobe Color för att undersöka vilken typ att färgschema som användes.

Resultat
-----------------------
<b>Reacts</b> färgpalett: #DAFBF8, #282C34, #20232A

<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 50px; width: 50px; background-color: #DAFBF8">
<td style="height: 50px; width: 50px; background-color: #282C34">
<td style="height: 50px; width: 50px; background-color: #20232A">
</tr>
</table>

React har valt att använda sig av en ljusturkos accentfärg tillsammans med två nyanser av väldigt mörkblå färger som närmar sig svart. Webbplatsen har inget regelrätt färgschema men skulle till viss del kunna tolkas att ha en minimalistisk kompromiss någonstans mellan ett analogt och ett monokromatiskt färgschema gällande de två mörkblå färgerna.
Accentfärgen används sparsamt för att framhäva det mest huvudsakliga med webbplatsens syfte. I det här fallet så är det namnet på projektet, en knapp som tar en till dokumentationen samt en länk till en tutorial.

Den mörkare av de två mörkblå färgerna används som bakgrundsfärg för navbaren samt footern. Den ljusare av de två mörkblå färgerna används som bakgrundsfärg till hero-sektionen för webbplatsen.

Det typsnitt som används på webbplatsen är Segoe UI som tillhör kategorin Sans-serif. Detta gäller navbaren, de olika heading-elementen samt brödtexten. Undantaget är de kodexempel som finns på webbplatsen vilka i stället använder sig av typsnittet Menlo som även den tillhör kategorin Sans-serif.
Jag anser att webbplatsens färgval och typografi överensstämmer mycket bra med Reacts profil som projekt. Både webbplatsen och React som projekt bygger på minimalism och enkelhet. Den accentfärg som används på webbplatsen är dessutom samma färg som Reacts logga.

<b>Angulars</b> färgpalett: #0D47A1, #42A5F5, #1976D2, #C3002F, #DD0031

<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 50px; width: 50px; background-color: #0D47A1">
<td style="height: 50px; width: 50px; background-color: #42A5F5">
<td style="height: 50px; width: 50px; background-color: #1976D2">
<td style="height: 50px; width: 50px; background-color: #C3002F">
<td style="height: 50px; width: 50px; background-color: #DD0031">
</tr>
</table>

Webbplatsen använder sig av en linear-gradient som bakgrund för den övre delen av sidan. Denna gradient börjar från en mörkare blå färg (#0D47A1) och övergår till en ljusare blå färg (#42A5F5). Ytterligare en blå färg (#1976D2) används för headings på webbplatsen.

Två röda färger skulle kunna tolkas som accentfärger. Dessa är en mörkare röd (#C3002F) och en ljusare röd (#DD0031). Dessa förekommer dock nästan uteslutande i Angulars logga. Loggan används dock i flera sektioner på webbplatsen och kompletterar särskilt den blåa bakgrunden på ett väldigt slående sätt.

Webbplatsen har inget regelrätt färgschema men skulle till viss del kunna tolkas att ha en viss minimalistisk kompromiss mellan ett analogt och ett monokromatiskt färgschema gällande gradienten.

Typsnittet som används på webbplatsen är Roboto som tillhör kategorin Sans-serif. Detta gäller heading-element och brödtexten. Heading-elemeten har en aning tjockare font-weight jämfört med brödtexten.

Jag anser webbplatsens färgval och typografi återspeglar Angulars profil på ett bra sätt. Webbplatsen har en mer komplicerad, tyngre design (och färgpalett) än exempelvis Reacts webbplats. Detta återspeglar filosofin i de båda projekten då Angular är ett regelrätt ramverk som är mer komplext och kommer med mer funktionalitet out-of-the-box än React som snarare beskrivs som ett bibliotek som kräver ytterligare tredjepartsbibliotek för att uppnå samma tyngd och funktionalitet som Angular.

<b>Vues</b> färgpalett: #42B983, #475050

<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 50px; width: 50px; background-color: #42B983">
<td style="height: 50px; width: 50px; background-color: #475050">
</tr>
</table>

Webbplatsen är extremt minimalistisk gällande färger. En ljusare grön färg (#42B983) används som accentfärg för knapparna på webbplatsen samt även för tre headings som beskriver fördelarna med att använda sig av Vue som JavaScript-ramverk. Utöver detta så hittar vi en mycket mörk och något gråaktig turkos färg (#475050) i webbplatsens footer. Dessa två färger återspeglar färgerna i Vues logga. Webbplatsen använder sig inte av ett regelrätt färgschema.

Typsnittet som i huvudsak används av webbplatsen är Open Sans som tillhör kategorin Sans-serif. Detta typsnitt används både för headings och för brödtexten. För menyalternativen i navbaren används dock typsnittet Inter, som även den tillhör kategorin Sans-serif.

Jag anser att sidans mycket minimalistiska val av färger väl återspeglar Vues simplistiska designfilosofi som JavaScript-ramverk som går ut på enkelhet och en lätt foot-print. Typsnittet ger även ett modernt och enkelt intryck.

Analys
-----------------------

Ingen av de tre webbplatserna jag valde att analysera använder sig av regelrätta färgscheman enligt teoretisk modell. Detta trots att de är extremt populära webbplatser för projekt som har miljoner nedladdningar av deras respektive NPM-paket varje vecka. Detta kan anses vara något anmärkningsvärt ifall man lägger stor vikt vid implementering av de teoretiska modellerna för färgscheman. 

Jag anser att man här skulle kunna framföra argumentet att dessa modeller utgör en väldigt abstrakt vetenskap som till stor del lever ett eget liv utanför den verkliga realitet som existerar gällande de färgpaletter som faktiskt används av webbplatser.

I det här fallet så kan dock avsaknaden av implementering av nämnda modeller även bero på att webbplatserna som jag undersökt är av väldigt teknisk karaktär och i första hand vänder sig till mjukvaruutvecklare. Simpliciteten gällande val av färgpalett kan ses som ett sätt att framhäva det rent tekniska innehållet på webbplatserna samt även som en medveten strävan efter enkelhet. 

Det är dessutom utan tvivel ett intressant faktum i sammanhanget att det tyngsta och mer komplexa ramverket (Angular) även kan anses ha den mest komplexa sidan gällande design och färgpalett.

Vad gäller de förekommande typsnitten så kan vi konstatera att samtliga webbplatser använde sig av typsnitt tillhörande kategorin Sans-serif. Jag anser att detta är naturligt då typsnitt av denna kategori kan anses ha en väldigt modern och teknisk feel jämfört med Serif. En strävan efter och tyngd på modernitet är så klart mycket angelägen och möjligtvis helt naturlig när det kommer till webbplatser som tillhandahåller information och dokumentation kring några av världens mest populära JavaScript-ramverk.

Referenser
-----------------------

https://reactjs.org/

https://angular.io/

https://v3.vuejs.org/

https://color.adobe.com/


Övrigt
-----------------------

Analys skriven av G.C. (guco20)