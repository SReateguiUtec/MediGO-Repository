# MediGO

**MediGO** es una solución tecnológica diseñada para modernizar el acceso a la salud. Permite la interacción segura y eficiente entre médicos y pacientes, eliminando barreras geográficas mediante videollamadas integradas, gestión de historiales clínicos y un sistema de pagos automatizado.

Este proyecto ha sido desarrollado para el curso **CS 2031 Desarrollo Basado en Plataformas** de la **Universidad de Ingeniería y Tecnología (UTEC)**.

<div align="center">
  <img src="MediGO.gif" alt="MediGO Logo" width="450">
</div>

## 🚀 Repositorios del Proyecto

| Componente | Repositorio | Tecnologías Clave |
| :--- | :--- | :--- |
| **Backend** | [MediGO Backend Repository](https://github.com/SReateguiUtec/backend-medigo) | Spring Boot 3.5, Java, PostgreSQL |
| **Frontend** | [MediGO Frontend Web Repository](https://github.com/SReateguiUtec/frontend-medigo.git) | React 19, TypeScript, Vite |


## 🛠️ Stack Tecnológico

### Frontend
![React](https://img.shields.io/badge/React-19.2.0-blue?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.9.3-blue?style=flat-square&logo=typescript)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4.1.17-cyan?style=flat-square&logo=tailwind-css)
![Vite](https://img.shields.io/badge/Vite-7.2.2-purple?style=flat-square&logo=vite)

### Backend
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.5.6-green?style=flat-square&logo=spring-boot)
![Java](https://img.shields.io/badge/Java-17+-orange?style=flat-square&logo=openjdk)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-blue?style=flat-square&logo=postgresql)

### Servicios de Terceros
* 💳 **Stripe:** Pasarela de pagos segura.
* 🎥 **Whereby:** Motor de videollamadas integradas.
* 🤖 **Gemini AI:** Inteligencia artificial para asistencia en consultas.


## ✨ Características Principales

### Para Pacientes 👥
* 🔍 **Búsqueda Avanzada:** Filtros por especialidad, precio y disponibilidad.
* 📅 **Agendamiento:** Gestión dinámica de citas médicas.
* 💳 **Pagos Seguros:** Proceso integrado antes de cada consulta.
* 🎥 **Teleconsulta:** Videollamadas en tiempo real sin salir de la app.

### Para Médicos 👨‍⚕️
* 📊 **Dashboard Profesional:** Vista general de agenda y pacientes.
* 📝 **Historial Clínico:** Creación y actualización de expedientes digitales.
* 👤 **Perfil Médico:** Gestión de especialidades y honorarios.


## 🏗️ Arquitectura del Sistema

El sistema utiliza una arquitectura **Cliente-Servidor** desacoplada:
1.  **Capa de Presentación:** SPA construida con React y componentes de alta calidad (Aceternity UI, Radix UI).
2.  **Capa de Negocio:** API RESTful robusta con Spring Boot siguiendo el patrón MVC.
3.  **Seguridad:** Autenticación y autorización basada en **JWT (JSON Web Tokens)**.


## 👥 Equipo de Desarrollo

| Nombre | Código |
| :--- | :--- |
| **Sebastian Hernan Reategui Bellido** | 202410048
| **Juan Diego Mejia Armas** | 202410271


## 📄 Licencia

Este proyecto está bajo la **Licencia MIT**. Esto permite el uso, copia y modificación del software de forma libre, siempre que se mantenga la atribución original. Consulta el archivo `LICENSE` para más detalles.