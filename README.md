# Proyecto Final DevOps
 
## Descripción
 
Aplicación web desarrollada con FastAPI para el Trabajo Final DevOps.
El proyecto construye una imagen Docker, publica la imagen en Docker Hub y permite ejecutar un contenedor configurado mediante variables de entorno.
 
## Grupo
 
**Grupo:** Grupo 1
 
**Integrantes:**
 
- César Jácome
- Marcela Baldeón
 
## Estructura del proyecto
 
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
```
 
## Endpoints disponibles
 
| Endpoint | Descripción |
|---|---|
| `/` | Página principal de la aplicación. |
| `/health` | Verificación del estado del servicio. |
| `/info` | Información de la aplicación, grupo y contenedor. |
| `/metrics` | Métricas básicas de ejecución. |
 
## Ejecución con Docker
 
```bash
docker run -d   --name devops-final-project-grupo1   -p 8001:8000   -e GROUP_NAME="Grupo 1"   -e GROUP_MEMBERS="César Jácome, Marcela Baldeón"   -e COURSE_NAME="Curso de Profesionalización en DevOps"   cefer181/devops-final-project:v1
```
 
Abrir en el navegador:
 
```text
http://localhost:8001
```
 
## Imagen Docker
 
```text
cefer181/devops-final-project:v1
MarchelitaBG/devops-final-project:v1
```
