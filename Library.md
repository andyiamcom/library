**Kasutajad**Kõik kasutajatüübid omavad ligipääsu library view’sse. Iga kasutajatüüp näeb objekte, mis on tema loodud või/ja on üks kasutajatest (on temale jagatud).**Library ****eesmärk**

Kasutajaga seotud objektide (raiderid, projektid) esitamine. Võimalus neid sorteerida nime, kuupäeva järgi. Võimalus teostada üldiseid toiminguid objektidega (ümbernimetamine, kustutamine, tähistamine, avamine). Võimalus siduda (drag and drop) omavahel raidereid ja projekte. Võimalus lisada projekte, raidereid. Võimalus objekte otsida. 

Library kui query kasutaja objektidest.**Olemid-atribuudid**

Library

Sorteerimisviis

**Seosed teiste registritega**Users - 1 - Igal kasutajal on oma library.

Raider 0...n - Ühes libraryis võib olla 0...n raiderit.

Project 0...n - Ühes libraryis võib olla 0...n projekti.**Põhilised sündmused**Projekti tähtaja algus - projektid, mis on alanud, tähistatakse teise värviga

Projekti tähtaja lõpp - projektid, mis on lõppenud, tähistatakse teise värviga

Raideri/projekti jagamine kellegi teise kasutaja poolt.

Projekt/raider on avamata - projekt, mida pole avatud, saab teise tähistuse. Nt. värvitakse teist värvi. Nt juhul kui kasutajale jagatakse midagi, kuid ta ei ole veel seda avanud detailvaates.**kasutusjuhud (nimi, kasutajad, eesmärgid, info****vaated****, uml+mockupid)**

Raiderite, projektide tähistamine

Raiderite, projektide avamine

Raiderite, projektide ümbernimetamine

Raiderite, projektide kustutamine

Raiderite, projektide sheerimine

Raiderite, projektide otsimine

Raideri ja projektide sidumine

Raiderite, projektide loomine

----------------

NB! Näidisobjektid pärast regamist esmakordsele kasutajale.

**Library: vaade sõltub, mis kasutaja tüüp on?**

