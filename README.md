# Minimalist E-Commerce Backend - Production Ready API

## 🚀 About This Project

**The complete backend API** powering the [Minimalist E-Commerce Frontend](https://franciscojgonzalezfernandez-lgtm.github.io/minimalist-e-commerce/). Built with **NestJS** for enterprise-grade scalability, featuring full product management, authentication, and database integration.

**[📖 API Docs](https://minimalist-ecommerce-backend.onrender.com/api/)** | **[ 📖 Frontend Demo](https://franciscojgonzalezfernandez-lgtm.github.io/minimalist-e-commerce/)**

## ✨ Featured Technologies

| Category     | Tech Stack              |
|--------------|-------------------------|
| Framework    | **NestJS** (Node.js)    |
| Language     | TypeScript              |
| Database     | PostgreSQL              |
| ORM          | TypeORM / Prisma        |
| Container    | Docker + Docker Compose |
| Linting      | ESLint + Prettier       |
| Testing      | Jest                    |


## 🎯 Key Features

- **Full Product CRUD** - Create, read, update, delete products
- **User Authentication** - JWT tokens + secure sessions
- **RESTful API** - Clean endpoints with validation
- **Database Migrations** - Schema management
- **Docker Ready** - One-command deployment
- **Production Config** - Environment variables + logging

**Powers the complete e-commerce flow** - cart, orders, inventory

## 🎯 Getting Started

```bash
# Clone & Install
git clone https://github.com/franciscojgonzalezfernandez-lgtm/minimalist-ecommerce-backend.git
cd minimalist-ecommerce-backend
npm install

# Development (with hot reload)
npm run start:dev

# Production Build
npm run build:prod

# Docker (Postgres + API)
docker-compose up -d
🗄️ Database Setup
text
# docker-compose.yaml excerpt
postgres:
  image: postgres:16
  environment:
    POSTGRES_DB: ecommerce
    POSTGRES_USER: postgres
    POSTGRES_PASSWORD: password
📊 API Endpoints
Method	Endpoint	Description
POST	/auth/login	User authentication
GET	/products	List all products
POST	/products	Create new product
PUT	/products/:id	Update product
DELETE	/products/:id	Delete product
🎯 Full Stack Demo
Complete E-Commerce Experience
```

Built with ❤️ using enterprise-grade NestJS (2026 stack)

**⭐ Star for more APIs**
