# Car Dashboard Design
*Optimalisatie van autodashboard-interactie door middel van een fysieke verplaatsbare knop op het touchscreen.* 

*Projectteam: Korneel Verraes; Warre Robbe*

24/01/2024

## Samenvatting
De nieuwe generatie auto's worden steeds meer uitgerust met slimme dashboards die een breed scala aan functies en flexibele interacties bieden. Het ideale schoolvoorbeeld van deze trend is de Tesla, met één groot touchscreen en slechts twee knoppen op het stuur. Hoewel dit ontwerp er heel fancy uitziet, stelt zich de vraag of dit allemaal nog veilig en wenselijk is. Worden we door dergelijke minimalistische interfaces te veel afgeleid? Of, op welke (gebruiksvriendelijke) manier kunnen we de functies in het dashboard bedienen zonder onze focus op de weg te verliezen?

Uit enkele *contextual inquiries* is gebleken dat het niet het touchscreen zelf is die voor de afleiding zorgt, maar het feit dat je geen tactiele feedback krijgt bij het bedienen van een functie. Verschillende artikels en wetenschappelijke onderzoeken bevestigen dat.

Onze oplossing is gebaseerd op de magnetische *Surface Dial* van Microsoft. Zo'n *dial* is een fysieke verplaatsbare knop die je op het touchscreen kan plaatsen. Elke plaats op het scherm representeert een bedienbare functie. Ook de combinatie met een *head-up-display* (HUD) is interessant omdat hierbij de ogen niet van de baan afwijken. 

In tegenstelling tot de standaard fysieke knoppen kun je met zo'n *dial* toch een breed scala aan functies gaan bedienen, met behoud van de tactiele feedback. Ook het touchscreen is er nog steeds voor wanneer men stilstaat of voor de passagier.

<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/343d123c-7247-4bda-b35b-b851a2511b5b" width="49%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/6388c215-353b-473f-b0ad-b9d9dbf4852b" width="49%"/>
</p>

## Introductie

In de hedendaagse auto's zijn touchscreens de standaard geworden, waarbij bestuurders verschillende functies bedienen, variërend van navigatie tot entertainment. Echter, het toenemende gebruik van touchscreens in auto's heeft zorgen gewekt over de veiligheid, met name de visuele afleiding die het met zich meebrengt. Een artikel van de VRT[^1] benadrukt dit probleem en stelt dat het bedienen van touchscreens in de auto drie keer gevaarlijker kan zijn dan rijden onder invloed. Het vermindert aanzienlijk de reactieijd van bestuurders en het risico op ongevallen vergroot.

> "Alternatieven zijn de bediening via knoppen op je stuur of schermen die synthetische feedback leveren, zoals een trilfunctie op je smartphone, als bevestiging dat je opdracht is uitgevoerd zodat visuele verificatie niet meer nodig is."

In 2020 voerde het gerenommeerde Britse instituut, *Transport Research Laboratory (TRL)*, een onderzoek[^2] uit naar de impact van het gebruik van aanraakschermen, Apple CarPlay en Android Auto op het rijgedrag van automobilisten. TRL heeft zijn onderzoeksresultaten getoetst aan de richtlijnen van de Amerikaanse *National Highway Traffic Safety Administration (NHTSA)* met betrekking tot afleiding door elektronische apparaten in voertuigen. Uit deze analyse blijkt dat het handmatig bedienen van touchscreens tijdens het rijden als potentieel onveilig wordt beschouwd. Bediening via spraakherkenning wordt volgens deze richtlijnen net als veilig beschouwd.

Granstudio, een gereputeerd mobiliteitsonderzoek- en ontwerpstudio challenged ons om het autodashboard van de toekomst te ontwerpen. Welke informatie moet weergegeven worden en hoe kan dat veilig gedaan worden?

**Op welke (gebruiksvriendelijke) manier kunnen we de functies in het dashboard bedienen zonder onze focus op de weg te verliezen?**

Randvoorwaarden:
- veilig
- gebruiksvriendelijk

> [!NOTE]
> Volledige protocollen en reports zijn te vinden onder de bijlagen.

