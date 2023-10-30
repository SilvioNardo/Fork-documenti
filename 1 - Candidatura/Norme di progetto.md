# Norme di progetto

TODO:
- [ ] strumenti
- [ ] git
- [ ] riunioni
- [ ] buone pratiche
- [ ] comunicazione con proponente
- [ ] monitoraggio
- [ ] feedback interno
- [ ] team mission
- [ ] versioning
- [ ] do's and dont's
- [ ] glossario

## Strumenti

### VCS

- GitHub

### ITS

- Linear (o YouTrack)

### Altri strumenti

- Discord: piattaforma di messagistica istantanea e videocalling ad uso interno;
- Loom: condivisione di brevi video on-demand, ad uso ambivalente;
- Zoom: videocalling ad uso esterno.

## Principi

La comunicazione è aperta, onesta, proattiva e frequente.
Il monitoraggio è chiave.
In tutti gli scenari si vuole evitare la necessità di "polling" tra membri del gruppo. Lo stato attuale del progetto dev'essere sempre consultabile tramite il sistema ITS adottato.

### Aperta

Le comunicazioni avvengono in modalità pubblica, ovvero tutti i membri possono partecipare (compatibilmente con i loro impegni di progetto). I messaggi, le eventuali registrazioni e i verbali sono sempre consultabili.
I verbali delle riunioni vengono pubblicati non oltre le 18 ore successive al termine della riunione. Contengono:

- riferimenti al gruppo;
- partecipanti alla riunione;
- l'ordine del giorno;
- il riassunto della riunione;
- una lista di azioni da attuare a seguito della riunione.

### Onesta

Quanto comunicato durante le riunioni rappresenta lo stato del progetto. Nessun membro, in nessun caso, deve nascondere le criticità incontrate.

### Proattiva

Ogni comunicazione deve richiedere il minor tempo possibile ai partecipanti, siano essi interni od esterni. Affrontare le riunioni con preparazione, cercando di offrire spunti concreti di discussione.

### Frequente

Fornire al proponente aggiornamenti almeno settimanali sul progresso. Gli aggiornamenti vengono preferibilmente forniti in modalità differita, se necessario sfruttando servizi di video on-demand.


## Comunicazioni

### Interne

I contatti con i membri del gruppo avvengono tramite Discord, sia in modalità testuale che in video chiamata. A seguito di ciascuna riunione viene prodotto un verbale secondo le regole descritte nell'apposita sezione.

La comunicazione tra i membri avviene in modalità collegiale oppure one-to-one.

Le comunicazioni che riguardano l'implementazione sono preferibilmente differite. I singoli membri sono comunque liberi di organizzare sessioni di lavoro collettive e informali, senza richiedere l'intervento del Responsabile.

### Esterne

I contatti con proponente e committente avvengono tramite e-mail, esclusivamente tramite l'indirizzo del gruppo, o su piattaforme di videochiamata individuate di comune accordo.

Si sottolinea l'importanza di una comunicazione che rispetti i principi chiave delineati.

Le modalità e la frequenza delle comunicazioni con proponente e committente sono da stabilirsi con i diretti interessati, secondo necessità e disponibilità degli interlocutori.


## Documenti

### Versionamento
`
Tutti i documenti vengono versionati secondo questa semantica:

X.Y.Z

I numeri di versione vengono incrementati di una unità con queste regole:

- X: quando le modifiche riguardano almeno il 30% del documento;
- Y: quando avvengono modifiche sostanziali (aggiunta di paragrafi);
- Z: per correzioni di minore entità (come correzione typo).

## Feedback

### Feedback esterno

Il feedback ricevuto dal proponente o dal committente ha carattere vincolante.

### Feedback interno

Tutte le riunioni sono occasione di condivisione con il team o il gruppo di lavoro.

Il gruppo analizza la segnalazione e, se giudicata significativa, si adopera per risolverla.
Le segnalazioni vengono documentate nel relativo verbale interno.

### Buone norme

Le buone pratiche vanno condivise con il resto del team durante le riunioni di fine ciclo. Vengono discusse ed eventualmente integrate nelle norme di progetto.

## VCS

Le modalità di utilizzo del VCS sono prestabilite in sessione collettiva e adottate da tutti i membri del gruppo.

### Repository

Il gruppo si munisce di due repository:

1. **Documenti** contiene la documentazione prodotta ai fini di progetto e non direttamente legata al software prodotto;
1. **WMS3** contiene il software e la documentazione di supporto.

Non si esclude la possibilità di utilizzare repository aggiuntive, ad esempio per la separazione di PoC e PB.

### Branching

Il gruppo adotta una metodologia standard per la gestione dei branch di sviluppo.

### Commit

Le modifiche apportate da ciascun commit devono essere atomiche.

```
Inserire documento Netlifter
```

