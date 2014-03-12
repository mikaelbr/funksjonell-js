# Utkast til agenda

- Hei og velkommen
- Intro: Hva er funksjonell programmering
    - "Funksjonelle språk" finnes ikke, men språk legger til rette for funksjonell programmering i ulik grad
    - Høyere ordens funksjoner
        - dvs, komponering av funksjonalitet vha funksjoner
    - Immutable state
        - mindre kompleksitet
    - Begreper vi kommer til å bruke, som deltagerne må kjenne (veldig kort)
        - Closures
        - Lexical scoping
        - Monad: "Monoid in the category of endofunctors." (for LOLs)
            + ref: http://james-iry.blogspot.no/2009/05/brief-incomplete-and-mostly-wrong.html
- Praktisk: Hvordan komme i gang med kodingen på en praktisk måte
- Oppgaver: Enkle HOF
    - Teori: 
        - hva er en HOF 
        - førsteklasses funksjon 
        - underscore.js
    - Enkle funksjoner som (veldig enkelt)
        - tar funksjoner som argumenter, 
        - returnerer funksjoner
        - holder på state vha closures
        - modifiserer oppførsel til andre funksjoner
    - Enkel bruk av filter, map, reduce fra _
    - Implementere filter, map, reduce selv (ikke farlig om alle rekker)
- Oppgaver: Partial applicaton
    - Teori: Hva er dette
    - Gjøre vha _
    - Implementere `partial` selv

- Oppgaver om verdien av immutable state???
    - Rekursjon?
    - Hvordan strukturere koden slik at en ikke trenger å mutere på stuff hele tiden?
    - Pragmatisk: *alt* må ikke være immutable. State har en plass.
- Andre oppgaver???

- Idé til større del
    + Implementere så mye som mulig av _ fra bunnen av
    + Litt større ting vha Node
        * Presentere data fra et kult API på en ny måte? (som krever en del transformering der funksjonelle konsepter kan passe godt inn)
        * Se etter API som er relevant!
