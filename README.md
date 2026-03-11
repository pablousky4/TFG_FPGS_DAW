# TFG_FPGS_DAW
# 🏢 AnyRent - Plataforma de Alquiler y Reservas

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

**AnyRent** es el frontend de una plataforma web diseñada para conectar a clientes con empresas locales. Permite a los usuarios buscar, alquilar productos o reservar servicios (como peluquerías, restaurantes y alquiler de vehículos), mientras que ofrece a los negocios un panel modular para gestionar su escaparate digital.

---

## ✨ Características Principales

### Para Usuarios (Clientes)
* **Búsqueda Integrada:** Buscador principal para encontrar negocios por nombre, categoría o zona.
* **Exploración por Categorías:** Filtros rápidos para Peluquería, Restaurante, Maquinaria, Vehículos, Profesionales y Hostelería.
* **Reserva Dinámica:** Formularios de reserva que se autocompletan si el usuario ha iniciado sesión previamente.
* **Pasarela de Pago:** Simulación de una pasarela de pago para confirmar reservas mediante tarjeta.

### Para Empresas (Negocios)
* **Distintivo PRO:** Opción para que las empresas destaquen en los resultados de búsqueda como perfiles "PRO".
* **Constructor de Escaparate (Modular Panel):** Un panel interactivo que permite a los negocios (ej. Restaurante Casa Pepe) personalizar su formulario de reservas, añadiendo bloques como "Nº Comensales", "Fecha y Hora" o "Seguro de no presentación".

---

## 🛠️ Tecnologías Utilizadas

* **Estructura y Estilos:** HTML5 y CSS3.
* **Framework Frontend:** Bootstrap (v4.5 y v5.x) para un diseño completamente responsivo adaptado a móviles, tablets y escritorio.
* **Interactividad:** JavaScript (Vanilla) y jQuery para la manipulación del DOM, validación de credenciales estáticas y actualización de la UI en tiempo real.
* **Iconografía:** Bootstrap Icons, FontAwesome y Feather Icons.

---

## 🚀 Instalación y Despliegue Local

Al tratarse de un proyecto estático (Frontend), no se requiere la instalación de un servidor backend ni dependencias mediante npm.

1. **Clona el repositorio:**
   ```bash
   git clone [https://github.com/TU_USUARIO/AnyRent.git](https://github.com/TU_USUARIO/AnyRent.git)

2. **Abre el proyecto:**
Navega a la carpeta descargada y abre el archivo index.html en tu navegador web favorito.

---

## 🔐 Credenciales de Prueba 
Para probar los flujos restringidos y la lógica de inicio de sesión implementada en JavaScript:

Cliente: User(pablo) Password(pablo)

Empresa: User(admin) Password(admin)

---

## 📂 Estructura de Vistas principales
/index.html: Landing page principal.

/login.html & /register.html: Autenticación de clientes.

/login-empresa.html & /register-empresa.html: Autenticación de negocios.

/escaparate.html & /escaparate-logueado.html: Vistas públicas del negocio.

/MenuEscaparate.html: Panel de configuración interno del negocio.

/pago.html & /correcto.html: Flujo de checkout y pantalla de éxito.

---

## 🤝 Contribución
¡Las contribuciones son bienvenidas! Si deseas mejorar el diseño, añadir nuevas funcionalidades o conectar este frontend con una API backend:

Haz un Fork del proyecto.

Crea una nueva rama (git checkout -b feature/NuevaFuncionalidad).

Haz commit de tus cambios (git commit -m 'Añade nueva funcionalidad').

Haz push a la rama (git push origin feature/NuevaFuncionalidad).

Abre un Pull Request.