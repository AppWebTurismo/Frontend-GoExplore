# GoExplore - Frontend

Este repositorio contiene la parte frontend de GoExplore, una aplicación web desarrollada como proyecto para la materia de Fundamentos de Ingeniería de Software en la Universidad Instituto Tecnologico de Minatitlan. Ver

## Acerca del Proyecto

GoExplore es una plataforma web diseñada para facilitar la gestión y administración de usuarios, proporcionando una interfaz intuitiva y moderna que permite:
- Registro e inicio de sesión de usuarios
- Panel de administración para gestión de usuarios
- Interfaz personalizada para diferentes roles de usuario
- Sistema de autenticación seguro

## Desarrollado por:
- Aguilar tomas Randal Steven 
- González Domínguez Angel Dario 
- Hernández Storey Roberto de Jesús 
- Jiménez Valdés ya zirí
- Rivera Couoh Yael Eduardo

## Supervisado por:
- Molina Gomez Kevin David

Materia: Fundamentos de Ingeniería de Software
Semestre: 6to semestre
Instituto Tecnologico de Minatitlan. Ver

## Estructura del Proyecto

```
frontend/
├── templates/
│   ├── index.html          # Página principal
│   └── iniciosesion/
│       ├── admin.html      # Panel de administrador
│       ├── login.html      # Página de inicio de sesión
│       └── usuario.html    # Panel de usuario
└── static/
    ├── css/               # Estilos
    ├── js/                # Scripts de JavaScript
```
## Tecnologías Utilizadas

- HTML5
- CSS3
- JavaScript
- Jinja2 (Motor de plantillas)
- Bootstrap (si lo usas)

## Características

- Diseño responsivo
- Interfaz moderna y amigable
- Sistema de autenticación
- Paneles específicos para usuarios y administradores

## Requisitos

- Navegador web moderno
- Conexión a internet

## Integración con Backend

Este frontend está diseñado para trabajar con el [backend de GoExplore](link-al-repo-backend).
Las plantillas están configuradas para funcionar con Flask y utilizan Jinja2 para el renderizado dinámico.

## Instalación y Uso

1. Clona este repositorio
2. Asegúrate de tener el backend configurado
3. Sigue las instrucciones de instalación del backend
4. Las plantillas se cargarán automáticamente cuando el servidor Flask esté corriendo 