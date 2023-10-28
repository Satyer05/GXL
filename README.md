# GXL
La mia applicazione si basa sul mondo videoludico; un'applicazione che contiene tutte le informazioni dei videogiochi più famosi ed i loro problemi!
I problemi che mi sono posto sono i più comuni e che mi ritrovo ad affrontare anche io: non riuscire a superare un livello, non trovare un determinato oggetto per migliorare il livello/l'equipaggiamento, non avere amici online con cui giocare, non sapere le statistiche dei giocatori,non riuscire a migliorare.<br>
<br>
Requisiti applicazione:
<details>
<summary>Registrazione:</summary>
  *  Requisti Funzionali Utente
- Gli utenti, appena scaricata l’applicazione, si troveranno la classica schermata di registrazione dove inseriranno la propria email e password, con possibilità di cambiarla in caso di dimenticanza.<br>
- Ci sarà la possibilità di attivare anche l’autenticazione a due fattori, ovvero aggiungere una sicurezza in più per proteggere il tuo account.
</details>     
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)<(Autenticazione a due fattori)"> 
<details>
<summary>Profilo:</summary>
- Gli utenti potranno personalizzare il loro profilo cambiando le proprie informazioni come il nome e cognome, la propria immagine profilo, lo stato “online, assente, offline”, la password, la mail.
- Ogni utente potrà vedere tutte le sue statistiche, sia dei giochi online (come Fortnite, Rainbow Six Siege, Call of Duty…) sia dei giochi offline (The Last of Us, Spiderman, Uncharted…).
</details> 
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)<(Modifica profilo), (Accesso)<(Vedere statistiche)">
<details>
<summary>Collegamento degli account:</summary>
- L’utente dovrà collegare i propri account (account PlayStation, account Fortnite, account Xbox…).
- In questo modo potrà rendere visibile la propria attività ad altri utenti.
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)>(Collegare account esterni), [Sistema GXL]-(Collegare account esterni)"> 
<details>
<summary>Selezione:</summary>
- L’utente potrà selezionare un gioco a cui è interessato e “fissarlo”, metterlo nei preferiti per vederlo ogni volta senza doverlo selezionare.
- In questo modo, dopo aver selezionato il gioco/i giochi l'utente potrà vedere tutti gli altri utenti che al momento ci stanno giocando e vedere il loro stato di avanzamento.
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)<(Cerca e fissa giochi), (Cerca e fissa giochi)>(Vedere utenti online), [Sistema GXL]-(Prendere profili), (Prendere profili)-(Vedere utenti online)"> 
<details>
<summary>Informazioni utente:</summary>
- L’utente potrà cercarne un altro e vedrà tutte le statistiche di chi è online su un determinato gioco, come il KD ( uccisioni per morti), da quando ha iniziato la sessione di gioco, quando l’ha installato la prima volta…
- Inoltre l'utente potrà inviare una richiesta d'amicizia. 
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)<(Cerca utenti), (Cerca utenti)<(Richiesta amicizia),(Richiesta amicizia)>(Vedere statistiche)">
<details>
<summary>Chat:</summary>
- Dopo aver stretto amicizia, l'utente avrà l’accesso ad una chat dove potrà scriversi o stare in chiamata con l’altro utente.
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)<(Cerca utenti), (Cerca utenti)<(Richiesta amicizia),(Richiesta amicizia)<(Chat)">
<details>
<summary>Informazioni gioco:</summary>
- Ci sarà anche una sezione dedicata a tutte le informazioni del gioco desiderato, come quanto spazio occupa, quali sono i requisiti minimi, quando è uscito.
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)<(Cerca giochi), (Cerca giochi)>(Informazioni)"> 
<details>
<summary>Guide:</summary>
- Saranno disponibili anche guide per superare un determinato livello o trovare un oggetto che ti potenzierà l’equipaggiamento.
- Queste potranno essere caricate da chiunque riesca a superare/trovare e potranno essere valutate con un like o dislike.
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)<(Cerca giochi), (Cerca giochi)>(Tutorial)" >
<details>
<summary>Coaching:</summary>
- Per quanto riguarda i giochi multiplayer come Fortnite, Rainbow Six Siege, Apex… saranno disponibili delle “lezioni” sotto forma di video oppure “dal vivo” per aiutare l’utente ad acquisire più abilità.
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)<(Cerca giochi), (Cerca giochi)>(Coaching)" >
<details>
<summary>Condivisioni:</summary>
- Ci sarà anche una sezione stile home page di Instagram dove ognuno potrà condividere foto/video di ciò che è riuscito a fare, come trickshot, speedrun… o semplicemente per chi vuole discutere su un gioco.
- Inoltre ci sarà un tasto Spoiler che nasconderà le immagini/video che non sono ancora state raggiunte dall’utente (livelli non ancora superati, oggetti non scoperti…)
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso), (Accesso)>(Sezione di condivisione)" >
<details>
<summary>Abbonamenti:</summary>
- Ci sarà un abbonameno Premium, che permetterà di sbloccare più funzionalità.
- Questo abbonamento sarà sia mensile, che annuale, con la possibilità di selezionare quanti mesi o anni si vuole.
</details>
<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso),(Accesso)<(Premium),(Premium)>(Aggiungi carta),(Premium)>(Scegli il piano),(Premium)>(Paga),[Banca]-(Elaborazione),(Elaborazione)>(Invia risultato di conferma),[Sistema GXL]-(Attiva Premium)" >
