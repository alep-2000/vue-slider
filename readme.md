PROBLEMA:
Partendo dal markup della versione svolta in js plain, rifare lo slider ma questa volta usando Vue. Nello zip allegato trovate le immagini, il file index.html, il file js con già l'array di oggetti impostato ed il file css.

SOLUZIONE:
1 - Creare la struttura di Vuejs nel file script;
2 - Aggiungere nel data l'array di oggetti;
3 - Creare una variabile con l'immagine corrente settata a 0;
    3.1 - Utilizzare il v-bind e la variabile nell'src per inserire le immagini dinamicamente;
4 - Creare una variabile per il titolo e una per il paragrafo;
    4.1 - Utilizzare v-bind e la variabile per inserire titolo e paragrafo dinamicamente;
5 - Applicare al div con la classe thumb il v-for per inserire dinamicamente le immagini;
    5.1 - Creare una condizione per spostare la classe active da un immagine all'altra;
    5.2 - ? SE è l'immagine corrente e uguale all'indice applica la classe active;
    5.3 - :ALTRIMENTI vai avanti;
6 - Creare un evento al click per andare avanti o indietro nelle immagini;
7 - Creare la funzione da collegare all'evento click per andare avanti o indietro;
    7.1 - Creare una condizione;
    7.2 - ? SE l'immagine corrente è uguale alla lunghezza dell'array - 1, l'immagine corrente = 0;
    7.3 - : ALTRIMENTI l'immagine corrente è uguale alla lunghezza dell'array - 1;
