# WDD-API-MilaMassaro

Link naar mijn Notion: https://www.notion.so/Minor-Webdesign-Development-2fd4a28d1c2c8004a247e9f0794a6be0?source=copy_link 

## GEBRUIKTE API'S

- Tarot API
- Web animations API
- Pointer Events API
- LocalStorage API


## WEEK 1

**woensdag 1 april**

Wat heb ik vandaag gedaan?

Ik heb research gedaan naar API's en wat er mogelijk mee is. Ik heb zeer beperkte kennis van werken met API's, dus ik vond het moeilijk om te weten wat de opties zijn. 
Ik heb een concept bedacht en bedacht hoe ik dit aan zou kunnen pakken. Vind het wel moeilijk om in te schatten hoeveel tijd alles me gaat kosten, dus ik heb een iets kleinere versie bedacht van mijn concept en een versie die heel uitgebreid is. Dus afhankelijk hoe het werken met API's me afgaat zal ik één van beide kiezen. Misschien dat ik ga starten met de simpelere versie en het later uitbreid...


Hoeveel tijd heeft dit me gekost?

6 uur.
1,5 uur kick-off en uitleg van Astro.
2 uur research naar API's en inspiratie opdoen.
1 uur concept bedenken en uitwerken. 



Wat heb ik geleerd?

Wat mogelijk is met API's, maar vond het lastig om hier een goed beeld van te krijgen, en vooral om te weten wat haalbaar is met mijn capaciteiten...



Wat ga ik morgen doen?

Voortgangsgesprek.

_Ik had mijn check-out met Rafi. Toen ik mijn concept vertelde kwam hij met suggesties dat ik zou kunnen doen of web API'S die ik eventueel zou kunnen gebruiken. Hij stelde bijvoorbeeld view transitions API voor, zodat ik de overgang van het trekken van de kaart naar het openen van de kaart een beetje mooi/"whimsical" kan doen_


### VOORTGANGSGESPREK 1

- Web Speech API
- Clippy (Web AI)

