
GTSC official website. powered by [Hugo](https://gohugo.io/).

Autor: Simone Mignami <simone.mig29@gmail.com>


Gestione sito
--------------

Pagina "segreta" con elenco news: **url/news**

Creazione nuova news:

~~~
hugo new news/nuova_news.md
~~~

- descrizione: sommario della news che appare nella bacheca
- data: la data della news (display only)

Tabelle CSV: creare file e codificare come UTF8 prima di aprire Excel altrimenti mette la sua codifica che non va bene.

Shortcodes:

- dati: carica e mostra un valore presente nel file /data/contatti. Parametri: nome della variabile
- glyphicon: produce uno span con il Glyphicon specificato. Parametri: il nome del Glyphicon (senza prefisso)
- tbl_compiti_comitato, tbl_cronologia, tbl_programma: stampano i CSV come tabelle HTML


Disciplina
-----------

Proprietà:

- immagine: viene mostrata nella colonna a sinistra
- didascalia: mostrata sotto l'immagine
- alt: testo alternativo per l'immagine
