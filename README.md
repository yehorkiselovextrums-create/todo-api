# Todo API

A full-stack todo application with Express.js backend, PostgreSQL database, and a modern responsive frontend.

## Features

- ✅ Add, complete, and delete todos
- 📱 Fully responsive design
- 🎨 Beautiful gradient UI with animations
- 🚀 Fast Express.js API
- 🗄️ PostgreSQL database persistence
- 🔄 Real-time updates

## Tech Stack

- **Backend**: Express.js 4.19 + Node.js 18+
- **Database**: PostgreSQL
- **Frontend**: HTML5, CSS3, Vanilla JavaScript (no frameworks)
- **Deployment**: Railway

## Local Development

```bash
# Install dependencies
npm install

# Set DATABASE_URL
export DATABASE_URL="postgresql://localhost/todos"

# Start server
npm start

# Visit http://localhost:3000
```

## API Endpoints

- `GET /api/todos` — Get all todos
- `POST /api/todos` — Create a todo
- `PATCH /api/todos/:id` — Update a todo (toggle completed or edit title)
- `DELETE /api/todos/:id` — Delete a todo

## Deployment

Deployed on Railway with automatic PostgreSQL integration.