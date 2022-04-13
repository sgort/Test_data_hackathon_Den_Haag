# Toelichting

Bevat testgevallen voor Individuele Inkomenstoeslag zoals gespecificeerd voor de gemeente Utrecht. Informatie hierover in context wordt [hier](https://open-regels.nl/methoden/ALEF/) toegelicht. En dit is de [directe link](https://open-regels.nl/Rapportages/Rapportage_Individuele_Inkomenstoeslag.html) naar de specificatie.

De testgevallen specificeren de volgende attributen:
- woonplaats
- oawLeeftijdBehaald
- ouderDan21
- thuiswonendeKinderen
- inkomenPerMaand
- vermogen

De inhoud van "test" komt overeen met de Regelgroep Recht beschrijving zoals die gespecificeerd is in de specificatie (zie illustratie hieronder).

![Recht beschrijving](./images/rechtbeschrijving.png)

Het veld "recht", tenslotte, bevat de verwachtte uitkomst van de regelservice die we confronteren met het onderhavige testgeval. Het veld "postmanCheck" toont de waarde bij handmatige test op het moment van aanmaken testgevallen.

## Afwijkende testgevallen

De set bevat óók afwijkende testgevallen:

- waar een waarde ontbreekt is deze geen onderdeel van de criteria voor recht beschrijving
- waar een waarde "N/A" is deze bedoeld een test te zijn voor incomplete informatie, allen bedoeld een testgeval te zijn voor Recht beschrijving 01.