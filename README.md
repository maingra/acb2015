# Athega Code Base 2015

Den årliga hackdayn genomfördes i år i det ganska karga och blåsiga hörn av Nynäshamns skärgård där <a href="http://www.sodexomeetings.se/nynashavsbad/">Nynäshams Havsbad och Spa</a> ligger. 

<img src="https://raw.githubusercontent.com/athega/acb2015/master/tornet.jpg">

## Projekten

 - <a href="#sticky-spider">Sticky Spider</a> - iOS Swiftspel
 - <a href="#in-the-shadows">In the Shadows</a> - Javaspel med libGDX
 - <a href="#atheganes">athega.nes</a> - NESspel i 8 bitar
 - <a href="#athega-print3r">ATHEGA PRINT3R</a> - En plotter byggd med Lego Mindstorm EV3
 - <a href="#närvaroräknare-och-physical-web">Närvaroräknare och Physical Web</a> - Med Tessel och La Metric
 - <a href="#parkera">Parkera</a> - Android app för lättare parkering
 - <a href="#parallell-metaprogrammering">Parallell metaprogrammering</a> - Pi med tusentals decimaler i Ruby
 - <a href="#game-theory-och-tensorflow">Game Theory och Tensorflow</a> - Fördjupning och presentation
 - <a href="#slideshow-i-apple-tv">Slideshow i Apple TV</a> - AppleTV-app med TVMLKit

### Sticky Spider

<img src="https://raw.githubusercontent.com/athega/acb2015/master/stickyspiderpreview.png">

Litet Swift program som använder Fysik, SpriteKit och GamePlayKit med landscape stöd. Banan och fiender slumpas fram och spindeln byter höjd med knapptryckning på skärmen.

#### Tekniker:

 - Swift
 - SpriteKit
 - GameplayKit
 - XCode

#### Demo
<a href="https://youtu.be/uAOrqWSfsbg"><img src="https://i.ytimg.com/vi/uAOrqWSfsbg/hqdefault.jpg"></a>

### In the shadows

Ett väldigt litet spel där målet är att hitta utgången innan batteriet till ficklampan tar slut.

![In the shadows](in_the_shadows.png) 

#### Tekniker:

 - [libGDX](https://libgdx.badlogicgames.com/)
 - [Box2D](http://box2d.org/)
 - [Box2DLights](https://github.com/libgdx/box2dlights)

Koden ligger på [Github](https://github.com/ragulin/InTheShadows).

### athega.nes

En ROM för Nintendo Entertainment System skriven i C med biblioteket Shiru's neslib. Kompilerad med [cc65](https://cc65.github.io/cc65/).

Koden finns på <https://github.com/peterhellberg/nesdev/tree/master/src/athega>

#### Video

[![Video](https://i.ytimg.com/vi/7Ymu9AEUTDo/hqdefault.jpg)](https://www.youtube.com/watch?v=7Ymu9AEUTDo)

### ATHEGA PRINT3R

En plotter byggd med Lego Mindstorm EV3 enligt modellen BANNER PRINT3R men med modifierat program för att skriva "athega".

#### Video

<a href="https://youtu.be/SBb7P-RoYLU"><img src="https://i.ytimg.com/vi/SBb7P-RoYLU/hqdefault.jpg"></a>

### Närvaroräknare och Physical Web

Inför årets jullunch tänkte jag att vi skulle följa hur många som druckit glögg, ätit julbord, osv med hjälp av bluetooth som många gäster har aktiverat i sina telefoner. Detta åstadkommer jag genom att skriva små trackers som körs på Tessel-mikrokontroller. De kan då samtidigt agera Physical Web beacons. Eftersom varje station är bemannad, kan man bara genom att ta fram sin telefon få mer information om den man pratar med. För demon har jag även visualiserat besöken på en La Metric.

#### Teknik

 - JavaScript
 - [Tessel](https://tessel.io/)
 - [La Metric](https://lametric.com/)
 - [Physical Web](http://google.github.io/physical-web/)

#### Demo

<a href="https://youtu.be/1QNqxcHJ3w8"><img src="https://i.ytimg.com/vi/1QNqxcHJ3w8/hqdefault.jpg"></a>

#### Kod

 - https://github.com/lizell/tessel-lametric-track
 - https://github.com/lizell/tessel-physicalweb

### Parkera

En Android app som ska hjälpa fordonsägare att undvika parkeringsböter genom att skapa en påminnelse om gatustädning. När användaren har parkerat startar den appen. Användarens GPS-position hämtas och parkeringsinformation hämtas ifrån Stockholm Opens api. En förifylld dialog för att spara en påminnelse i kalendern visas upp.

#### Tekniker:

 - Google Play Services
 - Stockholm Open API

### Parallell metaprogrammering

Π framställs med generaliserad kedjebråkbeskrivning av en Machin-liknande formel och M500 numeriska talbibliotek.
<a href="https://github.com/athega/acb2015/blob/master/datascience.md" target="_blank">
<img src="https://cloud.githubusercontent.com/assets/1481275/11237828/4c03e5c8-8de2-11e5-8fdb-6dc0a6499049.png">
</a>
#### Kod

 - https://github.com/maingra/PI---a-generalised-continued-fraction-factory

### Game Theory och TensorFlow

#### Fördjupning och presentation Game Theory

Fördjupade mig i Game Theory genom att titta på föreläsningar på Yale Open University och deras Introduction to Game Theory. Presenterade vad Game Theory är och dess historia. Vi tittade på ”Prisoners Dilemma” https://sv.wikipedia.org/wiki/Fångarnas_dilemma

<img src="http://athega.se/system/uploads/2015/11/prisoner.png"/>

#### TensorFlow

Google släpper delar av sitt ramverk för machine learning, TensorFlow. Jag gjorde en djupdykning och testade några av de tutorials som finns på http://tensorflow.org


### Slideshow i Apple TV

En TVMLkit applikation som visar slides på nya Apple TV. Allt som behövs är ett enklare Swiftprogram i XCode som accessar ett Javascript på en webbserver som presenterar sidor med TVML. TVML är ett XML-format som definerar ett enkelt markupspråk för att skapa sidor i en Apple TV. Mycket enkelt att bygga tillämpningar i för den som är famliljär med Javascript och HTML när det väl är uppsatt och konfigurerat.





