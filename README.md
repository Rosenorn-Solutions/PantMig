# PantMig
## Et projekt til fordel for alle og miljøet!


PantMig skal fungere som en platform til at forbinde de folk der ønsker at donere deres pan (eller bare gerne vil slippe for opgaven selv), og dem hvor pengene kan betyde meget! 

I Danmark er vi generelt gode til at pante vores produkter igen - omkring 93% af den solgte pant kommer tilbage, men det kan enten gøres bedre, med højere procenter, eller på en anden måde. 

For nogle er det halv-omstændigt at slæbe to store poser pant til den lokale automat, eller det er bare ikke en prioritet at få gjort - lad en tage opgaven, og se det hele give værdi. 


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





