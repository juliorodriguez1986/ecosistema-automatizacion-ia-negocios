# Ecosistema de Automatización IA Autónomo para Negocios

## Descripción

Proyecto final desarrollado con n8n para automatizar la recepción, análisis y almacenamiento de correos electrónicos mediante Inteligencia Artificial.

## Tecnologías utilizadas

- n8n (Orquestador)
- Gmail (Canal de entrada)
- OpenAI GPT-4o Mini (Procesamiento IA)
- Airtable (Base de datos y memoria)

## Flujo implementado

TRG_REVISION_CORREO
↓
GMAIL_OBTENER_CORREOS
↓
SET_DATOS_EMAIL
↓
FORMATEAR_FECHA
↓
OPENAI_ANALIZAR_CORREO
↓
AIRTABLE_GUARDAR_INTERACCION

## Funcionalidad

1. Obtiene correos desde Gmail.
2. Extrae y normaliza la información.
3. Analiza el contenido mediante OpenAI.
4. Clasifica el correo por categoría y prioridad.
5. Genera una respuesta sugerida.
6. Guarda la información en Airtable.

## Archivos incluidos

### Workflow

workflow/WF_ATENCION_CLIENTE_IA.json

### Evidencias

Capturas y documentación en la carpeta evidencias.

### Documentación

Documentación final en la carpeta docs.
