# 🏢 Administración de Edificios – SaaS App (MVP)

App web para la administración de edificios y consorcios, con gestión de unidades, expensas, reclamos y avisos.

---

## 🚀 Tecnologías

- 🔙 Backend: Java + Spring Boot
- 🌐 Frontend: React + Tailwind CSS
- 🛢️ Base de datos: MySQL / PostgreSQL
- 🔐 Seguridad: JWT (Spring Security)
- 📦 Monorepo: Frontend y Backend en un solo repo

---

## 📁 Estructura del Proyecto

```
admin-edificios/
├── backend/       → Spring Boot (API REST)
└── frontend/      → React + Tailwind (SPA)
```

---

## ▶️ Cómo correr el proyecto

### 📦 Backend

1. Entrar a la carpeta `backend`:

```bash
cd backend
```

2. Configurar la base de datos en `src/main/resources/application.yml`

3. Correr con Maven o tu IDE:

```bash
./mvnw spring-boot:run
```

La API corre por defecto en: [http://localhost:8080](http://localhost:8080)

---

### 🌐 Frontend

1. Entrar a la carpeta `frontend`:

```bash
cd frontend
```

2. Instalar dependencias:

```bash
npm install
```

3. Correr el servidor de desarrollo:

```bash
npm run dev
```

La app abre en: [http://localhost:5173](http://localhost:5173)

---

## 📌 Funcionalidades del MVP

- Registro y login con JWT
- Roles: Administrador / Propietario
- Gestión de edificios y unidades
- Carga y visualización de expensas
- Reclamos y seguimiento
- Avisos del administrador
- Dashboard por rol

---

## 🛠️ En desarrollo

Este proyecto está en etapa MVP y seguirá creciendo. Se aceptan sugerencias y mejoras 💬

---

## 🧑‍💻 Autor

Bruno Giménez – [LinkedIn](https://linkedin.com)
