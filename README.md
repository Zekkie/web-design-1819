#Back to the basics

##Demo
[Klik hier voor de demo](https://zekkie.github.io/dessembler/)

##CLI!!
Mijn denkwijze voor dit ontwerp was, Marijn heeft waarschijnlijk moeite met het gebruiken van een muis en hij is programmeur. Dus dacht ik, ik ga maar een soort taal ontwikkelen waarbij hij met commando's een element kan verslepen van een plek naar een ander.

###De taal
Omdat Marijn het liefst zo minder mogelijk typt heb ik een taal proberen te ontwerpen waarbij hij met zo min mogelijk toetsaanslagen een element van A naar B kan verplaatsen. Daarbij kwam ik als eerste instantie uit op "mov w,q,1". Dit zijn 9 toets aanslagen. Daarna heb ik mov veranderd in alleen m, waarbij de toetsaanslagen van 9 naar 7. En daarmee heb ik mijn tests gedaan.


#Test Scenario
Marijn is klaar met een taak en wil vanuit zijn TODO lijst een nieuwe taak verplaatsen naar WORKING ON. Echter, vanwege zijn beperking kan hij moeilijk slepen van A naar B.

##Jobstory
Wanneer ik klaar ben met een taak, wil ik vanuit mijn TODO lijst een nieuwe taak slepen naar mijn WORKING-ON lijst, zodat ik kan bijhouden waar ik mee bezig ben.

#Test 1

##Opvallend
Marijn gebruikte GEEN tabs om te navigeren, maar spaties en zijn trackpad. Hij gebruikte liever H,J,K,L om te navigeren dan pijltjes toetsen of W,A,S,D. Dit omdat hij gewend was om in VI te gebruiken. VI is een oude text editor in UNIX systemen die in de terminal te gebruiken is. En voor iemand met spasmes kon hij best wel snel en accuraat typen. 

##Uitkomsten test 1
Hij vond het idee leuk alleen hij had een paar aanmerkingen. Hij wilde geen spatie's typen en case insensitive typing. Want hij had perongeluk zijn capslock aan gehouden en toen werkte de code niet meer. 

###Iteratie 
Aan de hand van zijn feedback en bevindingen heb ik het ontwerp geweizigd. Door comma's en spaties te verwijderen is de commando mwq1 geworden. En daardoor zijn de toetsaanslagen gehalveerd van het originele 9 toetsen naar 4. Ook heb ik de input en buttons groter gemaakt zodat hij daar makkelijker bij kon met zijn muis.

#Test 2

##Uitkomsten test 2
Dit keer had Marijn maar een aanmerking. Hij had liever dat hij als eerst zijn target kon selecteren en daarna de destination. Dus in plaats van MWQ1, wilde hij dat het MQW1 zou zijn.

###Iteratie
Omdat wij pas laat waren begonnen met testen, is er geen tijd meer om een iteratie te doen. Maar Marijn had nog wel een leuke feature voorstel. Hij zou ook graag via een commando content van een card willen wijzigen.


#Wishes
