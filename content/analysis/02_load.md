---
Title: Load
Template: colorReports
---
Laddningstid och användbarhet
=======================

Syftet med denna uppgift är att analysera tre stycken olika webbplatsers laddningstid och användbarhet för att därefter analysera om det finns delar på sidan som kan förbättra de båda delarna.

Urval
-----------------------
De wepplatser jag har valt att undersöka tillhör tre stycken olika nyhetskällor:
- <a href= "https://www.aftonbladet.se/">Aftonbladet</a>
- <a href= "https://www.dn.se/">Dagens Nyheter</a>
- <a href= "https://www.mitti.se/">Mitt i Stockholm</a>

Jag valde dessa webbsidor eftersom nyhetskällor ofta har stort innehåll med många bilder och därav skulle det vara intressant att ta reda på hur lång tid sidornas laddningstid är. Jag valde två stycken olika kvällstidningar (Aftonbladet och Expressen) och en lokaltidning (Mitt i Stockholm) för att kunna se om de olika publikationerna spelar någon roll i laddningstiden och användbarheten.

Metod
-----------------------
För att kunna besvara syftet använder jag googles verktyg "<a href="https://pagespeed.web.dev/?utm_source=psi&utm_medium=redirect">PageSpeed Insight</a>" till min hjälp för både Desktop och Mobile. Den sidan mäter av laddningstiden på olika webbplatser och kommer med förslag på förbättringar. Webbläsarens DevTools används för att mäta laddningstiden, sidans storlekt i Mb och hur mycket som skickas. Laddningstiden mäts tre gånger för att sedan ta ut medelvärdet. För att dokumentera datan jag samlar in använder jag "Google Kalkylark".

Resultat
-----------------------
<h3>Statistik från Google Page Speed:</h3>
<div class="spreadsheet">
    <iframe title="Google page speed" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTVM3BB5x4QEPWSR7Bv0AnHsCN6-E9FetuGSghYyKxSzWxt4-lkugDFqDyBNiskxfLoAqFQdpWMrRal/pubhtml?widget=true&amp;headers=false"></iframe>
</div>

<h3>Statistik från devtools:</h3>
<div class="spreadsheet">
    <iframe title="Devtools" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRI1iO0I4WbQeDvz-dw1Ab3BjzWVDXY2hcCar9ZCAo-KKvFse8LoWADReJM4E315iSmBWF_pECy-XMv/pubhtml?widget=true&amp;headers=false"></iframe>
</div>

<h3 class="center-font">Aftonbladet</h3>
<img src= "%base_url%/image/aftonbladet.jpg" alt= "Aftonbladet" class="color-img">

Förslag på förbättringar (Mobilt):
<ul>
    <li>Reducera JavaScript som inte används
    <li>Använd bilder med rätt storlek
    <li>Aktivera textkomprimering
</ul>

Förslag på förbättringar (Desktop):
<ul>
    <li>Reducera JavaScript som inte används
    <li>Använd bilder med rätt storlek
    <li>Skicka bilder i modernare bildformat
</ul>

<h3 class="center-font">Expressen</h3>
<img src= "%base_url%/image/expressen.jpg" alt= "Expressen" class="color-img">

Förslag på förbättringar (Mobilt):
<ul>
    <li>Reducera JavaScript som inte används
</ul>

Förslag på förbättringar (Desktop):
<ul>
    <li>Reducera JavaScript som inte används
</ul>

<h3 class="center-font">Mitt i Stockholm</h3>
<img src= "%base_url%/image/mitti.jpg" alt= "Mitt i Stockholm" class="color-img">

Förslag på förbättringar (Mobilt):
<ul>
    <li>Reducera JavaScript som inte används
    <li>Ta bort resurser som blockerar renderingen
    <li>Reducera CSS som inte används
    <li>Skjut upp inläsningen av bilder som inte visas på skärmen
    <li>Koda bilder effektivt
</ul>

Förslag på förbättringar (Desktop):
<ul>
    <li>Reducera JavaScript som inte används
    <li>Ta bort resurser som blockerar renderingen
    <li>Reducera CSS som inte används
    <li>Skjut upp inläsningen av bilder som inte visas på skärmen
</ul>

Analys
-----------------------
Analys av förbättringar - 
Alla tre sidor har som förslag på förbättringar att reducera JavaScript som inte används. Ofta var det upp emot 1 sekund extra det tog att ladda in sidan på grund av överflödig JavaScript. Just bildstorlek/format är också en faktor som drar ner laddningstiden och användbarheten på sidorna.

Något som tog upp mycket i laddningstiden var reklamen på alla webbplatser. På alla tre dök det först upp annonser som man behövde klicka bort för att komma vidare till den "riktiga" sidan. Eftersom alla tre hade dessa annonser var det svårt att jämföra hur stor skillnaden skulle bli om en sida inte hade en reklam och hur stor påverkan blev. Detta kan vara ett förslag till framtida forskning. 

Vinnaren är helt klart Expressen som både vann i Page Speed och Devtools. Webbplatsen har minst Mb i resources vilket kan vara en bidragande faktor att sidan laddas snabbare (genomsnittet 3,30 s). I prestanda i Page Speed landar Expressen på 53 på mobil och 92 på desktop vilket var en ganska markant skillnad från de andra webbplatserna. På andra plats skulle jag vilja sätta Aftobladet även att Mitt i Stockholm fick bättre resultat i prestanda och speed index på Google Speed. Aftonbladet hade lägre laddningstid och inte alls lika många förslag på förbättringar som Mitt i Stockholm. Dock skulle jag säga att de båda sidorna har både för- och nackdelar som väger upp varandra vilket gör att det är mycket jämnt mellan dem.

En anledning till att Mitt i Stockholm kanske inte har lika höga poäng i laddningstid och användbarhet kan vara för att det är en sida som kanske inte lika många personer besöker som Aftonbladet och Expressen och därav inte behövs utvecklas lika snabbt.

Slutsats
-----------------------
Efter att ha analyserat dessa tre webbplatser och satt mig in i dess laddningstid har jag kommit fram till att ca 3 sekunder skulle jag vilja säga uppfattar som en snabb webbplats. Det är bara Expressen som uppfyller det kravet enligt DevTools och när jag går in på de olika sidorna märker jag skillnad på att det tar lite längre tid för de andra att läsas in och kan upplevas som lite mer långsamma, dock inget som störs så pass mycket.

Referenser
-----------------------
  
<i>Länkar till de analyserade webbplasterna:</i>
- <a href= "https://aftonbladet.se/">Aftonbladet</a>
- <a href= "https://expressen.se/">Expressen</a>
- <a href= "https://www.mitti.se/">Mitt i Stockholm</a>


Övrigt
-----------------------
Skriven av: Emmie Fahlström