---
Title: Home
Description: Webbplatsdesign
---

Design och Webbplatser
=======================

I den här uppgiften ska jag analysera, sammanställa och utvärdera min egen sidas laddningstider.

Urval
-----------------------

På uppdrag av Organisationen Valfrihet ska jag göra en analys på laddningstider på min egen hemsida. 

Metod
-----------------------


För att få mina värden använder jag mig utav pagespeed Insights och Inspektera>Network i webbläsaren Chrome.
Jag har även wifi med en svarstid på 32.37 ms, en nedladdning på 28.74 MB och uppladdning på 5.55 MB enligt bredbandskollen. 

Resultat
-----------------------

<a style="color: blue; font-size: 2em" href="https://docs.google.com/spreadsheets/d/1gPk_CeVKrrJ7JmajDnKsZSd9GP5GkzkUwhR32eorwzw/edit?usp=sharing">Excel data</a>

Solstråles Advokatbyrå
-----------------------
<a href="../assets/img/soltråles.jpg">
<img height="200px" width="300px" src="../assets/img/soltråles.jpg">
</a>

Startsidan på mobil fick av Pagespeed Insights ett betyg 84 av 100 och på desktop 97. Storleken som laddades in var 540kB, antalet requests var 20 och laddningstidens medelvärde 0,497 sekunder. 

På about sidan så fick den betyget 99 på mobil och 98 på desktop. Storleken 640kB, antalet requests var 19 och en snittladdningstid på 0,672 sekunder. 

På highlight sidan så fick den ett betyg på 99 på mobil och 100 på desktop. Storleken var här 200kB, antalet requests var 12 och laddningstid 
0,552 sekunder.


Analys
----------------------

Enligt pageSpeed Insights så finns det en del saker man kan förbättra. En sak som verkar ta en del av laddningstiden är min Herobild. Då den är rätt stor så hinner det andra laddas in innan den är helt klar. Det skulle man kunna lösa genom att ladda in den först och sedan resten av innehållet. Jag tror att det är det för att jag valde att lägga width till 100% istället för att att sätta en fast bredd. Jag valde att göra det för att bilden skulle bli lite lättare att göra responsiv samtidigt som att sidan är rätt liten så att jag tänkte att det räckte att göra så istället för att ha många olika nivåer på responsiviteten. 
Man kan även spara lite på att ta bort oanvänd javascript och css. Men det är då väldigt lite skillnad det kommer att göra. 
Dessa problem jag har tagit upp nu är problem för mobilsidan. På desktop sidan så är de föreslagna förbättringarna mindre. Man kan optimera bilderna så att de laddas in lite bättre men det skulle inte spara så mycket tid och storleken skulle inte ändras så att man märker någon större skillnad. 

Storleken på sidorna är ungefär lika stor, skillnaden är på highlight sidan som inte har några bilder och då blir rätt mycket mindre. Antalet request är även mindre på den sidan av samma anledning. 

Ska jag rangordna dessa sidor på laddningstider så blir det såhär:
    1. Highlight sidan
    2. About sidan
    3. Hem sidan

Det blir såhär för att det är i den ordningen de rankas av både pagespeed Insights och av hur snabbt de laddas in. Men det är även viktigt att tänka på att Hem sidan är den sida med mest innehåll och highlight sidan har minst innehåll.

Så om jag skulle ta med innehållet kontra laddningstidena så blir det istället såhär:
    1. Hem sidan
    2. About sidan
    3. Highlight sidan


Referenser
-----------------
https://developers.google.com/speed/pagespeed/insights/

http://www.student.bth.se/~jopt19/dbwebb-kurser/design/me/kmom10/

http://www.student.bth.se/~jopt19/dbwebb-kurser/design/me/kmom10/about

http://www.student.bth.se/~jopt19/dbwebb-kurser/design/me/kmom10/highlight

https://docs.google.com/spreadsheets/d/1gPk_CeVKrrJ7JmajDnKsZSd9GP5GkzkUwhR32eorwzw/edit?usp=sharing

Övrigt
-----------------
Jonatan Pettersson


