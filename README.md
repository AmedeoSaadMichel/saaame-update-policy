# Policy aggiornamenti Saaame

Questo repository pubblica la policy usata da Saaame per verificare la
disponibilità e l'obbligatorietà degli aggiornamenti.

Il file servito da GitHub Pages è `app-update.json`.

- `latestVersion`: versione più recente proposta all'utente.
- `minimumVersion`: versione minima consentita dall'app.
- `storeUrl`: pagina ufficiale di Saaame nell'App Store.
- `notBefore`: istante UTC prima del quale la policy non viene applicata.

Prima di aumentare una versione, sostituire `storeUrl` con l'URL definitivo
dell'app e verificare che l'aggiornamento sia già disponibile sull'App Store.
