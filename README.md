# Car Dashboard Design
*Optimalisatie van autodashboard-interactie door middel van een fysieke verplaatsbare knop op het touchscreen.* 

*Projectteam: Korneel Verraes; Warre Robbe*

24/01/2024

## Samenvatting
De nieuwe generatie auto's worden steeds meer uitgerust met slimme dashboards die een breed scala aan functies en flexiebele interacties bieden. Het ideale schoolvoorbeeld van deze trend is de Tesla, met één groot touchscreen en slechts twee knoppen op het stuur. Hoewel dit ontwerp er heel fancy uitziet, stelt zich de vraag of dit allemaal nog veilig en wenselijk is. Worden we door dergelijke minimalistische interfaces te veel afgeleid? Of, op welke (gebruiksvriendelijke) manier kunnen we de functies in het dashboard bedienen zonder onze focus op de weg te verliezen?

Uit enkele *contextual inquiries* is gebleken dat het niet het touchscreen zelf is die voor de afleiding zorgt, maar het feit dat je geen tactiele feedback krijgt bij het bedienen van een functie. Verschillende artikels en wetenschappelijke onderzoeken bevestigen dat.

Onze oplossing is gebaseerd op de magnetische Surface Dial van Microsoft. Zo'n surface dial is een fysieke verplaatsbare knop die je op het touchscreen kan plaatsen. Elke plaats op het scherm representeert een bedienbare functie. Ook de combinatie met een head-up-display is interessant omdat hierbij de ogen niet van de baan afwijken. 

In tegenstelling tot de standaard fysieke knoppen kun je met zo'n dial toch een breed scala aan functies gaan bedienen, met behoud van de tactiele feedback. Ook het touchscreen is er nog steeds voor wanneer men stilstaat of voor de passagier.

> [!NOTE]
> Hero sketch/render/image

## Introductie

In de hedendaagse auto's zijn touchscreens de standaard geworden, waarbij bestuurders verschillende functies bedienen, variërend van navigatie tot entertainment. Echter, het toenemende gebruik van touchscreens in auto's heeft zorgen gewekt over de veiligheid, met name de visuele afleiding die het met zich meebrengt. Een artikel van de VRT[^1] benadrukt dit probleem en stelt dat het bedienen van touchscreens in de auto drie keer gevaarlijker kan zijn dan rijden onder invloed. Het vermindert aanzienlijk de reactieijd van bestuurders en het risico op ongevallen vergroot.

> "Alternatieven zijn bediening via knoppen op je stuur of schermen die synthetische feedback leveren, zoals een trilfunctie op je smartphone, als bevestiging dat je opdracht is uitgevoerd zodat visuele verificatie niet meer nodig is."

In 2020 voerde het gerenommeerde Britse instituut, het Transport Research Laboratory (TRL), een onderzoek[^2] uit naar de impact van het gebruik van aanraakschermen, Apple CarPlay en Android Auto op het rijgedrag van automobilisten. TRL heeft zijn onderzoeksresultaten getoetst aan de richtlijnen van de Amerikaanse National Highway Traffic Safety Administration (NHTSA) met betrekking tot afleiding door elektronische apparaten in voertuigen. Uit deze analyse blijkt dat het handmatig bedienen van touchscreens tijdens het rijden als potentieel onveilig wordt beschouwd. Bediening via spraakherkenning wordt volgens deze richtlijnen net als veilig beschouwd.

Granstudio, een gereputeerd mobiliteitsonderzoek- en ontwerpstudio challenged ons om het autodashboard van de toekomst te ontwerpen. Welke informatie moet weergegeven worden en hoe kan dat gedaan worden? **Op welke (gebruiksvriendelijke) manier kunnen we de functies in het dashboard bedienen zonder onze focus op de weg te verliezen?**

Randvoorwaarden:
- veilig
- gebruiksvriendelijk

## Methodologie
> [!NOTE]
> Max 400 woorden. Beschrijf je methodologie (enkel SEM1, zie les methodologie). Maak hierbij gebruik van een afbeelding om je tijdlijn weer te geven. Op deze tijdlijn moeten minimaal een tijdsincatie te zien zijn, moeten fasen te zien zijn en moeten activiteiten te zien zijn.

