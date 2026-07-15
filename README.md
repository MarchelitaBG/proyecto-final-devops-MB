<div align="center">

 #  PROYECTO FINAL DEVOPS

![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?logo=docker&logoColor=white)
![DevOps](https://img.shields.io/badge/DevOps-Automatización-blueviolet)
![Status](https://img.shields.io/badge/Estado-Finalizado-success)


## Automatización del Ciclo de Vida de una Aplicación mediante DevOps

### Curso de Profesionalización en DevOps

</div>

---

### Grupo 1

**Integrantes:**

**- Marcela Baldeón**  
**- César Jácome**

---

### 📖 Trabajo Final Académico

Aplicación web desarrollada bajo un enfoque DevOps, integrando control de versiones, gestión de ramas, automatización de procesos, contenerización y despliegue continuo.

---

# 🎯 Objetivo del Proyecto

Implementar una solución completa basada en prácticas DevOps que permita gestionar el ciclo de vida de una aplicación desde el desarrollo hasta su despliegue automatizado.

---

# 🚀 Alcance del Proyecto

- Gestión del código fuente mediante Git.
- Aplicación de GitFlow.
- Control de versiones.
- Desarrollo de aplicación FastAPI.
- Contenerización con Docker.
- Publicación en Docker Hub.
- Automatización con GitHub Actions.
- Integración Continua (CI).
- Entrega Continua (CD).

---

# ⚙️ Tecnologías Implementadas

| Categoría | Tecnología |
|------------|------------|
| Control de versiones | Git |
| Estrategia de ramas | GitFlow |
| Repositorio remoto | GitHub |
| Automatización | GitHub Actions |
| Backend | FastAPI |
| Contenedores | Docker |
| Registro de imágenes | Docker Hub |
| Lenguaje | Python |
| Servidor ASGI | Uvicorn |

---

# 📚 Flujo DevOps Aplicado

Planeación, Desarrollo, Integración, Automatización, Contenerización, Publicación y Validación.

---

# 💾 Entregables Generados

- Repositorio GitHub.
- Workflow GitHub Actions.
- Imagen Docker.
- Repositorio Docker Hub.
- Informe técnico.
- Documentación del proyecto.

---

# 💻 Competencias Aplicadas

- DevOps.
- CI/CD.
- Docker.
- GitFlow.
- Automatización.
- Despliegue de aplicaciones.

---

# 🖥️ Resultados Alcanzados

Implementación exitosa de un flujo DevOps completo para la construcción, publicación y despliegue automatizado de una aplicación web.

---

## 📂 Estructura del proyecto
 
```text
proyecto-final-devops/
├── app/
│   ├── main.py
│   └── templates/
│       └── index.html
├── docs/
│   ├── capturas/
│   └── evidencias/
├── .dockerignore
├── .gitignore
├── Dockerfile
├── INFORME.md
├── README.md
└── requirements.txt

---

## 📌 Endpoints disponibles
 
| Endpoint | Descripción |
|---|---|
| `/` | Página principal de la aplicación. |
| `/health` | Verificación del estado del servicio. |
| `/info` | Información de la aplicación, grupo y contenedor. |
| `/metrics` | Métricas básicas de ejecución. |
 
---

## 📦 Ejecución con Docker
 
```bash
docker run -d   --name devops-final-project-grupo1   -p 8001:8000   -e GROUP_NAME="Grupo 1"   -e GROUP_MEMBERS="César Jácome, Marcela Baldeón"   -e COURSE_NAME="Curso de Profesionalización en DevOps"   cefer181/devops-final-project:v1
```
 
Abrir en el navegador:
 
```text
http://localhost:8001
```
 
## 🐳 Imagen Docker
 
```text
cefer181/devops-final-project:v1
marchelita/devops-final-project:v1
```
<div align="center">
 
### 🐳 Docker • 📦 Contenedores • 🚀 DevOps

</div>
