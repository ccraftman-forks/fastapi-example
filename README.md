[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ccraftman-forks_fastapi-example&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ccraftman-forks_fastapi-example)
# Comandos
## Instalar dependencias
`pip install --no-cache-dir --upgrade -r requirements.txt`
## Ejecutar el servicio
`uvicorn app.main:app --host 0.0.0.0 --port 8000`
## Ejecutar pruebas unitarias
`python -m unittest discover tests`
## Compilar Docker
`docker build -t devco/fast-api-example:latest .`