## Methodologie
<img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/513eaa47-d3dd-45f1-a3e3-30b060c04b0e"/>

Elk ontwerpproces start vanuit de ontdekking van de opdracht. Wat is de opdracht? Is het gestelde probleem ook daadwerkelijk een probleem, en vooral kunnen we dit probleem gaan onderbouwen of weerleggen met bestaande en nieuwe onderzoeken? Onze opdracht startte met een ontmoeting van de opdrachtgevers van dit project. We gingen in gesprek met Gransstudio en kregen te horen wat van ons verwacht werd. We konden aan de slag met het onderzoek in de probleemruimte. 

Wat vinden gebruikers die zich al langere tijd in de probleemruimte bevinden van het gestelde probleem en welke oplossingen hebben zij in gedachten? Het probleem werd alvast sterk bevestigd uit enkele *contextual inquiries* en uit een focusgroep kwamen enkele interessante oplossingsmethodes. Door te gaan kijken naar wat vandaag de dag al op de markt is (benchmarking) en te gaan overleggen met medestudenten konden we in de oplossingsruimte al het een en ander gaan ontdekken. Dit eerste onderzoek leidde tot de uitwerking van een concept die later geoptimaliseerd en nog extra onderzocht kon worden. Na de voorstelling van het concept werden we verenigd in een team en konden we ideeën en bedenkingen gaan uitwisselen. We kwamen tot een sterke en doordachte brainstorm vol ideeën die we in de definitiefase verder zouden kunnen gaan uitwerken. Hiermee werd de ontdekkingsfase afgerond.

We startten met het ontwerp van enkele prototypes van *interfaces* en *dials*. We kregen ook de kans ons concept te gaan voorstellen aan ingenieursstudenten uit Gent die met enkele maatschappelijke bedenkingen kwamen. We optimaliseerden onze prototypes en gingen ook aan de slag met digitale interfaces. Er volgden twee belangrijke gebruikerstesten die leidden tot nieuwe inzichten. Dankzij uitgebreid onderzoek, feedbackmomenten en gebruikerstesten konden we tot een uitgewerkt visueel concept komen.

## Discovery
Tijdens de ontdekkingsfase streven we ernaar om een helder beeld te krijgen van de probleemruimte en op zoek te gaan naar opportuniteiten. Deze opportuniteiten ontstaan zowel uit gebruikersinzichten, als uit een analyse van de markt. Het probleem waarop we focussen wordt met andere woorden scherpgesteld en onderzocht.
### Doelstellingen
Een helder geformuleerde "how might we" bekomen.
### Materiaal & methoden
- contextual inquiries
- focus group
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

#### Focus Group
Voor we als team verder gingen had Warre ook al een focusgroep georganiseerd. Die focusgroep ging ook over de veiligheid en afleiding in wagens, specifiek  toegepast op het interieur van elektrische auto’s. Ook uit die focusgroep kwamen enkele interessante topics. Aan acht mensen werd de opdracht gegeven om hun droomdashboard te maken met allerlei verschillende interieuronderdelen. Zes van de acht gebruikers plaatsten een draaiknop in hun interieur en twee mensen plaatsten er zelf meerdere waaronder ook op het stuur. Dat ze geliefd zijn bij een grote groep mensen is dus alvast zeker. Zes mensen kozen ook om een *head-up-display* te plaatsen in de voorruit.
Toen er werd gevraagd wat mensen vonden van een Tesla-interieur waren ze enerzijds enthousiast over het minimalistische, maar anderzijds niet te spreken over de functionaliteit en veiligheid van één groot touchscreen zonder fysieke knoppen.
Een ander interessant aspect dat aangehaald werd was het veilig versturen van sms’en achter het stuur. Een alternatief op spraakbediening wanneer deze niet optimaal zou werken is het kiezen tussen vaste berichten die je via ons concept zou kunnen lezen in het *HUD*. Scrollen en selecteren gebeurt dan met de *dial*.

<p>
<img width="60%" alt="Afbeelding1" src="https://github.com/korneelverraes/tussentijds-rapport/assets/154961545/3cf6f8a2-57d1-42c0-b24c-b35e5d91109a">
<img width="38%" src="https://github.com/korneelverraes/tussentijds-rapport/assets/154961545/11ac8081-ad86-4a6b-90de-81e648b0a837">
</p>

