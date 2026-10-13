# Chiusura classi

Controllo di fine giornata: registro ClasseViva confrontato con la pianificazione, più l'elenco dei sostegni firmati.

## Uso
1. Apri `chiusura-classi.html` con Chrome o Edge (doppio clic). Serve internet perché la pagina carica le librerie per leggere PDF ed Excel; i file però restano sul PC.
2. Trascina nel riquadro 1 il PDF del registro del giorno, estratto da ClasseViva.
3. Trascina nel riquadro 2 l'Excel della pianificazione. La pagina usa i primi due fogli, l'orario e la struttura dei codici. In alternativa puoi caricare insieme i due CSV.
4. Tab **Confronto**: elenca solo le anomalie, divise per classe: docente diverso, materia diversa, ora senza firma, firma non pianificata, supplenza.
5. Tab **Sostegni**: riepilogo per docente e dettaglio per classe, con la casella da spuntare sul cartaceo. Si stampa con "Stampa sostegni".
6. Se una materia o un docente risultano "diversi" ma in realtà sono la stessa cosa, premi **= materia** / **= docente**: l'equivalenza viene ricordata e la trovi nel tab **Equivalenze**.

## Note
- Ora I = 08:30, ora II = 09:30, e così via.
- Le classi del registro che non hanno una colonna nella pianificazione (4AE, 4BD, 4CG, I-II, III, TPM) non vengono confrontate, ma i loro sostegni compaiono.
- Scarica il PDF a fine giornata: se lo estrai prima, le ore del pomeriggio risultano "senza firma".
