---
Title: Kmom10
Description: Det här är min sida för kmom01.
Template: kmom
---

Kmom10 / Projekt
==========================

<div class="kmomreport menu">
<a href="kmom01" aria-label="menu"><ul><li>Kmom01</li></ul></a>
<a href="kmom02" aria-label="menu"><ul><li>Kmom02</li></ul></a>
<a href="kmom03" aria-label="menu"><ul><li>Kmom03</li></ul></a>
<a href="kmom04" aria-label="menu"><ul><li>Kmom04</li></ul></a>
<a href="kmom05" aria-label="menu"><ul><li>Kmom05</li></ul></a>
<a href="kmom06" aria-label="menu"><ul><li>Kmom06</li></ul></a>
<a href="kmom10" aria-label="menu"><ul><li>Projekt</li></ul></a>
</div>

<div class="kmomreport">
<p>Jag har under denna examination implementerat krav 1-4 och 6, dvs 'webbplats', 'tema', 'responsivitet och tillgänglighet', 'tema alternativt' och 'analys valfri'.
<br><br></p>

<h2>Uppdrag 1: Webbplats</h2><br><br>

<p>När jag skulle börja med detta projekt så valde jag att börja från grunden och göra en ny installation. Jag kände att det skulle bli enklare så och att jag skulle ha bättre koll på vad jag gjorde/implementerade. Jag ville heller inte riskera att det kom med något från portfolion som inte behövde vara med, jag ville alltså ha DRY kod. Jag valde att göra en advokatfirma åt kund 1. Jag har använt mig av en hero-bild som följer med på alla tre undersidor, det tyckte jag blev snyggt. Jag tycker även att bilden ger ett intryck av att man kommer hamna i trygga händer om man väljer oss som advokatfirma. Bilden på loggan har jag hämtat från Pixabay och sedan har jag lagt till texten under själv, jag tycker den representerar en advokatfirma bra. Alla bilder som jag har lagt in använder sig av Cimage så bilderna får rätt storlek.
<br><br></p>

<p>Jag har anpassat navigeringen för både desktop och mobil och är lite extra nöjd över hover-effekten. Stor del av texterna jag har på min sida är kopierade och anpassade från andra sidor om jag skulle fastna i urkund.
<br><br></p>

<h2>Uppdrag 2: Tema</h2><br><br>

<p>När jag skulle skapa temat så vägde jag in både vad jag själv anser passar på en advokatfirmas hemsida och kundens önskemål. Färgerna ger ett intryck av lyx och trovärdighet vilket är viktigt och vad kunden efterfrågade. För att skapa mina teman så har jag delat upp stylen i olika SASS-moduler så att det blir lättare att uppdatera sidan om det skulle behövas. Jag har alla färger för sidan i separata SASS-moduler och variabler för att enkelt uppdatera dessa. Typografin har jag valt utefter vad andra advokatbyråer har och vilka fonter som var vanligast bland denna typ av webbsida. I min dokumentation-sida berättar jag lite mer om detta, den finns <a href="http://www.student.bth.se/~jopn20/dbwebb-kurser/design/me/kmom10/about/doc">HÄR.</a><br><br></p>

<h2>Uppdrag 3: Responsivitet och tillgänglighet</h2><br><br>

<p>Sidan som jag har byggt är responsiv och tillgänglig för alla. För att göra min sida responsiv så har jag på alla sidor använt mig av CSS-grid. Detta gör att jag enkelt kan stylea om sidan för mindre skärmar. Sidan har inga horisontella scrollbars och alla bilder laddas in via Cimage och picture/srcset. Alla mina sidor når även 100 under 'accessibility'. Det enda jag behövde fixa för mina sidor var att ta bort 'tab-index' från nav-baren då den ansågs vara onödig. Jag har även kollat alla mina sidor i 'Toptal - Colorblind Web Page Filter' för att se om färgerna passar bra för färgblinda, vilket det gör.
<br><br></p>

<h2>Uppdrag 4: Tema alternativt</h2><br><br>

<p>Mitt alternativa tema är ett ljusare tema än huvudtemat. Jag har ändrat färgpaletten så att bakgrundsfärgerna går mer åt det beigea/orangea/guldiga hållet. Dessa färger tog jag fram genom att lägga in färgkoden för rubrikerna för huvudtemat och välja två ljusare nyanser. Sedan låg den blåa färgen som en komplementär färg till dessa så då tog jag den eftersom det ändå hörde ihop med huvudtemat. Jag ville ändå att båda temana skulle hänga ihop lite. Sedan ändrade jag typografin till ett typsnitt som var snarlikt det andra från huvudtemat då jag gillade det.
<br><br></p>

<p>I det alternativa temat har jag mer använt mig av designprincipen 'line' än vad jag gjorde i huvudtemat. Detta var ett sätt för mig att ändra designen en del. Linjerna tilsammans med färgerna och typografin anser jag uppfyller kundens krav, alltså propert och lyxigt.
<br><br></p>

<h2>Uppdrag 6: Analys valfri</h2><br><br>

<p>I min valfria analys så valde jag att undersöka min webbsidas laddningstider. Jag valde detta analystema då jag kände att jag redan hade gått in på färger och designprinciper i min dokumentation, så jag kände att det vore kul att kolla på något nytt. Jag kollade på laddningstiderna med hjälp av PageSpeed Insights och dev-tools flik 'network'. Det var intressant att se hur det skilde sig lite mellan desktop och mobil. I övrigt så var det annars inte så stor skillnad mellan de tre undersidorna.
<br><br></p>

<h2>Hur projektet gick att genomföra</h2><br><br>

<p>Jag skulle ändå säga att det har gått bra att genomföra projektet. Jag tycker att det har varit kul och lärorikt. Det har varit alldeles lagom svårt för mig, vissa delar svårare än andra. Något jag hade svårt med var att få till den genomskinliga 'overlayn' i headern. Jag googlade mig till en lösning som jag sedan fick äta upp. Jag fick då nämligen problem med nav-baren i mobilläge. Den öppnade sig inte riktigt som jag ville och jag förstod inte vad problemet var. Jag frågade då Niklas på Discord och han hjälpte mig lösa problemet. Det visade sig bero på hur jag hade implementerat overlayn. Så det var en motgång jag hade och fick lägga lite extra tid på. En annan sak som jag har märkt att jag kan lägga ganska mycket tid på är att komma på hur jag vill att sidan ska se ut, det är svårt tycker jag. Sen när jag har kommit på hur jag vill ha det brukar själva kodnings-delen gå rätt snabbt, snabbare än själva tänka-delen i alla fall. De delar som jag tyckte gick lättare var de delar som var rätt lika från tidigare uppgifter. T.ex. så gick det mycket lättare för mig att implementera ett nytt tema denna gång än när vi gjorde det i ett kursmoment, vilket är kul då man känner att man lärt sig av sina misstag. Jag tycker att detta projekt var roligt och en rimlig examination för denna kurs.
<br><br></p>

<h2>Tankar om kursen</h2><br><br>

<p>Denna kurs tycker jag genomgående har varit kul och lärorik, det finns så många saker som man inte tänkt på tidigare när det kommer till design. Jag tycker att både föreläsningarna och guiderna har varit tydliga och pedagogiska. Jag uppskattar även lärarnas tillgång i Discord, man behöver aldrig vara orolig för att inte få hjälp där. Jag har lärt mig massor och skulle verkligen rekommendera denna kurs till andra. Kursen får 10/10 av mig.
</p>
</div>