## Discovery
Tijdens de ontdekkingsfase streven we ernaar om een helder beeld te krijgen van de probleemruimte en op zoek te gaan naar opportuniteiten. Deze opportuniteiten ontstaan zowel uit gebruikersinzichten, als uit een analyse van de markt. Het probleem waarop we focussen wordt met andere woorden scherpgesteld.
### Doelstellingen
Een helder geformuleerde "how might we" bekomen.
### Materiaal & methoden
- contextual inquiries
- benchmarking
### Resultaten
#### Contextual inquiries
Door middel van contextual inquiries kunnen we huidige gebruikspatronen in hun natuurlijke context begrijpen, pijnpunten definiëren en een beter begrip krijgen van de contextuele randvoorwaarden voor ideeën en opportuniteiten.

Om dit te realiseren trokken we de baan op met verschillende autobestuurders. We startten met een introductie om een beter beeld te krijgen van de deelnemer. Daarna werd hem/haar gevraagd verschillende dingen te doen; zijn/haar favoriete liedje opleggen, volume verhogen, verwarming verlagen, navigeren met de gps... We hebben alles geobserveerd en een tabel opgesteld met de verschillende functies en hoe ze bediend worden.

<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/8aae7aa7-7bcd-4c1c-bbfc-2a0e0ae37a1a" width="49%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/e852cd28-31a8-4f7b-8c11-9bdf23cd5b85" width="49%"/>
</p>

||Buttons on steering wheel|Physical buttons|Touchscreen|Voice commands|
|---:|:---:|:---:|:---:|:---:|
|Volume|X|X - X|
|Air conditioning||X|X - X - X|
|Seat heating||X|X - X - X|
|Steering wheel heating|||X - X|
|Navigation|||X - X|X - X|
|Music|||X - X - X|X - X|
|Answering calls|||X - X - X|
|Start calls|||X - X|X|

#### Benchmarking
Om de markt te analyseren maken we gebruik van benchmarking omdat heel veel designkeuzes al succesvol zijn opgelost door anderen. Je hoeft niet alles opnieuw te onderzoeken, maar door bestaande oplossingen aandachtig te bestuderen kunnen we focussen op meer belangrijke onbekende factoren.

Het probleem werd opgesplitst in twee fundamentele deelproblemen. Hoe kunnen we informatie weergeven en hoe kunnen we bepaalde functies bedienen? Voor beide werden de voor- en nadelen op een rijtje gezet. Daarna werd alles samengegoten in een overzichtelijke problem-solution matrix.

<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/bbfada7e-b3ca-40c8-96b6-b0b40c4434f0" width="49%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/4d45a730-82ee-462b-829c-040572d9b47c" width="49%"/>
</p>

<img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/1f392304-7c29-4ec8-93da-6fe266cbce7e"/>

### Conclusies & implicaties
De afleiding wordt niet veroorzaakt door het touchscreen zelf maar door het gebrek aan tactiele feedback bij het bedienen van het scherm. Je moet visueel verifiëren wat je gedaan hebt en of je het juist gedaan hebt. Verder genieten knoppen op het stuur en bediening via het touchscreen de voorkeur van gebruikers, gevolgd door fysieke knoppen en stembediening.

Head-Up Displays (HUDs) die in de voorruit of op het onderste zwarte band worden geplaatst, tonen informatie zonder dat de bestuurder zijn ogen van de baan hoeft te halen, wat de veiligheid bevordert. Deze displays kunnen echter moeilijk zichtbaar zijn bij zonnig weer. 3D-schermen en hologrammen bieden een goede ervaring en een grote aanpasbaarheid, maar zijn over het algemeen kostbaarder en complexer. Augmented reality-schermen combineren digitale informatie met de echte wereld, wat de navigatie- en veiligheidskenmerken verbetert, hoewel ze mogelijk een leercurve vereisen voor bestuurders. Traditionele schermen, hoewel kosteneffectief en vertrouwd, kunnen de aandacht van de weg afleiden. Fysieke knoppen en knoppen op het stuur geven prioriteit aan tastbare feedback en minimale afleiding, terwijl aanraakschermen en spraakbesturing veelzijdigheid bieden, maar mogelijk ten koste gaan van de veiligheid. Context, compatibiliteit en de leercurve zijn ook belangrijke factoren om in overweging te nemen.

