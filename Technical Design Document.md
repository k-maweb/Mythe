# Mythe
Technisch Design Document Template

Voeg een technical ontwerp/design toe aan het game design document. Een technisch ontwerp omschrijft (mogelijke) technische problemen en de desbetreffende oplossing. 

![image](https://github.com/k-maweb/Mythe/assets/167420754/23afce09-e0fa-4de8-aa79-388e43383860)


Technisch ontwerp (pre-production):
Voordat er aan het spel gewerkt wordt kun je technische ontwerpen documenteren. Je documenteerd hierbij het technische opstakel en de (mogelijke) oplossing(en). 

_Voorbeeld probleem:_
"Om ervoor te zorgen dat het laden van nieuwe gebieden in de game geen vertragingen veroorzaakt, implementeren we een 'streaming' systeem waarbij alleen de directe omgeving van de speler wordt
geladen op basis van zijn locatie. Dit zorgt voor een vloeiende spelervaring zonder haperingen tijdens het verkennen van de grote open wereld." Oplossingen die we gaan toepassen:
1. Definiëren van gebieden:
   - Definieer de spelwereld in verschillende gebieden of sectoren. Deze gebieden kunnen bijvoorbeeld worden gemarkeerd met behulp van 'triggers' of coördinaten in de spelwereld.
2. Beheer van geladen gebieden:
  - We maken een managerklasse aan die verantwoordelijk is voor het beheren van de geladen gebieden. Deze manager houdt bij welke gebieden momenteel geladen zijn en welke gebieden in de buurt van de speler liggen..


Technisch ontwerp (release): 
Dit ontwerp wordt in release fase gemaakt. 

1. Probleemomschrijving:
   - Beschrijf het technische probleem dat zich tijdens de ontwikkeling heeft voorgedaan.

2. Impact:
  - Wat was het effect van dit probleem op de gameplay, prestaties of gebruikerservaring?

3. Oplossing:
  - Beschrijf wat er is gedaan om het probleem op te lossen. Dit kan variëren van het wijzigen van code en scripts tot het implementeren van specifieke Unity-functies of plugins om het probleem aan te pakken

4. Reflectie:
  - Wat hebben we geleerd van dit proces en hoe kunnen we vergelijkbare problemen in de toekomst voorkomen?
