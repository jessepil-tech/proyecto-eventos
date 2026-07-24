# Plataforma de Eventos - Backend

## Descripción
API REST para una plataforma de gestión de eventos e inscripciones. Este proyecto corresponde a la pre-entrega 1 de Backend II, donde se establece la estructura arquitectónica base del servidor.

## Tecnologías
- Node.js
- Express
- dotenv

## Instalación
\`\`\`bash
git clone https://github.com/jessepil-tech/proyecto-eventos.git
cd proyecto-eventos
npm install
\`\`\`

## Configuración de variables de entorno
Crear un archivo `.env` en la raíz basado en `.env.example`, con las siguientes variables:
- `PORT`: puerto donde corre el servidor
- `NODE_ENV`: entorno de ejecución (development/production)
- `MONGO_URL`: URL de conexión a MongoDB
- `JWT_SECRET`: clave secreta para JWT

## Cómo ejecutar
\`\`\`bash
npm run dev
\`\`\`

## Estructura de carpetas
```
src/
├── app.js
├── server.js
├── config/
├── routes/
│   ├── events.router.js
│   └── sessions.router.js
├── controllers/
├── services/
├── repositories/
├── dao/
├── models/
│   ├── User.js
│   └── Event.js
├── middlewares/
└── utils/
```

## Rutas disponibles
| Método | Ruta | Descripción |
|---|---|---|
| GET | /api/health | Verifica que el servidor esté activo |
| GET | /api/events | Lista de eventos (vacía en esta etapa) |
| GET | /api/sessions | Estructura inicial de sesiones (vacía en esta etapa) |

##  Autor
Jessica Martinez