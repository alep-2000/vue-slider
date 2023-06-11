PROBLEMA:
1- al click su una thumb, visualizzare in grande l'immagine corrispondente
2- applicare l'autoplay allo slider: ogni 3 secondi, cambia immagine automaticamente
3- quando il mouse va in hover sullo slider, bloccare l'autoplay e farlo riprendere quando esce

SOLUZIONE:
1 - Creare un evento al click sull'img;
2 - Creare una funzione per mostrare l'immagine attiva;
3 - Richiamare la funzione nell'evento creato precedentemente;
4 - Creare un set interval per creare l'autoplay dentro una funzione;
5 - Aggiungere un evento al click;
6 - Creare una funzione per bloccare l'autoplay;
    6.1 - Creare un controllo;
    6.2 - ? SE il mouse è sopra l'immagine bloccare l'autoplay;
    6.3 - : ALTRIMENTI l'autoplay riprende;
7 - Richiamare la funzione nell'evento creato precedentemente;