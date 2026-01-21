# 🦷 Sistema OdontoCare – Backend Flask

Proyecto final del curso **Python C1**.  
El sistema OdontoCare es una API REST desarrollada en Flask para la gestión de citas médicas odontológicas, implementada con una arquitectura distribuida basada en microservicios.

---

## 🚀 Tecnologías utilizadas
- Python 3
- Flask
- Flask-JWT-Extended
- SQLAlchemy
- SQLite
- Requests
- Docker y Docker Compose

---

## 🧱 Arquitectura
El sistema está compuesto por dos microservicios independientes:

1. **Servicio de Autenticación**
   - Gestión de usuarios
   - Login
   - Generación de token JWT

2. **Servicio de Citas**
   - Creación y gestión de citas médicas
   - Acceso protegido mediante JWT

Los servicios se comunican únicamente a través de endpoints REST.

---

## 🔐 Autenticación
El acceso a los endpoints protegidos requiere un token JWT enviado en el header:
