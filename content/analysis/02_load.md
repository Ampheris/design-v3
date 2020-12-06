---
Title: Report: Laddningstid och användbarhet
Description: An report about websites colors
---

Rapport: Colors
==================

Analysering av laddningstid och användbarhet hos hemsidor.

Urval
-----------------------

De tre allra mest trafikerade hemsidorna i USA, Amazon, ebay och walmart. Eftersom de är de tre absolut mest trafikerade
hemsidorna så är det intressant och se hur bra deras sidor faktiskt är. (1)

Metod
-----------------------

Det som användas för undersökningen var Google Pagespeed samt Devtools.

Resultat
-----------------------
<div class="analysis-img">
<img src="../image/amazon.png" alt="amazon">
<img src="../image/ebay.png" alt="ebay">
</div>

<div class="analysis-img">
<img src="../image/walmart.png" alt="walmart">
</div>
<br>
<br>

<table>
<caption><a href="https://docs.google.com/spreadsheets/d/18WUQvMAmKoAY1n2Yhu_mS6Aia6rcuFKBy_rRwHGwVuo/edit?usp=sharing"_>Kmom05: Load tabell</a> </caption>
<thead>
  <tr>
    <th></th>
    <th colspan="2">Google Pagespeed</th>
    <th colspan="4">Devtools</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Hemsida</td>
    <td>Mobil</td>
    <td>Dator</td>
    <td>resurser(MB)</td>
    <td>MB Överfört</td>
    <td>Laddningstid(s)</td>
    <td>Requests</td>
  </tr>
  <tr>
    <td><a href="http://walmart.com/">walmart.com</a></td>
    <td>18</td>
    <td>65</td>
    <td>5.77</td>
    <td>2.75</td>
    <td>5.98</td>
    <td>189</td>
  </tr>
  <tr>
    <td><a href="http://ebay.com/">ebay.com</a></td>
    <td>40</td>
    <td>65</td>
    <td>2.8</td>
    <td>6.1</td>
    <td>2.71</td>
    <td>121.67</td>
  </tr>
  <tr>
    <td><a href="http://amazon.com/">amazon.com</a></td>
    <td>49</td>
    <td>80</td>
    <td>11.6</td>
    <td>4.2</td>
    <td>9.69</td>
    <td>282</td>
  </tr>
</tbody>
</table>

Vinnaren mellan dessa tre hemsidor är Amazon medan walmart är den sämsta om de tre. Trots att walmart inte gjorde flest
requests eller använde sig av flest resuser så var de fortfarande sämst. Ifall man jämför de tre hemsidorna så har alla
en snartlik layout, alla har minst 1 slideshow och multipla bilder med länkar som hänvisar dig vidare till produkterna.

När man går in på hemsidorna så märker man knappt någon skillnad på laddningstiden trots det är så att vissa av de laddar
in fler resurser och gör flera requests till deras servers. 

### Walmart
Det som walmart kan förbättra är följande:
* Skicka bilder i modernare bildformat
* Koda bilder effektivt
* Minska serverns första svarstid
* Använd bilder med rätt storlek

### Ebay
Det som Ebay kan förbättra är följande:
* Använd bilder med rätt storlek
* Ta bort javascript som inte används
* Ta bort resurser som blockerar renderingen
* Koda bilder effektivt
* Skicka bilder i modernare bildformat
* Ta bort oanvänd CSS
* Undvik att skicka äldre JavaScript till moderna webbläsare.


### Amazon
Det som Amazon kan förbättra är följande:
* Ta bort javascript som inte används
* Undvik upprepade omdirigeringar
* Skicka bilder i modernare bildformat
* Använd bilder i rätt storlek
* Koda bilder effektivt
* Skjut upp inläsningen av bilder som inte visas på skärmen
* Minska serverns första svarstid



Analys
-----------------------

Det är förvånandsvärt att dessa tre enorma hemsidor med så himla mycket trafik skulle få så pass dåliga betyg från
Google PageSpeed. Det som verkar vara mest förekommande förslag på förbättring till mobilversionen är följande:
1. Använd bilder i rätt storlek
2. Koda bilder effektivt
3. Skicka bilder i modernare bildformat

Det mesta verkar kretsa kring bilderna på hemsidan, vilket inte är ett förvånande resultat med tanke på hur många
bilder som det faktiskt finns med på sidorna samt bildspelen. Det kan vara lätt hänt att man inte tänker på att scala ner
på bilderna på rätt sätt när det kommer till mobilversionen. Dock så förväntar man nästan sig att sådana här pass stora
företag att ha bra koll på deras hemsidor, speciellt ebay och Amazon då deras enda inkomst är från deras webbsidor.

Att walmart är sämst är inte speciellt förvånande med tanke på att det finns fysiska butiker för walmart medan Amazon och
Ebay inte har butiker som folk kan handla i. 

Den gränsen som jag själv anser vara långsam är om hemsidan tar mer än 5 sekunder och då syftar jag på när du tittar på
skärmen men den bara snurrar i 5 sekunder. Varken Amazon, Ebay eller walmart var långsamma men det tog dom lång tid att
hämta all data på hemsidan.

Referenser
-----------------------

1. https://www.semrush.com/blog/most-visited-websites/

Övrigt
-----------------------

Mathilda Holmsträm