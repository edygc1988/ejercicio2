# Microservicio "Hola Mundo" (FastAPI)

Microservicio mínimo en Python que responde `hola mundo` en un GET `/`.

Instrucciones rápidas:

- Crear un entorno virtual (opcional):

```bash
python3 -m venv .venv
source .venv/bin/activate
```

- Instalar dependencias:

```bash
pip install -r requirements.txt
```

- Ejecutar localmente con `uvicorn`:

```bash
uvicorn main:app --host 0.0.0.0 --port 8000
```

Abre `http://127.0.0.1:8000/` y verás la respuesta JSON con `{"message":"hola mundo"}`.

- Ejecutar con Docker (desde la raíz del proyecto):

```bash
docker build -t hola-mundo-fastapi .
docker run -p 8000:8000 hola-mundo-fastapi
```
# ejercicio2
