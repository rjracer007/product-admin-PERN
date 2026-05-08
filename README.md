# 📦 Product Admin - PERN Stack

Un sistema integral de administración de productos que implementa el stack **PERN** (PostgreSQL, Express, React y Node.js). Esta aplicación permite gestionar un inventario completo con persistencia de datos en una base de datos relacional.


## 🏗️ Arquitectura (PERN Stack)

- **P**ostgreSQL: Base de datos relacional para el almacenamiento seguro de productos.
- **E**xpress: Framework de backend para la creación de una API RESTful robusta.
- **R**eact: Interfaz de usuario dinámica y responsiva para la gestión administrativa.
- **N**ode.js: Entorno de ejecución para el servidor de la aplicación.

## ✨ Funcionalidades Principales

- **Gestión CRUD Completa:** Crear, Leer, Actualizar y Eliminar productos del catálogo.
- **Disponibilidad Dinámica:** Control de stock y cambio de estado de disponibilidad en tiempo real.
- **API REST:** Endpoints estructurados para la comunicación entre el cliente y el servidor.
- **Validación de Datos:** Implementación de validaciones tanto en el frontend como en el backend para asegurar la integridad de la información.
- **Type Safety:** Uso de TypeScript en todo el proyecto para minimizar errores en tiempo de ejecución.

## 🛠️ Tecnologías y Herramientas

### Backend
- **Node.js & Express**: Servidor y ruteo.
- **Sequelize / Prisma / TypeORM**: (Ajustar según el ORM usado) Para la interacción con PostgreSQL.
- **Zod**: Para validación de esquemas de datos.
- **Cors & Morgan**: Middlewares para seguridad y logs.

### Frontend
- **React**: Con Vite para un desarrollo ultra rápido.
- **Tailwind CSS**: Para un panel de administración limpio y funcional.
- **React Router Dom**: Manejo de rutas protegidas y navegación.
- **Axios / React Query**: Gestión de peticiones asíncronas a la API.

## 🚀 Configuración Local

### 1. Requisitos previos
- Node.js instalado.
- Instancia de PostgreSQL corriendo.

### 2. Configuración del Servidor
```bash
cd server
npm install
# Configura tu archivo .env con las credenciales de tu DB
npm run dev
