#Chatbot Practico

## Objetivo del proyecto
Este proyecto implementa un chatbot en Python con una arquitectura modular.
Su proposito es mostrar como organizar un asistente conversacionarl que:
-Use un cliente de modelo de lenguaje para procesar las entradas.
-Mantenga memoria de la conversacion.
-Defina diferentes roles y prompts para personalizar la interaccion.

##Instalacion de dependencias
1-Clonar el repositorio:
    git clone <url-del-repositorio>
    cd <carpeta-donde-se-clono>

2-Crear y activar un entorno virtual:

    python -m venv venv

    source venv/bin/activa #Linux
    venv\Scripts\activate #Windows

3-Instalar las dependencias:

    pip install -r requirements.txt

4-Configurar un archivo .env con variables necesarias como la clave API y el modelo de la ia(gemini-1.5-flash)

5-Ejecucion

    python main.py