# Namen en taakverdeling
student A: Ilyas  
opdrachten gemaakt 
1,2,3,4,5,6,7
- challenge B
- challenge D


student B: Maud 
opdrachten gemaakt 
2,3,4,5,6,7 
- challenge A
- challenge C
- challenge E


# bewijs 
- Installatie student A: bewijs/installatie-A.png
- Installatie student B: bewijs/installatie-B.png
- Overzicht met drie games: bewijs/overzicht.png
- Validatiefout lege titel: bewijs/validatie-lege-titel.png


# Kennischeck les 1:

1. de docent template is de basis voor een simpele start, onze repository is ons eigen project dat we kunnen weizigen zonder dat basis wordt veranderd en de clone is de lokale kopie waarmee je op je laptop werkt
2. omdat ik dan de commit deel met mijn collaborator via github zodat hun het kunnen ophalen
3. PHP pakketen
4. omdat de games in ieder zijn eigen database zit
5. het formulier gebruikt noValidatie en de games komen in react 

# kennischeck les 2:
1. De browser mag niet rechtstreeks in de database schrijven. De route vangt de wijziging op en save() slaat ze op
2. Inloggen is je hebt een account. Eigenaar is deze game is van jou. Dat is niet hetzelfde, dus wordt apart gecontroleerd
3. Props komen van buiten van Laravel en zijn alleen-lezen. State houdt de pagina zelf bij en kan veranderen. 
4. games is de volledige lijst met voortgang. visibleGames telt hoeveel er na het zoeken nog zichtbaar zijn
5. Het wist alleen de zoekterm in de pagina. Er wordt niets opgeslagen, dus geen Laravel of database nodig.
6. bijna elke code hebben we zelf toe gevoegdt allen bij die laast 2 opdracht hebben we hulp gevraagt aan ia 






# opdracht 2 Test je applicatie
Test	Verwacht    uitkomt    status 
1. Toevoegen en vernieuwen           Game blijft in de lijst          de nieuwe toegevoegte gaames zijn zichtbaar     geslaagd 
2. Lege titel versturen 	        “Vul een titel in.”; geen extra game        vul een titel in        geslaagd 
3. Titel met 81 tekens versturen 	“Gebruik maximaal 80 tekens.”; geen extra game        Gebruik maximaal 80 tekens     geslaad 
4. Status heen en terug wijzigen, telkens vernieuwen     	De nieuwe status blijft beide keren opgeslagen            de satus blijven opgeslagen     geslaagd       
5. MARIO en  mario  zoeken.	        Beide vinden Mario Kart.        kan met beiden mario kart vinden            geslaag 
6. zzzz zoeken                  	Geen kaarten, wel de melding “Geen games gevonden”       Geen games gevonden. Probeer een andere zoektekst       geslaagd
7. Zoeken met één uitgespeelde game van drie     	De voortgang blijft “1 van 3 uitgespeeld”           der blijft het zelfde staan          geslaagd 
8. Wis zoeken gebruiken          	Zoekveld leeg en alle kaarten terug         zoekveld leeg alle kaarten komen weer terug     geslaagd 
9. Resultatenteller controleren  	3 van 3, 1 van 3 en 0 van 3 bij de voorbeelden hierboven               de reasultaten klopen           geslaagd   
10. Uitloggen en /games openen    	Je komt bij het inlogscherm                 moet eerst weer inlogen             geslaagd 
11. Tweede account op dezelfde laptop maken      	Nieuwe, lege collectie      krijg je lege collectie             geslaagd
12. Code pushen en partner laten pullen.	Partner ziet de codewijziging, maar behoudt eigen accounts en games     partner zie de codewijziging maar heeft zijn iegen games nog   geslaagd 




# overdracht via GitHub
we deeden gewoon het gewoon om de buurt dus als maud de opdracht had gemaakt push ze die naar ilyas en dan pull die hem en dan hebben we allen bij die opdracht. 