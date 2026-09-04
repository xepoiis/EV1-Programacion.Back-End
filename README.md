# Programación Back-End: Sistema de Tickets de Soporte

El proyecto consiste en la configuración inicial de un sistema backend utilizando Django 6.1, estructurando el núcleo del sistema y una aplicación inicial.

## Descripción del Proyecto

El proyecto se compone de:
* **DRF:** El núcleo del proyecto donde se alojan las configuraciones principales, como enrutamiento global y variables de entorno.
* **Sistema de Tickets de Soporte:** La aplicación principal que gestionará la lógica de negocio.
* **Vistas Personalizadas:** Implementación de un `index.html` como página de inicio y una página `404.html` personalizada para el manejo de rutas no encontradas.

---

## Instrucciones de Instalación y Ejecución

Pasos para preparar y ejecutar el proyecto en entorno local:

### 1. Clonar el repositorio

Abra su terminal y ejecute el siguiente comando para descargar el proyecto:
```bash
git clone https://github.com/xepoiis/Proyecto-BackEnd.git
cd EV1-Programacion.Back-End
```

### 2. Crear y activar el ambiente virtual
Es estrictamente necesario crear un ambiente virtual para aislar las dependencias del proyecto.

**En Windows:**
```bash
python -m venv .venv
.venv\Scripts\activate
```

**En macOS o Linux:**
```bash
python3 -m venv .venv
source .venv/bin/activate
```
*(Debe asegurarse de que el nombre del ambiente virtual aparezca en su terminal, indicando que está activo).*

### 3. Instalar dependencias
Con el ambiente virtual activado, instale los paquetes necesarios especificados en el archivo `requirements.txt`:
```bash
pip install -r requirements.txt
```

### 4. Ejecutar el proyecto
Finalmente, levante el servidor de desarrollo local utilizando el archivo `manage.py`:
```bash
python manage.py runserver
```

Una vez que el servidor esté en ejecución, abra su navegador web e ingrese a `http://127.0.0.1:8000/` para visualizar la página de bienvenida. 

**Prueba de la página 404:**
Para verificar el funcionamiento de la página de error personalizada, ingrese deliberadamente a una ruta inexistente, por ejemplo: `http://127.0.0.1:8000/ruta-inexistente`.

---
*Desarrollado por Jose Galdamez para la Evaluación 1 de Programación Back-End.*
