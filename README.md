## Español ✨

Auth Backend – Desafío Full Stack (Usuarios, JWT y PostgreSQL)

Este proyecto corresponde al desarrollo del backend de un sistema de autenticación de usuarios, utilizando **Node.js**, **Express**, **JWT** y **PostgreSQL**, enfocado en el registro, login y obtención segura de datos de usuarios autenticados.

El objetivo fue construir un servidor robusto que permita manejar credenciales, generar tokens de acceso y proteger rutas mediante middlewares personalizados.

# Características principales

- Registro de nuevos usuarios mediante la ruta **POST /usuarios**, con contraseñas encriptadas usando **bcrypt**.
- Inicio de sesión con la ruta **POST /login**, que genera un **token JWT** firmado utilizando una llave secreta.
- Ruta protegida **GET /usuarios** que devuelve la información del usuario autenticado.
- Validación del token recibido en la cabecera **Authorization** usando un middleware personalizado.
- Middleware adicional para reportar en la terminal todas las solicitudes realizadas al servidor.
- Uso del patrón **MVC** (Model-View-Controller) para mantener una arquitectura clara y escalable.
- Manejo de errores centralizado para devolver respuestas claras al cliente.

# Tecnologías utilizadas

- Node.js  
- Express  
- PostgreSQL  
- pg  
- JWT (jsonwebtoken)  
- bcryptjs  
- dotenv  

---

## English ✨

Auth Backend – Full Stack Challenge (Users, JWT & PostgreSQL)

This project focuses on developing the backend of an authentication system using **Node.js**, **Express**, **JWT**, and **PostgreSQL**, handling user registration, login, and secure retrieval of authenticated user data.

The goal was to build a robust server capable of managing credentials, generating access tokens, and protecting routes through custom middlewares.

# Key Features

- User registration via **POST /usuarios**, with passwords encrypted using **bcrypt**.
- Login through **POST /login**, which returns a signed **JWT token** containing the user’s email.
- Protected route **GET /usuarios** that returns the authenticated user’s information.
- Token validation through a custom middleware that checks the **Authorization** header.
- Additional middleware to log all incoming server requests directly in the terminal.
- Implementation of the **MVC** (Model-View-Controller) pattern for a clean and scalable architecture.
- Centralized error handling to provide clear and consistent API responses.

# Technologies Used

- Node.js  
- Express  
- PostgreSQL  
- pg  
- JWT (jsonwebtoken)  
- bcryptjs  
- dotenv  
