# FakeStrava

**Descrizione:**

Il mio progetto, FakeStrava, è un'applicazione per smartphone ideale per chi vuole tenere traccia del proprio storico di allenamenti e vuole interfacciarsi anche con altri utenti. 

--------

**Problemi che risolve:**

1) Archiviazione dei dati di allenamento: FakeStrava permette agli utenti di salvare il proprio storico di allenamenti, consentendo loro di monitorare i progressi personali.
2) Condivisione dei dati di allenamento: Gli utenti possono condividere i propri allenamenti con altri membri della community, inclusi tracce dei percorsi, dati prestazionali e foto, facilitando la condivisione con amici e conoscenti.
3) Motivazione e ispirazione: L'applicazione consente agli utenti di visualizzare i percorsi e le attività di altri utenti, fornendo una fonte di motivazione e ispirazione per migliorare le proprie prestazioni sportive.
4) Analisi delle prestazioni: FakeStrava offre dettagliate informazioni sulle prestazioni durante l'allenamento, tra cui distanza, tempo, ritmo e altitudine, aiutando gli utenti a monitorare il proprio progresso nel tempo.

--------

**Funzionalità/requisiti dell'applicazione:**

<details>
<summary>  1. Registrazione degli allenamenti </summary>
<p>

--------

Gli utenti di Strava possono registrare e tenere traccia delle loro sessioni di allenamento. Possono inserire dettagli come il tipo di attività, la data, l'ora, la durata e la distanza percorsa. Questi dati vengono registrati per consentire agli utenti di monitorare i propri progressi nel tempo.

**Requisiti Funzionali:**
- Gli utenti devono essere in grado di registrare dettagli specifici delle attività, tra cui il tipo di attività, la data e l'ora, la durata e la distanza percorsa.
  
- Devono poter aggiungere note o commenti alle sessioni di allenamento.
  
**Requisiti Non Funzionali:**
- L'interfaccia utente per la registrazione deve essere intuitiva e facile da usare.

**Requisiti di Dominio:**
- L'applicazione deve garantire l'integrità dei dati registrati, evitando la modifica non autorizzata delle attività.

--------

</p>
</details>

<details>
<summary> 2. Confronto con conoscenti e amici </summary>
<p>

--------

Strava permette agli utenti di confrontare le proprie performance con quelle dei loro amici e conoscenti. Questo avviene attraverso classifiche e confronti basati su dati come tempi, distanze e altre metriche, incoraggiando una sana competizione e la condivisione di successi.

**Requisiti Funzionali:**
- Gli utenti devono poter visualizzare i risultati delle loro attività in confronto con quelli dei loro amici.
  
- Devono essere in grado di visualizzare classifiche o confronti basati su dati come tempi e distanze.

**Requisiti Non Funzionali:**
- I risultati dei confronti devono essere visualizzati in modo chiaro e facilmente interpretabile.

**Requisiti di Dominio:**
- L'applicazione deve garantire che i dati dei confronti siano accurati e aggiornati.

--------

</p>
</details>

<details>
<summary> 3. Registrazione e autenticazione </summary>
<p>

--------

Gli utenti devono registrarsi e autenticarsi nell'applicazione. Questo processo consente loro di creare un account personale, accedere in modo sicuro e mantenere un profilo utente. L'autenticazione assicura la protezione dei dati personali.

**Requisiti Funzionali:**
- Gli utenti devono essere in grado di creare un account e accedere all'applicazione.
  
- Devono poter recuperare la password se dimenticata.
  
**Requisiti Non Funzionali:**
- Il processo di registrazione e autenticazione deve essere semplice e sicuro.

**Requisiti di Dominio:**
- L'applicazione deve proteggere i dati dell'utente e rispettare le normative sulla privacy dei dati personali.

--------

</p>
</details>

<details>
<summary> 4. Profilo </summary>
<p>

--------

Ciascun utente ha un profilo personale in Strava. Possono personalizzare il proprio profilo con informazioni personali come nome, età, sesso, foto del profilo e altre statistiche. Questo profilo è visibile ad altri utenti e fornisce una panoramica delle attività dell'utente.

**Requisiti Funzionali:**
- Gli utenti devono poter creare e modificare il proprio profilo, aggiungendo informazioni come nome, età, sesso, foto del profilo e statistiche personali.
  
- Possono scegliere di condividere determinate informazioni del profilo con altri utenti.
  
**Requisiti Non Funzionali:**
- Il profilo deve essere facilmente personalizzabile dall'utente.

**Requisiti di Dominio:**
- L'applicazione deve consentire agli utenti di gestire le proprie informazioni personali in modo sicuro.

--------

</p>
</details>

