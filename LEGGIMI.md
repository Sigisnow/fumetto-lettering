# Sito per i testi delle tavole (Elena)

- `index.html` — il sito: elenco tavole, clic su un punto = nuovo testo (chi parla, tipo, testo). Si salva da solo su Supabase (tabella `commenti_lettering`, progetto dell'app La Via Perduta).
- `tavole/` — le tavole in JPG leggeri (1400 px di altezza), generate da `tavole create da marco`.
- `tavole.json` — l'elenco delle tavole mostrate.
- Per aggiungere tavole nuove: Claude rigenera `tavole/` e `tavole.json` e ricarica tutto su GitHub.
