<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/3202/3202926.png" />

# 🚗 Laravel Car Rental System

### Plataforma moderna de renta y gestión de vehículos 🚀

<p align="center">
  <b>Laravel Car Rental System</b> es un sistema web desarrollado con Laravel para administrar reservaciones, clientes, pagos y flota vehicular desde una plataforma segura, escalable y moderna.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-12-FF2D20?style=for-the-badge&logo=laravel&logoColor=white">
  <img src="https://img.shields.io/badge/PHP-Backend-777BB4?style=for-the-badge&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Bootstrap-Frontend-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-FullStack-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Laravel Car Rental System** es una plataforma web full stack diseñada para automatizar procesos de renta de vehículos mediante una arquitectura moderna basada en Laravel.

El sistema permite administrar:

- 🚘 Vehículos y flota
- 📅 Reservaciones online
- 👥 Clientes y usuarios
- 💳 Pagos y facturación
- 📊 Dashboard administrativo
- 🔐 Seguridad y autenticación
- 📂 Gestión de contenido
- 📈 Reportes y estadísticas

El proyecto está enfocado en ofrecer una solución moderna, escalable y profesional para empresas de alquiler automotriz.

---

# ✨ Características

## 🚘 Gestión de vehículos

- 🚗 Registro de automóviles
- 🏷️ Gestión de marcas y categorías
- 📸 Galería de imágenes
- 📋 Especificaciones detalladas
- ⛽ Tipo de combustible
- 📊 Control de disponibilidad
- 🔧 Historial de mantenimiento

---

## 📅 Sistema de reservaciones

- 📆 Reservaciones online
- 🔍 Consulta de disponibilidad
- 📍 Selección de fechas
- ⚡ Confirmación automática
- 📋 Historial de reservas
- 🧾 Gestión de contratos

---

## 👥 Gestión de usuarios

- 🔐 Registro e inicio de sesión
- 👤 Perfil de usuario
- 🔑 Recuperación de contraseña
- 📄 Historial de rentas
- 👨‍💼 Roles y permisos
- 🛡️ Seguridad avanzada

---

## 💳 Gestión financiera

- 💵 Registro de pagos
- 🧾 Facturación electrónica
- 📊 Reportes financieros
- 💳 Integración con pasarelas de pago
- 📈 Análisis de ingresos

---

## 🛠️ Panel administrativo

- 📊 Dashboard moderno
- 🚘 Administración de flota
- 👥 Gestión de clientes
- 📅 Control de reservaciones
- 📈 Estadísticas en tiempo real
- ⚙️ Configuración del sistema

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,bootstrap,js,vue" />
</p>

- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- Vue.js
- Blade Templates

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=php,laravel" />
</p>

- Laravel 12
- PHP 8+
- Laravel Breeze
- Middleware
- Eloquent ORM
- API REST

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- Migraciones Laravel
- Relaciones Eloquent
- Seeders y Factories

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman" />
</p>

- Git
- GitHub
- Visual Studio Code
- Composer
- Postman
- Laravel Artisan

---

# 📂 Estructura del proyecto

```bash
PlataformaRentaVehiculoLaravel/
│
├── app/
│   ├── Http/
│   ├── Models/
│   ├── Services/
│   └── Providers/
│
├── bootstrap/
├── config/
├── database/
│   ├── migrations/
│   ├── seeders/
│   └── factories/
│
├── public/
├── resources/
│   ├── views/
│   ├── js/
│   └── css/
│
├── routes/
│   ├── web.php
│   └── api.php
│
├── storage/
├── tests/
│
├── artisan
├── composer.json
└── README.md
```

---

# ⚡ Instalación

## 📋 Requisitos

- PHP 8+
- Composer
- MySQL
- Node.js
- Laravel CLI
- XAMPP / Laragon

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/PlataformaRentaVehiculoLaravel.git
```

---

## 2️⃣ Entrar al proyecto

```bash
cd PlataformaRentaVehiculoLaravel
```

---

## 3️⃣ Instalar dependencias

```bash
composer install
```

---

## 4️⃣ Instalar dependencias frontend

```bash
npm install
```

---

## 5️⃣ Configurar variables de entorno

Duplicar archivo:

```bash
.env.example
```

Renombrar a:

```bash
.env
```

---

## 6️⃣ Generar clave Laravel

```bash
php artisan key:generate
```

---

## 7️⃣ Configurar base de datos

Editar:

```env
DB_DATABASE=car_rental
DB_USERNAME=root
DB_PASSWORD=
```

---

## 8️⃣ Ejecutar migraciones

```bash
php artisan migrate --seed
```

---

## 9️⃣ Compilar assets

```bash
npm run dev
```

---

## 🔟 Ejecutar servidor

```bash
php artisan serve
```

Abrir:

```bash
http://127.0.0.1:8000
```

---

# 📊 Funcionalidades principales

## 🚗 Administración de flota

- Registro de vehículos
- Control de disponibilidad
- Gestión de mantenimiento
- Administración de categorías

---

## 📅 Gestión de reservas

- Reservaciones online
- Historial de alquileres
- Confirmaciones automáticas
- Gestión de contratos

---

## 👥 Gestión de usuarios

- Clientes y administradores
- Roles y permisos
- Seguridad avanzada
- Gestión de perfiles

---

## 📈 Dashboard administrativo

- Estadísticas generales
- Reportes dinámicos
- Ingresos mensuales
- Supervisión del sistema

---

# 📸 Vista previa

<div align="center">

### 🏠 Dashboard principal
<img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70?q=80&w=1200" width="900"/>

### 🚘 Catálogo de vehículos
<img src="https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?q=80&w=1200" width="900"/>

### 📅 Sistema de reservaciones
<img src="https://images.unsplash.com/photo-1485291571150-772bcfc10da5?q=80&w=1200" width="900"/>

### 📊 Panel administrativo
<img src="https://images.unsplash.com/photo-1556740749-887f6717d7e4?q=80&w=1200" width="900"/>

</div>

---

# 🔐 Roles del sistema

## 👨‍💼 Administrador

- Gestión completa del sistema
- Administración de vehículos
- Gestión de usuarios
- Estadísticas y reportes

---

## 👤 Cliente

- Reservar vehículos
- Gestionar perfil
- Historial de rentas
- Realizar pagos

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y desarrollo

- Laravel Full Stack
- Arquitectura MVC
- APIs REST
- Seguridad web
- Gestión de bases de datos
- Desarrollo empresarial

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- ☁️ Infraestructura cloud
- 🤖 IA para recomendaciones
- 🔔 Notificaciones en tiempo real
- 🌐 Multi idioma
- 💳 Stripe y PayPal
- 📍 Geolocalización de vehículos

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Full Stack Developer

Desarrollador apasionado por plataformas empresariales, Laravel y sistemas web modernos 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source bajo licencia MIT para fines educativos y empresariales.

---

<div align="center">

### 🚗 Laravel Car Rental System — administración moderna de renta vehicular 🚀

</div>
