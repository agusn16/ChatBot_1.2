# ChatBot Gemini

# Objetivo
Chatbot de consola que responde en español y puede asumir distintos roles (Profesor, Traductor, Programador, Asistente).

# Instalación

1. Crear un entorno virtual:
   Windows: `python -m venv venv`
   Linux/Mac: `python3 -m venv venv`

2. Activar el entorno:
   Windows: `venv\Scripts\activate`
   Linux/Mac: `source venv/bin/activate`

3. Instalar dependencias: pip install -r requirements.txt

4. Crear un archivo `.env` con:
  GEMINI_API_KEY=<tu_api_key>
  MODEL=gemini-1.5-flash

# Ejecución

5. python main.py

# Archivos principales
 `main.py`: Bucle principal e interacción con el usuario.
 `chat_service.py`: Lógica del chatbot y manejo de memoria.
 `config.py`: Configuraciones del sistema.
 `roles.py`: Roles disponibles y prompts de sistema.
 `llm_client.py`: Cliente para la API de Gemini.
 `memory.py`: Gestión del historial de la conversación.
 `prompts.py`: Construcción de prompts y manejo del historial.
 `requirements.txt`: Lista de librerías necesarias para ejecutar el chatbot.