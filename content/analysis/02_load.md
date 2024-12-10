---
Title: Load
Description: This is our load page.
Template: color
---

Load Rapport
=======================

Hemsidor
------------
Hemsidorna jag har valt är U.GG, OP.GG och Wikipedia.
Jag valde U.GG och OP.GG för båda sidorna har samma syfte och är hyfsat lika så ville se vad skillnaden på dem och vad som gjorde en snabbaren än den andra, sedan ville jag även ha en vanlig populär sida som jag kunde jamföra och då tyckte jag wikipedia var perfekt, en ganska simpel sida som används av många.

Metoder
--------------

Metoderna jag använde i denna undersökningen var, f12 (högerklick -> inspektera), google sheets och hemsidan pagespeed.
Jag använde dem här verktyg för att kolla hur snabbt hemsidorna laddade och vad de är som gör att de tar sån tid.

Wikipedia
=======================
<img src='../image/WIKI-START.PNG' alt='hejsan' width='800'>


Wikipedia Mobil Prestanda
------------

<a href='https://pagespeed.web.dev/analysis/https-sv-wikipedia-org-wiki-Portal-Huvudsida/1rqnz6cl7y?form_factor=mobile'>
<img src='../image/Wiki-Phone.PNG' alt='hejsan' width='800'>
</a>

Wikipedia Desktop Prestanda
------------

<a href='https://pagespeed.web.dev/analysis/https-sv-wikipedia-org-wiki-Portal-Huvudsida/1rqnz6cl7y?form_factor=desktop'>
<img src='../image/Wiki-DESKTOP.PNG' alt='hejsan' width='800'>
</a>


Vad som kan fixas för att göra Wikipedias sida snabbare
------------
Wikipedias sida var väldigt snabb redan så de var inte så mycket som kunde göra den snabbare men en sak som kunde göra att sidan blev ännu snabbare var att skicka bilderna med ett modernt bildformat.


U.GG
=======================

<a href=''>
<img src='../image/U-GG-START.PNG' alt='hejsan' width='800'>
</a>

U.GG Mobil Prestanda
------------
<a href='https://pagespeed.web.dev/analysis/https-u-gg/nkihyima3w?form_factor=mobile'>
<img src='../image/U-phone.PNG' alt='hejsan' width='800'>
</a>

U.GG Desktop Prestanda
------------
<a href='https://pagespeed.web.dev/analysis/https-u-gg/nkihyima3w?form_factor=desktop'>
<img src='../image/U-Desktop.PNG' alt='hejsan' width='800'>
</a>

Vad som kan fixas för att göra U.GG sida snabbare
------------
U.GG sida fick ganska dåliga prestandas betyg de som kan fixas för att göra sidan snabbare var Moderna bildformat, minska körningstiden för Javascript och pop up där dem frågar ifall dem får spara och använda din personliga data.

Op.GG
=======================
<img src='../image/OP-START.PNG' alt='hejsan' width='800'>

OP.GG Mobil Prestanda
------------
<a href='https://pagespeed.web.dev/analysis/https-www-op-gg/kiefc71a0m?form_factor=mobile'>
<img src='../image/OP-Phone.PNG' alt='hejsan' width='800'>
</a>

OP.GG Desktop Prestanda
------------

<a href='https://pagespeed.web.dev/analysis/https-www-op-gg/kiefc71a0m?form_factor=desktop'>
<img src='../image/OP-Desktop.PNG' alt='hejsan' width='800'>
</a>

Vad som kan fixas för att göra OP.GG sida snabbare
------------
OP.GG fick också ganska dåliga prestandas betyg, en sak som dem kunde fixa var en reklam i headern som man kunde stänga ner om man klicka på x på den, men sen även saker som minska körningstiden på javascript, ha bilder i rätt storlek skicka i modernare bildformat och reducera saker som inte används.

Excel ark för sidornas laddningstider mät med devtools
------------
<iframe width="100%" height="500px" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQy-VUh1r8gFSn42lk3O7sRMDCUVC2sQRu4pEyxVvSlmyXNGMEW3RBFkEqJtw4G7zIpfR8zsZLoChrC/pubhtml?widget=true&amp;headers=false"></iframe>

Sammanfattning av Saker som kan förbättras
=======================
De som jag märkte kunde förbättras på alla 3 sidor var fixa bilder och använda modernare bildformat och rätt storlek på bilderna, minska körtiden på javascript och ta bort saker som inte används och även minska tiden det tar att tolka, kompilera och köra JS-kod. Även saker som gör sidorna långsammare är saker som popups och ads på sidorna men sidorna behöver ju sånt för att "överleva" så de är lättare sagt en gjort att bara ta bort sånna saker.

Ranking
------------
Jag hade rankat sidorna
1. WIkipedia
2. U.GG
3. OP.GG

Wikipedia var solklart 1a och fick nästan 100 score på både mobil och desktop när testade på pagespeed, och sidan var även snabbast när jag testa den själv med devtools, jag antar att detta beror på att wikipedia är en simplare sida och använder inte lika mycket script och bilder som de andra sidorna.

U.GG var 2a skulle jag säga den fick lite bättre betyg på både mobil och desktop när jag testade sidan på pagespeed och var även snabbare när jag testa med devtools, sidan läste in mest data av sidan och var ändå snabbare än OP.GG.

OP.GG var lätt sist, sidan var lite sämre än U.GG när jag testa och kollade statsen med devtools och presterade mycket sämre på pagespeed speciellt på mobilen där sidan fick en score av 10, jag antar att dem inte har brytt sig om sidan så mycket eftersom de finns en app på mobilen men de är inte det vi jämför här.
Det som var största problem var adsen som verkligen gjorde sidans laddning långsammare.


Gräns för laddningstid
-----------------------

Jag hade sagt att gränsen för laddningstid är runt 3.5-4s, är sidan långsammare än så är sidans laddningstid mot de dåliga hållet, En score på pagespeed över 90 är bra och undre 50 är dåligt vilket kan vara en bra sak att också titta på för att se ifall sidan är snabb. Jag hade också sagt att de beror på hur "komplicerad" sidan är så för exempel ger jag U.GG och OP.GG lite leway eftersom de har mer script och läser av data för att visa på sidan medans Wikipedia är en väldigt simpel sida så Wikipedia borde vara snabbare.

När jag kollar själv på sidans laddningstid så passerar alla en okej gräns av hur snabba dem är, de viktigaste är ju ändå hur långt tid man tror de tar, alltså hur lång tid de tar för en att se självaste sidan och komma in på den, de kanske tar lite tid för något script eller sånt som man inte märker om du inte hade devtools uppe. 

Så när man tänker på hur snabbt de tar för att se sidan, och laddningstiden för allt på sidan så hade jag sagt att alla 3 sidor för godkännt och är under gränsen.

Rapport skriven av mig Timothy
------------------
