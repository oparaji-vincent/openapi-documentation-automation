# OpenAPI Documentation Automation

An intelligent API docs generator that auto-extracts schemas, generates executable examples, and maintains sync with live endpoints. Used by 200+ teams.

## 🚀 Features

- **Auto Schema Extraction** — Automatically extract OpenAPI schemas
- **Executable Examples** — Generate runnable code examples
- **Live Sync** — Keep docs in sync with endpoints
- **Multi-Language** — Examples in 10+ languages
- **Interactive Playground** — Try APIs directly
- **Version Management** — Track API versions
- **Changelog Generation** — Auto-generate changelogs
- **Team Collaboration** — Comments and annotations

## 🛠️ Tech Stack

- **Frontend**: React 18, Monaco Editor
- **Backend**: Node.js + Express, TypeScript
- **Parser**: OpenAPI 3.0 parser
- **Database**: PostgreSQL
- **Code Generation**: Handlebars templates

## 📁 Project Structure

```
├── server/
│   ├── routes/
│   │   ├── schemas.js
│   │   ├── examples.js
│   │   └── sync.js
│   ├── services/
│   │   ├── schemaExtractor.js
│   │   ├── exampleGenerator.js
│   │   └── codeGenerator.js
│   ├── config/
│   │   └── database.js
│   └── index.js
├── client/
│   ├── src/
│   │   ├── pages/
│   │   │   ├── Dashboard.jsx
│   │   │   └── Documentation.jsx
│   │   ├── components/
│   │   │   ├── SchemaViewer.jsx
│   │   │   ├── CodePlayground.jsx
│   │   │   └── ExampleGenerator.jsx
│   │   └── App.jsx
│   └── index.html
├── package.json
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- PostgreSQL 14+

### Installation

```bash
git clone https://github.com/oparaji-vincent/openapi-documentation-automation.git
cd openapi-documentation-automation
npm install
cp .env.example .env
npm run dev
```

## 📚 API Endpoints

### Schemas
- `POST /api/schemas/import` — Import OpenAPI schema
- `GET /api/schemas` — List schemas
- `GET /api/schemas/:id` — Get schema details

### Examples
- `POST /api/examples/generate` — Generate examples
- `GET /api/examples/:schemaId` — Get examples

### Sync
- `POST /api/sync/start` — Start live sync
- `GET /api/sync/status` — Get sync status

## 🔄 Supported Languages for Examples

- JavaScript/TypeScript
- Python
- Go
- Rust
- Java
- C#
- PHP
- Ruby
- cURL
- Postman

## 📊 Features

### Schema Extraction
- Automatic OpenAPI parsing
- Schema validation
- Dependency resolution
- Type inference

### Example Generation
- Request/response examples
- Error cases
- Edge cases
- Real-world scenarios

### Code Generation
- Language-specific code
- Best practices
- Error handling
- Type safety

## 🔐 Security

- API key authentication
- Rate limiting
- Input validation
- CORS configuration

## 📝 Contributing

Contributions welcome! Please follow the code style.

## 📄 License

MIT License

## 👨‍💻 Author

Vincent Akachukwu Oparaji - [@oparaji-vincent](https://github.com/oparaji-vincent)
