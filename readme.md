# Simon Says #

Visualizzare in pagina 5 numeri casuali diversi. Da lì parte un timer di 30 secondi.
 Dopo 30 secondi i numeri scompaiono e l'utente deve inserire, uno alla volta, i numeri che ha visto precedentemente, tramite il prompt().
Dopo che sono stati inseriti i 5 numeri, il software dice quanti e quali dei numeri da indovinare sono stati individuati.

- Creo una function che mi generi un array di 5 numeri casuali diversi tra loro.
- Utilizzo un **While** per generare 5 numeri casuali, controllo che siano diversi usando il **Do while**.
- Utilizzando un **Ciclo for** inserisco gli elementi dell'array precedentemente creata nel DOM.
- Creo una function che aggiunga la classe '*d-none*' all'elemento del DOM.
- Creo un **setTimout** nella quale inserirò la funtion precedentemente creata.
- Creo una function che chieda all'utente i numeri che successivamente andranno inseriti all'interno di un'array.
 - Inserisco la function precedentemente creata all'interno della **Timing function**.
    - Creo un ciclo for che verifichi se i numeri inseriti dall'utente siano contenuti nell'array dei numeri random.
    - Inserisco un alert che comunichi all'utente quanti numeri ha indovinato.
- Inserisco un **setInterval** che mi faccia da countdown diminuendo una variabile precedentemente dichiarata.
