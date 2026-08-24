# 💍 Giulia & Giovanni — Sito del Matrimonio

Sito web per il matrimonio di **Giulia Gariglio** e **Giovanni Vignola**, l'**8 maggio 2027** a Torino.

🌐 **Sito live:** [giovignola94.github.io/wedding](https://giovignola94.github.io/wedding)

---

## Contenuto del sito

| Sezione | Descrizione |
|---------|-------------|
| 🏠 Home | Hero con countdown al giorno del matrimonio e Mole Antonelliana in sfondo |
| ✉️ Presenze e intolleranze | Form Google per conferma presenza e intolleranze alimentari |
| 📍 Dove | Mappa della chiesa (Str. Revigliasco 86, Moncalieri) e del ricevimento (Via Mirabello 3/D, Torino) |
| 🕐 Programma | Timeline della giornata dall'accoglienza al party serale |
| 💝 Regalo | IBAN per contribuire al viaggio di nozze |
| 📸 Foto | Bottoni per caricare/scaricare le foto dall'album Google Foto condiviso |

L'ordine sopra è anche l'ordine di navigazione (menu laterale e pulsanti "successivo" tra le pagine).

Ogni pagina è raggiungibile anche via link diretto con l'hash nell'URL, ad es. `index.html#foto` — utile per generare un QR code che apra direttamente la pagina foto.

---

## Come aggiornare il sito

1. Vai su [github.com/giovignola94/wedding](https://github.com/giovignola94/wedding)
2. Clicca su `index.html`
3. Clicca l'icona matita ✏️ in alto a destra
4. Modifica il contenuto
5. Clicca **Commit changes**

Il sito si aggiorna automaticamente in 1-2 minuti.

---

## Cose da aggiornare prima del matrimonio

- [ ] **IBAN** — sostituire `IT00 X000 0000 0000 0000 0000 000` con quello reale
- [ ] **Orari** — verificare gli orari nel programma della giornata
- [ ] **Google Form** — assicurarsi che il form RSVP sia attivo e collegato al foglio Google
- [ ] **Album Google Foto** — creare un album condiviso ("chiunque con il link può aggiungere foto"), poi sostituire i due `href="#"` nella pagina Foto (`.foto-cta` e `.foto-cta-secondary`) con il link dell'album
- [ ] **QR code** — generarlo puntando a `index.html#foto` (o all'URL live), una volta pronto l'album

---

## Palette colori

| Nome | Hex |
|------|-----|
| Blu polvere | `#8FA8C8` |
| Rosa antico | `#D4A5A5` |
| Avorio | `#F5F0EA` |
| Oro | `#C9A84C` |

---

*Sito realizzato con ❤️ — Solo HTML, CSS e JavaScript vanilla. Nessuna dipendenza esterna.*
