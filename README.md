
# Sito web ufficiale di V-CaOS

Questo è il repository del sito https://v-caos.iceiy.com, ed è stato generato con [Nikola](https://www.getnikola.com/).

## Requisiti di sviluppo

- sarebbe ottimale avere una distribuzione Linux o Mac OS X, ma ci possiamo adattare anche a Windows, basta una shell bash.
- una versione installata e funzionante di Python (io ho usato la 3.11)
- un minimo di familiarità con il terminale

## Installazione

Installa Nikola:

```
python -m pip install Nikola[extras]
```

Clona il repository e apri la cartella scaricata:

```
git clone https://gitlab.com/fatualux/v-caos && cd v-caos/
```

Installa ora il plugin per il tema:

```
nikola plugin -i sass # viene scaricato dentro il repository
```

## Generare pagine del blog

**The easy way:**

Inviate il testo che vorreste pubblicare ai nostri contatti Telegram/e-mail.
Per favore, formato .txt... Vi prego, non usate **per nessuna ragione** suite office che esportano in formati eseguibili (.doc, .docx, ma nemmeno .ods),
perché sarebbe un inutile spreco di tempo (mio e vostro).

**The geek way:**

```
nikola new_post -e
```

La via del geek non necessita spiegazioni, ma per qualsiasi dubbio usate la formula *nikola + comando + -h*

## Sviluppare in locale

```
nikola build
nikola auto --browser
```

Quando hai finito, fai un commit e invia una pull request. Grazie per ogni contributo!

## Creare una build statica

Per creare una singola build statica, eseguire questo comandi dalla cartella `linux-it`:

```
nikola build
```

Per segnalazioni e richieste, apri una *issue* oppure scrivi sul gruppo Telegram indicato in https://v-caos.iceiy.com/contact/.

Grazie!

## Licenza

Salvo ove diversamente indicato tutti i contenuti sono rilasciati con licenza GPL 3.0.

https://www.gnu.org/licenses/gpl-3.0.html

Eccezioni: loghi di associazioni, di partner e sponsor. Contattarli per conoscere le relative licenze.
