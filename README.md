
# Sito web ufficiale di V-CaOS

Questo è il repository del sito https://v-caos.iceiy.com, ed è stato generato con [Nikola](https://www.getnikola.com/).

## Requisiti di sviluppo

- sarebbe ottimale avere una distribuzione Linux o Mac OS X, ma ci possiamo adattare anche a Windows, basta una shell bash.
- una versione installata e funzionante di Python (io ho usato la 3.11)
- un minimo di familiarità con il terminale

```
python -m pip install Nikola[extras]
nikola plugin -i sass # viene scaricato dentro il repository
```

## Sviluppare in locale

```
nikola build
nikola auto --browser
```

Quando hai finito, fai un commit e invia una pull request!

Grazie per ogni contributo!

## Creare una build statica

Per creare una singola build statica, eseguire questo comandi dalla cartella `linux-it`:

```
nikola build
```

Per segnalazioni e richieste, apri una *issue* oppure scrivi sul gruppo Telegram indicato in https://v-caos.iceiy.com/contact/.

Grazie!

## Licenza

Salvo ove diversamente indicato tutti i contenuti sono rilasciati in pubblico dominio, Creative Commons Zero.

https://creativecommons.org/publicdomain/zero/1.0/

Eccezioni: loghi di associazioni, di partner e sponsor. Contattarli per conoscere le relative licenze.