#### Benchmarking
Om de markt te analyseren maken we gebruik van benchmarking, heel wat designkeuzes zijn vaak al succesvol opgelost door anderen. Je hoeft niet alles opnieuw te onderzoeken, maar door bestaande oplossingen aandachtig te bestuderen kunnen we focussen op meer belangrijke onbekende factoren.

Het probleem werd opgesplitst in twee fundamentele deelproblemen. Hoe kunnen we informatie weergeven en hoe kunnen we bepaalde functies bedienen? Voor beide werden de voor- en nadelen op een rijtje gezet. Daarna werd alles samengegoten in een overzichtelijke *problem-solution* matrix.

<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/bbfada7e-b3ca-40c8-96b6-b0b40c4434f0" width="49%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/4d45a730-82ee-462b-829c-040572d9b47c" width="49%"/>
</p>

<img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/1f392304-7c29-4ec8-93da-6fe266cbce7e"/>

### Conclusies & implicaties
De afleiding tijdens het rijden wordt niet veroorzaakt door het touchscreen zelf maar door het gebrek aan tactiele feedback bij het bedienen van het scherm. Je moet visueel verifiëren wat je gedaan hebt en of je het juist gedaan hebt. Verder genieten knoppen op het stuur en bediening via het touchscreen de voorkeur van gebruikers, gevolgd door fysieke knoppen en stembediening.

*Head-Up Displays* die in de voorruit of op de onderste zwarte band van de ruit geplaatst worden tonen informatie zonder dat de bestuurder zijn ogen van de baan hoeft te halen, wat de veiligheid bevordert. Deze displays kunnen echter moeilijk zichtbaar zijn bij zonnig weer. 3D-schermen en hologrammen bieden een goede ervaring en een grote aanpasbaarheid, maar zijn over het algemeen kostbaarder en complexer. Augmented reality-schermen combineren digitale informatie met de echte wereld, wat de navigatie- en veiligheidskenmerken verbetert, hoewel ze mogelijk een leercurve vereisen voor bestuurders. Traditionele schermen kunnen ondanks dat ze kosteneffectief en vertrouwd zijn de aandacht van de weg brengen. Fysieke knoppen en knoppen op het stuur geven prioriteit aan tastbare feedback en minimale afleiding, terwijl aanraakschermen en spraakbesturing veelzijdigheid bieden, maar mogelijk ten koste gaan van de veiligheid. Context, compatibiliteit en de leercurve zijn ook belangrijke factoren om in overweging te nemen.

**Hoe kunnen we een *dial* en een HUD gebruiken om afgeleide bestuurders gefocust te houden op de weg terwijl ze interageren met het dashboard?**

## Definition
In de definitiefase geven we vorm aan de oplossingen die we dit jaar zullen uitwerken. Gebruikmakend van het eerder gedefinieerde probleem, onderzoeken we mogelijke oplossingen om zo een weloverwogen conceptkeuze te maken. Dit concept dient dan als basis voor verdere ontwikkeling in het tweede semester.
### Doelstellingen
Tot een conceptueel ontwerp komen.
- thematische schets
- storyboard
- *quick-and-dirty* prototype
### Materiaal & methoden
- *sensorial boards*
- kartonnen prototypes
- digitaal ontworpen *interfaces*
- gebruikersinterviews
- gebruikerstesten
### Resultaten
#### Dial
Door het uitvoeren van concepttesten kunnen we ons concept evalueren met echte gebruikers. Hierdoor kunnen we ook het gedrag van de gebruiker tijdens de interactie observeren en analyseren.

