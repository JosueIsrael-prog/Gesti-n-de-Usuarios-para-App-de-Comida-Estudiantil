<div align="center">

# 🍽️ CateringCRUD: Gestión de Usuarios para App de Comida Estudiantil

<img src="https://img.shields.io/badge/Status-En%20Desarrollo-yellow?style=for-the-badge" alt="Status">
<img src="https://img.shields.io/badge/Frontend-React%20%2B%20Vite-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
<img src="https://img.shields.io/badge/Backend-Node.js%20%2F%20Express-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">

*Panel de administración full-stack moderno y seguro para la gestión integral de usuarios en plataformas de comida estudiantil.*

</div>

---

## 🚀 Acerca del Proyecto

**CateringCRUD** es una aplicación web full-stack diseñada para la administración eficiente de usuarios (**Create, Read, Update, Delete**) dentro de un entorno enfocado en la comunidad estudiantil. El sistema simula un panel de control centralizado (*Dashboard*) donde el personal autorizado puede supervisar y administrar cuentas de manera segura.

### ✨ Características Principales
* **Autenticación Segura:** Control de acceso mediante **JWT (JSON Web Tokens)** para operaciones de inicio y cierre de sesión.
* **Rutas Protegidas:** Implementación avanzada con **React Router v6** para restringir vistas según el estado de sesión del usuario.
* **CRUD Completo:** Interfaz fluida en el frontend para crear, listar, editar y eliminar registros de usuarios.
* **Diseño Acogedor:** Interfaz con una paleta de colores cálida inspirada en la atmósfera de una cafetería.

---

## 🎨 Paleta de Colores

El diseño visual busca transmitir cercanía y calidez, ideal para aplicaciones orientadas a estudiantes:

| Nombre Visual | Color Hexadecimal | Uso Principal |
| :--- | :---: | :--- |
| **Amarillo Primario** | `#FFCC33` | Resaltados, botones de acción y efectos *hover* |
| **Marrón Café** | `#8B4513` | Barra de navegación, encabezados de tablas y botones principales |
| **Blanco Crema** | `#FAF8F5` | Color de fondo general de la aplicación |
| **Blanco Puro** | `#FFFFFF` | Superficies de tarjetas, modales y formularios |

---

## 🛠️ Tecnologías Utilizadas

La arquitectura del proyecto está dividida en dos capas principales:

### Frontend
* **React:** Biblioteca principal para la construcción de interfaces de usuario interactivas.
* **Vite:** Entorno de desarrollo rápido y empaquetador moderno.
* **React Router v6:** Enrutamiento dinámico y protección de rutas.
* **CSS Moderno:** Estilos modulares basados en variables nativas.
* **Custom Hooks (`useAuth`):** Lógica centralizada para la gestión de la sesión.

### Backend
* **Node.js / Express:** Servidor robusto para el desarrollo de la API REST.
* **JWT:** Mecanismo de autenticación basado en tokens cifrados.
* **Base de Datos:** PostgreSQL / SQLite / MongoDB.

---

## ⚙️ Guía de Instalación y Configuración

Sigue estos pasos para clonar y levantar el proyecto en tu entorno local:

### 1. Clonar el Repositorio
Abre tu terminal y ejecuta el siguiente comando utilizando tu repositorio limpio:
```bash
git clone [https://github.com/JosueIsrael-prog/Gesti-n-de-Usuarios-para-App-de-Comida-Estudiantil.git](https://github.com/JosueIsrael-prog/Gesti-n-de-Usuarios-para-App-de-Comida-Estudiantil.git)
cd Gesti-n-de-Usuarios-para-App-de-Comida-Estudiantil
