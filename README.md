Programmet læser en tekstfil kaldet playlist.txt, hvor hver linje indeholder en sangtitel. Når programmet starter, åbner det filen og gennemgår linjerne én for én. Hver titel får fjernet sit newline-tegn og bliver derefter lagt ind i en enkelt-lænket liste (singly linked list), hvor hvert element repræsenterer et musiknummer.

Når playlisten er indlæst, udfører programmet to ændringer for at demonstrere manipulation af linked lists: det sletter node nummer 4 i rækkefølgen, og indsætter derefter et nyt nummer på position 3. Disse operationer bruger funktioner fra den tilhørende linked-list-implementering, som håndterer indsættelse, sletning og navigation i listen.

Til sidst gemmer programmet hele den opdaterede playlist i en ny fil, playlist-out.txt, hvor ændringerne fremgår. Samtidig udskriver det alle numrene til terminalen i deres nuværende rækkefølge. Hele projektet demonstrerer dermed filhåndtering, dynamisk hukommelse og brugen af enkelt-lænkede lister i C.
