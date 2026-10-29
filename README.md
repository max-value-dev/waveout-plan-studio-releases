# WaveOut Plan Studio

Crea programmi di allenamento e alimentazione con anteprima PDF, libreria atleti e salvataggio locale.

**[Scarica l’ultima versione per Windows](https://github.com/max-value-dev/waveout-plan-studio-releases/releases/latest)**

## Primo avvio

1. Scarica l’installer `.exe` dalla pagina qui sopra e aprilo.
2. Installa WaveOut Plan Studio e avvialo dal menu Start.
3. Scegli il nome del tuo Studio, la lingua dei PDF e le preferenze dei nuovi piani.

Compatibile con Windows 10/11 x64 (Intel o AMD). Non servono un account GitHub, un server o strumenti di sviluppo. L’app funziona offline; la connessione serve per gli aggiornamenti.

Se usavi la versione portatile 1.2, esporta un backup, chiudila e installa la nuova versione con lo stesso account Windows. I dati rimangono in `%APPDATA%\WaveOut Plan Studio`. Dopo la verifica usa il nuovo collegamento nel menu Start.

## Aggiornamenti

L’app controlla le nuove versioni all’avvio e ogni quattro ore. Quando compare il messaggio, scegli **Scarica aggiornamento**. Puoi continuare a lavorare. **Salva e riavvia** conserva le modifiche, crea un backup e installa la nuova versione; **Più tardi** rimanda il riavvio.

Puoi controllare manualmente dall’icona aggiornamenti nella barra sinistra o da **Aiuto → Controlla aggiornamenti**. Non serve ricevere un nuovo file ogni volta.

## I tuoi dati

Profili, piani e PDF restano sul tuo PC. Questo repository contiene soltanto il programma da scaricare e le istruzioni: non caricare qui dati degli atleti o backup. Esporta regolarmente un backup da **Impostazioni → Backup e dati** su un disco separato.

L’installer non ha un certificato del produttore Windows (Authenticode): Windows potrebbe mostrare un avviso. Verifica che il file provenga da questa pagina. Gli aggiornamenti vengono verificati dall’app con una firma Ed25519 e un controllo SHA-512 prima dell’installazione. Non disattivare le protezioni del computer.
