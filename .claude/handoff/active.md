---
saved-at: 2026-11-11T22:58:16Z
saved-at-sha: d1a73f4
saved-at-branch: main
saved-from-cwd: /home/claude/francy30
---

Progetto: sito regalo per i 30 anni di **Franci** (sorella di Seba), compleanno **24 novembre 2026**. Parla con Seba sempre in italiano, diretto e concreto; distingui fatto, proposta e verifica; non dire "fatto" senza aver controllato; avvisa prima di qualsiasi azione che costa soldi o crediti.

- **Cosa riprendere:** migliorare e completare il sito, poi inserire i contenuti reali man mano che Seba li manda. Prima di modificare, chiedigli solo cosa è cambiato e quali contenuti ha pronti.
- **Dove sta:** tutto il sito è in `index.html` (HTML/CSS/JS in un file, nessuna build) + `borsa.webp`, `anteprima.jpg` (anteprima link), `icona.png`. Online su GitHub Pages: https://rotondiseba-14.github.io/francy30/ (branch `main`, root). Ogni push a `main` aggiorna il sito. Copia secondaria su claude.ai artifact slug `ca694389-c467-41bb-a83a-6b043d7931ac` (opzionale tenerla allineata).
- **Contenuti da inserire (oggi segnaposto "Testo di prova"):** foto inserite il 22/11 in `foto/` (galleria `FOTO`, Cavalli, retro delle passioni) dalla cartella del Mac "COMPLEANNO FRA"; `TAPPE` ora hanno una foto ciascuna (anni stimati dalle foto, marcati `stima: true`, da confermare; 1996 senza foto: Seba porterà foto di quando era piccola); introduzione; retro delle 4 passioni; (sezione messaggi/bigliettini eliminata il 22/11); canzone Suno FATTA il 23/11: link in `SUNO_LINK` (https://suno.com/s/rnglsgx1QTXn4ZWR), titolo "Auguri Franci"; video di auguri FATTO il 23/11: `auguri.mp4` (13 videomessaggi in cornici su sfondo stellato + apertura e chiusura animate, 71 s, 15 MB; sorgenti e script in /tmp/ed non persistenti), niente nomi a schermo per scelta di Seba; la capsula del tempo è stata eliminata il 21/11; frase "cercala vicino a…" nel gratta e scopri; 
- **Vincoli:** NON toccare la prima schermata (pacco da aprire → "30" di particelle che esplode al tocco → "Buon compleanno Franci" a macchina), Seba l'ha approvata. Nome sempre "Franci" (non "Francy"). Palette blu/bianco, pulita e moderna, niente numerini/etichette in maiuscolo. NON cambiare l'URL: il QR del cartellino stampato (`stampa/`) punta a `/francy30/`; se si rinomina il repo va rigenerato il QR. Il sito è pubblico: attenzione a foto e dati personali.
- **Verifica obbligatoria:** ogni modifica va provata su viewport iPhone (390×844 e schermo piccolo 320–375), senza scroll orizzontale né errori in console; Safari iPhone è il target reale (blocco scroll con `body.chiuso` + `blocca()/sblocca()`, safe-area, `pointer: coarse`). Rispetta `prefers-reduced-motion`.
- **Domande aperte:** se aggiungere musica (serve file audio da Seba); dove nasconderà la borsa (Under Armour Undeniable 5.0 Small blu notte, già comprata).
