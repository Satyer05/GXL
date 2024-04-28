# GXL
La mia applicazione si basa sul mondo videoludico; un'applicazione che contiene tutte le informazioni dei videogiochi più famosi ed i loro problemi!
I problemi che mi sono posto sono i più comuni e che mi ritrovo ad affrontare anche io: non riuscire a superare un livello, non trovare un determinato oggetto per migliorare il livello/l'equipaggiamento, non avere amici online con cui giocare, non sapere le statistiche dei giocatori,non riuscire a migliorare.<br>
<br>
Requisiti applicazione:
<details>
<summary>Registrazione:</summary>
  *  Requisti Funzionali Utente<br>
 <br>
- Gli utenti, appena scaricata l’applicazione, si troveranno la classica schermata di registrazione dove inseriranno la propria email e password, con possibilità di cambiarla in caso di dimenticanza.<br>
- Ci sarà la possibilità di attivare anche l’autenticazione a due fattori, ovvero aggiungere una sicurezza in più per proteggere il tuo account.
 *  Requisti Funzionali Sistema<br>
 <br>
 - Gestione accesso, registrazione, reset password e autenticazione a due fattori.
</details>     
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)<(Autenticazione a due fattori)"> 
<details>
<summary>Profilo:</summary>
 *  Requisti Funzionali Utente<br>
 <br>
- Gli utenti potranno personalizzare il loro profilo cambiando le proprie informazioni come il nome e cognome, la propria immagine profilo, lo stato “online, assente, offline”, la password, la mail.
- Ogni utente potrà vedere tutte le sue statistiche, sia dei giochi online (come Fortnite, Rainbow Six Siege, Call of Duty…) sia dei giochi offline (The Last of Us, Spiderman, Uncharted…).
  *  Requisti Funzionali Sistema<br>
 <br>
 -Gestione modifiche apportate al profilo.
</details> 
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)<(Modifica profilo), (Accesso)<(Vedere statistiche)">
<details>
<summary>Collegamento degli account:</summary>
 *  Requisti Funzionali Utente<br>
 <br>
- L’utente dovrà collegare i propri account (account PlayStation, account Fortnite, account Xbox…).
- In questo modo potrà rendere visibile la propria attività ad altri utenti.
  *  Requisti Funzionali Sistema<br>
 <br>
 -Supporto per collegamento e sincronizzazzione degli account dei giochi.
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)>(Collegare account esterni), [Sistema GXL]-(Collegare account esterni)"> 
<details>
<summary>Selezione:</summary>
 *  Requisti Funzionali Utente<br>
 <br>
- L’utente potrà selezionare un gioco a cui è interessato e “fissarlo”, metterlo nei preferiti per vederlo ogni volta senza doverlo selezionare.
- In questo modo, dopo aver selezionato il gioco/i giochi l'utente potrà vedere tutti gli altri utenti che al momento ci stanno giocando e vedere il loro stato di avanzamento.
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)<(Cerca e fissa giochi), (Cerca e fissa giochi)>(Vedere utenti online), [Sistema GXL]-(Prendere profili), (Prendere profili)-(Vedere utenti online)"> 
<details>
<summary>Informazioni utente:</summary>
 *  Requisti Funzionali Utente<br>
 <br>
- L’utente potrà cercarne un altro e vedrà tutte le sue statistiche, come il KD ( uccisioni per morti), da quando ha iniziato la sessione di gioco, quando l’ha installato la prima volta… e anche a che giochi sta giocando al momento
- Inoltre l'utente potrà inviare una richiesta d'amicizia.
  *  Requisti Funzionali Sistema<br>
 <br>
 -Raccolta di informazioni pubbliche di altri utenti
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)<(Cerca utenti), (Cerca utenti)<(Richiesta amicizia),(Richiesta amicizia)>(Vedere statistiche)">
<details>
<summary>Chat:</summary>
 *  Requisti Funzionali Utente<br>
 <br>
