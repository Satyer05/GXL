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
