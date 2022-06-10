# SEPE-HP_PRIME
Marcello Manfrin 01/04/2022

Raccolta di codici per la risoluzione di esercizi di Sistemi Elettrici Per l'Energia per calcolatrice grafica programmabile HP PRIME.

Scarica "HP Prime Connectivity Kit" per caricare sulla calcolatrice i programmi da: https://www.hpcalc.org/details/8938.

Per usare i programmi, una volta trasferiti sulla calcolatrice, premere il tasto toolbox (quello con l'immagine della cassetta degli attrezzi), selezionare il programma e premere enter senza inserire alcun argomento tra parentesi.

Ogni programma adotta la filosofia "domanda-risposta" dove il software, una volta fatto girare, chiede volta per volta i valori in input necessari (quindi ogni programma non necessita di argomenti in input).
È stata adottata questa scelta di design perchè permette, secondo mia opinione personale, un'interfaccia più user-friendly e plug-n-play verso chi si trova alle prime armi con il calcolatore grafico.


Questa raccolta contiene:

**1. Parziale1:**

1.1 ReteTotale:
calcola e stampa tutti i parametri di una rete a costanti distribuite ad un numero arbitrario di tratte e terne per tratta compresa la matrice di trasmissione totale (calcolata come cascata delle singole) che viene salvata nello slot di memoria M0 per essere richiamata dai programmi successivi;

1.2 Energizzazione:
calcola e stampa la tensione subtransitoria e la corrente a vuoto di una ipotetica energiggazione della linea la cui matrice di trasmissione è salvata nello slot M0;

1.3 Ossanna:
calcola e stampa tutti i parametri necessari a verificare la fattibilità della realizzazione fisica di un sistema tramite il teorema di ossanna;

1.4 CompDer:
compensa per un certo valore di potenza reattiva la rete salvata nello slot M0 (il programma ipotizza una compensazione uguale alla partenza e all'arrivo) e ne calcola e stampa i parametri.


**2. Parziale2:**

2.1 DisturboFrequenza:
calcola e stampa la variazione di frequenza conseguente alla presenza di un disturbo di potenza;

2.2 ImpedenzaOnda:
calcola e stampa l'impedenza d'onda di una linea di trasmissione forniti tipo di linea e adeguati parametri;

2.3 Fulminazioni:
calcola e stampa, a seconda della casistica del tipo di fulminaizone, la minima corrente equivalente di fulminaizone affinchè avvenga la scarica e ne indica la probabilità;

2.4 Graticcio:
calcola e stampa i parametri per lo svolgimento del classico esercizio del diagramma a graticcio.


Il file del secondo parziale è scarsamente commentato in quanto i codici sono relativamente banali e, facciamola breve, non c'avevo voglia.

Come per ogni mio pdf di appunti che lascio girare tra gruppi universitari, anche qui rinnovo il "prendete e fateci quello che volete ma per carità non fate gli stronzi".

In bocca al lupo per l'esame di SEPE c:
