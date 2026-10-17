# Integración de Llama Stack con WhatsApp

## Objetivo

Implementar y probar agentes de atención automatizada mediante la integración de modelos de lenguaje con WhatsApp, utilizando Google Colab como entorno de desarrollo.

## Tecnologías utilizadas

- **Llama Stack:** gestión de conversaciones y ejecución de herramientas.
- **Ollama:** ejecución del modelo de lenguaje.
- **WhatsApp Cloud API:** recepción y envío de mensajes.
- **FastAPI:** implementación del webhook.
- **ngrok:** exposición del servidor local mediante una URL pública.
- **Google Colab y Python:** desarrollo y ejecución del ejercicio.

## Ejercicios realizados

**Hands-On:** implementación del ejemplo proporcionado en el curso, correspondiente a un asistente para un taller mecánico.

**Challenge:** adaptación del ejemplo para construir un agente de atención a pedidos de una tienda en línea.

Se realizaron pruebas de consulta de pedidos, preguntas frecuentes, detección de cargos urgentes y escalamiento a atención humana.

## Resultados y observaciones

La integración funcionó y permitió intercambiar mensajes mediante WhatsApp. Se verificaron las llamadas a herramientas, el almacenamiento de conversaciones y las reglas de atención prioritaria.

Se identificaron algunas limitaciones: el modelo no siempre conservó exactamente la información proporcionada por las herramientas y la detección de urgencias dependió de expresiones específicas.

**Nota para el instructor:** el notebook conserva las salidas de ejecución como evidencia de las pruebas realizadas. Para reproducirlas, es necesario configurar las credenciales correspondientes y establecer un nuevo túnel con ngrok.
