# Giochi in CAA con Gemini – motore delle attività

Motore delle attività create con la skill **/giochi-caa** per Gemini, a cura di **Sabrina Pallara**.

Attività didattiche in CAA, in forma ludica, per alunni che comunicano con i simboli: l'alunno/a mette ogni cartoncino al posto giusto (scene disegnate, cartina vera dell'Italia, contenitori, metti in ordine, conta e metti, tombola, tabella parlante, mimo; in italiano, inglese o spagnolo), con voce, simboli ARASAAC, livelli 1-5, pannello per l'insegnante e versione da stampare.

## File
- `motore-v1.js` – il motore. Le attività lo caricano da `https://profpally.github.io/giochi-caa/motore-v1.js`. **Non modificarlo:** per le nuove versioni si crea un file nuovo (`motore-v2.js`), così le attività già create non cambiano.
- `esempio-italia.html` – set di esempio sull'Italia (cartina, Nord-Centro-Sud, tombola, tabella parlante).
- `esempio-discipline.html` – set di esempio per più discipline (metti in ordine, conta e metti, tombola in inglese, tabella in spagnolo).
- `creatore.html` – crea un set di giochi scegliendo le parole dalla libreria di simboli, senza Gemini.
- `lettore.html` – per aprire un'attività incollando il suo blocco CONFIG.
- `fonts/` – carattere Atkinson Hyperlegible, ospitato qui per non collegarsi a servizi esterni.

## Licenze e attribuzioni
- Motore, testi e disegni: © Sabrina Pallara, licenza [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.it). Uso didattico gratuito, non commerciale, citando l'autrice e condividendo le modifiche con la stessa licenza.
- Pittogrammi: una libreria di ~700 parole è inclusa nella cartella `simboli/` (controllata a mano, `lessico.json`); per le altre parole l'attività li cerca sul sito ARASAAC. Autore: Sergio Palao. Origine: ARASAAC (https://arasaac.org). Licenza: CC BY-NC-SA. Proprietà: Governo di Aragona (Spagna).
- Carattere Atkinson Hyperlegible: © Braille Institute of America, licenza SIL Open Font License 1.1 (`fonts/OFL.txt`).

## Privacy
Il motore non raccoglie né invia dati. Nome dell'alunno/a e impostazioni restano nella pagina e nel browser del dispositivo. L'attività si collega solo a GitHub (per il motore e il carattere) e ad ARASAAC (per i pittogrammi).
