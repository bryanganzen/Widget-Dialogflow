# Widget-Dialogflow
Este desarrollo genera un script del widget de Dialogflow para enbeber en página web

# Widget de Dialogflow

## Descripción

Este proyecto implementa un widget de Dialogflow en una página web, permitiendo la interacción con un agente virtual de Dialogflow directamente desde la interfaz. El widget se puede personalizar visualmente y configurar para responder a diferentes intenciones del agente.

### Características principales

- **Integración con Dialogflow**: Permite la interacción con un agente de Dialogflow utilizando el widget integrado en la página web.
- **Personalización del Widget**: Incluye opciones de personalización para los colores del widget, mensajes de usuario y del bot, y la apariencia general del chat.
- **Interfaz Intuitiva**: Proporciona una interfaz sencilla y fácil de usar para los usuarios finales, que pueden comunicarse con el agente virtual sin necesidad de conocimientos técnicos.

## Requisitos

- Un agente configurado en [Dialogflow](https://dialogflow.cloud.google.com/).
- Los siguientes datos del agente de Dialogflow:
  - `agent-id`: ID del agente de Dialogflow.
  - `intent`: Intención predeterminada para iniciar la conversación (por ejemplo, `WELCOME`).
  - `chat-title`: Título del chat que se mostrará en el widget.

## Personalización
Puedes personalizar la apariencia del widget ajustando las siguientes propiedades de estilo dentro del archivo `Dialogflow.html`:

```css
df-messenger { 
  --df-messenger-bot-message: #0d6fb8; /* Color de los mensajes del bot */
  --df-messenger-button-titlebar-color: #0d6fb8; /* Color de la barra de título */
  --df-messenger-chat-background-color: #fff; /* Color de fondo del chat */
  --df-messenger-font-color: #fff; /* Color de la fuente */
  --df-messenger-user-message: #f68b1f; /* Color de los mensajes del usuario */
  --df-messenger-button-titlebar-font-color: #fff; /* Color de la fuente de la barra de título */
  --df-messenger-input-box-color: #e7e7f1; /* Color de la caja de entrada */
  --df-messenger-input-font-color: #383838; /* Color de la fuente de entrada */
  --df-messenger-input-placeholder-font-color: #383838; /* Color del texto de marcador en la caja de entrada */
  --df-messenger-minimized-chat-close-icon-color: #ffffff; /* Color del icono de cierre en el modo minimizado */
  --df-messenger-send-icon: #0d6fb8; /* Color del icono de envío */
}
```

## Estructura del Proyecto
`Dialogflow.html`: Archivo HTML principal que contiene el código para incrustar el widget de Dialogflow en una página web.

## Contacto
Si tienes alguna pregunta o sugerencia, no dudes en ponerte en contacto.

- Bryan Ganzen
- 55 75 45 65 81
