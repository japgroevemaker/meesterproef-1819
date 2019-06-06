<!-- # Meesterproef 2019 @cmda-minor-web · 2018-2019

In de Meesterproef ga je toepassen wat je in de Minor Webdev hebt geleerd.
Voor de Meesterproef krijg je een opdracht van een echte opdrachtgever.
Je gaat leren hoe je je geleerde kennis en skils kan gebruiken om een oplossing voor een echt probleem te ontwerpen en maken.

Je kan kiezen uit verschillende projecten. Hier ga je 5 weken aan werken.

Coaches: Joost Faber, Laurens Aarnoudse, Vasilis van Gemert, Janno Kapritsias en Koop Reynders.

## Werkwijze

Voor de Meesterproef geef je met een eerste en tweede keuze aan welk project je graag wil doen. Daarna wordt door de coaches een indeling gemaakt.  

In de eerste week krijg je een briefing bij de opdrachtgever en schrijf je een debriefing.
Dat is de opdracht en de doelstellingen in eigen woorden beschreven.
Daarna ga je iedere week een proof-of-concept bespreken met je opdrachtgever.
In week 5 presenteer je het eindresultaat tijdens een expositie.
Hiervoor moet je ook een passende presentatie maken.

Elke week zijn er 2 coachingsmomenten gepland.
Op vrijdag ga je naar de opdrachtgever om je vorderingen te bespreken.

- Maandag/Dinsdag - Debriefing met een van de coaches.
- Woensdag/Donderdag - Code review met een van de coaches.
- Vrijdag - Bespreking met de opdrachtgever.


## Criteria en beoordeling

Met de Meesterproef laat je zien wat je hebt geleerd tijdens de minor.
Studenten die de vakken hebben gehaald kunnen aan de Meesterproef beginnen.

