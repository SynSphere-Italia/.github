# SynSphere Italia

Partner Microsoft per le piccole e medie imprese italiane. Sedi operative a
Segrate (Milano) e Bolzano.

Qui pubblichiamo gli strumenti che usiamo tutti i giorni sui tenant dei nostri
clienti. Non sono esempi scritti per l'occasione: sono gli script che giriamo
noi, con dentro gli errori che abbiamo già fatto e le avvertenze che vorremmo
aver letto prima.

---

## Che cosa trovi

**[synsphere-powershell-toolkits](https://github.com/SynSphere-Italia/synsphere-powershell-toolkits)**
— 247 script PowerShell per amministrare Microsoft 365, Azure ed Entra ID,
organizzati in 29 raccolte.

La parte che vale non è il codice: è la sezione di avvertenze in ogni raccolta.
Dice quando un report può uscire vuoto per un permesso mancante invece che
perché non c'è niente da segnalare, quali script agiscono su tutta la
sottoscrizione se non li si restringe, e quali CSV finiscono sul disco con
dentro chiavi di ripristino BitLocker o indirizzi IP di accesso.

Gli stessi contenuti sono scaricabili come archivi ZIP da
[synsphere.it/download](https://synsphere.it/download/), per chi preferisce un
file a un `git clone`. Gli archivi si generano da questo repository: non ci sono
due copie da tenere allineate a mano.

---

## Una nota sulla lingua

La documentazione è bilingue, italiano e inglese. **Il codice no**: messaggi a
schermo, commenti e intestazioni dei CSV sono in italiano, perché sono stati
scritti per le PMI italiane e per chi ci lavora dentro. È un dato di fatto sul
perimetro, non un programma di traduzione futura.

---

## Licenza e marchi

Apache License 2.0. Il nome e il logo SynSphere non sono coperti dalla licenza.

Microsoft, Microsoft 365, Azure, Entra, Intune, Purview, Defender, Exchange,
SharePoint, Teams e Windows sono marchi del gruppo Microsoft: qui sono usati in
modo referenziale, per identificare i prodotti che questi script amministrano.
SynSphere Italia non è affiliata a Microsoft né approvata da Microsoft.

Gli script sono forniti **"as is"**. Eseguirli su un tenant di produzione è
responsabilità di chi li esegue: leggi l'header, usa `-WhatIf` dove c'è, prova
su un perimetro ristretto.

---

# SynSphere Italia (English)

A Microsoft partner for Italian small and medium businesses, with offices in
Segrate (Milan) and Bolzano.

We publish here the tools we use every day on our customers' tenants. They are
not examples written for the occasion: they are the scripts we actually run,
carrying the mistakes we have already made and the warnings we wish we had read
first.

## What's here

**[synsphere-powershell-toolkits](https://github.com/SynSphere-Italia/synsphere-powershell-toolkits)**
— 247 PowerShell scripts for administering Microsoft 365, Azure and Entra ID,
in 29 collections.

The valuable part is not the code: it is the warnings section in every
collection. It tells you when a report can come back empty because of a missing
permission rather than because there is nothing to report, which scripts act on
an entire subscription unless you narrow them, and which CSVs land on disk
holding BitLocker recovery keys or sign-in IP addresses.

The same content is downloadable as ZIP archives from
[synsphere.it/download](https://synsphere.it/download/). The archives are
generated from this repository — there are not two copies to keep in sync by
hand.

## A note on language

The documentation is bilingual. **The code is not**: console output, comments
and CSV headers are in Italian, because they were written for Italian SMEs and
the people who work inside them. That is a statement of scope, not a plan to
translate later.

## Licence and trademarks

Apache License 2.0. The SynSphere name and logo are not covered by the licence.

Microsoft, Microsoft 365, Azure, Entra, Intune, Purview, Defender, Exchange,
SharePoint, Teams and Windows are trademarks of the Microsoft group of
companies, used here referentially to identify the products these scripts
administer. SynSphere Italia is not affiliated with or endorsed by Microsoft.

The scripts are provided **"as is"**. Running them against a production tenant
is the responsibility of whoever runs them.

---

<sub>[synsphere.it](https://synsphere.it) · [Contattaci](https://synsphere.it/contattaci) · info@synsphere.com</sub>