- Dopo aver stretto amicizia, l'utente avrà l’accesso ad una chat dove potrà scriversi o stare in chiamata con l’altro utente.
  *  Requisti Funzionali Sistema<br>
 <br>
 -Fornire un sistema di chat. 
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)<(Cerca utenti), (Cerca utenti)<(Richiesta amicizia),(Richiesta amicizia)<(Chat)">
<details>
<summary>Informazioni gioco:</summary>
 *  Requisti Funzionali Utente<br>
 <br>
- Ci sarà anche una sezione dedicata a tutte le informazioni del gioco desiderato, come quanto spazio occupa, quali sono i requisiti minimi, quando è uscito.
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)<(Cerca giochi), (Cerca giochi)>(Informazioni)"> 
<details>
<summary>Guide:</summary>
 *  Requisti Funzionali Utente<br>
 <br>
- Saranno disponibili anche guide per superare un determinato livello o trovare un oggetto che ti potenzierà l’equipaggiamento.
- Queste potranno essere caricate da chiunque riesca a superare/trovare e potranno essere valutate con un like o dislike.
  *  Requisti Funzionali Sistema<br>
 <br>
 -Gestire la ricerca, la valutazione e il caricamento dei tutorial.
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)<(Cerca giochi), (Cerca giochi)>(Tutorial)" >
<details>
<summary>Coaching:</summary>
 *  Requisti Funzionali Utente<br>
 <br>
- Per quanto riguarda i giochi multiplayer come Fortnite, Rainbow Six Siege, Apex… saranno disponibili delle “lezioni” sotto forma di video oppure “dal vivo” per aiutare l’utente ad acquisire più abilità.
  *  Requisti Funzionali Sistema<br>
 <br>
 -Gestire il caricamento di "lezioni" affidabili sui videogiochi.
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)<(Cerca giochi), (Cerca giochi)>(Coaching)" >
<details>
<summary>Condivisioni:</summary>
 *  Requisti Funzionali Utente<br>
 <br>
- Ci sarà anche una sezione stile home page di Instagram dove ognuno potrà condividere foto/video di ciò che è riuscito a fare, come trickshot, speedrun… o semplicemente per chi vuole discutere su un gioco.
- Inoltre ci sarà un tasto Spoiler che nasconderà le immagini/video che non sono ancora state raggiunte dall’utente (livelli non ancora superati, oggetti non scoperti…).
  *  Requisti Funzionali Sistema<br>
 <br>
 -Fornire una "home page" stile Instagram dove gli utenti potranno condividere contenuti, vedere le storie, mettere like e lasciare un commento.
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)>(Sezione di condivisione)" >
<details>
<summary>Abbonamenti:</summary>
 *  Requisti Funzionali Utente<br>
 <br>
- Ci sarà un abbonameno Premium, che permetterà di sbloccare più funzionalità.
- Questo abbonamento sarà sia mensile, che annuale, con la possibilità di selezionare quanti mesi o anni si vuole.
  *  Requisti Funzionali Sistema<br>
 <br>
 -Gestione acquisto di abbonamenti
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso),(Accesso)<(Premium),(Premium)>(Aggiungi carta),(Premium)>(Scegli il piano),(Premium)>(Paga),[Banca]-(Elaborazione),(Elaborazione)>(Invia risultato di conferma),[Sistema GXL]-(Attiva Premium)" >
<details>
<summary>Requisiti Non Funzionali Sistema</summary>
 <br>
 <details>
<summary>Sicurezza:</summary>
   <br>
-Il sistema deve garantire la sicurezza dei dati dell'utente, compresi i dati dell'account e le informazioni del gioco.
</details>
<details>
<summary>Performance:</summary>
  <br>
-Il sistema deve essere reattivo e garantire tempi di risposta rapidi.
</details>
<details>
<summary>Scalabilità:</summary>
  <br>
-Il sistema deve essere in grado di gestire un numero crescente di utenti e dati di gioco.
</details>
<details>
<summary>Usabilità:</summary>
  <br>
-L'applicazione deve essere intuitiva e facile da usare per gli utenti.
</details>
<details>
<summary>Disponibilità:</summary>
  <br>
