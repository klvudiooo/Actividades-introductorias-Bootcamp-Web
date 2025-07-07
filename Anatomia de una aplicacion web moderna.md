# 🚀 Arquitectura de Aplicaciones Web

## 🖥️ 1. **Frontend** (Lo que el usuario ve e interactúa)

### 📌 ¿Qué es?
El **frontend** es la **parte visual** de una aplicación web, es decir, **todo lo que ves y con lo que interactúas** en tu navegador.

### ✅ ¿Qué incluye?
- Botones
- Formularios
- Textos
- Imágenes
- Menús
- Animaciones

### 🧠 ¿Qué tecnologías se usan?

| Tecnología | ¿Para qué sirve? |
|------------|------------------|
| **HTML** | Estructura del contenido |
| **CSS** | Diseño y estilos visuales |
| **JavaScript** | Lógica e interactividad |
| **Frameworks** (React, Vue, Angular) | Crear interfaces dinámicas más rápido |

### 🎯 Objetivo
Que el usuario **pueda ver, entender y usar** la aplicación de forma cómoda y atractiva.

---

## ⚙️ 2. **Backend** (La lógica interna y el servidor)

### 📌 ¿Qué es?
El **backend** es la parte **que no ves**, pero que **hace que todo funcione** por detrás. Se encarga de:
- Procesar los datos
- Responder peticiones del usuario
- Conectarse con la base de datos
- Aplicar reglas del negocio

### ✅ ¿Qué incluye?
- Servidor (donde vive la app)
- Lógica del negocio
- Seguridad y validaciones
- API (interfaz para comunicarse con el frontend)

### 🧠 ¿Qué tecnologías se usan?

| Lenguaje | Frameworks comunes |
|----------|-------------------|
| **Java** | Spring Boot |
| **JavaScript** | Node.js |
| **Python** | Django, Flask |
| **PHP** | Laravel |

También se usan servidores como **Apache**, **Nginx**, o plataformas como **Firebase** y **Heroku**.

### 🎯 Objetivo
**Responder al frontend** con la información correcta, realizar procesos y garantizar que todo funcione bien.

---

## 🗄️ 3. **Base de datos** (Donde se guarda la información)

### 📌 ¿Qué es?
Una **base de datos** es un lugar donde la aplicación **guarda la información de forma organizada**. Es como una gran "libreta digital" que almacena todo.

### ✅ ¿Qué guarda?
- Usuarios registrados
- Contraseñas (encriptadas)
- Productos
- Mensajes
- Historiales, pedidos, comentarios, etc.

### 🧠 Tipos de bases de datos:

| Tipo | Ejemplos |
|------|----------|
| **Relacionales** | MySQL, PostgreSQL |
| **No relacionales** | MongoDB, Firebase |

Las relacionales usan **tablas** con filas y columnas (como Excel), mientras que las no relacionales usan estructuras como **documentos o colecciones**.

### 🎯 Objetivo
Guardar, organizar y permitir el acceso eficiente a la **información importante** de la aplicación.

---

## Diagrama explicativo de como se conectan los tres 

## 🔄 Flujo de Conexión: Frontend - Backend - Base de Datos

```text
┌─────────────┐     API/HTTP     ┌─────────────┐     Query     ┌──────────────┐
│  FRONTEND   │ ◄──────────────► │   BACKEND   │ ◄────────────►│  BASE DATOS  │
│             │                  │             │               │              │
│ • HTML      │                  │ • Servidor  │               │ • Tablas     │
│ • CSS       │                  │ • API       │               │ • Documentos │
│ • JS        │                  │ • Lógica    │               │ • Consultas  │
│ • Frameworks│                  │ • Seguridad │               │ • Respaldos  │
└─────────────┘                  └─────────────┘               └──────────────┘
     ↑                                                            ↑
     │                                                            │
     └─────────────── El usuario ve los datos ───────────────────┘

### 🎯 Puntos clave para recordar:
- **Frontend**: Lo que ve el usuario
- **Backend**: La lógica que no se ve
- **Base de datos**: Donde se guarda todo
- **API**: El puente de comunicación entre Frontend y Backend
- **Flujo**: Usuario → Frontend → Backend → Base de datos → Backend → Frontend → Usuario

