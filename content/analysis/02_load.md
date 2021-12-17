---
Title: Load
Description: This is my load analysis page.
Template: analysis
---
# Load

Rapporten som följer mäter tre företags hemsidors laddningstid och användarhet. Syftet är att jämföra sidorna inbördes men även se om det finns uppenbara förbättringar att göra för respektive företag.

Urval
-----------------------

Jag har valt att fortsätta att analysera Elgiganten, Mediamarkt och Webhallen. De är rikstäckande företag som riktar sig mot samma marknad. I och med att jag redan har analyserat deras färgval kändes det intressant att vidare analysera dessa företagen. Jämförelsen jag har gjort mellan dem har gjorts på tre sidor på respektive hemsida som är motsvarande varandra. Deras start-sida, en produkt-sida med en produkt vald från deras start-sida och deras kampanj-sida.

Metod
-----------------------

För att utföra mätningarna har jag använt mig av PageSpeed Insights och webläsarens inspect-tool. Datan har sedan sammanställts i ett excel-ark nedan.

Resultat
-----------------------
<div class="load-stats">
<iframe title="load-statistics" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTxQJkfCT4shQjb3xG-1LAwD_GM12azSNjtHBWRuWraUmsgXJxhzaVEE2--jb_NagQvu7fKnUZUIHNH/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
</div>

*Alla resultat är i sekunder om inte annat specificerats.

###Elgiganten

![Elgiganten](../image/Elgiganten.png?w=700)

Det som främst sticker ut hos Elgiganten är deras kampanj-sida. Den laddade extremt långsamt dels på desktop men ännu värre på mobil. Det var också mycket data som skulle hämtas. Det låg två reklamfilmer på sidan och var även mycket bilder. Utöver det var det många css-filer som tog mycket plats. Man hade kunnat minifiera bland annat css:erna för att göra mindre filer. Kanske hade man även kunnat ha optimerat bild-storlekarna. Reklamfilmerna hade man nog kunnat ta bort helt.

###Mediamarkt

![Mediamarkt](../image/Mediamarkt.png?w=700)

Mediamarkt var överlag lite långsammare än konkurrenterna men hade inget som stack ut som Elgigantens kampanjsida. De var dock väldigt långsamma för mobil där time to interactive sticker ut. Det gällde även de andra men Mediamarkt var relativt sett sämst där och det är något de definitivt kan förbättra.

###Webhallen

![Webhallen](../image/Webhallen.png?w=700)

Webhallens hem-sida förde över väldigt mycket data och hade nog kunnat hålla ner det lite. De hade dock inte alls samma problem med page-speed som Elgiganten hade med sin kampanj-sida även om det inte var ett särskilt bra resultat för dem heller.

Analys
-----------------------

Alla tre sidor gjorde väldigt svaga resultat. Det var mycket rött och oranget i mätningarna vilket indikerar på långsamma sidor. Två av elgigantens sidor fick bra resultat men kampanj-sidan var klart sämst av alla mätningar. Jag tycker därför att Webhallen är den bästa av sidorna om man ser till helheten. De följs av Elgiganten som utöver kampanj-sidan levererade bäst resultat medan Mediamarkt kommer sist. Mediamarkt var dels långsammast för desktop om man exkluderar extremvärdet på Elgigantens kampanjsida men de var även klart långsammare än konkurrenterna för mobil. Även relativt sett mot hur sidorna laddade för desktop var de sämst där med en laddningstid som var flera gånger långsammare.

Det tydligaste förbättringsområdet för alla tre är laddningstiden för mobil. Mediamarkt stack ut men de hade alla svaga resultat, även om Elgiganten överlag var lite bättre. Jag fokuserar mer på desktop och tycker att ca två sekunder känns som ett rimligt maxtak för en sida att ladda. Mediamarkt var de som inte nådde upp till det, utöver Elgigantens extremfall. Jag tycker det stämmer rätt väl med känslan när man är inne på sidorna också. Webhallen och Elgiganten känns lite snabbare och smidigare att navigera på.


Referenser
-----------------------

https://www.elgiganten.se/

https://www.elgiganten.se/product/vitvaror/diskmaskin/324361/electrolux-diskmaskin-esm89310ux-rostfr

https://www.elgiganten.se/cms/veckans-annons/veckans-erbjudanden

https://www.mediamarkt.se/

https://www.mediamarkt.se/sv/product/_msi-gf63-thin-10uc-675neu-15-6-b%C3%A4rbar-gamingdator-med-nvidia-rtx-3050-1337032.html

https://www.mediamarkt.se/sv/shop/kampanjer.html

https://www.webhallen.com/se/

https://www.webhallen.com/se/product/341335-Acer-Nitro-XV272S-165Hz-OC-27-1080p-IPS-144Hz-0-5ms-DP-Freesync

https://www.webhallen.com/se/campaigns?sort=discountSales

https://pagespeed.web.dev/



Övrigt
-----------------------

Björn Molin