De Meesterproef bestaat uit 3 projectweken en een eindproject van 5 weken.
De 3 projectweken,
[PW1](https://github.com/cmda-minor-web/project-1-1819),
[PW2](https://github.com/cmda-minor-web/project-2-1819) en
[PW3](https://github.com/cmda-minor-web/project-3-1819) tellen mee als AVV.

Het eindproject wordt beoordeeld op een Design rationale, een Product biografie en een reflectie op het eigen niveau.
Én of de klant blij is met het gemaakte project.

### Design rationale
In de Design rationale schrijf je de debriefing, de probleem-definitie, toon je de oplossing en schrijf je een uitleg van de code.
De Design rationale is een verantwoording van je ontwerp.

### Product biografie
In het eindproject doorloop je een iteratief proces.
Elke week bespreek je met je opdrachtgever je vorderingen en ideeen.
In de Product biografie hou je stap voor stap bij wat je allemaal hebt gedaan.
Je schrijft over het proces, de werkwijze en de planning.
Ook schetsen, testen, uitprobeersels en inspiratie zijn deel van de Product biografie.

### Reflectie op eigen niveau
Aan de hand van de vakrubrics reflecteer je systematisch op je werk.
In een aantal gesprekken met een coach _reviewen_ we de code van je project.
Dit doen we op basis van de rubrics van de verschillende vakken.
Zo krijg je een goed beeld van je eigen niveau, mogelijke aandachtspunten en/of aspecten van het design-proces waar je je nog op kan verbeteren.

### Een blije klant
Voor de klant maak je een (werkend) prototype. Gericht op een bepaalde gebruikersgroep, geschikt voor verschillende apparaten, met echte data, én een goede UX.
Jeweettoch.
Een blije klant is een goede klant.
Soms ontkom je er niet aan dat je een beetje eigenwijs moet doen.
Dan doe je juist niet wat de klant wil en probeer je de opdrachtgever te overtuigen met een proof-of-concept.
En soms kan het voorkomen dat het proces niet helemaal soepel loopt.
Dat hoort erbij en daar leer je van.
Aan het eind van het project vragen we de klant feedback op het geleverde werk...  -->

# OBA Date
## Week 1
###### Maandag
Omdat ik door omstandigheden een week later dan de rest kon beginnen heb ik op de zaken vooruit gelopen door adhv de caseomschrijving een concept te maken. Deze heb ik op de 1e ontmoeting met onze opdrachtgever, Mark Vos, gepresenteerd. Het concept luidde als volgt:

<i>
Ik wil ervoor zorgen dat de gebruiker zijn eigen profiel kan aanmaken. Tijdens het registreren krijgt de gebruiker naast de gebruikelijke vragen (naam, achternaam, wachtwoord) ook een aantal keuzes voorgeschoteld. Deze keuzes staan symbool voor de interesses en kennis van de gebruiker. De keuzes die de gebruiker maakt worden opgeslagen in het profiel en worden later gebruikt om de gebruiker vindbaar te maken voor andere gebruikers.
</i>

<i>
Als de gebruiker zichzelf eenmaal geregistreerd heeft en bereid is zijn kennis te delen, kan de gebruiker een eigen ‘room’ aanmaken, oftewel een eigen omgeving waar in de gebruiker te kennen geeft over kennis te beschikken en deze te willen delen. Als de gebruiker deze ‘room’ aanmaakt moet hij deze van een paar instellingen voorzien. Zo moet er een titel worden gedefinieerd, deze komt als het ware op de ‘deur’ van deze ‘room’ te staan en moet iedereen duidelijk maken waar het in deze ‘room’ over gaat. Ook moeten er een of meerdere onderwerpen
(max 3) worden gedefinieerd, deze zullen als tags aan de ‘room’ gekoppeld worden zodat de ‘room’ op deze manier via de zoekfunctie te vinden is.
</i>

<i>
Binnenin de ‘room’ is een chat aanwezig. Via deze chat kan een afspraakje gemaakt worden.
</i>

Mark had hier gelijk een aanmerking op: Kunnen we er niet voor zorgen dat de gebruikers zich helemaal niet hoeven aan te melden of registreren? Dit i.v.m dat de OBA dan gevoelige info opvraagt en dat moet opslaan en daarom de drempel om de app te gebruiken misschien te groot wordt. Daarbij komt dat het een app moet zijn die makkelijk en snel, door iedereen, te gebruiken is. Dus ook mensen die alleen een vraag hebben over een bepaald boek, en die mensen willen natuurlijk niet zichzelf eerst moeten inloggen of registreren. De afspraak was dat we later in de week met een verscherpt voorstel terug zouden komen.

Hier moest ik nog goed over nadenken. Daarnaast had ik besloten, na het horen van Stan zijn concept, dat het misschien beter was om samen te gaan werken aangezien onze concepten bijna identiek waren. Dit hebben we diezelfde dag nog met Janno besproken en die gaf groen licht. Er werden afspraken gemaakt omtrent leerdoelen en we hebben besproken hoe we bijvoorbeeld het beste GitHub kunnen gebruiken aangezien we beide nog nooit aan een gezamelijk project op GitHub hadden gewerkt.


###### Dinsdag
Dinsdag hebben we ons concept teruggebracht naar de tekentafel. Dit hebben we gedaan om te kijken hoe we ervoor gaan zorgen dat de app makkelijk te gebruiken is en er niet ingelogd/geregistreerd hoeft te worden? We waren er beide heilig van overtuigd dat je wel zou moeten kunnen registreren/inloggen om volledig gebruik te kunnen maken van de app. Als eerst hadden we bedacht dat er wel een optie was om in te loggen en te registreren maar dat dat niet hoefde en dat je adhv een gastaccount ook gebruik kon maken van de app. Je had dan weliswaar niet alle functionaliteiten van de app, maar je kon hem gebruiken. Maar welke functies zouden dan niet beschikbaar zijn als je je niet registreerd? Daar hadden we beide niet echt een goed antwoord op en daarom gingen we het eens omdraaien, wat nou als je je echt niet kan regisreren? Wat blijft er dan over?

We gingen kijken wat er mogelijk was binnen een session based app. Een app waarbij je tijdelijk een persoonlijke ID toegewezen krijgt en zodoende dus geen gevoelige gegevens hoeft op te geven of op te slaan. Dit idee bleek eigenlijk heel goed haalbaar en daarom hebben we besloten hiermee verder te gaan.

Vervolgens zijn we de basis elementen gaan opzetten. We hebben een test repo aangemaakt om uit te proberen hoe het nou is om samen aan een project op GitHub te werken. Dit bleek vrij simpel te zijn. Daarna heb ik een Node server opgezet en zijn we taken gaan verdelen in GitHub projects.

Die dag ben ik ook gestart met het maken van een prototype via Adobe XD om ons aangescherpt concept dat we donderdag moesten verdedigen zo visueel mogelijk te maken.
