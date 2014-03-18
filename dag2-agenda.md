# Utkast til agenda for dag 2

- Repetisjon av funksjonell programmering
- Motivasjon til FRP
- Introduksjon til reactive programming

**(Pause)**

- Introduksjon av praktisk FRP
    - Nevne forskjellige implementasjoner
    - Introdusere Bacon.js (Praktisk I)
        - Gå igjennom innkapsling av reaktive datatyper og onValue
            - Fra event target eller fra data (constant, interval, fromArray)
            - end() og error handling
            - Oppgaver om datatyper + LF

**(Pause)**

- Introduksjon av praktisk FRP
    - Videre om Bacon.js (Praktisk II)
        - Kjapp oppsummering om subscribers
            - Lazy i utgangspunktet
            - Subscribers returnerer unsubscribe
            - log særtilfelle (legger til subscriber!)
        - Gjennomgang av basic kombinatorer
            - Map, Filter, DoAction (Each)
            - fold/scan
            - Oppgaver + LF

**(Pause)**

- Mer avansert praksis
    - Streaming teori (Praktisk III)
        - Gå igjennom forhold mellom event streams og properties
            - toProperty()
            - Filtrere/mappe på property
        - Gå igjennom håndtering av property/eventstreams
            - merge/combine
            - and/or
            - sampleby
            - debounce/throttle/take/skip
            - flatMap
        - Oppgaver + LF

**(Pause)**

- Introdusere case
    - Løsing av case.
    - LF av case

- Videreutvikling av case basert på forslag/idéer eller egne innslag.
- Ferdig for helgen