# chamilor

Este proyecto permite levantar una instancia de Chamilo LMS usando Docker y Docker Compose, con volúmenes persistentes para la web y la base de datos.

## Requisitos

- Docker y Docker Compose instalados
- Crear las carpetas de volúmenes en `C:/docker/chamilo_web` y `C:/docker/chamilo_bd`
- Clonar este repositorio en `C:/proyectos/chamilo-docker`

## Estructura esperada

C:/proyectos/chamilo-docker/ 
├── chamilo_web/ 
├── chamilo_bd/
├── docker-compose.yml 
├── .env
└── README.md 