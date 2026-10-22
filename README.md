# Mini ERP - Práctica de Laboratorio

Este proyecto es un Mini ERP desarrollado con una arquitectura Frontend-API-Backend-Base de datos.

## Tecnologías
- **Frontend:** React + TypeScript + Vite
- **Backend:** Node.js + Express
- **Base de Datos:** MySQL (Laragon)
- **Pruebas:** Postman

## Cómo ejecutar
1. Importar `mini_erp.sql` en HeidiSQL.
2. En `backend`: `npm install` y luego `npm run dev`.
3. En `frontend`: `npm install` y luego `npm run dev`.
4. Abrir `http://localhost:5173`.

## Características
- CRUD de Productos y Clientes.
- Registro de Ventas con validación de stock.
- Middlewares (Logger, Validación, Autenticación).