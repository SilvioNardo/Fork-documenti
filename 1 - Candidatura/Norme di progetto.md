# Norme di progetto

TODO:
- [x] strumenti
- [ ] git
- [ ] riunioni
- [x] buone pratiche
- [ ] comunicazione con proponente
- [ ] monitoraggio
- [x] feedback interno
- [ ] team mission
- [ ] versioning
- [ ] do's and dont's
- [ ] glossario

## Strumenti

Il gruppo si dota dei seguenti strumenti a supporto delle attività di progetto. Tutti gli strumenti sono stati adottati in maniera definitiva o fino ad alterate necessità, durante la riunione del 00/11/2023.

### Version Control System (VCS)

- GitHub: piattaforma di controllo di versione.

### Issue Tracking System (ITS)

- Jira: piattaforma di issue tracking.

### Altri strumenti

- Discord: piattaforma di messagistica istantanea e videocalling ad uso interno;
- Gmail: posta elettronica ufficiale, utilizzata per tutte le comunicazioni scritte ad uso esterno;
- Zoom: videocalling ad uso esterno (verso proponente e committente);
- Loom: condivisione di brevi video on-demand, ad uso ambivalente;
- Miro: collaborazione su lavagna digitale, utilizzata per retrospettiva;

## Principi

La comunicazione è aperta, onesta, proattiva e frequente.
Il monitoraggio è chiave.
In tutti gli scenari si vuole evitare la necessità di "polling" tra membri del gruppo. Lo stato attuale del progetto dev'essere sempre consultabile tramite il sistema ITS adottato.

### Aperta

Le comunicazioni avvengono in modalità pubblica, ovvero tutti i membri possono partecipare (compatibilmente con i loro impegni di progetto e sempre nel rispetto delle rispettive responsabilità).

I membri del gruppo hanno accesso e possono liberamente consultare i messaggi, le eventuali registrazioni e i verbali.

I verbali delle riunioni vengono pubblicati, secondo disciplina, entro 18 ore dal termine della riunione. Contengono:
- riferimenti del gruppo (nel frontespizio);
- partecipanti alla riunione e durata dell'intervento;
- l'ordine del giorno;
- il riassunto della riunione;
- una lista di azioni da attuare a seguito della riunione.

### Onesta

Quanto comunicato durante le riunioni rappresenta lo stato del progetto. Nessun membro, in nessun caso, deve nascondere le criticità incontrate.

### Proattiva

Affrontare le riunioni con preparazione, cercando di offrire spunti concreti di discussione. Ogni comunicazione deve poter essere processata dagli interessati nel minor tempo possibile.

### Frequente

Fornire al proponente aggiornamenti almeno settimanali sul progresso, utilizzando la casella e-mail del gruppo. Gli aggiornamenti vengono preferibilmente forniti in modalità differita, se necessario sfruttando servizi di video on-demand.


## Comunicazioni

### Interne

Le riunioni tra i membri del gruppo avvengono su Discord, sia in modalità testuale che in video chiamata. A seguito di ciascuna riunione viene prodotto un verbale secondo le regole descritte nell'apposita sezione.

La comunicazione tra i membri può avvenire in modalità collegiale oppure one-to-one.

Le comunicazioni relative ad ogni elemento che richieda VCS avvengono per iscritto tramite l'ITS preposto. Le comunicazioni che riguardano l'implementazione sono preferibilmente differite; i singoli membri sono comunque liberi di organizzare sessioni di lavoro collettive e informali, senza richiedere l'intervento del Responsabile.

### Esterne

I contatti con proponente e committente avvengono tramite e-mail, esclusivamente tramite l'indirizzo del gruppo, o su piattaforme di videochiamata individuate di comune accordo.

Si sottolinea l'importanza di una comunicazione che rispetti i principi chiave delineati.

Le modalità e la frequenza delle comunicazioni con proponente e committente sono da stabilirsi con i diretti interessati, secondo necessità e disponibilità degli interlocutori.

I verbali delle riunioni vengono pubblicati, secondo disciplina, entro 18 ore dal termine della riunione. Contengono:
- riferimenti del gruppo (nel frontespizio);
- destinatari;
- partecipanti alla riunione e durata dell'intervento;
- l'ordine del giorno;
- il riassunto della riunione;
- (se rivolto al proponente) un campo di firma per la convalida.
Contestualmente alla pubblicazione del verbale esterno, il Responsabile si impegna a comunicare all'attore esterno la disponibilità del documento. Nel caso di verbali riguardanti i rapporti con il proponente, è richiesta la validazione tramite ack o firma.

## Documenti

### Versionamento

Tutti i documenti vengono versionati secondo questa semantica:

X.Y.Z

I numeri di versione vengono incrementati di una unità con queste regole:

- X: quando le modifiche riguardano almeno il 30% del documento;
- Y: quando avvengono modifiche sostanziali (aggiunta di paragrafi);
- Z: per correzioni di minore entità (come correzione di errori ortografici).

## Feedback

### Feedback esterno

Il feedback ricevuto dal proponente o dal committente deve necessariamente essere discusso alla prima riunione utile.
Le segnalazioni ricevute durante gli incontri vengono documentate nel relativo verbale esterno, assieme ai risultati della relativa discussione.

### Feedback interno

Tutte le riunioni sono occasione di condivisione con il team o il gruppo di lavoro.

