# Checklista för C# utvecklare  🛠  beta 0.6.7
![RCA computer room 1959](Konventioner/Bilder/RCA-computer-room-1959.jpg)

***
### Vad är det här?
Ansatsen för det här dokumentet är att ge riktlinjer för att utveckla i programmeringsspråket C#. Konventionerna utgår från egna erfarenheter, Microsoft-dokumentation, StyleCop-regler samt många andra artiklar kring C#-praxis. Det förekommer punkter som inte har någon särskild motivering. Bakgrunden till dessa val är att det är bättre att bestämma en standard, och vara konsekvent, än att det blir godtyckligt.

Dokumentet kan fungera som underlag när man vill sätta upp kodpraxis i team. Tänker man samma? Mest av allt är det en kom-ihåg-lista att gå igenom innan man gör kodgranskningar och migrerar ihop kod. Det är inte en komplett redogörelse för språket C#, SOLID, designmönster eller TDD. De finns andra mer djuplodade böcker och kurser för det. Den tar inte heller upp några riktlinjer för frontend-utveckling med JavaScript-ramverk, CSS etcetera.

***
### Varför kodpraxis?
Det kanske är så att vissa ser att kodningsriktlinjer begränsar kreativitet och tar för mycket tid i anspråk att följa. Men det är värt ansträngningen. Huvudskälet till att använda en konsekvent uppsättning kodningskonventioner är att standardisera struktur och kodstil för en applikation så att du och andra lätt kan läsa, förstå och underhålla koden.

Fördelar med kodpraxis:
* Konventioner behövs för att öka medvetenheten om att kod i allmänhet läses tio gånger mer än den ändras.
* Konventioner behövs för att åskådligöra potentiella fallgropar för vissa konstruktioner i C#.
* Riktlinjer behövs för att göra oss bekanta med konventioner i .NET Framework, t.ex. IDisposable, LINQ-uttryck och Exceptions.
* Konventioner leder också till att minska gapet mellan erfarna och juniora utvecklare. Det är också en stor hjälp för nya teammedlemmar.
* Riktlinjer leder till minskad kostnad då underhåll av applikation går snabbare och är enklare.

***
### Innehåll
* [Introduktion](Konventioner/01-Introduktion.md)
* [Mindset](Konventioner/02-Mindset.md)
* [Namnkonventioner](Konventioner/03-Namnkonventioner.md)
* [Layoutkonventioner](Konventioner/04-Layoutkonventioner.md)
    *  <a href="Konventioner\04-Layoutkonventioner.md#generellt" target="_blank">Generellt</a>
    *  <a href="Konventioner\04-Layoutkonventioner.md#storlekar-och-antal" target="_blank">Storlekar och antal</a>
* [Kommentarkonventioner](Konventioner/05-Kommentarkonventioner.md)  
* [Språkkonventioner och checklista](Konventioner/06-Sprakkonventioner_och_checklista.md)  
    * [Generellt](Konventioner/06-Sprakkonventioner_och_checklista.md#generellt)  
    * [ASP.NET MVC](Konventioner/06-Sprakkonventioner_och_checklista.md#aspnet-mvc)