Het doel van deze concepttest is een conceptueel ontwerp te hebben voor onze *dial*. Welke grootte? Welke vorm? Welk materiaal? Na een korte introductie gaven we elke deelnemer een stuk klei/plasticine. We gaven hen de opdracht om hun ideale *dial* te ontwerpen en hierbij te variëren in vorm, grootte, afwerking... Hierbij moest de focus op het praktische aspect liggen, minder op het esthetische. Nadat elke deelnemer zijn of haar ideale *dial* gemaakt had gingen we over naar het tweede deel van de test. We ontwikkelden drie sensorial boards: 6 verschillende groottes, 9 vormvarianten en 6 verschillende materialen. Elke deelnemer kreeg de kans elk bord te exploreren door aan de verschillende modellen te voelen. Per bord moesten de deelnemers hun voorkeur weergeven in een top 3. Alle ruwe data van deze testen werd verzameld door middel van gebruikersformulieren.

<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/be6cc5d6-7650-431e-9ba6-cfa813c49f62" width="49%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/198f2613-7320-4ca4-aff1-784e1299125a" width="49%"/>
</p>

<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/32ce6646-530c-4345-8756-1add4a0a7c50" width="32%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/adb85d60-3b40-4850-976b-fa47c739d4e0" width="32%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/6a0e6b91-5974-44c3-8501-f5fe65bec01a" width="32%"/>
</p>

<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/3b04e2db-3944-436a-a286-f12fd0ff7720" width="24.5%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/e968982e-3144-466e-a84e-1ee76f731413" width="24.5%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/2d331046-e235-418d-8396-5f38a1292f60" width="24.5%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/f1c3d883-f741-44cd-900d-0132655e38f1" width="24.5%"/>
</p>

Na de test werden alle formulieren verzameld en geanalyseerd. De resultaten van de opgestelde top 3's werden samengegoten in een scoringsmatrix. Prototypes op plaats 1 kregen een score +3, prototypes op plaats 2 kregen een score +2 en prototypes op plaats 3 kregen een score +1. Prototypes waar deelnemers eerder een afkeur voor hadden, kregen een -1. Door de scores voor elk model van alle deelnemers bij elkaar op te tellen, hebben we een eindscore afgeleid. Een hogere eindscore duidde op een gunstigere ervarging.

<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/b92d9d28-47f9-425c-8d22-e52728740833" width="32%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/7543fa3a-3238-4145-b062-8d649b2974c4" width="32%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/7d9ae298-c574-4e09-a875-06955b0f1f41" width="32%"/>
</p>

#### User interface
Uit de eindscores van de eerste gebruikerstesten konden we met de meest ideale dialvorm opnieuw naar de gebruiker trekken. Deze keer werd bewust gekozen voor nieuwe testpersonen. Door het kiezen van nieuwe testpersonen kunnen er nieuwe visies ontstaan en kunnen we al dan niet bevestigd krijgen of de gebruiker ons concept begrijpt.
Met deze test richten we ons op de conceptuele interactie van de dialfuncties en een interface. In het tweede semester zetten we deze resultaten om in een functioneel en interactief ontwerp.
We trokken naar de gebruiker met drie schermgroottes gevisualiseerd op dibond (een glad aluminium-kunsstofplaat), zes verschillende interfaces geprint op papier, een werkende interactie-interface - gemaakt in Figma - en natuurlijk de *dial*.
Na een korte toelichting volgden er al enkele positieve reacties op het concept en kwamen er enkele interessante opmerkingen. Daarna mocht iedereen kiezen tussen drie schermgroottes, wel met de functie van de *dial* in hun achterhoofd.
Ze kregen ook zes interfaces voorgeschoteld waarvan ze een top drie mochten maken en eventueel een interface als onbruikbaar voor het concept markeren.
<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/fd368b4d-b61f-463a-bbdc-4681d9475e06" width="32%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/cffdc532-c142-435d-90ca-f65d48e7fa92" width="32%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/87eb61fc-b998-477a-a893-6e9897ce553a" width="32%"/>
</p>

<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/25a6964c-2720-44ed-a69b-ef41411702af" width="32%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/1409a5c7-5506-4ab8-b4d2-f8888acba818" width="32%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/2a0eaeb2-5656-4379-bbb0-8aa31fae2a70" width="32%"/>
</p>