Il gruppo analizza la segnalazione e, se giudicata significativa, si adopera per risolverla o implementarla. È compito del Responsabile, sentito l'Amministratore, e sempre in comune accordo con almeno il segnalatore, individuare e attuare soluzioni adeguate.

Le segnalazioni e le eventuali misure adottate vengono documentate nel relativo verbale interno.

Ogni settimana, al termine di ciascuno sprint e in data e ora concordate, il gruppo si riunisce in sessione collegiale per un incontro durante il quale affronta:

1. Retrospettiva: è un momento di confronto atto ad individuare comportamenti e procedure funzionali o da migliorare. A questo scopo, ogni membro del gruppo avrà aggiunto alla lavagna digitale (Miro) le proprie opinioni su Keep doing e Improvements sotto forma di post-it digitali. L'aggiunta di queste informazioni dovrà avvenire obbligatoriamente prima della riunione ed essere brevemente giustificata durante la riunione.
1. Consuntivo di periodo: è una valutazione dell'operato del gruppo nel corso dello sprint appena concluso. Il suo scopo è migliorare la pianificazione futura.

### Buone norme

Le buone pratiche vanno condivise con il resto del team durante le riunioni di fine ciclo. Vengono discusse ed eventualmente integrate nelle norme di progetto.

## VCS

Le modalità di utilizzo del VCS sono prestabilite in sessione collettiva e adottate da tutti i membri del gruppo.

### Repository

Il gruppo si munisce di due repository pubblici:

1. **Documenti** contiene la documentazione prodotta ai fini del progetto didattico;
1. **WMS3** contiene il software e la relativa documentazione di supporto.

Ogni membro ha accesso in lettura e scrittura ai contenuti dei repository, secondo le modalità previste per l'integrazione.

### Branching

In base a quanto stabilito durante la riunione interna del 29/10/2023, il gruppo adotta una metodologia standard per la gestione dei branch di sviluppo.

In particolare, la metodologia adottata prevede l'uso di:

- branch `main`, principale
- branch `develop`, di sviluppo
- branch di funzionalità, per lo sviluppo di funzionalità atomiche e indipendenti (inclusi i bug fix)

### Commit

Le modifiche apportate da ciascun commit devono essere atomiche.

```
Convenzioni Git
Perché scrivere buoni commit ripaga
I messaggi di commit scritti bene servono ad almeno tre scopi:

- velocizzare il processo di review.
- ci aiutano a scrivere dei buoni changelog.
- aiutano nella manutenzione. Chi si ricorda perché ha fatto una modifica al codice due anni fa?

https://imgs.xkcd.com/comics/git_commit.png

I messaggi di commit sono importanti.

È inutile scrivere "aggiornato readme", perché il VCS segnala già quali file sono stati modificati. È bene invece indicare le ragioni o lo scopo del commit.

Il commit non è un contenitore dove buttare dentro ogni modifica. Suddividiamoli con logica e facciamone tanti, almeno finché non li tasseranno.

Consigli
Se hai difficoltà a riassumere le modifiche in modo conciso, forse è perché include cambiamenti o bugfix diversi che andrebbero separati.
Errori comuni
Ecco alcuni esempi negativi da evitare:

Non pushare un commit contenente tutte le modifiche fatte durante la giornata. Git non è un sistema di backup.
Un commit per ciascun file: una modifica che interessa più file non dovrebbe essere divisa tra più commit.
Messaggi di commit con etichette imprecise e/o pigri.
Commit che raggruppano modifiche autonome, che dovrebbero avere ciascuna il proprio commit. Ad esempio: "Fixed bug 2345 and renamed all files" non ha senso di esistere e complica la vita quando è ora di stanare un bug.
Modifiche ai caratteri di spaziatura e tabulazione vanno in un commit a parte.
Code drop: copia-incolla di centinaia di linee di codice che sovrascrivono l'intero contenuto del file. Bello, ma non si fa perché le modifiche devono avvenire gradualmente.
Riferimenti alle linee guida
- [git-scm.com](https://www.git-scm.com/book/en/v2/Distributed-Git-Contributing-to-a-Project#_commit_guidelines).
- [On commit messages](http://who-t.blogspot.com/2009/12/on-commit-messages.html).
- [A Note About Git Commit Messages](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html).
- [How to write a git commit message](https://cbea.ms/git-commit/).
```

### Pull Request

L'integrazione di funzionalità, bug fix e rilasci avviene secondo il concetto di Continous Integration.

Per integrare un ramo di sviluppo, i membri si impegnano ad utilizzare la funzione di Pull Request (PR) offerta da GitHub.

Ogni PR dovrà riguardare un singolo aspetto, secondo le regole date per il branching.

Per potere essere integrata, una PR dovrà:

1. essere approvata da almeno un verificatore
1. superare tutti i test previsti

Qualora almeno uno dei due vincoli non fosse soddisfatto, l'integrazione non potrà avvenire. Sarà cura dell'autore e del verificatore individuare soluzioni per soddisfare i vincoli di integrazione.

Al termine della procedura di merging, si suggerisce la cancellazione del branch integrato per mantenere il repository ordinato e manutenibile.

Caratteristiche delle PR. Ogni PR dovrà avere:

1. titolo significativo
1. il codice di riferimento alla issue dell'ITS risolta o implementata
1. una descrizione, anche breve, dell'oggetto della PR. Indicare, se necessario, le scelte implementative, i riferimenti ai verbali e ogni altra informazione utile ai fini della verifica.
1. assegnatario
1. verificatore (almeno uno)
1. categoria (almeno una)