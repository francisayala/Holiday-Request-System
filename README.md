# Holiday Request System (Sistema de Solicitud de Vacaciones)

## Descripción del Proyecto

Este proyecto es una aplicación web (Business Service) desarrollada como parte del módulo "Principles of Modern Software Development and Engineering Thinking" de la Maestría en Inteligencia Artificial Aplicada.

El sistema tiene como objetivo digitalizar y agilizar el proceso de solicitud de vacaciones dentro de una empresa (RRHH). Permite a los empleados crear solicitudes con sus fechas y motivos, y a los gerentes visualizar, filtrar y gestionar el estado de dichas solicitudes.

## Tecnologías Utilizadas

- **React** (Biblioteca de interfaz de usuario)
- **Vite** (Herramienta de construcción y servidor de desarrollo)
- **CSS** (Estilos personalizados)
- **Git / GitHub** (Control de versiones)

## Estructura del Proyecto

```text
src/
├── assets/       # Recursos estáticos (imágenes, logos)
├── components/   # Componentes reutilizables (Formularios, Tarjetas, Listas)
│   └── ui/       # Componentes básicos de interfaz (Botones, Inputs)
├── layouts/      # Estructuras de diseño (Header, Footer, MainLayout)
├── pages/        # Vistas principales (Dashboard, Nueva Solicitud, Lista)
└── utils/        # Funciones de validación y ayuda
```

## Cómo ejecutar el proyecto en local

1. Clona este repositorio:
   ```bash
   git clone https://github.com/francisayala/Holiday-Request-System.git
   ```
2. Entra a la carpeta del proyecto:
   ```bash
   cd Holiday-Request-System
   ```
3. Instala las dependencias:
   ```bash
   npm install
   ```
4. Inicia el servidor de desarrollo:
   ```bash
   npm run dev
   ```

## Estado del Proyecto (MVP Scope)

- [x] Definición del MVTS v1 (Requisitos y alcance).
- [x] Configuración inicial del repositorio y estructura de carpetas.
- [ ] Desarrollo de la interfaz de usuario (Formulario y Lista).
- [ ] Implementación de la lógica de validación de fechas.
- [ ] Cambio de estado de solicitudes (Pendiente, Aprobado, Rechazado).

## Autor

- **Francis Ayala** - _Desarrollo inicial_ - [francisayala](https://github.com/francisayala)
