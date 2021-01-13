---
Title: Laddningstid
Description: Det här är min sida för 02_load.
Template: kmom
---

Laddningstid
==========================

<div class="kmomreport menu">
<a href="01_colors" aria-label="menu"><ul><li>Färger</li></ul></a>
<a href="02_load" aria-label="menu"><ul><li>Laddningstid</li></ul></a>
<a href="03_design_principles" aria-label="menu"><ul><li>Designprinciper</li></ul></a>
<a href="11_design-och-webbplatser" aria-label="menu"><ul><li>Laddningstid Advokatfirma</li></ul></a>
</div>

<div class="kmomreport">

<p>Den här uppgiften går ut på att analysera tre olika webbplatsers laddningstid. Jag tittar sedan på om det finns några saker som kan förbättras med tanke på laddningstid och användbarhet.<br><br></p>

<h2>Urval</h2>

<p><br>Jag har valt att analysera Nelly, Handelsbanken och Aftonbladet. Jag valde dessa då alla tre är webbplatser som har många besökare men samtidigt har olika syften med sina sidor. Jag tycker det ska bli intressant att se om/hur de skiljer sig åt.<br><br></p>


<h2>Metod</h2>

<p><br>För att mäta de olika webbsidornas laddningstid har jag använt mig av verktyget Pagespeed Insights och devtools flik 'network'. När jag fick fram de olika siffrorna för respektive webbplats så sammanställde jag allt i ett excelark.<br><br></p>

<h2>Resultat</h2>

<p>Du hittar excelarket: <a href="https://studentbth-my.sharepoint.com/:x:/g/personal/jopn20_student_bth_se/EWx57JaQ4bJHh1Aa0fh5U9QBuj8Lfj4B3JpEsxHkVTdFmw?e=2Xa9rc">HÄR</a></p>

<p><br><strong>Nelly</strong></p>
<img src="../assets/img/nelly.png" alt="Startsida Nelly" width=100% height=auto>


<p><br>Nellys webbsida hamnade under 49 (rött) för både mobil och dator på alla tre sidor. Den största möjligheten Nelly har för att förbättra dessa siffror är att ta bort oanvänd CSS. De kan även ta bort resurser som blockerar renderingen och ta bort JavaScript som inte används.
<br><br></p>

<p><strong>Handelsbanken</strong></p>
<img src="../assets/img/handelsbanken.png" alt="Startsida Handelsbanken" width=100% height=auto>


<p><br>Handelsbankens webbsida fick medelbra(orange) betyg för datorn men dåligt(rött) för mobilen. Den största möjligheten Handelsbanken har för att förbättra dessa siffror är att ta bort JavaScript som inte används. De kan även använda bilder i modernare bildformat och se till så att bilderna är i rätt storlek.
<br><br></p>


<p><strong>Aftonbladet</strong></p>
<img src="../assets/img/aftonbladet.png" alt="Startsida Aftonbladet" width=100% height=auto filter=none;>


<p><br>Aftonbladets webbsida fick medelbra(orange) betyg för datorn men dåligt(rött) för mobilen. Den största möjligheten Handelsbanken har för att förbättra dessa siffror är att ta bort JavaScript som inte används. De kan även ta bort resurser som blockerar renderingen och oanvänd CSS.
<br><br></p>


<h2>Analys</h2>

<p><br>Alla tre webbplatser presterar bättre på datorn än mobilen. Handelsbanken och Aftonbladet ligger på det orangea värdet för datorn och rött för mobilen medan Nelly ligger på rött för både dator och mobil. Alla tre webbsidor fick som förbättringsåtgärd att ta bort JavaScript som inte används och oanvänd CSS. Vi kan även se att Nelly har väldigt mycket mer resurser än vad både Handelsbanken och Aftonbladet har. Dock så har även Aftonbladet mycket resurser på sin startsida.
<br><br></p>

Min rangordning på dessa webbplatser baserat på deras mätvärden blir:<br><br>
1. Handelsbanken<br>
2. Aftonbladet<br>
3. Nelly<br>

<p><br>Den solklara vinnaren för mig var Handelsbanken. Deras snitt på laddningstid, antal resurser och sidans storlek var lägst på allihopa. De var även den sida som hade bäst PageSpeed av alla tre webbsidor. Jag valde att sätta Aftonbladet på andra plats trots att de hade en rätt hög snittladdningstid (3,16s). Men om man tittar på alla de tre olika sidorna jag har valt från Aftonbladet så är det startsidan som drar upp laddningstidens snitt. Eftersom de var bättre än Nelly på övriga snittvärden och PageSpeed så fick de ändå en andra plats.
<br><br></p>

<p>Min gräns för en absolut laddningstid är två sekunder. De som klarar av mitt test är Nelly och Handelsbanken. När det tar mer än två sekunder så börjar jag bli otålig och kan i värsta fall lämna webbplatsen. Jag antar att Aftonbladets sida tar långt tid på sig eftersom den uppdateras hela tiden med nya artiklar och att de har mycket reklam på sidan. Något jag som användare stör mig på vid användandet av Nellys webbsida är att det ploppar upp en flash-notis vart man än navigerar sig på sidan. Mycket störigt och gör bara mig som besökare irriterad, det hade räckt med en gång kan jag tycka.
<br><br></p>


<h2>Referenser</h2><br><br>

PageSpeed Insights <br>
<a href="https://developers.google.com/speed/pagespeed/insights/">https://developers.google.com/speed/pagespeed/insights/<br><br></a>

Nelly <br>
<a href="https://nelly.com/se/kl%C3%A4der-f%C3%B6r-kvinnor/">https://nelly.com/se/kl%C3%A4der-f%C3%B6r-kvinnor/
<br><br></a>

Handelsbanken <br>
<a href="https://www.handelsbanken.se/sv/">https://www.handelsbanken.se/sv/
<br><br></a>

Aftonbladet <br>
<a href="https://www.aftonbladet.se/">https://www.aftonbladet.se/
<br><br></a>

<h2>Övrigt</h2><br><br>

Jag har gjort rapporten/analysen själv och mitt namn är Johanna Persson.
</div>
