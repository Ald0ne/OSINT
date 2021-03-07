## Procedura

# Come iniziare?
- Trovare la maggiore quantità di materiale possibile
- Prendere una strada e trovare il particolare che può fornire una leva

> Tra le risorse e gli strumenti che ho selezionato, **quelli con l'icona
> :star: ritengo possano essere più utili**.

# [Menu](#menu)

 - [Risorse: blog, collezioni, account interessanti](#risorse-blog-collezioni-account-da-seguire)
 - [Raccolta informazioni: Strumenti Web](#raccolta-informazioni-strumenti-web)
 - [Quali impronte lasciamo?](#quali-impronte-lasciamo-visitando-un-link) 
 - Raccolta informazioni: Strumenti per Linux
 - Domain Threat Intelligence: partiamo da un dominio...
 - Le fasi di un attacco
 - Anonimato in rete
 - :fire: New: [Malware Research Section](#malware-research-section)

## [Risorse: blog, collezioni, account da seguire](#risorse)

|Titolo|Lingua|Tipo|Link|Argomenti|Note
|------|----|-----|:--:|----|-------|
|OsintOps |:it:|:dog: Blog|[https://osintops.com/](https://osintops.com/)|Buscador, DarkWeb|Aggiornato
|Osint Frameworks|:uk:|Raccolta|[https://osintframework.com/](https://osintframework.com/)|OSINT|La "Bibbia", da usare con cautela!|
|Awesome OSINT|:uk:|Raccolta|[<img src="https://img.shields.io/github/stars/jivoi/awesome-osint?style=social">]([https://github.com/jivoi/awesome-osint](https://github.com/jivoi/awesome-osint))|OSINT|Completa e aggiornata|
|Indagini Online|:it:|:dog: Blog|[https://indaginionline.com/](https://indaginionline.com/)|OSINT / Informatica Forense|Scoperto grazie all'amico Leonida Reitano|
|YOGA (Your Osint Graphical Analyzer)|:uk:|:dog: Mappa|[https://yoga.osint.ninja/](https://yoga.osint.ninja/)|OSINT|Hai un dato da cui partire? Cerca le correlazioni|
|Bellingcat|:uk:|Blog|[https://www.bellingcat.com/](https://www.bellingcat.com/)|Giornalismo|Investigazioni|
|Technisette|:uk:|Raccolta|[https://www.technisette.com/p/home](https://www.technisette.com/p/home)|OSINT Tools|Completa ed aggiornata|
|Sector035|:uk:|:dog: Blog|https://sector035.nl/|OSINT|Un must da leggere ogni settimana|
|Quiz Time|:uk:|Twitter|[<img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/quiztime?style=social">](https://twitter.com/quiztime)|OSINT|Quiz OSINT settimanali!|
|Nico Dekens|:uk:|Twitter|[<img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/dutch_osintguy?style=social">](https://twitter.com/dutch_osintguy)|OSINT, CyberSec|VP di Osintcuro.us|

 [:arrow_double_up: Menu](#menu)
 
Hai dei suggerimenti? Idee? Modifiche?
Segnala ciò che ritieni opportuno tramite una *Pull request* o una *Issue* o "alla vecchia maniera" [via email!](mailto:info@marcogovoni.it)
 

## [Raccolta informazioni: Strumenti Web](#strumenti-web)
  
|Titolo|Link|A cosa serve|Note|
|-----|-----|-----|-----|
|Intelligence X|[https://intelx.io/](https://intelx.io/)|Motore di ricerca|Molte informazioni anche nella versione free|
|ImmuniWeb|[https://www.immuniweb.com/radar/](https://www.immuniweb.com/radar/)|DTI & Scan|Community version free|
|Google Hacking|[https://pentest-tools.com/information-gathering/google-hacking#](https://pentest-tools.com/information-gathering/google-hacking#)|Dorks|Analisi Dorks pre-impostate|
|Have I Been Pwned|[https://haveibeenpwned.com/](https://haveibeenpwned.com/)|Ricerca email corrotte|Free|
|Email Header Analyzer|[https://mha.azurewebsites.net/](https://mha.azurewebsites.net/)|Analisi email|Free|
|Wayback Machine|[http://web.archive.org/](http://web.archive.org/)|Archivio pagine web|Free|
|Terrapattern|http://www.terrapattern.com/|Mappe Satellitari|Beta project|
|Shodan|https://www.shodan.io/|Motore di rierca IOT|Il "Google" degli oggetti internet|

## [Quali impronte lasciamo visitando un link?](#impronte)
Per sapere quali dati pubblici lasciamo, semplicemente cliccando un link, puoi utilizzare i seguenti servizi. Ricorda che tutte queste informazioni possono essere utilizzate nella prima fase di un attacco, chiamata "Information Gathering" che ha appunto l'obiettivo di raccogliere dati sui bersagli e catalogarli.

|Titolo|Link|
|-----|-----|
|Electronic Frontier Fundation|[https://panopticlick.eff.org](https://panopticlick.eff.org)
|Browser Leaks|[https://browserleaks.com](https://browserleaks.com)|DTI & Scan|Community version free|

## Strumenti per Linux
In arrivo! Iscriviti alla newsletter per ricevere gli aggiornamenti
[<img src="https://img.shields.io/badge/iscriviti-clicca qui-blue">](https://mlgn.to/81gl)

## Domain Threat Intelligence (v.0.2)
L'attività DTI prevede una analisi di informazioni pubbliche (OSINT) e semipubblice (CLOSINT) volte a trovare tracce rilevanti che possa evidenziare vulnerabilità che a loro volta possano essere utilizzate per un attacco informatico. Queste informazioni vengono spesso utilizzate nella prima fase di un attacco, quella della **raccolta informazioni** (Information Gathering)

E' possibile associare alla fase di DTI anche una analisi delle vulnerabilità dei siti web e uno scan esterno della rete, al fine di produrre un report che fornisca informazioni utili per una prima analisi. Queste attività devono essere esplicitamente autorizzate dall'utente.

**Strumenti utilizzati**

|Strumento|Target|Obiettivo|
|---------|------|---------|
|Shodan|IP Pubblico|Analisi rete dall'esterno|
|SpiderFoot|IP Pubblico e Dominio|Raccolta informazioni|
|NMAP|IP Pubblico|Raccolta informazioni|
|Sublist3r|Dominio|Raccolta sottodomini|
|Google Dorks|Dominio|Informazioni esposte|
|Intelligence X|Dominio|Compromissione email|
|Emotet search|Dominio|Compromissione email|



 [:arrow_double_up: Menu](#menu)
