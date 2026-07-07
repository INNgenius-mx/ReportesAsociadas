# Reporte de Asociadas Betterware

App privada en Streamlit para procesar PDFs CTBT Betterware, generar Excel/PDF y crear Google Sheets.

## Archivos que sí van a GitHub
- app.py
- requirements.txt
- README.md
- .gitignore
- logo.png, si tienes uno

## Archivos que NO van a GitHub
- .env
- token.json
- credentials.json
- .streamlit/secrets.toml

## Secrets necesarios en Streamlit Cloud
Configura estos valores en App > Settings > Secrets:

```toml
CLAVE_APP="tu_contraseña_privada"
ANTHROPIC_API_KEY="tu_clave_de_claude"
GEMINI_API_KEY="tu_clave_de_gemini"

GOOGLE_CREDENTIALS_JSON = """
contenido completo de credentials.json
"""

GOOGLE_TOKEN_JSON = """
contenido completo de token.json
"""
```