<details>
<summary> 5. Gps e tracciamento </summary>
<p>

--------

Strava utilizza il GPS del dispositivo dell'utente per tracciare e registrare le attività in modo preciso. Questo include la mappatura dei percorsi, la misurazione della distanza percorsa, la velocità e altre metriche basate sulla posizione in tempo reale.

**Requisiti Funzionali:**
- L'applicazione deve utilizzare il GPS del dispositivo per tracciare l'attività durante l'allenamento.
 
- Deve registrare dati come la posizione, la distanza percorsa e la mappa del percorso.
  
**Requisiti Non Funzionali:**
- Il tracciamento GPS deve essere preciso e in tempo reale.

**Requisiti di Dominio:**
- L'applicazione deve garantire l'accuratezza dei dati di tracciamento e la protezione della privacy dell'utente.

--------

</p>
</details>

<details>
<summary> 6. Condivisione e feed sociale </summary>
<p>

--------

Gli utenti possono condividere le proprie attività con la community di Strava attraverso un feed sociale. Possono anche interagire con le attività degli altri utenti, lasciando commenti, mettendo "Mi piace" e condividendo attività interessanti.

**Requisiti Funzionali:**
- Gli utenti devono poter condividere le loro attività con altri utenti attraverso un feed sociale.
  
- Possono interagire con le attività altrui attraverso commenti, "Mi piace" e condivisione.
  
**Requisiti Non Funzionali:**
- Il feed sociale deve essere accessibile e facilmente navigabile.

**Requisiti di Dominio:**
- L'applicazione deve proteggere la privacy dell'utente consentendo il controllo delle impostazioni di condivisione.

--------

</p>
</details>

<details>
<summary> 7. Modalità premium </summary>
<p>

--------

Strava offre una modalità premium a pagamento che fornisce agli utenti funzionalità aggiuntive. Queste funzionalità premium possono includere analisi avanzate delle prestazioni, supporto prioritario e altre opzioni che migliorano l'esperienza dell'utente.

**Requisiti Funzionali:**
- Gli utenti devono poter accedere a funzionalità premium tramite un abbonamento a pagamento.
  
- Queste funzionalità possono includere analisi avanzate e funzionalità aggiuntive.
  
**Requisiti Non Funzionali:**
- Il processo di sottoscrizione di un abbonamento premium deve essere chiaro e semplice.

**Requisiti di Dominio:**
- L'applicazione deve gestire correttamente gli abbonamenti e garantire l'accesso alle funzionalità premium.

--------

</p>
</details>

<details>
<summary> 8. Soddisfazione requisiti GDPR </summary>
<p>

--------

Strava deve rispettare i requisiti del Regolamento Generale sulla Protezione dei Dati (GDPR) per garantire la privacy e la sicurezza dei dati personali degli utenti. Ciò include la gestione del consenso dell'utente e la protezione dei dati personali.

**Requisiti Funzionali:**
- L'applicazione deve rispettare i requisiti del GDPR in termini di protezione dei dati personali e consenso dell'utente.
    
**Requisiti Non Funzionali:**
- Deve essere garantita la protezione dei dati personali dell'utente in conformità con le leggi sulla privacy.

**Requisiti di Dominio:**
- L'applicazione deve conformarsi alle leggi sulla privacy dei dati e consentire all'utente di gestire le proprie impostazioni di privacy.

--------

</p>
</details>

<details>
<summary> 9. Statistiche dettagliate </summary>
<p>

--------

Strava fornisce statistiche dettagliate sulle attività degli utenti, come distanza, tempo, altitudine, velocità, frequenza cardiaca e altro. Queste statistiche aiutano gli utenti a valutare e analizzare le loro performance.

**Requisiti Funzionali:**
- Gli utenti devono essere in grado di accedere a statistiche dettagliate delle loro attività, tra cui distanza, tempo, velocità, altitudine, frequenza cardiaca, ecc.
  
- Possono visualizzare queste statistiche in varie forme, come grafici e tabelle.
  
**Requisiti Non Funzionali:**
- Le statistiche devono essere visualizzate in modo chiaro e comprensibile.

**Requisiti di Dominio:**
- L'applicazione deve calcolare e presentare in modo accurato le statistiche basate sui dati dell'attività.

--------

</p>
</details>

<details>
<summary> 10. Segmenti </summary>
<p>

--------

Gli utenti possono creare e cercare segmenti specifici su percorsi. Strava tiene traccia dei tempi dei segmenti, consentendo agli utenti di confrontare le proprie prestazioni con gli altri atleti su segmenti specifici.

**Requisiti Funzionali:**
- Gli utenti devono essere in grado di creare, cercare e competere su segmenti specifici dei percorsi.
  