### Conclusies & implicaties
Uit de klei-test blijkt dat gebruikers een voorkeur hadden voor kleinere knoppen, echter vermelden een aantal deelnemers dat hun voorkeur gaat naar een knop met voldoende volume en grip. De groottes variëren niet zo heel veel, maar de vormen wel, gaande van klassieke cilinders tot schuivers en bolvormige knoppen. Een interessant suggestie is een conische knop met het smallere oppervlak op het scherm. Dit zorgt niet enkel voor een betere grip maar geeft ook het signaal aan de gebruiker dat de knop verplaatst kan worden. Uit de scoringsmatrix blijkt dat een knop met een diameter van 60 mm en een hoogte van 20 mm het meest geschikt is, ook de licht hogere *dial* werd positief bevonden. Daarnaast gaat de voorkeur qua vorm naar een gegolfde contour. Op vlak van materiaal preferen de deelnemers een licht indrukbaar materiaal, maar ook de ruwere materialen vallen in de smaak.

Samengevat:
- conische vorm
- diameter 55 mm
- hoogte 30 mm
- geribbelde contour
- rubberachtig materiaal (nog te exploreren via 3D-printen)

Uit de interfacetest blijkt dat onderstaand interface als het meest aangenaam, modern, intuïtief en gebruiksvriendelijk aanvoelt. De interactie met de *dial* moet niet noodzakelijk visueel verduidelijkt worden. Volgens de gebruikers is het slechts een gewoontekwestie om de interactie met de *dial* en het scherm te begrijpen.
Gebruikers beschouwen de mediummaat van het touchscreen als meest ideaal. Het is noodzakelijk dat die niet te klein is om gemakkelijk met de *dial* te kunnen interageren op verschillende plaatsen op het scherm. De belangrijkste functies zijn vooral de standaardfuncties zoals temperatuurregeling, muziek, volume en navigatie. Met zes mogelijke posities op ons scherm, en dus zes bedienbare functies tijdens het rijden, zitten we goed.
Daarnaast geeft een gebruiker aan dat de *dial* ook naast het scherm bedienbaar moet zijn zodat je niet telkens met heel je arm tot aan het scherm dient te strekken. Het is belangrijk rekening te houden met verschillende armlengtes. Het scherm mag niet te ver zijn en is best gericht naar de bestuurder. Dit zet ons aan het denken om een kantelbaar scherm te integreren waarbij beperkingen opgelegd worden aan de hand van de richting van het scherm (bestuurder vs passagier)...

<p>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/154961545/62c4561d-bfc4-4668-9827-9c784b2e44a1" width="47%"/>
  <img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/06f6e012-620e-411b-b870-2c24fe74bff6" width="52%"/>
</p>

## Bill of materials
- touchscreen (oude tablet)
- werkende interface
- rotary encoder
- rond lcd schermpje inclusief RPI (HyperPixel 2.1 Round)
- haptische motor
- HUD
- 3D-printmateriaal
- ...

## Kritische reflectie
We hebben heel wat bijgeleerd tijdens de ontdekkings- en definitiefase dit semester. We zijn reeds gestart met de eerste prototypes en hebben dankzij onze gebruikerstesten al een concreet beeld over hoe we een fysieke interactie tot stand gaan brengen tussen het scherm, de *dial* en een *head-up-display*. Onze testgebruikers waren alvast enthousiast over het concept, ze zien duidelijk het potentieel erin en ook het achterliggende probleem is duidelijk.

We blikken terug op een periode met een effectieve en vlotte samenwerking en kijken ernaar uit om in het tweede semester te werken aan de ontwikkelings- en eindfase. Moesten we de definitiefase opnieuw kunnen doen zouden we tussen de eerste testen met de dialvormen en -groottes iets meer tijd gelaten hebben. Zo zouden we een uitgebreidere interface kunnen gaan ontwerpen om een tweede maal met een iets realistischer prototype naar de gebruiker te trekken. We hadden graag in deze fase nog getest hoe gebruikers het liefst tactiele feedback ontvangen van de *dial*. Hoe intens en hoe snel moet de vibratie zijn bij het bedienen van de *dial*? 

