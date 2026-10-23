@@ -1,2 +1,134 @@
# 2026_MA_CAPSTONE_005D_GRUPO_9
Repositorio CAPSTONE. Carrera de Ingeniería en Informática. Duoc UC sede Maipú

# FloweView - Flores Para Toda Ocasión

> Sitio Ecommerce - Gestion de Productos Florares

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Django](https://img.shields.io/badge/Framework-Django-092E20?logo=django)
![Bootstrap](https://img.shields.io/badge/Frontend-Bootstrap_5-7952B3?logo=bootstrap)
![Methodology](https://img.shields.io/badge/Metodología-Scrum-orange)

---

Tabla de Contenidos
- [Equipo de Desarrollo](-equipo-de-Desarrollo)
- [Acerca del Proyecto](-acerca-del-proyecto)
- [Características Principales](-características-principales)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Instalación y Configuración](#-instalación-y-configuración)
- [ Gestión Ágil y Documentación](#-gestión-ágil-y-documentación*)


---
##  Equipo de Desarrollo

* **Felipe Vargas** - *Product Owner / Developer*
* **Alejandro Peña** - *Scrum Master / Developer*
* **Camilo Muñoz** - *Lead Developer* 


---

## Acerca del Proyecto
**FlowerView-FloresParaTodaOcasion** es una solución web integral diseñada para la modernización, digitalización y automatización operativa de una tienda de diseño floral ubicada en la comuna de Padre Hurtado. El sistema aborda la transición desde un modelo de ventas informal y manual hacia un entorno digital centralizado, optimizando tanto la experiencia de compra del cliente como la gestión interna del negocio.

El proyecto contempla una tienda en línea *responsive*, control de inventario en tiempo real, integración de pasarela de pagos, un módulo de Business Intelligence (BI) para la toma de decisiones estratégicas e innovación con IA generativa para la personalización interactiva de arreglos florales. 

---

##  Características Principales

* **Catálogo de Productos:** Visualización de arreglos florales y productos con imágenes y detalles.
* **Autenticación de Usuarios:** Sistema de inicio de sesión, registro y control de acceso mediante decoradores.
* **Panel de Administración (Dashboard):** Interfaz para la gestión interna del negocio.
* **CRUD de Productos Florales:** Capacidad de Crear, Leer, Actualizar y Eliminar productos del catálogo desde el panel de administración.
* **Diseño Responsivo:** Interfaz adaptable a dispositivos móviles y de escritorio gracias a **Bootstrap**.

---

## Tecnologías y Herramientas Utilizadas

* **Backend:** [Python / Django Framework ]
* **Frontend:** [HTML5 / CSS3 / Bootstrap / JavaScript]
* **Base de Datos:** [PostgreSQL / SQLite]
* **Control de Versiones:** [Git / GitHub]
* **Seguridad:** Control de acceso basado en roles
* **Gestión & Metodología:** Scrum (Sprints de 2 semanas), Trello
* **Control de Versiones:** Git / GitHub

---

## Estructura del Proyecto
```text
proyecto-floreria/
│
├── config/              # Configuración principal de Django (settings, urls, wsgi, asgi)
├── env/                 # Entorno virtual de Python
├── media/               # Archivos multimedia subidos por el administrador (imágenes de productos)
│   └── productos/       # Imágenes específicas del catálogo floral
├── tienda/              # Aplicación principal del e-commerce
│   ├── migrations/      # Migraciones de la base de datos
│   ├── static/          # Archivos estáticos (CSS, JS, imágenes de la interfaz)
│   ├── templates/       # Plantillas HTML de la tienda y vistas
│   ├── admin.py        
│   ├── decorators.py    # Decoradores personalizados para control de acceso
│   ├── forms.py         # Formularios para el registro y gestión de productos
│   ├── models.py        # Modelos de datos (Productos, Categorías, etc.)
│   ├── urls.py          # Rutas de la aplicación tienda
│   └── views.py         # Lógica de negocio
│
├── .gitignore           # Archivos ignorados por Git
├── db.sqlite3           # Base de datos SQLite
├── manage.py            # Script principal de gestión de Django
└── requirements.txt     # Dependencias del proyecto
```
---
## Instalación y Configuración

Pasos para clonar y ejecutar el proyecto localmente en el equipo:

### 1. Requisitos Previos
* **Python 3.10+**
* **Git**

### 2. Clonar el Repositorio
```bash
git clone https://github.com/PhilipV4/proyecto-floreria.git
cd proyecto-floreria
```

### Crear Entorno Virtual
```bash
python -m venv env
```

### En Windows:
```bash
env\Scripts\activate
```

### En macOS/Linux:
```bash
source env/bin/activate
```
### Instalar Dependencias
```bash
pip install -r requirements.txt
```
### Crear Superusuario
```bash
python manage.py createsuperuser
```
### Ejecutar Servidor
```bash
python manage.py runserver
```
---
## Gestión Ágil y Documentación (Scrum)
- **Product Backlog:** [Invitacion Tablero Trello](https://trello.com/invite/b/6aa32e5847e88887712426e3/ATTI56f430172ccb1f5896775c64b4f0bf47CDE482EA/flowerview)
- **Sprint Reviews:**
  - [Sprint Review 1 ](https://docs.google.com/document/d/1hahMLXQRjfLF3lhJJK9i0bAD5a0X6MxR/edit?usp=sharing&ouid=115062794258160277342&rtpof=true&sd=true)

  - [Sprint Review 2 ](https://tu-enlace-sprint-2)

  - [Sprint Review 3 ](https://tu-enlace-sprint-3)