- Tarot card API (telt niet als API, foto's gebruiken vna github halen)
- Tarot API
- Customizable select (css)
- Web animations API
- evt. View transition API

### REFLECTIE WEEK

Ik zag vooral heel veel beren op de weg deze week. Het ging me allemaal wat snel. Ik heb zelden met API's gewerkt, nog nooit met Astro en nog nooit in een terminal. Veel mensen om mij heen wel al, waardoor ik enorm het gevoel kreeg dat ik op achterstand stond. De workshops en lessen gingen deze week erg snel voor mij... Dus ik heb wel stress voor de rest van het vak, maar ik ga het per week proberen te bekijken. Wel vond ik het heel leuk om na te denken over mijn concept en hier schetsen voor te maken.


## WEEK 2

**woensdag 8 april**

Wat heb ik vandaag gedaan?

Geoefend (klassikaal) met Astro en API. Dit vond ik best lastig. Ik vond het wel goed te volgen en begreep wat er gedaan en gezegd werd, maar toen ik het zelf moest doen vond ik het toch heel lastig. Ik vond het vooral lastig om te weten wat ik waar moest neerzetten met die componenten en layouts.
Ik heb images voor de tarot cards gedownload en alle 78 namen aangepast zodat hij matcht met de naam uit de API. Toen heb ik "image" toegevoegd aan die lijst uit API door ze op te roepen vanuit de map images. Nu moet ik nog zorgen dat het op mijn pagina te zien is.


Hoeveel tijd heeft dit me gekost?

6 uur.
2,5 uur klassikale uitleg over Astro met demo.
45 min image namen aanpassen.
2 uur werken aan project.



Wat heb ik geleerd?

Van alles over Astro.



Wat ga ik morgen doen?

Hopelijk mijn afbeeldingen met mijn API combineren en zorgen dat ik deze op mijn pagina te zien krijg. 


_Ik had mijn check-out met Nienke. Zij raadde mij deze site aan omdat hier ook een voorbeeld met kaarten is: https://css-tricks.com/abusing-customizable-selects/_


**donerdag 9 april**

Wat heb ik vandaag gedaan?

Ik heb mijn images gekoppeld aan mijn API op een nettere en kortere manier. Ik heb ze voor nu op de index even als overzicht staan in een grid.
Ik heb gewerkt met een drag and drop API. Dit is werkend voor 1 dropzone, maar wil nu kijken met meer dropzones. dus dat moet ik nog aanpassen.
Ik heb met javascript een spread gemaakt van 78 kaarten die onderin het scherm te zien zijn.


Hoeveel tijd heeft dit me gekost?

6 uur.
1 uur workshop local storage.
4 uur zelf werken.


Wat heb ik geleerd?

drag and drop API
Meer over Astro en hoe dat werkt. Vind dat nog best lastig.



Wat ga ik morgen doen?
Voortgangsgesprekken.


### VOORTGANGSGESPREK 2

Tijdens het voortgangsgesprek heb ik mijn proces tot nu toe laten zien. De drag and drop web API werkte en ik heb het werkend gemaakt voor 3 dropzones (op donderdagavond). In het gesprek heb ik aangegeven dat ik niet zo goed weet hoe ik mijn images met de juiste tarot card moet koppelen aan de gemaakte kaarten met javascript, maar Jad kan me hierbij helpen.
Voor mijn tweede web API wil ik web animations API gebruiken. Hier ga ik me volgende week op focussen.

### REFLECTIE WEEK

Deze week is de drag en drop API gelukt, waar ik erg blij mee ben. Dit is het grootste gedeelte van mijn concept, dus ben blij dat ik hier stappen in heb kunnen zetten. Ik vind het soms lastig omdat ik heel veel ideeën in mijn hoofd heb en dan blokkeer ik een beetje omdat ik dan zo veel wil en niet weet waar ik moet of wil beginnen. Dit merk ik heel erg bij dit vak. Maar ik ga het van dag tot dag proberen te bekijken. 


## WEEK 3

**woensdag 15 april**

_Vandaag was ik bij Smashing Conference._


**donderdag 16 april**

Wat heb ik vandaag gedaan?

Ik heb gewerkt met web animations API. Ik heb nu de functies geschreven dat mijn kaarten smooth animeren als erop geklikt wordt. 
Ik heb geprobeerd om de drag and drop API beter werkend te maken. Omdat mijn kaarten een voor- en achterkant hebben zie ik die als ik de achterkant drag met deze API. Het lukte me niet om dit smoother en mooier te maken.
Ik heb thuis verder gekeken naar oplossingen voor dit probleem. Toen kwam ik erachter dat ik met pointer events API hetzelfde kan doen als met de drag and drop API, maar dan veel smoother. Dus ik heb een nieuwe versie hiervan gemaakt met deze web API. Ik heb het magnetic gemaakt en dat hij snapt. Voor nu heb ik gebruik gemaakt van 3 kaarten en 3 dropzones. Volgende week moet ik de spread toevoegen en de rotatie functie en er 1 geheel van maken.


Hoeveel tijd heeft dit me gekost?

5,5 uur.
30 min onderzoek naar web animations API.
1,5 uur web animations API eigen project.
1 uur drag and drop smoother maken.
2,5 uur pointer events API.



Wat heb ik geleerd?

Dat drag and drop API niet de beste optie is voor mijn concept. Dat Pointer events API een verbeterde versie van mousemove is en dat deze ook voor mijn concept ingezet kan worden.



Wat ga ik morgen doen?

The Web You Want.


### VOORTGANGSGESPREK 3
_Deze week waren er geen voortgangsgesprekken_


## WEEK 4

**woensdag 22 april**

Wat heb ik vandaag gedaan?

Ik moest al mijn experimenten en projecten samenvoegen en dit ging helaas echt totaal niet soepel. De pointer events werkten niet in combinatie met mijn spread code. Toen ik dit werkend had gekregen werkte het klikken weer niet met de rotate functie. Toen dit werkend was lukte het resetten naar de oude positie weer niet... Uiteindelijk heb ik gekozen dat als de kaart eenmaal in de dropzone ligt, dat hij dan locked is en niet meer verplaatst kan worden. Dit is wat betreft UX duidelijker denk ik en maakt het voor de code ook beter dat er minder snel bugs en errors zijn.
Mijn project op GitHub gezet met Render erbij.


Hoeveel tijd heeft dit me gekost?

5,5 uur.
1 uur project op GitHub.
2,5 uur alles combineren wat ik tot nu toe heb.
30 min readme bijwerken.
30 min mijn werk op visual studio code zetten (had alles op codepen).



Wat heb ik geleerd?

Dat dingen combineren in javascript best wel ingewikkeld kan zijn....



Wat ga ik morgen doen?

De content API op de kaarten zetten.
Kijken hoe ik het het beste op kan delen met componenten in Astro.
Nog een detail pagina waar de description bij elke kaart komt. 



**donderdag 23 april**

Wat heb ik vandaag gedaan?

Vandaag kon ik me heel slecht concentreren. Ik was ook de hele week ziekig, wat niet echt hielp... Ik heb wel de content API op de kaarten gezet. Ik ben aan de slag gegaan met mijn homescherm, waar ik een soort altaar van wil maken. De overzichtspagina heb ik iets verder uitgewerkt.


Hoeveel tijd heeft dit me gekost?

3 uur.
1 uur content API koppelen aan de div kaarten in spread.
1 uur navigatie maken met kaarten.
1 uur code opruimen.



Wat heb ik geleerd?

Dat je met <script define:vars={{tarotMeanings}}> de tarot meanings in dit geval als variabelen krijgt en deze kan gebruiken in je javascript.



Wat ga ik morgen doen?

Voortgangsgesprekken.



### REFLECTIE WEEK

Ik heb veel kleine dingen gedaan deze week om het beter te maken, zoals bijvoorbeeld code opschonen. Hierdoor heb ik het gevoel dat ik weinig stappen heb gezet, terwijl het eigenlijk heel goed is wat ik heb gedaan. Er zijn ook nog best wat dingen te doen. Ik moet nog de definitie pagina maken van de getrokken kaarten. Ik denk dat ik dit met localStorage wil gaan doen. Jad heeft aangegeven in het voortgangsgesprek dat ik eerst die definitie pagina het beste uit kan werken en als ik nog tijd heb het menu op de homepagina met de kaarten zoals mijn idee is. Hij zei dat dat best wat moeite kan kosten, maar het lijkt me heel leuk om te maken en echt iets toevoegen, dus wil dit toch graag nog gaan doen. 


## Concept

Mijn concept is om de Rider Waite tarotcards op een moderne en interactieve manier te vertalen van de fysieke wereld naar de digitale wereld. Hierbij heb ik geprobeerd om de ervaring zoals hij in de fysieke wereld is zo veel mogelijk na te bootsen. Gebruikers kunnen kaarten vanuit een spread zelf verplaatsen naar de "dropzones", wat voor een gevoel van betrokkenheid zorgt denk ik. Ook kunnen ze echt zelf kaarten kiezen uit de spread in plaats van dat het automatisch gegenereerd wordt, waardoor het ook intuïtief in gebruik is. Ik vond het heel belangrijk dat de reading ook echt van waarde zou kunnen zijn voor de gebruiker, dus het intuïtieve en interactieve heb ik bewust erg toegevoegd.

Ik heb ervoor gekozen om een home-scherm te maken waarop een soort altaar te zien is. Dit geeft echt het mystieke gevoel mee en past in het concept om de fysieke ervaring om te zetten naar een digitale ervaring. Vanuit het home-scherm kan je navigeren naar een overview pagina, waar alle kaarten te zien zijn. Elke kaart kan je roteren en dan kan je op de achterkant de naam, arcana en korte betekenis lezen. Ook kun je vanuit het homescherm navigeren naar de reading. Hier zie je onderaan de spread met alle kaarten en in het midden van het scherm de dropzones. Je kunt vervolgens 3 kaarten verslepen naar de dropzones. Wanneer alle dropzones gevuld zijn, verdwijnt de spread met kaarten en komt er een button tevoorschijn met "get my interpretation". Deze brengt je vervolgens naar de uitgebreidere omschrijving van jouw getrokken kaarten. 

## Technologiën en gebruikte API's

Ik heb 1 content API en 3 web API's gebruikt. Voor de content API heb ik gebruik gemaakt van **Tarot API** (https://tarotapi.dev/api/v1/cards). In deze API staan met name de namen en definities van de kaarten. Helaas waren er geen images bij deze API te vinden. Daarom heb ik zelf alle images gedownload (via https://github.com/krates98/tarotcardapi) en deze vervolgens gekoppeld aan de juiste kaarten. De eerste web API die ik heb gebruikt is **Pointer Events API**. Hiermee heb ik het verslepen van de kaarten naar de dropzones gemaakt. De tweede web API is **web animations API**. Deze heb ik o.a. ingezet voor het roteren van de kaarten. De derde web API die ik gebruikt heb is **localStorage API**. Deze heb ik gebruikt voor het opslaan van de 3 getrokken kaarten, waarna je de definitie/interpertatie op een volgende pagina terug kunt zien. 


## REFLECTIE

Ik vond dit een heel interessant vak, maar toch ook wel lastig. Ik heb zelf alleen in sprint 0 met een API gewerkt, maar daarvoor nog nooit, dus API's is echt iets nieuws voor mij. Ook heb ik tot deze minor nog nooit in een terminal gewerkt of eigenlijk zelfs nog bijna nooit gezien. Dus toen wij de eerste week opstartten had ik hier heel veel moeite mee en ging het me allemaal erg snel. Voor mijn gevoel werd het een beetje verteld alsof het logisch of algemene kennis was, maar dat was het voor mij gewoon echt niet. Dus daardoor was ik wel een beetje angstig voor de rest van het vak en twijfelachtig. Maar uiteindelijk viel wat je met de terminal moest doen hartstikke mee. Iets anders wat compleet nieuw voor mij was, was Astro. Het werken met componenten en layouts vond ik lastig, omdat ik het hierdoor lastig vond om te weten wat ik nou waar moest neerzetten. De gegeven workshops hierover vond ik goed te volgen, maar als je het vervolgens zelf moet doen voor jouw (ingewikkeldere) ideeën is dat toch gewoon heel anders. Ook was het hele vak vooral gericht op Javascript, waar ik ook niet super veel ervaring mee heb tot nu toe... Kortom, heel veel nieuwe dingen en uitdagingen, waardoor ik soms meer tijd kwijt was als het ware aan die dingen ontdekken en uitvinden hoe het werkt, dan aan coderen zelf. 

Het werken met Javascript vond ik, nadat ik over de eerste leer curve heen was, wel heel leuk. Ik merkte dat ik soms dingen wel echt even een aantal keer moest doen om het helemaal onder de knie te krijgen. Ik had bijvoorbeeld verschillende codepens gemaakt waar ik verschillende dingen los werkend maakte. Dus bijv een codepen voor roteren van kaarten, een codepen voor het verslepen van kaarten etc. Toen ik deze samen moest voegen waren er best wat problemen waardoor het niet werkte. Het lastige aan Javascript vind ik dat het lastig te achterhalen is waar het nou precies mis gaat. Met veel console.logs en hulp van de docent kwam ik er uiteindelijk uit gelukkig. 

Ik ben best heel tevreden over mijn eindproduct. Ik denk dat ik veel heb gedaan in korte tijd, ondanks dat alles nieuw voor me was. Ik heb grotendeels uit kunnen werken wat ik in gedachte had. Er is nog wel 1 ding wat het helemaal af had gemaakt voor mij en dat is dat gebruikers konden kiezen tussen verschillende type spreads en ze dan naar aanleiding van de spread een passende definitie kregen. Dus niet alleen van de kaart, maar echt volledig passend binnen de context. Dus dat is iets voor de toekomst misschien nog!

## BRONNENLIJST
- https://tarotapi.dev/api/v1/cards
- https://codepen.io/Sidstumple/pen/ByjXVLw
- https://codepen.io/tkdev-hub/pen/RNGBZMo
- https://developer.mozilla.org/en-US/docs/Web/API/Pointer_events
- https://developer.mozilla.org/en-US/docs/Web/API/PointerEvent/pointerId
- https://developer.mozilla.org/en-US/docs/Web/API/Element/setPointerCapture
- https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API/Using_the_Web_Animations_API
- https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage
- https://github.com/krates98/tarotcardapi


