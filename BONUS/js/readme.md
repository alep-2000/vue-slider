PROBLEMA:
1- al click su una thumb, visualizzare in grande l'immagine corrispondente
2- applicare l'autoplay allo slider: ogni 3 secondi, cambia immagine automaticamente
3- quando il mouse va in hover sullo slider, bloccare l'autoplay e farlo riprendere quando esce

SOLUZIONE:
1 - Creare un evento al click sull'img;
2 - Creare una funzione per mostrare l'immagine attiva;
3 - Richiamare la funzione nell'evento creato precedentemente;
4 - Crare una proprietà a cui assegniamo valore null;
5 - Creare un set interval per creare l'autoplay dentro una funzione;
6 - Creare metodo created in cui richiamo la funzione autoplay;
7 - Aggiungere un evento al click;
8 - Creare una funzione per bloccare l'autoplay;
    8.1 - Creare un controllo;
    8.2 - ? SE il mouse è sopra l'immagine bloccare l'autoplay;
    8.3 - : ALTRIMENTI l'autoplay riprende;
9 - Richiamare la funzione nell'evento creato precedentemente;