-Il sistema deve essere disponibile e accessibile in modo affidabile.
</details>
</details>
<details>
<summary>Requisiti Dominio</summary>
 <br>
 <details>
<summary>Giochi Multiplayer e Singleplayer:</summary>
   <br>
-L'applicazione copre sia giochi multiplayer che singleplayer.
</details>
<details>
<summary>Comunità di Giocatori:</summary>
  <br>
-L'applicazione crea una comunità in cui gli utenti possono interagire, scambiare esperienze di gioco e aiutarsi reciprocamente.
</details>
<details>
<summary>Risorse di Gioco:</summary>
  <br>
-L'applicazione fornisce informazioni sui giochi, guide e risorse educative per migliorare le abilità di gioco.
</details>
<details>
<summary>Abbonamenti Premium:</summary>
  <br>
-L'applicazione offre opzioni di abbonamento premium per gli utenti interessati a funzionalità aggiuntive.
</details>
</details>

1.1 Interfaccia 50     1.2 Integrazione 40   1.3 Gestione progetto 10 <br>
1.1.1 Pagina login     1.2.1 Ideazione 10 <br>
1.1.2 Pagina profilo   1.2.1 Ideazione 10 <br>
1.1.3 pagina iniziale  1.2.2 Progettazione 10 <br>
1.1.4 Pagina tutorial  1.2.3 Montaggio 10 <br>
1.1.5 Pagina coaching  1.2.4 Collaudo 10<br>
1.1.6 Pagina chat <br>
1.1.7 Pagina "social"


USER STORY:

          Utente:

Registrazione e Accesso:

Come utente, voglio poter registrare un account inserendo la mia email e una password.
Come utente, voglio poter effettuare l'accesso usando le credenziali previamente inserite.
Come utente, voglio poter reimpostare la mia password in caso di dimenticanza.
Profilo Utente:

Come utente, voglio poter personalizzare il mio profilo con informazioni come nome, immagine del profilo e stato online/assente/offline.
Come utente, voglio poter visualizzare le statistiche dei miei giochi, inclusi quelli online e offline.
Come utente, voglio poter cercare altri utenti e visualizzare le loro statistiche di gioco.
Collegamento degli Account:

Come utente, voglio poter collegare i miei account di gioco (PlayStation, Fortnite, Xbox) per condividere la mia attività con altri utenti.
Come utente, voglio poter selezionare e fissare i giochi di mio interesse per monitorare l'attività di altri utenti che stanno giocando a quei titoli.
Come utente, voglio poter inviare richieste d'amicizia e comunicare con altri utenti tramite una chat.
Informazioni di Gioco e Condivisioni:

Come utente, voglio accedere a informazioni dettagliate su un gioco specifico, come requisiti di sistema e dimensioni di installazione.
Come utente, voglio poter condividere foto/video delle mie realizzazioni di gioco e partecipare a discussioni sulla piattaforma.
Abbonamenti Premium:

Come utente, voglio poter sottoscrivere un abbonamento premium mensile o annuale per accedere a funzionalità aggiuntive.
Videogiocatore:

Selezione dei Giochi e Guide:

Come videogiocatore, voglio poter selezionare e fissare i giochi preferiti per monitorare l'attività degli altri utenti.
Come videogiocatore, voglio poter trovare e valutare guide create da altri giocatori per superare livelli o trovare oggetti nei giochi.
Informazioni Utente e Coaching:

Come videogiocatore, voglio poter cercare altri utenti e visualizzare le loro statistiche di gioco.
Come videogiocatore, voglio accedere a lezioni o video dal vivo per migliorare le mie abilità nei giochi multiplayer.
Condivisioni e Comunità di Giocatori:

Come videogiocatore, voglio poter condividere foto/video delle mie realizzazioni di gioco sulla piattaforma.
Come videogiocatore, voglio partecipare a discussioni e interagire con altri utenti, creando una comunità di giocatori.
Sviluppatore:

Gestione Profilo e Collegamento degli Account:

Come sviluppatore, voglio implementare la gestione delle modifiche apportate al profilo.
Come sviluppatore, voglio implementare il collegamento degli account di gioco e la sincronizzazione.
Chat e Sistema di Valutazione:

