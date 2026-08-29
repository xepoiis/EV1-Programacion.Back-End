# Evaluación 1 - Programación Back-End

Este repositorio contiene la primera evaluación de la asignatura de Programación Back-End. Consiste en la configuración inicial de un proyecto utilizando el framework **Django**, estructurando el núcleo del sistema y su primera aplicación funcional orientada a un Sistema de Tickets de Soporte.

## Descripción del Proyecto

El proyecto se compone de:
* **DRF (Django Rest Framework/Core):** El núcleo del proyecto donde se alojan las configuraciones principales, como enrutamiento global (`urls.py`) y variables de entorno (`settings.py`).
* **Sistema de Tickets de Soporte:** La aplicación principal que gestionará la lógica de negocio.
* **Vistas Personalizadas:** Implementación de un `index.html` como página de inicio y una página `404.html` personalizada para el manejo de rutas no encontradas.

## Estructura del Repositorio

```text
EV1-Programacion.Back-End/
├── DRF/                            # Núcleo del proyecto Django
│   ├── settings.py                 # Configuraciones (DEBUG, ALLOWED_HOSTS, etc.)
│   └── urls.py                     # Enrutador principal
├── sistema_tickets_de_soporte/     # Aplicación Django
│   ├── templates/                  
│   │   ├── index.html              # Pantalla principal
│   │   └── 404.html                # Pantalla de error de página no encontrada
│   ├── views.py                    # Controladores de las vistas
│   └── ...
├── .gitignore                      # Archivos y carpetas ignorados por git (ej: entorno virtual)
├── manage.py                       # Gestor del proyecto Django
└── README.md                       # Documentación del proyecto
```

*Desarrollado por Jose Galdamez para la Evaluación 1 de Programación Back-End.*
