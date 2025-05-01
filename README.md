
# Backend – Node.js (Express)

Enkel API-backend för att hämta data till React-frontend.

## Så här kör du den lokalt

1. Navigera till mappen:
```bash
cd backend-node
```

2. Installera beroenden:
```bash
npm install
```

3. Starta servern:
```bash
npm start
```

Servern körs då på http://localhost:5000 och har en endpoint:
- `GET /api/data` – returnerar JSON med ett meddelande och aktuellt datum

Frontend-appen förväntar sig detta API för att visa data.
