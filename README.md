# Reportes Asociadas

App Streamlit para procesar reportes de asociadas Betterware, generar Excel/PDF y crear Google Sheets.

## Archivos importantes

Subir a GitHub:
- app.py
- requirements.txt
- README.md
- .streamlit/config.toml
- logo.png si lo tienes

No subir a GitHub:
- .env
- token.json
- credentials.json
- .streamlit/secrets.toml

## Secrets requeridos en Streamlit Cloud

CLAVE_APP="tu_contraseña"
ANTHROPIC_API_KEY="tu_api_key"
GEMINI_API_KEY="tu_api_key"
GOOGLE_CREDENTIALS_JSON="""
{...}
"""
GOOGLE_TOKEN_JSON="""
{...}
"""
