
NETTSIDE TIL PREDIKSJON AV OPPHOLDSLENGDE PÅ SYKEHUS



Formål og målgruppe:

Formålet til denne brukerdokumentasjonen er å gi brukeren en grundig forståelse av hvordan appen kan utnyttet optimalt. Applikasjonen er i hovedsak rettet mot helsepersonell, sykepleiere og leger som i teorien kan anvende appen til å predikere sykehusopphold for pasienter basert på ulike helserelaterte variabler.



Systemkrav:

For å kunne kjøre appen er det essensielt at brukeren har lastet ned og pakket ut programmet. Brukeren må også ha en oppdatert versjon av python installert. I tillegg er det nødvendig å laste ned følgende biblioteker for at applikasjonen skal kjøre: numpy, pandas, pickle, flask, waitress og logging.

Du kan laste ned bibliotekene ved å kjøre følgende kommandoer i terminalen.

pip install numpy
pip install pandas
pip install pickle
pip install flask
pip install waitress


Brukeren må også ha en nettleser, som f.eks Chrome eller Firefox. 



Hvordan kjøre programmet:

Her anbefaler jeg at du kjører programmet lokalt på din PC. Her er fremgangsmåten for å kjøre programmet:

Hvis du bruker windows/linux:

1. Åpne Windows Powershell.
2. Naviger deg til dit du lagrer programmet. cd /Users/ditt_brukernavn/Mappenavn
3. Kjøre appen på følgende vis: python app.py
4. Åpne din nettleser, og skriv inn følgende addresse: http://localhost:8080/

Hvis du bruker Mac:

1. Åpne Terminal
2. Naviger deg til dit du lagrer programmet. cd /Users/ditt_brukernavn/Mappenavn
3. Kjøre appen på følgende vis: python app.py
4. Åpne din nettleser, og skriv inn følgende addresse: http://localhost:8080/



Brukerveiledning:

Har du følgt stegene ovenfor, vil applikasjonen vises foran deg på nettsiden. Nå har du muligheten til å fylle inn verdier for de ulike variablene.

Om du ønsker kan du trykke på "Median verdi". Da fylles medianverdiene for alle de numeriske variablene inn automatisk. Husk at du fremdeles velge verdier for kategoriske data.

Når du har fylt inn verdier for alle variablene, trykk "Prediker". Pasientens predikerte oppholdslengde vises da nederst på skjermen.



Feilsøking:

Applikasjonen kontrollerer automatisk at de oppgitte verdiene er gyldige. Merk at:

* Brukeren kan ikke fylle inn tekst, input må være numerisk.
* Negative numeriske verdier gir feilmelding.
* Brukeren må fylle inn alle feltene.



