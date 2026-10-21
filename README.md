# 🍕 Pizzeria Bella Manu

Un piccolo progetto web dedicato a **Pizzeria Bella Manu**, a Fondi: un sito semplice e accogliente per raccontare la pizzeria, presentare i menu e aiutare i clienti a trovare le informazioni per una visita.

## Il progetto

Il sito è realizzato con **HTML e CSS**, senza framework o dipendenze da installare. La pagina principale presenta la pizzeria; la pagina contatti raccoglie indirizzo, telefono e orari. Le pagine dedicate a pizze, bibite e dolci sono predisposte per ospitare i rispettivi menu.

## Pagine

- **Home** — presentazione della pizzeria e della sua filosofia.
- **Menu pizze** — `menu/menupizze.html`
- **Menu bibite** — `menu/menubibite.html`
- **Menu dolci** — `menu/menudolci.html`
- **Contatti** — indirizzo, telefono e orari.

## Struttura dei file

```text
.
├── index.html             # Pagina principale
├── contatti.html          # Informazioni per raggiungere la pizzeria
├── style.css              # Stili condivisi
└── menu/
    ├── menupizze.html     # Menu delle pizze
    ├── menubibite.html   # Menu delle bibite
    └── menudolci.html    # Menu dei dolci
```

## Avvio in locale

Non serve compilare il progetto né installare pacchetti. Puoi aprire `index.html` direttamente nel browser oppure avviare un server locale dalla cartella del progetto:

```bash
python3 -m http.server 8000
```

Poi visita [http://localhost:8000](http://localhost:8000).

## Collaborazione

Ogni contributo aiuta a rendere il sito più completo. Le assegnazioni iniziali delle sezioni sono:

| Sviluppatore | Sezione |
| --- | --- |
| Jasmine | Pizze |
| Aurora | Dolci |
| Mattia | Bibite |

Per aggiungere o aggiornare una portata, modifica la pagina HTML della sezione corrispondente e mantieni coerenti navigazione e stile del sito.

## Prima della pubblicazione

Controlla e aggiorna i recapiti e gli orari mostrati in `contatti.html`: i dati presenti (incluso il numero telefonico) sono valori di esempio e vanno verificati prima di essere condivisi con i clienti.
