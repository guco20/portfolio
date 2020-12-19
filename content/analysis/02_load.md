---
Title: Laddningstider
Description: Sida för redovisning av rapporten Laddningstider
---

Laddningstider för webbplatser
==========================

I denna rapport så har jag undersökt laddningstider av ett antal webbplatser och därefter dokumenterat resultateten av min analys.

Urval
-----------------------

Jag valde att analysera webbplatserna för Stockholms tre största fotbollsklubbar, det vill säga AIK, Hammarby IF samt Djurgårdens IF.

Metod
-----------------------

Under analysen så har jag använt mig av Chrome Developer Tools för att mäta laddningstiderna, antalet resurser som hämtas från sidan samt den totala storleken på de resurser som hämtas. Jag har även använt mig av Google PageSpeed Insights för att ta del av deras graderingsskala samt de förslag på förbättringar som de menar skulle kunna utföras för att uppnå ett bättre resultat.

Resultat
-----------------------

<a href="%assets_url%/Laddningstider.xlsx"><b>Excel-fil</b></a> med rådatat.

<b>AIK</b>

![AIK](%assets_url%/img/aik.jpg){.image .center}

AIK:s startsida fick graderingen 65 (desktop) samt 25 (mobile) av Google PageSpeed Insights. Laddningstiden uppmätt med Chrome Developer Tools blev 2.15 sekunder i snitt. Antalet resurser som laddades ner var 81 och hade totalt en storlek på 6 MB. 

Biljettsidan fick graderingen 70 (desktop) samt 30 (mobile) av PageSpeed Insights. Laddningstiden var i snitt 2.56 sekunder. Antalet resurser som hämtades var 52 och deras totala storlek uppgick till 5.4 MB.

Supportersidan fick graderingen 70 samt 31 av PageSpeed Insights. Laddningstiden var i snitt 1.75 sekunder. Antalet som hämtades var 100 och deras totala storlek var 8.2 MB.

Ur förbättringssynpunkt så kan jag konstatera att sidorna på AIK:s webbplats hade den gemensamma nämnaren att de använde sig av PNG-filer för bilder istället för exempelvis JPG-filer som bättre lämpar sig för komprimering. Bilderna kunde även ha storleksanpassats för att uppnå bättre laddningstider.


<b>Djurgårdens IF</b>

![DIF](%assets_url%/img/dif.jpg){.image .center}

Djurgårdens startsida fick graderingen 25 (desktop) samt 16 (mobile) av PageSpeed Insights. Laddningstiden blev 3.69 sekunder i snitt och antalet resurser som hämtades var 116. Storleken på resurserna uppgick till 9.1 MB.

Webbplatsens 2021-sida fick graderingen 42 samt 18 av PageSpeed Insights. Laddningstiden uppgick till 2.66 sekunder i snitt. Antalet resurser som hämtades var 119 och storleken på dessa uppgick till 15.8 MB.

Bli medlem-sidan fick graderingen 82 samt 34 av PageSpeed Insights. Laddningstiden blev i snitt 2.31 sekunder och antalet resurser som hämtades var 58. Storleken på resurserna uppgick till 5 MB.

Vad gäller möjliga förbättringar så kunde bilderna på startsidan storleksanpassas för att nå bättre laddningstider. Det fanns även ett antal PNG-filer som skulle kunna ersättas med JPG-filer för en mer optimal komprimering. De två resterande sidorna hade JavaScript-moduler som laddades ner men inte användes på sidorna. Dessa skulle kunna plockas bort och istället ”lazy loadas” när de väl behövs.


<b>Hammarby IF</b>

![Hammarby IF](%assets_url%/img/hammarby.jpg){.image .center}

Hammarbys startsida fick graderingen 46 (desktop) samt 2 (mobile) av PageSpeed Insights. Laddningstiden blev i snitt 2.98 sekunder och antalet resurser som hämtades ner var 257. Storleken på resurserna var 27.9 MB.

Köp biljetter-sidan fick graderingen 48 samt 6. Laddningstiden var i snitt 2.35 sekunder och antalet resurser som hämtades ner var 146. Storleken på dessa uppgick till 8.1 MB.

Säsongskort-sidan fick graderingen 35 samt 17 av PageSpeed Insights och laddningstiden uppmättes till i snitt 2.64 sekunder med Chrome Developer Tools. Antalet resurser som hämtades ner uppgick till 147 och storleken på dessa var 7.3 MB.

Samtliga sidor på Hammarbys webbplats skulle kunna förbättra laddningstiderna genom att byta ut sina bildfiler i PNG-format till ett mer komprimeringsvänligt format så som JPG. Bilderna borde även storleksanpassas. En annan förbättringsåtgärd vore att plocka bort JavaScript som inte används på sidorna.

Analys
-----------------------

Den vanligaste förbättringsåtgärden för att uppnå bättre laddningstider för samtliga webbplatser är att de skulle kunna hantera sina bilder på ett bättre sätt. I princip samtliga sidor använde sig till olika stor grad av bildfiler i PNG-format. Dessa skulle kunna ersättas med mer komprimeringsoptimala alternativ så som bilder i JPG-format. Bilderna kunde även storleksanpassas efter den storlek som de tar upp på sidorna för att på så sätt laddas snabbare.

En annan möjlig förbättringsåtgärd för flera av sidorna vore att bättre hantera JavaScript-modulerna och hur dessa läses in. Script som inte används på en sida bör heller inte laddas in för att där med nå en snabbare laddningstid. Flera olika JavaScript-ramverk erbjuder möjligheter till så kallad Lazy Loading vilket innebär att modulerna laddas in allt efter att de faktiskt används. Här skulle man kunna utföra en genomlysning av möjligheterna för att förbättra laddningstiderna via en Lazy Loading-strategi.

Resultatet för webbplatserna rangordnade efter snabbaste laddningstider uppmätta med Chrome Developer Tools blev följande:

1.	AIK
2.	Hammarby IF
3.	Djurgårdens IF

Google PageSpeed Insights rangordnade däremot webbplatserna en aning annorlunda:

1.	AIK
2.	Djurgårdens IF
3.	Hammarby IF

Vinnaren blev klart AIK:s webbplats som toppade båda skalor. När jag själv testar att ladda och navigera på webbplatserna uppfattar jag att den rangordning som uppmättes via Chrome Developer Tools stämmer bra. Personligen skulle jag säga att en laddningstid på cirka två sekunder kan anses vara ”snabb” och det är ungefär där som AIK:s webbplats även ligger gällande dess sidors laddningstider. Djurgårdens IF:s hemsida är den webbplats som jag upplever som långsammast i jämförelse med de två andra.

Referenser
-----------------------

www.aikfotboll.se

www.dif.se

www.hammarbyfotboll.se

https://developers.google.com/speed/pagespeed/insights/?hl=sv


Övrigt
-----------------------

Analys skriven av G.C. (guco20)