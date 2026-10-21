# Sport Arbitrage — starter Next.js

Landing page scura stile sportsbook, calcolatore a due esiti e integrazione Stripe Checkout per abbonamento informativo.

## Avvio
1. `npm install`
2. Copia `.env.example` in `.env.local` e configura chiavi di **test** Stripe, Price ID ricorrente e URL applicazione.
3. `npm run dev` e visita http://localhost:3000.
4. Configura l'endpoint webhook Stripe `/api/webhook` per `checkout.session.completed` e `customer.subscription.deleted`.

## Prima di andare online
- Implementare registrazione/login, database utenti, collegamento Stripe customer agli utenti e attivazione/revoca accessi dal webhook con idempotenza. Queste funzioni NON sono implementate nello starter.
- Definire prezzo, condizioni commerciali, privacy/cookie policy, sicurezza, gestione rimborsi e obblighi fiscali.
- Confermare che Stripe consenta questa specifica attività e ottenere consulenza legale in merito a comparazione quote, affiliazioni e normativa gioco.
- Collegare feed quote con licenza/API: lo starter NON mostra quote reali.
- Non utilizzare claim di capitale o rendimenti garantiti.
