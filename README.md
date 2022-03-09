# Rubiks Cube @CSS-TO-THE-RESCUE-2122

## Table of contents
* [Eindresultaat](https://github.com/jody29/RubiksCube#eindresultaat)
* [Opdracht](https://github.com/jody29/RubiksCube#opdracht)
* [Technieken](https://github.com/jody29/RubiksCube#technieken)
* [Week 1](https://github.com/jody29/RubiksCube#week1)
* [Week 2]()
* [Week 3]()
* [Week 4]()
* [Credits]()

## Eindresultaat
<img width="1440" alt="Schermafbeelding 2022-03-09 om 13 29 16" src="https://user-images.githubusercontent.com/66092262/157444774-b13a7b48-afb5-4aba-ad2a-8f99be253c63.png">

## Opdracht
Ik heb ervoor gekozen om met CSS een interactieve rubiks kubus te gaan maken. Ik heb hiervoor gekozen, omdat ik hier de meeste uitdaging in zag zitten. Mijn grootste uitdaging in deze opdracht zal vooral alles goed op zn plek krijgen en zo efficient mogelijke code te schrijven.

## Technieken
* 3D-transform/perspective
* Custom Properties
* Grid
* Calc
* Selectoren
* Flexbox
* Animation
* Interaction

## Week 1
![Schermafbeelding 2022-03-04 om 01 23 17](https://user-images.githubusercontent.com/66092262/156675547-6a0a08fe-7959-4a25-be6f-945e51818709.png)

In week 1 ben ik op advies van Sanne begonnen om een enkel blokje te maken. Om namelijk een kubus te maken heb ik 26 van deze blokjes nodig. Ik heb er dus voor gekozen om 26 `<ul>` elementen te maken met daarin 6 `<li>` elementen erin. Deze list items zijn dan de zijdes van een blokjes. De lists zijn dan de blokjes. Ik heb hiervoor wel wat hulp gehad, onder anderen de [codepen van Sanne](https://codepen.io/shooft/pens/showcase) waar al een begin is gemaakt. Deze was heel nuttig om een goed beeld te krijgen hoe ik de kubus kan gaan maken. Nadat ik 26 blokjes had gemaakt, heb ik ervoor gezorgd dat ze gecentreerd staan. Vanuit dit middelpunt wil ik de blokjes gaan positioneren door middel van transform: translate en rotate.

### Wat is gelukt?
* Het maken van een 26 blokjes
* Gebruik van 3d en perspective

### Wat ging minder goed?
* Ik vond het lastig om een beeld te krijgen hoe ik de kubus uiteindelijk ging maken

### Wat heb ik geleerd?
* Dat je in CSS ook variabelen kan aanmaken en aanroepen, net als in JavaScript.

## Week 2
![cube_week2](https://user-images.githubusercontent.com/66092262/157346909-cee9206e-2f01-4be0-9e7f-2e281179edb9.png)

In week 2 kwam ik erachter dat ik de blokjes van mijn kubus niet kan draaien, omdat ik niet in layers heb gewerkt. Het is namelijk handiger als ik dmv translate begin met de bottom layer en zo omhoog ga. Op deze manier kan ik makkelijker een zijde selecteren en zo draaien. Op de afbeelding hierboven is te zien hoe dit is gegaan. Ik heb deze week ook ervoor gezorgd dat mijn code een stuk netter en overzichtelijker is. Hierdoor is het voor mij makkelijker te volgen als ik iets wil aanpassen.

### Wat is gelukt?
* Ik heb nu een volledige kubus die goed in elkaar zit.
* Gebruik gemaakt van custom properties.

### Wat ging minder goed?
* Het selecteren van een zeide ging nogal lastig, hier heb ik wel hulp voor gevraagd.

### Wat heb ik geleerd?
* Hoe je goed gebruik kan maken van de custom properties en deze kan aanpassen dmv checkboxes.

## Week 3
![cube_week3](https://user-images.githubusercontent.com/66092262/157446787-c876176a-7091-4e41-aff1-2d33e2669e0e.png)

In week 3 ben ik aan de slag gegaan met de controls van de kubus. Ik heb de controls gepositioneerd door een grid te gebruiken. Voor de controls om de kubus heb ik een `grid-template-columns: repeat(5, 1fr)` en `grid-template-rows: repeat(5, 1fr)` meegegeven waardoor er een grid ontstaat van 5 bij 5. Vervolgens heb ik elke label die in de grid zit gepositioneerd met een `grid-area`. Voor de kleine controls heb ik een `grid-template-columns: repeat(3, 1fr)` en `grid-template-rows: repeat(2, 1fr)` meegegeven zodat er een grid komt van 3 breedt en 2 hoog. Ook hierin zijn de labels gepositioneerd dmv grid-area. Om de kubus responsive te maken heb ik gebruik gemaakt van de vmin eenheid.

### Wat is gelukt?
* Kubus is interactief
* Kubus is responsive
* Controls zitten in een grid

### Wat ging minder goed?
* Het maken van het grid had ik erg veel moeite mee, dit was vooral veel finetunen.

### Wat heb ik geleerd?
* vmin eenheid
* grid-area
* de repeat in grid-template-rows/columns

## Week 4
<img width="1440" alt="Schermafbeelding 2022-03-09 om 13 29 16" src="https://user-images.githubusercontent.com/66092262/157444774-b13a7b48-afb5-4aba-ad2a-8f99be253c63.png">

In de laatste week was het vooral de bedoeling dat ik wat extraatjes erbij kon doen. Zo heb ik ervoor gezorgd dat het nu mogelijk is om een afbeelding te tonen op een zijde van de kubus. Dit heb ik gedaan door op de ::before van een `<li>` een background-image te zetten. Dit moet dan alleen op een zijde gebeuren. Ik heb een zijde kunnen selecteren door ul 1, 2, 3, 10, 11, 12, 19, 20 en 21 te selecteren. Per blokje geef ik de background-image een andere background-position. Zo komt er uiteindelijk op een zijde een afbeelding. Ook heb ik een knop toegevoegd dat de kubus transparant is. Vervolgens heb ik nog een crazy modus toegevoegd. Als je op de knop klikt dan krijgt de `<main>` een repeating-radial-gradient. Deze animeer ik door de background-size van 100% naar 200% te laten gaan in een loop. Dit moet een trippy gevoel krijgen.

## Credits
* Huilsessies
* [Sanne 't Hooft](https://github.com/shooft)
* [Pepijn](https://github.com/ppijn)
* [Bas](https://github.com/basv1996)
