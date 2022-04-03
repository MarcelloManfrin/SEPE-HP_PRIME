# SEPE-HP_PRIME
Marcello Manfrin 01/04/2022

Raccolta di codici per la risoluzione di esercizi di Sistemi Elettrici Per l'Energia per calcolatrice grafica programmabile HP PRIME.

Scarica "HP Prime Connectivity Kit" per caricare sulla calcolatrice i programmi.

Ogni programma adotta la filosofia "domanda-risposta" dove il software, una volta fatto girare, chiede volta per volta i valori in input necessari (quindi ogni programma non necessita di argomenti in input).
È stata adottata questa scelta di design perchè permette, secondo mia opinione personale, un'interfaccia più user-friendly e plug-n-play verso chi si trova alle prime armi con il calcolatore grafico.


Questa raccolta contiene:

1) ReteTotale
calcola e stampa tutti i parametri di una rete a costanti distribuite ad un numero arbitrario di tratte e terne per tratta compresa la matrice di trasmissione totale (calcolata come cascata delle singole) che viene salvata nello slot di memoria M0 per essere richiamata dai programmi successivi;

2) Energiggazione
calcola e stampa la tensione subtransitoria e la corrente a vuoto di una ipotetica energiggazione della linea la cui matrice di trasmissione è salvata nello slot M0;

3) Ossanna
calcola e stampa tutti i parametri necessari a verificare la fattibilità della realizzazione fisica di un sistema tramite il teorema di ossanna;

4) CompDer
compensa per un certo valore di potenza reattiva la rete salvata nello slot M0 (il programma ipotizza una compensazione uguale alla partenza e all'arrivo) e ne calcola e stampa i parametri.


Come per ogni mio pdf di appunti che lascio girare tra gruppi universitari, anche qui rinnovo il "prendete e fateci quello che volete ma per carità non fate gli stronzi".

In bocca al lupo per l'esame di SEPE c:
