# Manual tècnic - GreenLife


## Arquitectura
Aplicació client-servidor amb API REST.


## Tecnologies
- Backend: Node.js
- Frontend: React
- Base de dades: PostgreSQL
- Autenticació: JWT (JSON Web Tokens)

## Estructura del codi
- `/backend` - API i lògica de negoci
- `/frontend` - Interfície d'usuari
- `/database` - Migracions i models

## Autenticació JWT
- Farem servir JSON Web Tokens per autenticar les peticions. Cal obtenir un token i enviar-lo a cada petició protegida.