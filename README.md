# monitor-siti

Ogni 5 minuti chiama il controllo dei siti web di Ospita
(`/api/cron/controllo-siti`). Stato, storico e notifiche sono nel superadmin
di Ospita → **Siti web**.

- Il secret `CRON_SECRET` (Settings → Secrets and variables → Actions) deve
  essere uguale a quello del progetto Vercel di Ospita.
- Il repository è pubblico solo perché così i minuti di GitHub Actions sono
  gratuiti: non contiene dati né credenziali.
