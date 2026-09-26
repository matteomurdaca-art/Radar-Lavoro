# RADAR Lavoro — prototipo demo

Strumento per le agenzie per il lavoro. L'agenzia resta l'intermediario: aziende clienti e
lavoratori usano ciascuno la propria app, la filiale gestisce tutto dalla dashboard.

> Prototipo dimostrativo con dati di prova: nessun database, nessun dato reale.
> Software proprietario, vedi [LICENSE](LICENSE).

## Le tre viste
- **Agenzia**: approva le richieste arrivate dal portale, vede sul radar i lavoratori compatibili
  attorno al cliente, invia le proposte e segue le risposte o le fasi della selezione.
- **Azienda**: chiede personale e segue lo stato in tempo reale. Vede solo numeri e nomi dei
  confermati, mai l'elenco dei lavoratori né i loro contatti.
- **Lavoratore**: aggiorna disponibilità, turni e distanza, carica i rinnovi delle abilitazioni,
  risponde alle proposte.

## Tre tipi di ricerca
- **Urgente**: oggi o nei prossimi giorni; conta la vicinanza, risposte in minuti.
- **Missione**: somministrazione di settimane o mesi; risposte entro un giorno.
- **Selezione**: assunzione diretta; conta l'esperienza, con fasi candidato → colloquio →
  presentato al cliente → assunto.

## Pubblicazione
Caricare i file in un repository GitHub e attivare Pages (Settings > Pages > branch `main`).
