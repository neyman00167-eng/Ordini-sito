ORDINI FORNITORI PWA v1.4

Questa versione funziona su iPhone, Android e PC tramite browser e può essere installata dalla schermata Home.

INSTALLAZIONE SU IPHONE
1. Pubblica i file su un sito HTTPS (GitHub Pages va bene).
2. Apri l'indirizzo con Safari.
3. Premi Condividi.
4. Premi “Aggiungi alla schermata Home”.
5. Apri Ordini dalla nuova icona.

PUBBLICAZIONE SU GITHUB PAGES DAL TELEFONO
1. Crea un repository GitHub, ad esempio OrdiniFornitoriPWA.
2. Carica TUTTI i file contenuti in questa cartella (non lo ZIP come unico file).
3. Nel repository apri Settings > Pages.
4. In Build and deployment scegli “Deploy from a branch”.
5. Branch: main, cartella: /(root), quindi Save.
6. Dopo circa 1-2 minuti GitHub mostrerà l'indirizzo pubblico HTTPS.

COMPATIBILITA DATI
- “Esporta liste” genera il formato OrdiniFornitoriBackup versione 2, compatibile con la versione Android v1.4.
- “Backup completo” usa suppliers/history nello stesso schema della versione Android v1.4.
- Puoi quindi trasferire fornitori e prodotti tra Android e questa PWA tramite file JSON.

NOTE IOS
I dati dell'app vengono salvati localmente nel browser/PWA. Usa periodicamente “Backup completo” se i dati sono importanti.
