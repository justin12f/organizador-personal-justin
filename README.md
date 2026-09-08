# Organizador Personal

Aplicacion en desarrollo para administrar tareas y notas personales. Este
repositorio corresponde a la practica integradora de Git, GitHub y entorno de
trabajo de la materia Desarrollo de Aplicaciones y Servicios Virtuales.

## Objetivo

Preparar la estructura inicial de una aplicacion que, en el futuro, podria
administrar tareas y notas personales, aplicando de forma integrada el flujo de
preparacion, versionamiento y colaboracion de un proyecto.

## Tecnologias utilizadas

- Python 3
- Entorno virtual `venv`
- Git y GitHub
- Visual Studio Code
- Bibliotecas: `requests`, `python-dotenv`

## Pasos de instalacion

1. Clonar el repositorio:
   ```
   git clone URL_DEL_REPOSITORIO
   ```
2. Entrar a la carpeta del proyecto:
   ```
   cd organizador_personal
   ```
3. Crear el entorno virtual:
   ```
   python -m venv .venv
   ```
4. Activar el entorno virtual:
   - Windows (PowerShell): `.venv\Scripts\Activate.ps1`
   - Windows (CMD): `.venv\Scripts\activate.bat`
   - Linux / macOS: `source .venv/bin/activate`
5. Instalar las dependencias:
   ```
   pip install -r requirements.txt
   ```
6. Ejecutar el proyecto:
   ```
   python src/main.py
   ```

## Dependencias

Las dependencias del proyecto estan registradas en `requirements.txt`:

- `requests`
- `python-dotenv`

## Autor

Justin (cuenta de GitHub: justin12f) - Universidad Iberoamericana Leon.

## Estado

Proyecto en etapa inicial. Actualmente contiene unicamente la estructura base,
la documentacion inicial y la configuracion del entorno de trabajo. Las
funcionalidades descritas en `docs/funcionalidades.md` todavia no estan
implementadas.

## Colaboración
Este proyecto acepta contribuciones mediante fork y Pull Request. Antes de 
proponer un cambio, crea una rama específica para tu aportación y describe 
claramente qué modifica tu Pull Request.