Come sviluppatore, voglio implementare il sistema di chat tra utenti.
Come sviluppatore, voglio implementare un sistema di valutazione per le guide e le lezioni caricate dagli utenti.
Coaching e Condivisioni:

Come sviluppatore, voglio implementare il caricamento di lezioni affidabili sui videogiochi.
Come sviluppatore, voglio implementare la sezione di condivisioni stile home page di Instagram.
Gestore della Sicurezza:

Sicurezza e Autenticazione a Due Fattori:

Come gestore della sicurezza, voglio garantire la sicurezza dei dati dell'utente e delle informazioni di gioco.
Come gestore della sicurezza, voglio implementare l'autenticazione a due fattori per aumentare la sicurezza degli account.
Gestione Accesso e Protezione Dati:

Come gestore della sicurezza, voglio implementare la gestione dell'accesso, registrazione, reset password e autenticazione a due fattori.
Come gestore della sicurezza, voglio garantire la protezione dei dati sensibili degli utenti.
Sicurezza del Sistema e Abbonamenti:

Come gestore della sicurezza, voglio garantire la sicurezza del sistema, compresi i dati dell'account e le informazioni del gioco.
Come gestore della sicurezza, voglio implementare la gestione degli acquisti e della sicurezza per gli abbonamenti premium.

PIVOT DEL PROGETTO<br>
Sondaggi e Votazioni:
Aggiungi la possibilità per gli utenti di creare sondaggi su argomenti di interesse legati ai videogiochi.
Consentire agli utenti di votare sui sondaggi creati da altri utenti.
Visualizza i risultati dei sondaggi in tempo reale e offre funzionalità per analizzare i risultati.
Organizzazione di Tornei:
Implementa una sezione dedicata alla creazione e all'organizzazione di tornei all'interno dell'applicazione.
Gli utenti possono creare tornei su giochi specifici, definire regole e modalità di partecipazione.
Fornisci un sistema di gestione dei tornei che includa la registrazione dei partecipanti, la creazione di un tabellone e la gestione delle partite.
Collaborazione tra Giocatori:
Integra funzionalità per la creazione di gruppi o squadre di gioco all'interno dell'applicazione.
Consentire agli utenti di unirsi a gruppi esistenti o crearne di nuovi, con la possibilità di definire obiettivi comuni.
Fornire strumenti di comunicazione e coordinamento per i membri del gruppo, come chat di gruppo e schede di attività condivise.
Premi e Riconoscimenti:
Introduce un sistema di premi e riconoscimenti per gli utenti che partecipano attivamente alle funzionalità sociali dell'applicazione.
Assegna premi agli utenti che creano sondaggi popolari, organizzano tornei di successo o raggiungono obiettivi collaborativi con il loro gruppo.
Integrazione con Social Media Esterni:
Offri opzioni per condividere contenuti dall'applicazione su piattaforme di social media esterne, ampliando così la visibilità e l'interazione con la community di giocatori.
Implementa funzionalità per invitare amici da altri social media all'interno dell'applicazione GXL.
Moderazione e Gestione dei Contenuti:
Crea strumenti per la moderazione dei contenuti generati dagli utenti, come segnalazione di contenuti inappropriati o abusi.
Nomina moderatori all'interno della community per gestire segnalazioni e garantire un ambiente positivo e sicuro per tutti gli utenti.<br>
MULTITENANCY<br>
Potrei vendere la mia applicazione alle aziende che offrono corsi e formazioni su giochi e che quindi potrebbero essere interessate ad integrare GXL come strumento di supporto per gli studenti. GXL potrebbe aiutare gli studenti a trovare risorse educative, a seguire lezioni di coaching e a interagire con altri studenti appassionati di videogiochi.
Potrei rivolgermi anche a siti web specializzati nell'offrire informazioni e recensioni sui videogiochi, dato che potrebbero integrare GXL come una risorsa aggiuntiva per i loro lettori. GXL potrebbe fornire statistiche di gioco, guide e altre informazioni utili per gli utenti che visitano questi siti.

