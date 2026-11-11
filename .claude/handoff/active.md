---
saved-at: 2026-11-11T22:58:16Z
saved-at-sha: d1a73f4
saved-at-branch: main
saved-from-cwd: /home/claude/francy30
---

Progetto: sito regalo per i 30 anni di **Franci** (sorella di Seba), compleanno **24 novembre 2026**. Parla con Seba sempre in italiano, diretto e concreto; distingui fatto, proposta e verifica; non dire "fatto" senza aver controllato; avvisa prima di qualsiasi azione che costa soldi o crediti.

- **Cosa riprendere:** migliorare e completare il sito, poi inserire i contenuti reali man mano che Seba li manda. Prima di modificare, chiedigli solo cosa è cambiato e quali contenuti ha pronti.
- **Dove sta:** tutto il sito è in `index.html` (HTML/CSS/JS in un file, nessuna build) + `borsa.webp`, `anteprima.jpg` (anteprima link), `icona.png`. Online su GitHub Pages: https://rotondiseba-14.github.io/francy30/ (branch `main`, root). Ogni push a `main` aggiorna il sito. Copia secondaria su claude.ai artifact slug `ca694389-c467-41bb-a83a-6b043d7931ac` (opzionale tenerla allineata).
- **Contenuti da inserire (oggi segnaposto "Testo di prova"):** array `FOTO` e `TAPPE` in fondo al file; foto Cavalli; introduzione; retro delle 4 passioni; messaggi nel mazzo di bigliettini; lettera (si scrive a macchina); lettera capsula del tempo (si apre il 24/11/2036); frase "cercala vicino a…" nel gratta e scopri; video AI (da scegliere con Seba).
- **Vincoli:** NON toccare la prima schermata (pacco da aprire → "30" di particelle che esplode al tocco → "Buon compleanno Franci" a macchina), Seba l'ha approvata. Nome sempre "Franci" (non "Francy"). Palette blu/bianco, pulita e moderna, niente numerini/etichette in maiuscolo. NON cambiare l'URL: il QR del cartellino stampato (`stampa/`) punta a `/francy30/`; se si rinomina il repo va rigenerato il QR. Il sito è pubblico: attenzione a foto e dati personali.
- **Verifica obbligatoria:** ogni modifica va provata su viewport iPhone (390×844 e schermo piccolo 320–375), senza scroll orizzontale né errori in console; Safari iPhone è il target reale (blocco scroll con `body.chiuso` + `blocca()/sblocca()`, safe-area, `pointer: coarse`). Rispetta `prefers-reduced-motion`.
- **Domande aperte:** quale video AI fare e con che strumento; se aggiungere musica (serve file audio da Seba); dove nasconderà la borsa (Under Armour Undeniable 5.0 Small blu notte, già comprata).
