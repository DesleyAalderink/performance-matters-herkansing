# performance-matters-herkansing

## De opdracht
Ik heb besloten om de website "https://studiohomebase.amsterdam/" te verbeteren. Dit is een website die ooit gemaakt is door The Pack (bedrijf waar ik nu werk). Deze site is erg outdated en kan zeker een opfrisser gebruiken. Ik heb de checklist lijstje van Performance Matters erbij gepakt samen met de Google Audit tool en gekeken wat ik kan fixen. De audit zelf liet al genoeg opties zien wat veranderd kan worden.


# ![Audit score][banner]


## Mijn progressie

### Set Up
Ik ben begonnen met het vervangen van de code setup. Toen ik begon met stagelopen bij The Pack heb ik een nieuwe "Vanilla Template" gebouwd waarop gedeveloped kon worden. Deze template behoord aan veel eisen voor een hogere/snellere performance. Dit vanilla template heb ik geïmplementeerd in de Studiohomebase website. Alles wordt nu succesvol geminifyd en ook zit er [Modernizr](https://modernizr.com/) in. Dit is als het ware een feature detection die kijkt naar elementen die niet support worden in de browser en maakt hier een fallback voor.

### Lazy loading
Alle afbeeldingen worden nu lazy loaded ingeladen. Hiervoor heb ik de [Intersection Observer](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API) gebruikt. Het moment dat de afbeeldingen in de viewport komen zal deze worden ingeladen.

### Images
De vanilla template houdt al rekening met de compressie van afbeeldingen, maar nog niet met het serven van de afbeeldingen in de juiste formaat. Aangezien deze website draait op Wordpress heb ik een handige plug in tool gevonden genaamd 



[banner]: originele_auditscore.png
