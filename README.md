# Emmer

Een klein reflectie-instrument rond de emmer-metafoor: wat je emmer vult, en
welke ordening hem weer leegt.

**→ [asswijzer.irskolts.nl](https://asswijzer.irskolts.nl)**

Gebaseerd op de ASSwijzer-methodiek (Werkboek ASSwijzer, EvenZicht), een
behandelmethodiek voor autisme-gerelateerde overbelasting. Dit is geen product
van EvenZicht en vervangt geen behandeling; het is gemaakt voor eigen gebruik,
om mee te nemen naar een gesprek met een behandelaar.

## Hoe het werkt

Je zet erin wat je emmer vult (prikkels, contact en communicatie, veranderingen
en overzicht, anders) en welke ordening hem leegt — zowel *eigen ordening*, wat
je zelf doet, als *geboden ordening*, wat je omgeving je biedt. De regenton laat
het verschil zien, en twee balkjes laten zien hoe die twee vormen van ordening
zich tot elkaar verhouden.

Er staan met opzet nergens cijfers of scores in beeld.

## Je gegevens

Alles blijft in je eigen browser staan (`localStorage`). Er is geen server, geen
account en geen enkele vorm van meekijken: wat je invult verlaat je apparaat
niet.

Wil je op een ander apparaat verder, dan kun je exporteren naar een bestand. Dat
bestand is versleuteld met een wachtwoord dat je zelf kiest (AES-GCM, sleutel via
PBKDF2), zodat er niets leesbaars in staat als het ergens rondslingert. Raak je
het wachtwoord kwijt, dan is alleen dat ene bestand onbruikbaar — wat in je
browser staat blijft gewoon staan.

De pagina haalt lettertypes op bij Google Fonts. Verder gaat er niets naar buiten.

## Techniek

Eén HTML-bestand, zonder build-stap en zonder dependencies. De regenton is
inline SVG. Openen kan ook gewoon door het bestand lokaal te bewaren en te
dubbelklikken.
