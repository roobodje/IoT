# IoT

STAP 1:

Als eerst moet ik een account aanmaken bij Adafruit. Adafruit is een service die de Arduino aan het internet koppelt. Op deze manier kunnen we de kleur van de leds op afstand aanpassen. 
Binnen de website van Adafruit maak ik een account aan waarmee ik een persoonlijke gebruikersnaam en key kreeg. Deze moet ik later in Arduino invoeren om verbinding te kunnen maken. 

STAP 2: 

Om Arduino verbinding te laten maken met Adafruit moest ik een bestand aanmaken. Ik zocht in het library gedeelte naar adafruit IO arduino en installeerde het.
<img width="688" alt="Scherm­afbeelding 2023-10-04 om 13 36 07" src="https://github.com/roobodje/IoT/assets/118179204/4d64ad11-bd41-4c8d-b170-207811f8d8da">

STAP 3:

In Adafruit IO ging ik naar "Dashboards" en maakte een nieuw dashboard aan. In het nieuwe dashboard creëerde ik een nieuw blok via "Create New Block". Ik koos voor de "Color Picker" en gaf de feed de naam "color". Vervolgens maakte ik het blok aan.
Met deze stappen hebben we een dashboard en een feed aangemaakt waarmee we later de kleur van onze LED kunnen bedienen.
<img width="1080" alt="Scherm­afbeelding 2023-10-04 om 13 41 49" src="https://github.com/roobodje/IoT/assets/118179204/976964ed-691c-482e-86d7-466491a88ea7">


STAP 4:

Eerst moest ik het voorbeeldbestand openen. Hierin stond bijna alle code klaar om te gebruiken, ik hoefde alleen nog een paar kleine dingen aan te passen. In het tabblad 'config.h' plakte ik mijn gebruikersnaam en sleutel. Ik voerde de naam en het wachtwoord van mij hotspot in waarmee mijn laptop was vebonden. Daarna paste ik de pixel pin aan van 5 naar D5. Ik uploadde de software op mijn Arduino kit en klikte op serial monitor. Ik zorgde ervoor dat de serial monitor was ingesteld op een baudrate van 115200. Helaas kreeg ik niet het juiste resultaat. Ik kreeg geen foutmeldingen of iets, maar er leek geen verbinding te zijn. Als ik namelijk iets aanpas op de Adafruit site verandert er niks in mijn dashboard... Ik heb veel opgezocht op internet, maar het is mij niet gelukt dit probleem op te lossen.
<img width="1100" alt="Scherm­afbeelding 2023-10-04 om 13 46 23" src="https://github.com/roobodje/IoT/assets/118179204/3229f1c3-afd8-4be7-b6bb-032d281050ec">
