# PantMig
## A project in favour of everybody and environment

PantMig is to function as a platform for connecting people, who wish to donate their pant, and the people who will take the task for the payout of returned pant. 

In Denmark we are generally good at returning our recycleables, about 93% of the items with Pants gets returned, but we an do that better, and potentially redistribute the money. 

For some it's a big task to get two bags of pant down to the local machine, or for some, it's just not a priority to do themselves - a segment of people we want to hit, and let others take the task and pant. Have the entire task and end result give some value. 
We already have a lot of people collecting pant on the streets, lookring through public trashcans, and they would get a lot potential 

The following screenshots (coming) show the webpace and emulated Android/iOS PantMig app session.

## Webpage Screenshots
![alt_text]()


## App Screenshots
![alt_text]()

### NGO's and Other interestgroups
In Aalborg there is a "café" mainly targeting citizens with needs regarding food or a safe social environment away from streets and or the home. A lot of those people would especially have great use of this donation-based system. 

Café Parasollen already has a program for collecting pant, but it's on a "contract"-based premise for the place and through Parasollen the users. They drive out and collect bigger amount of Pant from companies/ offies, and sometimes at private homes. 

The values collected is calculted in a way by Parasollen, that it counts as a "salary", which supplement the social security benefits (førtidspension, kontanthjælp etc) or public pension, without the salary getting reduction in public payout. 

PantMig would be 100% supplementary to the Parasollen projects, and the individual users can avoid getting the pant reducted against their income. 

PantMig is NOT connected to any charity or NGO, and has no direct product to offer but the platform for donations. 

PantMig get no cut from donated pant, or any specific 





# PantMig
## Et projekt til fordel for alle og miljøet!


PantMig skal fungere som en platform til at forbinde de folk der ønsker at donere deres pant (eller bare gerne vil slippe for opgaven selv), og dem hvor pengene kan betyde meget! 

I Danmark er vi generelt gode til at pante vores produkter igen - omkring 93% af den solgte pant kommer tilbage, men det kan enten gøres bedre, med højere procenter, eller på en anden måde. 

For nogle er det omstændigt at slæbe to store poser pant til den lokale automat, eller det er bare ikke en prioritet at få gjort - lad en tage opgaven, og se det hele give værdi. 


I Danmark har vi allerede folk, der aktivt går på gaderne og samler panten smidt i skraldespandene - de ville få stor glæde i poser ad gangen. 

Simpel illustration af hvordan PantMig skal fungere: 
![alt text](https://github.com/Rosenorn-Solutions/PantMig/blob/main/Documentation/Models/PantMigUsecasePeterSara.png "Simpel forklaring.")


En Bruger kan sætte et "I nærheden af mig"-punkt med en MAX radius, hvor de vil få vist eller subscribe til notifikation om opgaver i området. 
Brugeren vil få vist Pant-opgaver, og nærmeste Pantmaskine inden for denne cirkel. 

(HVIS MULIGT skal der nusses regler, for at se om den donerede pant kan registreres passende, og potentielt direkte overføres til Skat (godt sentiment for at donere panten!).)


Hvis IKKE det er muligt, får brugerne som minimum:
   - Delt rapport på hvornår en Opgave blev:  oprettet -> Taget -> Afsluttet 
   - Samlet rapport på værdien af donationer (cirka tal)
   - Samlet rapport på værdien i den genanvendte materiale (cirka tal)
   - (Ønske) Mulighed for at tilføje "Følge"-tilstand på brugeren der Donerede panten. Hvis Donator godkender - kan der sendes direkte notifikationer, når der oprettet opgaver.


## Techstack
### Crossplatform solution
PantMig er bygget på: 
   - DaisyUI
   - React
   - MongoDB (JSON dokumenter)
   - C# 

## Brugerne
For at beskytte og undgå diskriminerende adfærd på platformen, bliver der taget højde for: 
   - Brugere får tildelt et automatisk brugernavn, der ikke kan ændres, baseret på dyreracer fra Danmarks natur + 2-3 bogstaver fra brugerens navn: Christine Larsen -> Skovmår-RCA, Lucas Rosenørn -> Tårnfalk_ELØ
   - Pantere kan rate en Donator -> Upassende adfærd, manglende fremmøde, affald i pant osv., kan være en del af vurderingen. Pantere kan vurderes på -> Upassende adfærd, fremmøde.
   - Hvis en bruger bliver vurderet som problematisk mere end tre gangen, vil der indsættes et ban-system. 

## Parasollen og Varmestuen
Bruger Input og Samarbejde: 
I Aalborg har Café Parasollen et program, Pantsjakket, der kører ud til afhentning af større mængder pant ved virksomheder og private. 
Panten afregning sådan at brugere af Parasollen og arbejderne få en løn, der kan supplementere offentligstøtte eller pension, uden at tage i deres pension. 
-> de parter har en direkte aftale mellem hinanden. 
PantMig vil være 100% udenfor Pantsjakkets regi - så arbejdere vil ikke blive påvirket af indtægter fra opgaver taget via PantMig. 
Ligeledes er PantMig ikke et direkte forbundet produkt til nogen velgørenhedsentitet med socialt arbejde - og derved også åben for deltagelse for alle. 





