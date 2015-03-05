# demoproject
Progetto dimostrativo per l'uso di GIT e GitHub


Introduzione
------------
In previsione di utilizzare GIT e GitHub come strumenti di collaborazione e condivisione sui progetti del Laboratorio RiminiLUG, stiamo prevedendo una serie di momenti informativi di base (serate e supporto in Mailing List) per apprendere i comandi basilari di GIT e le funzionalita' di GitHub.

A questo link potete scaricare le slide della serata tenuta al LAB il 3 marzo 2015:
[http://riminilug.it/tiki-download_file.php?fileId=668]

Questo progetto demo costituisce uno spazio per esercitarsi liberamente e testare le funzionalita' che poi torneranno utili per contribuire ai nostri progetti.

Come usare questo progetto
--------------------------

* Creare un proprio account GitHub e comunicarlo in Mailing List per essere aggiunti come contributors
* Installare GIT sul proprio computer
* Clonare il progetto in locale
* Creare una o piu' branch personali (usare nomi univoci, es <cognome>_<nome_branch>
* lavorare sulla propria branch e provare a fare il push

Non abbiate paura di sbagliare, non succede nulla :)

Inoltre invito anche a provare gli altri strumenti di GitHub:
* Issue
* Wiki

Riepilogo comandi base
----------------------

### Comandi su repository locale

`git clone https://github.com/riminilug/demoproject.git`

`git branch <nome_branch>`  Usare nomi per le branch del tipo <cognome_titolo>

`git checkout <nome_branch>`

.... modifico/aggiungo/rimuovo files

`git status`

`git add <nome_nuovo_file>`

`git commit -a -m"testo del messaggio"`

Per descrizioni piu' aticolate non usare l'opzione `-m`


Altri comandi utili:

`git log`

`gitk`  - il pacchetto gitk va installato, se non presente

`git diff`

`git merge <nome_branch_da_fondere>`


### Sincronizzazione con GitHub

`git pull`

`git push`

`git checkout <nome_branch> && git push origin <nome_branch>`

### Branch di Gabo 
Il branch "gabo_branch" è il branch di Gabriele Z.

