# Athega Code Base 2015

Den årliga hackdayn genomfördes i år i det ganska karga och blåsiga hörn av Nynäshamns skärgård där <a href="http://www.sodexomeetings.se/nynashavsbad/">Nynäshams Havsbad och Spa</a> ligger. 

<img src="https://raw.githubusercontent.com/athega/acb2015/master/tornet.jpg">

## Projekten

 - **Sticky Spider** - iOS Swiftspel
 - **In the Shadows** - Javaspel med libGDX
 - **athega.nes** - NESspel i 8 bitar
 - **Närvaroräknare och Physical Web** - Med Tessel och La Metric
 - **Parkera** - Android app för lättare parkering
 - **Parallell metaprogrammering** - Pi med tusentals decimaler i Ruby
 - **Game Theory och Tensorflow** - Fördjupning och presentation
 - **Slideshower** - AppleTV-app med TVMLKit
 - **ATHEGA PRINT3R** - En plotter byggd med Lego Mindstorm EV3

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

### athega.nes

En ROM för Nintendo Entertainment System skriven i C med biblioteket Shiru's neslib. Kompilerad med [cc65](https://cc65.github.io/cc65/).

Koden finns på <https://github.com/peterhellberg/nesdev/tree/master/src/athega>

#### Video

[![Video](https://i.ytimg.com/vi/7Ymu9AEUTDo/hqdefault.jpg)](https://www.youtube.com/watch?v=7Ymu9AEUTDo)

### ATHEGA PRINT3R

En plotter byggd med Lego Mindstorm EV3 enligt modellen BANNER PRINT3R men med modifierat program för att skriva "athega".

#### Video

<a href="https://youtu.be/SBb7P-RoYLU"><img src="https://i.ytimg.com/vi/SBb7P-RoYLU/hqdefault.jpg"></a>

### In the shadows

Ett väldigt litet spel där målet är att hitta utgången innan batteriet till ficklampan tar slut.

![In the shadows](in_the_shadows.png) 

#### Tekniker:

 - [libGDX](https://libgdx.badlogicgames.com/)
 - [Box2D](http://box2d.org/)
 - [Box2DLights](https://github.com/libgdx/box2dlights)

Koden ligger på [Github](https://github.com/ragulin/InTheShadows).

### Närvaroräknare och Physical Web

Inför årets jullunch tänkte jag att vi skulle följa hur många som druckit glögg, ätit julbord, osv med hjälp av bluetooth som många gäster har aktiverat i sina telefoner. Detta åstadkommer jag genom att skriva små trackers som körs på Tessel-mikrokontroller. De kan då samtidigt agera Physical Web beacons. Eftersom varje station är bemannad, kan man bara genom att ta fram sin telefon få mer information om den man pratar med. För demon har jag även visualiserat besöken på en La Metric.

#### Teknik

 - JavaScript
 - [Tessel](https://tessel.io/)
 - [La Metric](https://lametric.com/)
 - [Physical Web](http://google.github.io/physical-web/)

#### Demo

<a href="https://youtu.be/1QNqxcHJ3w8"><img src="https://i.ytimg.com/vi/1QNqxcHJ3w8/hqdefault.jpg"></a>

### Kod

 - https://github.com/lizell/tessel-lametric-track
 - https://github.com/lizell/tessel-physicalweb
