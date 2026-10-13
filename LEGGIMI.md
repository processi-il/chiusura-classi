# Chiusura classi

Controllo di fine giornata: registro ClasseViva confrontato con la pianificazione e con il piano aule del gestionale, più l'elenco dei sostegni firmati.

## Uso
1. Apri `index.html` (oppure la pagina pubblicata su GitHub Pages) con Chrome o Edge (doppio clic). Serve internet perché la pagina carica le librerie per leggere PDF ed Excel; i file però restano sul PC.
2. Trascina nel riquadro 1 il PDF del registro del giorno, estratto da ClasseViva.
3. Trascina nel riquadro 2 l'Excel della pianificazione. La pagina usa i primi due fogli, l'orario e la struttura dei codici. In alternativa puoi caricare insieme i due CSV.
4. Facoltativo: trascina nel riquadro 3 il `PianoAule.xls` del giorno scaricato dal gestionale. Nel confronto compare la colonna **Piano aule**.
5. Tab **Confronto**: elenca solo le anomalie, divise per classe: docente diverso, materia diversa, ora senza firma, firma non pianificata, supplenza; con il piano aule anche: non presente nel piano aule, docente o materia diversi nel piano aule, lezione solo nel piano aule.
6. Tab **Sostegni**: riepilogo per docente e dettaglio per classe, con la casella da spuntare sul cartaceo. Si stampa con "Stampa sostegni". Con il piano aule, ogni sostegno firmato dice se era previsto, e in testa ci sono i sostegni previsti nel piano aule ma non firmati.
7. Se una materia o un docente risultano "diversi" ma in realtà sono la stessa cosa, premi **= materia** / **= docente**: l'equivalenza viene ricordata e la trovi nel tab **Equivalenze**.

Anche senza il PDF, caricando pianificazione e piano aule si vede il confronto tra i due (utile la mattina, prima delle lezioni).

## Note
- Ora I = 08:30, ora II = 09:30, e così via.
- Le classi del registro che non hanno una colonna nella pianificazione (4AE, 4BD, 4CG, I-II, III, TPM) non vengono confrontate, ma i loro sostegni compaiono.
- Nel piano aule, quando in un'ora ci sono più docenti ("ROSSI MARIO - BIANCHI ANNA"), il primo è quello della lezione e gli altri sono sostegno o compresenza.
- Il piano aule viene confrontato solo se è dello stesso giorno del registro.
- Scarica il PDF a fine giornata: se lo estrai prima, le ore del pomeriggio risultano "senza firma".
