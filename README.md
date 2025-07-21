# 🍛 Recetas API

Este es el backend de una futura aplicación de recetas, desarrollada para mi portafolio personal. El objetivo es demostrar mis habilidades en la creación de APIs robustas, arquitectura backend, manejo de autenticación y bases de datos relacionales.

---

## 🛠️ Tecnologías utilizadas

- [Node.js](https://nodejs.org/es) – Entorno de ejecución para JavaScript en el servidor.
- [Express](https://expressjs.com/es/) – Framework minimalista y flexible para construir APIs.
- [PostgreSQL](https://www.postgresql.org/download/) – Sistema de gestión de bases de datos relacional.
- [Sequelize](https://sequelize.org/) – ORM para Node.js con soporte para PostgreSQL.
- [JSON Web Tokens (JWT)](https://jwt.io/) – Mecanismo para autenticación segura basada en tokens.

---

## 🚧 Estado del proyecto

> Este proyecto está en desarrollo activo.  
> Pronto se agregarán endpoints, documentación de la API, y ejemplos de uso.

---

## 📌 Objetivos

- Construir una API RESTful modular y escalable.
- Implementar autenticación con JWT.
- Crear endpoints para gestión de recetas, ingredientes y usuarios.
- Validaciones y manejo adecuado de errores.

---

## 📂 Estructura del proyecto

```plaintext
recetas-api/
├── src/
│   ├── config/            # Configuración de Sequelize, conexión DB, etc.
│   ├── controllers/       # Lógica de negocio para cada recurso
│   ├── middlewares/       # Middlewares personalizados (auth, validaciones, errores)
│   ├── models/            # Modelos Sequelize
│   ├── routes/            # Definición de rutas y endpoints
│   ├── services/          # Servicios reutilizables (opcional)
│   └── app.js             # Instancia de Express y configuración de middlewares
├── .env                   # Variables de entorno
├── .gitignore
├── package.json
└── README.md
```

---

## 📋 Próximamente

- Documentación de endpoints.
- Tests automatizados con Jest.
