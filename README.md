# BrazzaVibe

Billetterie + dédicaces + nightlife

## Structure

```
05-brazzavibe/
├── backend/          # Express.js API (Port 3005)
│   ├── server.js
│   ├── package.json
│   └── db.json
├── web/              # React frontend (HTML + Babel standalone)
│   └── index.html
└── mobile/           # Flutter app
    └── lib/main.dart
```

## Démarrage

```bash
# Backend
cd 05-brazzavibe/backend
npm install
npm start

# Web — Ouvrir 05-brazzavibe/web/index.html dans un navigateur
# ou servir avec: npx serve 05-brazzavibe/web

# Mobile
cd 05-brazzavibe/mobile
flutter pub get
flutter run
```

## API

| Endpoint | Description |
|----------|-------------|
| GET /api/health | Health check |
| GET /api/stats | Statistiques |
