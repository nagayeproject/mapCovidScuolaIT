# mapCovidScuolaIT
Archivio (NON Ufficiale) di segnalazioni focolai, singoli casi positivi nelle scuole in Italia 

## Perchè questo repository?
- Riguardo la scuola ed il tracciamento Covid i dati aperti non sono mai stati pubblicati e condivisi;
- L' idea è nata firmando la petizione online [https://www.datiBeneComune.it] promossa dall' associazione [https://ondata.it] e dal presidente Andrea Borruso, ma mai soddisfatta dal Governo e dagli enti preposti a fornire gli #openData;
- Perchè ho conosciuto via Twitter Giorgia Lodi che continua ad oggi con la sua richiesta, la nostra richiesta di OpenData riguardo la Scuola;

# Raccolta di segnalazioni
Questo repository vuole essere una raccolta delle evidenze, delle segnalazioni di focolai o casi di positività nelle scuole in Italia.
La ricerca è manuale e non automatizzata ergo sarà un progetto in costante sviluppo, probabilmente quotidiano, ma senza orari specifici di aggiornamento.

## Segnalazioni
Utilizzerò e propongo di usare su:

- *Twitter* il tag #mapCovidScuolaIT per segnalare casi di contagi, focolai nella scuola.
- *Telegram* @datiapertiscuolebot
Bot di segnalazioni
(In fase di test)
Grazie al contributo di @piersoft [www.piersoft.it] 

###  #mapCovidScuolaIT su Twitter
Questo è il link per vedere tutte le segnalazioni che ho condiviso su Twitter con il su citato hashtag:
- [https://bit.ly/39u0Vnu]

## Aggiornamenti repository
Per ora non c'è una cadenza temporale negli aggiornamenti di questo archivio. Il csv presente nella dir *dati/* è l'unico ed aggiornata alla data dell' ultimo record presente al suo interno.

# Il progetto
E' solo frutto personale (fine a se stesso) di riucire a raccogliere dati inerenti a Covid e Scuola in Italia e poter visualizzarli in una mappa per avere una visione d'insieme.

# La mappa
Verrà aggiornata la mappa italiana visibile a questo link:
[http://u.osmfr.org/m/553820/]
NOTA: si potranno scaricare i marker sia da questo repository in formato csv e sia dal link su citato in formato kml, gpx, full data.

# I dati
Nella directory dati/ sono inseriti l'ultimo csv aggiornato e i csv archivio
I marker della mappa e il csv su questo repository avrà i campi principali:

## Campi csv

Questa che segue è la struttura dati copiata dal progetto di *Vittorio Nicoletta* e *Lorenzo Ruffiino* :

-*Data* : Data comunicazione primo positivo se possibile risalire da fonte, altrimenti data fonte
-*Regione/PA* : Regione/PA in cui si trova la scuola, NA se dato mancante
-*Provincia* : Provincia in cui si trova la scuola, NA se dato mancante
-*Città* : Città in cui si trova la scuola, NA se dato mancante
-*Nome Scuola* : Nome scuola caso positivo, NA se dato mancante
-*Tipo Scuola* : Tipo scuola tra Infanzia (nido e materna), Primaria (elementare), Media, Superiore (liceo, isis, itis,...), Università, Istituto comprensivo, NA se dato mancante
-*Codice MG* : Codice meccanografico scuola da Ministero Istruzione. Potrebbero riferirsi all'Istituto Comprensivo nella sua totalità, NA se dato mancante
-*Positivi* : Numero primi studenti/studentesse/docenti/altro positivi, "In attesa" se tampone ancora senza risultato
-*Categoria* : La persona positiva e' Studente, Docente o Altro (personale ATA, ...), NA se dato mancante
-*Isolamento* : Numero persone in isolamento o insieme di persone in isolamento (Classe, Scuola, Insegnanti,...), NA se dato mancante
-*Chiusura scuola* : "Si" se intera scuola chiusa o didattica a distanza, "No" altrimenti
-*Contatti positivi* : Numero di contatti legati al primo caso in seguito positivi, NA fino ad aggiornamento dato a seguito di nuove informazioni
-*Primo Caso* : "Si" se e' il primo caso registrato nella scuola, "No" altrimenti
-*Fonte* : Fonte della notizia
-*Note* : Eventuali note descrittive
-*Aggiornamento* : Fonte eventuali aggiornamenti

# Ringraziamenti a:
*Vittorio Nicoletta* e *Lorenzo Ruffino* per avermi segnalato il loro progetto di raccolta e tracciamento.
- Metodologia seguita:
[http://bit.ly/metodo_scuole]
- Dataset:
[http://bit.ly/covid_scuole]

Thread twitter:
[https://twitter.com/davide_tommasin/status/1354126224931639302]
