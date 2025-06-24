# 🏗️ Arquitectura del Sistema – Libro de Clases Digital (LCD)

Este documento describe los principales componentes del sistema LCD y su interacción.

---

## 🧱 Componentes principales

- **Frontend (Angular)**  
  Aplicación web para docentes, UTP, apoderados y estudiantes.

- **Backend API (Node.js + Express)**  
  Servicios REST para gestión de usuarios, asistencia, calificaciones y reportes.

- **Microservicio de analítica (Python + Flask)**  
  Procesa métricas e indicadores educativos a partir de los datos del sistema.

- **Base de datos**  
  PostgreSQL alojada en la infraestructura institucional.

- **Integraciones externas**  
  - SIGE / MINEDUC  
  - LDAP para autenticación  
  - Servicios de notificación por correo electrónico

---

## 🔄 Flujo general

1. El usuario inicia sesión en el frontend con credenciales institucionales.  
2. El frontend hace peticiones a la API REST del backend.  
3. El backend consulta la base de datos y servicios externos según la petición.  
4. Para análisis avanzados, el backend delega al microservicio de analítica.  
5. La respuesta se envía de vuelta al frontend y se presenta al usuario.

---

## 🧩 Diagrama simple (descripción textual)

Pronto se añadirá un diagrama visual en formato SVG o PNG.

---

## 🔐 Seguridad y control de acceso

- **Autenticación**: Tokens JWT validados contra LDAP.  
- **Autorización**: Control de roles (docente, UTP, estudiante, apoderado).  

---

## 🧪 Entornos de despliegue

- **Desarrollo**: Entorno local con datos de prueba.  
- **Staging**: Validación interna antes de producción.  
- **Producción**: Uso real en establecimientos educativos.

---
