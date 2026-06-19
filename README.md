# project_upgrade_3018pro_CNC
Dit project heft de tekort komingen van de Vevor S3018 Pro Max op

 1. Niet stijf genoeg De RVS geleiders buigen door.
 2. De Aluminiumm plaat is niet vlak.
 3. De spindel motor heeft een te klein vermogen.
 4. De gebruikte controller heeft de in en uitgangen direct naar buiten uitgevoerd, gevoelig voor storing.
 5. Geen eindschatelaars voor homing.
 6. Te lichte XYZ motoren.
 7. Ondersteunt alleen GRBL.
 8. De moeren hebben backlash bij belasting.
 9. Geen Z-probe ingang
 10. Geen mist of Flood aansluiting

# aanpassingen

 1. Maak gebruik van aluminium profielen en lineaire rails met blokken.
 2. gebruik een vlakke stijve kunstof basis plaat.
 3. Maak gebruik van een borstelloze motor.
 4. Alle in en uitgangen worden gebufferd.
 5. WYZ eindschakelaars worden toegevoegd.
 6. De XYZmotoren zijn door zwaardere typen vervangen.
 7. Er is een nieuwe controller pico-CNC/GRBLHAL toegevoegd (RP2040 of RP2350, 64 bit).
 8. De moeren worden nu gesteld zodat er geen backlash meer is.
 9. aansluiting voor een touch plate of direct met de spindle
 10. ER zijn twee solid state uitgangen didirect uit de CNC router software aangestuurd kunnen worden.