Voor de materiaalkeuze van de *dial* trokken we naar enkele gebruikers met een houten plaat met daarop 6 verschillende materialen. We wilden een diverse keuze aan materialen voorstellen, maar hierop baseerden we ons op gevonden materialen. Graag hadden we wat meer tijd gehad om bijvoorbeeld verschillende 3D-printmaterialen erbij te plaatsen zoals poederprints. Of hadden we opzoek kunnen gaan naar speciale en duurzame metalen. In het tweede semester zullen we een definitieve *dial* (poeder)printen (zachter materiaal) om nog eens bij onze doelgroep te polsen welke materialen zij prefereren.

Als we kijken naar het prototypen van een *head-up-display* dan zit daar misschien nog de grootste uitdaging. We moeten op zoek naar een eenvoudig *head-up-display* dat toch een breed scala aan informatie kan weergeven en vooral uiterst vloeiend samenwerkt met de dial en het touchscreen. De uitdaging zit hem in het vinden van een optimale weergavebalans. Een tekort aan informatie zorgt ervoor dat de bestuurder terug naar het touchscreen moet kijken, maar een teveel aan informatie zorgt evenwel voor afleiding. Om het *head-up-display* praktisch te gaan realiseren hebben we oog op verschillende methodes. Zo bestaan er heel wat simpele methodes om aan de hand van een scherm en twee spiegels de informatie te gaan projecteren op een raam. Hiervoor kunnen we eventueel samenwerken met andere studenten.

Eenmaal alle afzonderlijke aspecten ontworpen en geoptimaliseerd zijn, is het tijd voor de volgende stap: het samenvoegen tot een mooi en realistisch geheel waarmee we naar de eindgebruiker kunnen trekken. Een gehele ervaring in een natuurlijke context leidt tot nieuwe inzichten en gevoelens, die we dan kunnen impliceren in een finaal prototype.

<img src="https://github.com/korneelverraes/tussentijds-rapport/assets/88773280/98a8524a-4ac3-4415-a94b-a4940125ff59"/>

## Bijlagen
- Discovery
  - Contextual inquiries
    - [protocol](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EbsFMVmtLS9PsmruQO7G164BsZ5_j9Fu6Rl854Qa3qWmYQ?e=QRkYSC)
    - [report](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/Eas4YG_7SpxApFeq5h0TQsYBoihKIDYJINAHUwYjbGnJOA?e=orFrf5)
  - Focus groups
    - [protocol](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EWh6baFsMMRGoy3ka52hPG4BzbzurMG2UVsQyipgFQgmfw?e=gE4W8u)
    - [report](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EcaQ1q157GFNu4digImXqBoBSc3dnoYHoLg65hIQWaBKaA?e=4kcSHy)
  - Benchmarking
    - [protocol](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EXawcWpXBVpEt_lIMpMp_2ABLn8YT56Gweo287PCzCVebw?e=ohLtQk)
    - [report](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/ES47CYFbTF1EnaaEx6L9F90BNoMAPfkbhsjLT51bKq1DlA?e=dMLCQ5)
- Definition
  - Dial
    - [protocol](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EXA8tLux91JJgyoZDhd7l8EBiHgo0lbct7zmwVrcxtyVpQ?e=EAw8CV)
    - [report](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/ES0ZpXk9lqNEglcTKWC2yTYBzBOITMq5B5F91GWfasvyiA?e=wBfrfh)
  - User interface
    - [protocol](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EZTgPm-nd4pIsmm8usEYeBUBz1gfDapTBei-XWnFm_MZ7g?e=bN2sFI)
    - [report](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EeAsWolB5e9JmBZqcdCANsUBhkX-JtqDsruhD6Gw2MzLAQ?e=icrMtT)

## Bronnen
[^1]: Beeckman, H. (2021, 11 maart). *Aanraakschermen in je auto bedienen drie keer gevaarlijker dan rijden onder invloed: “Europese regels nodig”.* VRTNWS. https://www.vrt.be/vrtnws/nl/2021/03/11/aanraakschermen-in-je-auto-bedienen-drie-keer-gevaarlijker-dan-r/
[^2]: TRL (2019, 15 april). *Distracted Driving Evidence Has Fallen Behind the Latest Technological Changes.* TRL. https://www.trl.co.uk/news/distracted-driving-evidence-has-fallen-behind-the-latest-technological-changes