**Hoe kunnen we een dial en een HUD gebruiken om afgeleide bestuurders gefocust te houden op de weg terwijl ze interageren met het dashboard?**

## Definition
In de definitiefase geven we vorm aan de oplossingen die we dit jaar zullen uitwerken. Gebruikmakend van het eerder gedefinieerde probleem, onderzoeken we mogelijke oplossingen om zo een weloverwogen conceptkeuze te maken. Dit concept dient dan als basis voor verdere ontwikkeling in het tweede semester.
### Doelstellingen
Tot een conceptueel ontwerp komen.
- thematische schets
- storyboard
- quick-and-dirty prototype
### Materiaal & methoden
- sensorial boards
- kartonnen prototypes
- gebruikersinterviews
- gebruikerstesten
### Resultaten
#### Dial
Door het uitvoeren van concepttesten kunnen we ons concept evalueren met echte gebruikers. Hierdoor kunnen we ook het gedrag van de gebruiker tijdens de interactie observeren en analyseren.

Het doel van deze concepttest is een conceptueel ontwerp te hebben voor onze dial. Welke grootte? Welke vorm? Welk materiaal? Na een korte introductie gaven we elke deelnemer een stuk klei/plasticine. We gaven hen de opdracht om hun ideale dial te ontwerpen en hierbij te variëren in vorm, grootte, afwerking... Hierbij moest de focus op het praktische aspect liggen, minder op het esthetische. Nadat elke deelnemer zijn of haar ideale dial gemaakt had gingen we over naar het tweede deel van de test. We ontwikkelden drie sensorial boards: 6 verschillende groottes, 9 vormvarianten en 6 verschillende materialen. Elke deelnemer kreeg de kans elk bord te exploreren door aan de verschillende modellen te voelen. Per bord moesten de deelnemers hun voorkeur weergeven in een top 3. Alle ruwe data van deze testen werd verzameld door middel van gebruikersformulieren.

<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/be6cc5d6-7650-431e-9ba6-cfa813c49f62" width="49%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/0cb97803-6960-4495-a09b-ec6937142b72" width="49%"/>
</p>

<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/fbff5f1c-9422-4b96-bba5-be57ad6b838f" width="33%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/c91aef7e-3df0-4721-a1b1-54d7d1c045e5" width="33%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/c19bb943-af3f-46c2-a78b-8dfcc9e7fd3e" width="33%"/>
</p>
  
<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/3b04e2db-3944-436a-a286-f12fd0ff7720" width="24.5%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/e968982e-3144-466e-a84e-1ee76f731413" width="24.5%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/2d331046-e235-418d-8396-5f38a1292f60" width="24.5%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/f1c3d883-f741-44cd-900d-0132655e38f1" width="24.5%"/>
</p>

Na de test werden alle formulieren verzameld en geanalyseerd. De resultaten van de opgestelde top 3's werden samengegoten in een scoringsmatrix. Prototypes op plaats 1 kregen een score +3, prototypes op plaats 2 kregen een score +2 en prototypes op plaats 3 kregen een score +1. Prototypes waar deelnemers helemaal geen voorkeur voor hadden, kregen een -1. Door de scores voor elk model van alle deelnemers bij elkaar op te tellen, hebben we een eindscore afgeleid. Een hogere eindscore duidde op een gunstigere ervarging.

<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/348c23b9-6e23-4900-8787-b12fc81ce1e6" width="33%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/c16e7c17-2c84-457e-9042-17f55a3d69b9" width="33%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/9bc380f4-f2a0-4127-b423-ec461c858998" width="33%"/>
</p>

