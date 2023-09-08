# javors-course
Ohjelmointitehtäviä Javorille

Tee tehtävät ja harjoittele samalla git versionhallinan alkeita. Versionhallinta on paikka jossa koodia säilytetään, se pitää myös kirjaa kaikista muutoksista koodissa.

## Tehtävä 1
Muuta funktiota niin, että se näyttää kellon ajan. Vinkki: kellonajan saat Date() funktiokutsulla

## Tehtävä 2
Muuta funktiota niin että se näyttää etunimen ja sukunimen. Vinkki: koodissa on jo esimerkki etunimen hakemiselle muuttujaan, Bonus: lisää nimien väliin välilyönti.

## Tehtävä 3
Muuta funktiota niin että se näyttää sekä etunimen että sukunimen 10 kertaa. <br/> 
Vihje: saat lisättyä muutujaan tekstiä näin:<br/>
<code>muuttuja = muuttuja + "tekstiä";</code> <br/>
Vihje: rivinvaihdon saat lisäämällä rivin loppuun "\<br/\>" <br/>

Tässä harjoitellaan for silmukkaa. <br/> 
For-silmukan syntaksi on: <br/>
<code>for (var i = 0; i < 100; i++){<br/>
	// tänne tulee koodi jota haluat suorittaa silmukassa<br/>
}</code><br/>

Katsotaan silmukkaa hiukan lähemmin:<br/>
<code>var i = 0;</code> luodaan indeksi-muuttuja jolla lasketaan kuinka monta kertaa silmukka on pyörähtäny.<br/>
<code>i < 100</code> ehto jonka ollessa tosi silmukkaa suoritetaan, kun epätosi silmukan suoritus loppuu.<br/>
<code>i++</code> komento jolla indeksiä kasvatetaan jokaisen kierroksen jälkeen (++ on erikois-operaattori joka lisää numeroon 1, sama kuin i+1)<br/>
Eli alussa i = 0, ensimmäisen kierroksen JÄLKEEN i = 1, toisen kierroksen JÄLKEEN i = 2 jne. 

## Tehtävä 4
Muuta funktiota niin että se näyttää nimen edessä "Mr. "  jo etunimi on Aku<br/> 
Vihje: saat lisättyä muutujan alkuun tekstiä näin:<br/>
<code>muuttuja = "tekstiä"  + muuttuja;</code>

Tässä harjoitellaan if lausetta. <br/> 
If-lauseen syntaksi on: <br/>
<code>if (muuttuja == "tekstiä"){<br/>
	// tänne tulee koodi jonka haluat suorittaa jos ehto on tosi<br/>
}</code><br/>

Katsotaan if-lausetta hiukan lähemmin:<br/>
<code>(muuttuja == "tekstiä")</code> ehto jota vertaillaan <br/>
Mahdollisia operaatoreita ehtolauseissa on <code>==, ===, !=, <, >, <=, >=</code>.<br/>
Osaatko sanoa mitä ne merkitsevät?