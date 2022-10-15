# HTML5-en-CSS3
## Programmeren met HTML5 en CSS3; de basis

HTML is de afkorting van HyperText Markup Language. Met HyperText wordt tekst bedoeld met directe verwijzingen in de vorm van aanklikbare links. Je hoeft dus niet meer via een index te zoeken maar kunt rechtstreeks van de ene pagina naar de andere springen. Markup betekent dat de taal uit markingstekens bestaat waarmee je aangeeft hoe de tekst opgemaakt moet worden.

Wanneer we een HTML-pagina (zeg maar een internet pagina) willen maken doen we dat door in een editor met gewone tekst en een aantal opdrachten aan te geven hoe de pagina eruit moet gaan zien. Willen we gewone tekst laten zien dan kunnen we dat ook min of meer normaal typen. Maar we hebben wel codes nodig die vertellen hoe de tekst eruit komt te zien en waar de tekst komt te staan. 

#### Bijvoorbeeld:
<title>Mijn eerste pagina</title> Wat je hier ziet noemen we een element. In dit geval het element waarmee de titel van een pagina wordt gemaakt. Een element bestaat uit tags met daartussen tekst of iets anders dat je op jouw HTML-pagina wilt hebben. <title> en </title> zijn de tags.

Wanneer we beginnen met een HTML 5 pagina wordt op de eerste regel altijd het type docu - ment aangegeven. Dat doe je met:
<!DOCTYPE html>

Hiermee geef je aan dat de pagina van het documenttype HTML is. Je kunt hier ook een ander type gebruiken en afhankelijk van het type zal de browser strenger of minder streng zijn in het toepassen van de regels.
Overigens is <!DOCTYPE> de enige tag die gewoonlijk met hoofdletters geschreven wordt hoewel dit niet verplicht is in HTML 5. Alle andere tags schrijven we in kleine letters alhoewel ook hiervoor weer geldt dat tags in hoofdletters net zo goed werken. Ook is <!DOCTYPE> van het void-type. Dat betekent dat deze tag geen eindtag heeft.
Na de <!DOCTYPE> tag volgt de eigenlijke webpagina. Iedere webpagina begint en eindigt met de HTML-tags. Binnen die HTML tags bevinden zich het head gedeelte en de body. In het head gedeelte komen vooral die zaken te staan die niet zichtbaar zijn op de pagina maar wel van belang zijn voor hoe de pagina op het scherm verschijnt. In de body komen de delen die straks wel zichtbaar zullen zijn.


```html
<!DOCTYPE html>
<html lang="nl">
<head>
<meta charset="utf-8">
<title>Mijn pagina</title>
</head>
<body>
Hier komt de inhoud van de webpagina
</body>
</html>
```

### Opdracht 1
Maak je eerste pagina met in de title-tag je naam en in de body "Hello World".
* Start de editor ([Visual Studio Code] (https://code.visualstudio.com/) kan je downloaden)
* Klik op Bestand - Nieuw
* Type de code zoals hierboven weergegeven en voeg de veranderingen uit de opdracht toe.
* Bewaar het bestand onder de naam opdracht1.html en test het in je webbrowser

Let op de volgende zaken:
*	Een tag staat altijd tussen < en >
* Bij een tag hoort (vrijwel altijd) een afsluitende tag, herkenbaar aan de “ /” voor het woord. Wanneer begin- en eindtag op meerdere regels staan zorg je ervoor     dat de code daartussenin ingesprongen wordt.
* Maak er een gewoonte van de tags altijd in kleine letters te typen.
* Een HTML-pagina bestaat altijd uit een head en een body
* Een HTML-pagina sla je altijd op met de extensie .html.











