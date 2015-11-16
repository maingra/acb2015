<h1>Data Science</h1><br>
På en dag av intensiv kodning visar jag några av de färdigheter som krävs i parallell programmering och problemlösning. Genom att simulera en <a href="https://sv.wikipedia.org/wiki/Big_data">"map-reduce"</a> –metod och att producera ett skript för att beräkna π till önskad upplösning eller rättare sagt antal signifikanta siffror.<br>
<h2>Bibliotek som jag använder</h2><br>
<a href="https://rubygems.org/gems/M500">M500</a> ett utökat bibliotek av numeriska datatyper för att möjliggöra snabbast kända metoder för att beräkna π, så kallade Machin-liknande formler och Kedjebråktals metoder.<br>
QZ ett bibliotek för parallella bearbetning i fler datorer och kalylering av M500 kod.<br>
<h2>Metod</h2>
image here <br>
Mallen <a href="https://github.com/maingra/PI---a-generalised-continued-fraction-factory">pi-gcff_TMP.rb</a> framställer en kodfil med parallellkod. Vilket i sin tur beräknar π.<br>
<h2>Hur gör man?</h2><br>
vid prompten skriver vi<br>
:> ruby pi-gcff_TMP >> output.rb<br>
Detta kommando omdirigerar resultatet från mallen och skriver den i output.rb filen.<br>
:> ruby output.rb >> result.txt<br>
Ovan kommando omdirigerar resultatet från beräkning av π och skriver den i filen result.txt.<br>
Läs resultat.txt för att se resultatet av ditt arbete med π.<br><br>
Kanske behöver du mer signifikanta siffror. Det kan göras genom att uppdatera pi-gcff_TMP filen.<br>
Ändra sedan rad 90 från: <br>
run = piPart(1,2)<br>
till<br>
run = piPart(1,5) till exämple.<br>
Detta kommer att producera fem beräkningar som sedan kan distribueras för parallell beräkning.<br>
<h2>Önskat resultat</h1><b2>
Jag hoppas att ni återupptäcker kraften i er dator och får en upplevelse i matematik<br>