#### User interface
Uit de eindscores van de eerste gebruikerstesten konden we met de - volgens de eerste gebruikerstesten - meest ideale dialvorm opnieuw naar de gebruiker trekken. Deze keer werd bewust gekozen voor nieuwe testpersonen. Door het kiezen van nieuwe testpersonen kunnen er nieuwe visies ontstaan en kunnen we ook al dan niet bevestigd krijgen of de gebruiker ons concept begrijpt.
Het doel van deze tweede gebruikerstest is het kiezen van een interface waarmee we in het tweede semester aan de slag kunnen om een werkend interface te kunnen maken die start vanuit de bediening van de dial. Met deze test richten we ons op de conceptuele interactie van de dial en een interface en de functies die de dial moet kunnen bedienen, in het tweede semester gaan we die functioneel en interactief op punt gaan zetten.
Aan de hand van drie schermgroottes gevisualiseerd op dibond (een glad aluminium-kunsstofplaat), zes verschillende interfaces geprint op papier, een werkend interactie-interface gemaakt in Figma en natuurlijk de dial trokken we naar de gebruiker.
Na een korte toelichting van het concept volgden er enkele positieve reacties op het concept en kwamen er enkele interessante opmerkingen. Daarnaast mocht iedereen kiezen tussen drie schermgroottes, wel met de functie van de dial in hun achterhoofd.
Ze kregen ook zes interfaces voorgeschoteld waarvan ze een top drie mochten maken en eventueel een interface als onbruikbaar voor het concept markeren.
<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/154961545/bbf31e88-9f21-40d6-b807-d79c55053d1c" width="33%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/154961545/8d309d77-48e4-4fa9-9264-1b4596134879" width="33%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/154961545/5d88d351-e011-4a49-9bc2-1caf032941dd" width="33%"/>
</p>

<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/154961545/2ce8c67c-8c63-42d6-ad18-1f08af2c26ce" width="33%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/154961545/11bf6835-41e6-42b0-a461-ed3afd08450f" width="33%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/154961545/367ee800-9be0-4f4e-aaca-302484eb9e2f" width="33%"/>
</p>

Uit de test bleek dat het volgende interface als het meest aangenaam, modern, intuïtief en gebruiksvriendelijk aanvoelt.
<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/154961545/ae366eeb-a956-4330-a032-dcf6c77f496e"/>
</p>
Als schermgrootte werd de mediummaat als meest ideaal aangegeven.
Als we de testpersonen vroegen naar welke functie's voor hen het belangrijkste zijn en waarom, kwamen er vooral de standaardfuncties naar boven zoals temperatuurregeling, muziek, volume en gps.

<img width="738" alt="user tijdens gebruik" src="https://github.com/korneelverraes/tussentijds-rapport/assets/154961545/62c4561d-bfc4-4668-9827-9c784b2e44a1">


### Conclusies & implicaties
Uit de klei-test blijkt dat gebruikers een voorkeur hadden voor kleinere knoppen, echter vermelden een aantal deelnemers dat hun voorkeur gaat naar een knop met voldoende volume en grip. De groottes variëren niet zo heel veel, maar de vormen wel, gaande van klassieke cilinders tot schuivers en bolvormige knoppen. Een interessant suggestie is een conische knop met het smallere oppervlak op het scherm. Dit zorgt niet enkel voor een betere grip maar geeft ook het signaal aan de gebruiker dat de knop verplaatst kan worden. Uit de scoringsmatrix blijkt dat een knop met een diameter van 60 mm en een hoogte van 20 mm het meest geschikt is, ook de licht hogere dial werd positief bevonden. Daarnaast gaat de voorkeur qua vorm naar een gegolfde contour. Op vlak van materiaal preferen de deelnemers een licht indrukbaar materiaal, maar ook de ruwere materialen vallen in de smaak.

Samengevat:
- conische vorm
- diameter 55 mm
- hoogte 30 mm
- geribbelde contour
- rubberachtig materiaal (nog te exploreren via 3D-printen)

> [!NOTE]
> Definieer de belangrijkste designbeslissingen (van deel user interface)

## Bill of materials
> [!NOTE]
> aanvullen
- touchscreen (oude tablet)
- werkende interface
- rotary encoder
- rond lcd schermpje inclusief RPI (HyperPixel 2.1 Round)

## Kritische reflectie
> [!NOTE]
> Max. 500 woorden
> iets over nog een gebruikerstest met vibratie van de knop

## Bijlagen

## Bronnen
[^1]: Beeckman, H. (2021, 11 maart). *Aanraakschermen in je auto bedienen drie keer gevaarlijker dan rijden onder invloed: “Europese regels nodig”.* VRTNWS. https://www.vrt.be/vrtnws/nl/2021/03/11/aanraakschermen-in-je-auto-bedienen-drie-keer-gevaarlijker-dan-r/
[^2]: TRL (2019, 15 april). *Distracted Driving Evidence Has Fallen Behind the Latest Technological Changes.* TRL. https://www.trl.co.uk/news/distracted-driving-evidence-has-fallen-behind-the-latest-technological-changes
