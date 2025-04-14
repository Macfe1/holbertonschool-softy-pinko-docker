# 🐳 Proyecto Dockerizado: Softy Pinko

Este proyecto tiene como objetivo construir una infraestructura de múltiples contenedores utilizando Docker y Docker Compose. La arquitectura incluye:

- Un proxy inverso con balanceo de carga utilizando NGINX.
- Un servidor web que sirve contenido estático.
- Múltiples servidores de aplicación (API) para manejar solicitudes dinámicas.
- Un sistema para cargar y servir archivos a través de los contenedores.

## 📁 Estructura del Proyecto
El repositorio está organizado en las siguientes tareas:

- task0: Configuración inicial y creación de la imagen base.
- task1: Implementación del servidor de aplicación básico.
- task2: Configuración del servidor web para contenido estático.
- task3: Implementación del proxy inverso con NGINX.
- task4: Configuración del balanceo de carga entre servidores API.
- task5: Integración del sistema de carga de archivos.
- task6: Despliegue completo utilizando Docker Compose.

## 🚀 Despliegue

*Clona el repositorio:*

```bash
git clone https://github.com/Macfe1/holbertonschool-softy-pinko-docker.git
cd holbertonschool-softy-pinko-docker
```

### Navega a la tarea final:

```bash
cd task6
```

### Construye y levanta los contenedores:

```bash
docker-compose up --build
```

### Accede a la aplicación en tu navegador en http://localhost.

## ⚙️ Tecnologías Utilizadas

- Docker
- Docker Compose
- NGINX
- Python (Flask)
- HTML/CSS/JavaScript

