# Inlämningsuppgift 1
## Uppgiften i korthet
Efterlikna vald hemsida med hjälp av HTML och CSS och gör den så lik som möjligt.
## Kivra
Jag valde [Kivra](https://www.kivra.se) som hemsida och enhet Dator. Allt utom typsnitten kunde jag använda för uppgiften. Dessa används endast för skoluppgiften.
## Utmaningar
### Ramverk
Första stora utmaningen var att få till Kivra-stylingen samtidigt som jag använder ett ramverk. I denna uppgift valde jag Bootstrap v5.3 och buttons då den hade liknande design och även form. Men det fanns bara hela paketet så jag fick även med resets som påverkade mina redan egen satta reset.

Här lade jag inledningsvis link efter min egen css och kunde först inte skriva över något. Efter ett tag klickade det till i huvudet och min styling kunde skriva över de delar jag ville.
### Video och captions
Andra stora utmaningen var att få till captions för video med elementet ```<track>``` och API Web Video Text Tracks (WebVTT). Det mesta verkade fungera lokalt men inte när det var på hemsidan. Efter ett antal sökningar på google hittade jag felet. I den vtt-fil jag hade skapat missade jag att för tidstämplarna sätta en punkt istället för kolon för millisekunder.
## Lärdomar och funderingar
Det jag tar med mig från denna uppgift är främst att tänka till före. Jag fick användning av skärmdump för att rita ut de olika delarna (läs header, nav, main, footer, section, article etc) och vilken/vilka tekniker som bäst lämpar sig för respektive del. Och på vilket sätt min HTML behöver struktureras. På liknande sätt vill jag framöver kunna strukturera min CSS, identifiera klasser och liknande, så den blir så optimerad från början. Avslutningsvis vikten av att kontinuerligt testa sidan med verktyg som Lighthouse, Wave och med skärmläsare som exempelvis Narrator (Windows) 