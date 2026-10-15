# Focchy Releases

Repository pubblico usato esclusivamente per distribuire gli APK di **Focchy**.

Il codice sorgente dell'app resta nel repository privato `lupo-spaziale/ottavia-pasti`.

## Regole
- Non inserire codice sorgente, keystore, token, password o dati personali.
- `Focchy.apk` è l'APK corrente del canale interno.
- `latest.json` contiene i metadati letti dall'app per rilevare gli aggiornamenti.
- `release-request.json` indica quale commit privato deve essere compilato.
- L'APK deve mantenere package `com.aniellopassariello.focchy` e la stessa firma per aggiornarsi senza cancellare i dati locali.
