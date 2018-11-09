Country-UI er en enkel React-applikasjon som lister nyttig informasjon om alle land i verden.

## Oppgave


1. Country-UI skal hente ut alle land gjennom datatjenestene til `restcountries.eu`, mer spesifikt [denne](https://restcountries.eu/rest/v2/all). Kallet skal gjøres automatisk.
2. Svaret fra API-kallet skal listes i en tabellvisning, der hver rad inneholder informasjon om landets navn, verdensdel og hovedstad. Flagget til landet skal også vises.
3. Siden som viser tabellen, skal ha en overskrift som sier hvor mange land den har hentet fra datatjenesten.
4. Tabellvisningen skal ha en knapp som sorterer landene alfabetisk, og bytter mellom å sortere fra a-å til å-a. Det skal gå tydelig frem i hvilken sorteringordre listen er sortert etter.
5. Dersom man trykker på en rad, skal raden ekspandere seg og vise informasjon om landets offisielle språk.
6. Tabellen skal kun vise 20 land om gangen per side, og det skal være mulig å hoppe fra side til side. Det skal med andre ord være en paginert tabell.
7. I tillegg skal applikasjonen ha en statisk `header` som viser navnet på applikasjonen.


### Design

Utvikleren står fritt til å velge hvordan applikasjon skal se ut, forutsatt at applikasjonen er enkel å bruke og inneholder alle kravene som står beskrevet ovenfor.

### Avhengigheter

Utvikleren står fritt frem til å bruke tredjepartsavhengigheter som kreves for å løse oppgaven, så sant de er nøye gjennomtenkt og gir verdi for prosjektet.
