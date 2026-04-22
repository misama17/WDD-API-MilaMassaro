# WDD-API-MilaMassaro

Link naar mijn Notion: https://www.notion.so/Minor-Webdesign-Development-2fd4a28d1c2c8004a247e9f0794a6be0?source=copy_link 


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


## WEEK 3

**woensdag 15 april**

Vandaag was ik bij Smashing Conference.


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