- Possono visualizzare i tempi dei segmenti e confrontarli con altri atleti.
  
**Requisiti Non Funzionali:**
- La visualizzazione dei segmenti e dei tempi deve essere chiara e facilmente accessibile.

**Requisiti di Dominio:**
- L'applicazione deve calcolare con precisione i tempi dei segmenti e consentire una competizione equa tra gli atleti.

--------

</p>
</details>

<details>
<summary> 11. Badge e premi </summary>
<p>

--------

Strava offre badge e premi agli utenti in base alle loro realizzazioni. Questi possono includere badge per la copertura di determinate distanze, la conquista di segmenti o altri obiettivi specifici.

**Requisiti Funzionali:**
- Gli utenti devono guadagnare badge e premi in base alle loro realizzazioni, come la copertura di determinate distanze o la conquista di segmenti.
  
- Possono visualizzare i badge nel proprio profilo.
  
**Requisiti Non Funzionali:**
- L'applicazione deve notificare gli utenti quando guadagnano un badge o un premio.

**Requisiti di Dominio:**
- L'applicazione deve gestire l'assegnazione dei badge e dei premi in base a criteri specifici.

--------

</p>
</details>

<details>
<summary> 12. Pianificazione di attività </summary>
<p>

--------

Gli utenti possono pianificare attività future e creare percorsi personalizzati su Strava. Possono impostare obiettivi per queste attività e visualizzare un calendario delle attività pianificate.

**Requisiti Funzionali:**
- Gli utenti devono poter pianificare attività future, creare percorsi personalizzati e impostare obiettivi per tali attività.
  
- Possono visualizzare una lista delle attività pianificate nel loro calendario.
  
**Requisiti Non Funzionali:**
- La pianificazione delle attività deve essere flessibile e facilmente gestibile.

**Requisiti di Dominio:**
- L'applicazione deve consentire agli utenti di pianificare attività in modo intuitivo e gestire i percorsi creati.

--------

</p>
</details>

<details>
<summary> 13. Compatibilità con dispositivi e app di terze parti </summary>
<p>

--------

Strava è compatibile con una varietà di dispositivi e app di terze parti, consentendo agli utenti di collegare l'app a orologi GPS, sensori di frequenza cardiaca e altre applicazioni fitness.

**Requisiti Funzionali:**
- Gli utenti devono essere in grado di connettere l'app Strava con dispositivi come orologi GPS, ciclocomputer, ecc.
  
- Possono sincronizzare i dati delle attività con altre applicazioni e servizi di terze parti.
  
**Requisiti Non Funzionali:**
- La connettività con i dispositivi e le app di terze parti deve essere affidabile.

**Requisiti di Dominio:**
- L'applicazione deve supportare una varietà di dispositivi e app di terze parti popolari.

--------

</p>
</details>

<details>
<summary> 14. Obiettivi e sfide </summary>
<p>

--------

Gli utenti possono impostare obiettivi personali per le loro attività e partecipare a sfide comunitarie. Questi obiettivi e sfide forniscono motivazione aggiuntiva agli utenti per migliorare le proprie performance.

**Requisiti Funzionali:**
- Gli utenti devono essere in grado di impostare obiettivi personali per le proprie attività, come una determinata distanza o tempo.
  
- Possono partecipare a sfide proposte dall'app o da altri utenti.
  
**Requisiti Non Funzionali:**
- L'applicazione deve notificare gli utenti sugli obiettivi raggiunti e sulle sfide disponibili.

**Requisiti di Dominio:**
- L'applicazione deve calcolare e tenere traccia del progresso verso gli obiettivi e le sfide.

--------

</p>
</details>

--------

**Casi d'uso:**

**1** L'utente, solo dopo aver effettuato l'accesso, avvia la registrazione e al termine la interrompe.
<img src="http://yuml.me/diagram/scruffy/usecase/, [Utente]-(Accesso Utente), (Accesso Utente)<(Avviare registrazione allenamento), (Avviare registrazione allenamento)>(Termina registrazione allenamento), [Sistema Strava]-(Calcolo dati allenamento),[Sistema Strava]-(Salvataggio record dei segmenti),[Sistema Strava]-(Salvataggio dati dell' attività)">

**2** L'utente dopo aver effettuato l'accesso visualizza i dati degli allenamenti precedenti.
<img src="http://yuml.me/diagram/scruffy/usecase/, [Utente]-(Accesso Utente), (Accesso Utente)<(Visualizza allenamenti precedenti)" >
**3** L'utente, solo dopo aver effettuato l'accesso, può vedere la classifica di un certo segmento.

**4** 

**5** 

**6** 

**7** 









