# M3-W2-P1-AlbumMusicaliBoostrap
<!-- Crea una pagina responsive per mostrarci i tuoi album musicali preferiti.

In questa pagina ci sarà una tua piccola biografia, i migliori album della tua vita, i peggiori che hai mai sentito, 
e qualsiasi altra cosa relativa alla musica che ami.



REGOLE:

Il progetto dev'essere caricato in una nuova repository su GitHub e linkata al tuo Docente.
Puoi usare Google / StackOverflow, MA ti suggeriamo caldamente di riferirti principalmente alla documentazione fornita, 
per non perderti in ricerche infruttuose per troppo tempo.

Prova il tuo lavoro su varie risoluzioni di schermo, ingrandendo e rimpicciolendo la finestra, 
e soprattutto usando i developer tools del browser che forniscono l'emulatore di svariati device sul quale potrai vedere esattamente come si comporta il tuo layout.

Usa le classi di Bootstrap4.6 per creare la griglia responsive quando necessario.
Usa container > row > col in questo ordine per ottenere un layout responsive perfetto.

NOTE:
Non c'è una design preciso da seguire, dai sfogo alla tua creatività. L'unica cosa importante è che sia responsive!
Fai qualche ricerca nel web per trarre ispirazione su come rappresentare un progetto musicale con svariate copertine di dischi.
Può essere simile ad Amazon Music, Spotify, o Apple Music, o qualsiasi altra collezione di dischi là fuori nel world wide web.



CONSIGLIO: Concentrati sulla struttura e la responsività prima, quando quella funziona puoi dedicarti alla parte grafica e di dettaglio.


ESERCIZI:

1) Andrai a creare un componente per rappresentare la carta del tuo album, che riutilizzerai in tutto il progetto. 
Bootstrap ti dà disponibili alcuni componenti per card e immagini. 
Puoi scegliere di partire da quelli e modificarli, oppure partire da zero e creare i tuoi componenti via CSS. Gli elementi necessari sono:  

L'elemento Card
L'immagine di copertina dell'album
Il titolo dell'album
Il gruppo / artista / dj dell'album
Il genere dell'album
La durata dell'album

NB: Assicurati di applicare le stesse regole di stile a tutti i componenti album che userai nella pagina per mantenere la coerenza degli elementi e degli stili.



2)  Implementa una navigation bar usando il componente boostrap apposito.

     Questa navigazione dovrà linkare ogni sezione nella tua pagina.


3) Crea una sezione responsive per i tuoi album preferiti.

     In questa sezione dovrai avere:

4 album per linea quando lo schermo è molto grande
3 album per linea quando lo schermo ha una dimensione intermedia (tablet o simili)
2 album per linea qunado lo schermo è molto piccolo (mobile)

4) Crea una sezione per le recensioni degli album.

      Prendi un album che ti piace molto e crea una sezione con:

Una grande immagine di copertina
Titolo
Band
Durata
Genere
Tracce dell'album ( in una tabella. Trovala tra i componenti Bootstrap ) 
... e qualsiasi cosa ti venga in mente di interessante che lo riguardi!

5) La lista dei peggiori album mai sentiti! Seleziona gli album che davvero non sopporti o qualcosa che pensi sia sopravvalutato e inseriscilo nella "hall of shame" in forma di tabella!


6) Tutte copertine! Tappezza una sezione di copertine di album. Solo immagini in un layout a griglia senza spazi fra di loro, con le immagini alla stessa altezza. Inserisci almeno 20 immagini per avere un bell'effetto.


EXTRA) Aggiungi un bottone ad ogni sezione, cliccandolo il corpo della sezione dovrà apparire (se nascosto) o nascondersi (se visibile).

SUGGERIMENTO: vedi se esiste un componente Bootstrap che faccia al caso tuo. Se non dovessi trovarlo puoi sempre raggiungere lo stesso effetto usando la normale manipolazione del DOM 
