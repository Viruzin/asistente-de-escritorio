# 📚 Librerías de Python para el Proyecto

Esta es una recopilación de librerías útiles organizadas por funcionalidad para el desarrollo del asistente de escritorio con IA.

## 🎨 Interfaces y Chat

### GUI Nativa
- **tkinter** - Librería GUI incluida en Python
  - Instalación: Viene con Python
  - Uso: Interfaces simples y rápidas
  
- **customtkinter** - Versión moderna de tkinter con diseño actualizado
  - Instalación: `pip install customtkinter`
  - Uso: Interfaces modernas sin complejidad

### GUI Avanzadas
- **PyQt5** - Framework completo para aplicaciones profesionales
  - Instalación: `pip install PyQt5`
  - Uso: Aplicaciones de escritorio profesionales
  
- **PySide6** - Alternativa oficial de Qt
  - Instalación: `pip install PySide6`
  - Uso: Similar a PyQt5, licencia más permisiva

### CLI (Terminal)
- **rich** - Salida de terminal con colores y formato
  - Instalación: `pip install rich`
  - Uso: Interfaces de consola atractivas

---

## 🤖 IA y LLMs

### APIs de IA
- **openai** - API oficial de OpenAI (GPT-4, ChatGPT)
  - Instalación: `pip install openai`
  - Uso: Integración con modelos de OpenAI
  
- **anthropic** - API de Claude (Anthropic)
  - Instalación: `pip install anthropic`
  - Uso: Integración con Claude

### Frameworks de IA
- **langchain** - Framework para aplicaciones con LLMs
  - Instalación: `pip install langchain`
  - Uso: Cadenas de prompts, agentes, memoria
  
- **ollama-python** - Cliente para modelos locales con Ollama
  - Instalación: `pip install ollama`
  - Uso: Ejecutar LLMs localmente (sin internet)

---

## 📁 Manejo de Archivos y Sistema

### Incluidas en Python
- **pathlib** - Manejo moderno de rutas y archivos
  - Instalación: Incluida
  - Uso: `from pathlib import Path`
  
- **os** - Operaciones del sistema operativo
  - Instalación: Incluida
  - Uso: `import os`
  
- **shutil** - Operaciones de alto nivel con archivos
  - Instalación: Incluida
  - Uso: Copiar, mover, eliminar archivos

### Externas
- **watchdog** - Monitorear cambios en el sistema de archivos
  - Instalación: `pip install watchdog`
  - Uso: Detectar cuando se crean/modifican archivos

---

## 🔒 Seguridad

- **python-dotenv** - Cargar variables de entorno desde archivos .env
  - Instalación: `pip install python-dotenv`
  - Uso: Proteger API keys y configuraciones
  
- **cryptography** - Encriptación y criptografía
  - Instalación: `pip install cryptography`
  - Uso: Encriptar datos sensibles
  
- **pydantic** - Validación de datos con tipos
  - Instalación: `pip install pydantic`
  - Uso: Validar entrada de usuarios

---

## 💾 Memoria y Persistencia

### Bases de Datos
- **sqlite3** - Base de datos SQL ligera
  - Instalación: Incluida
  - Uso: Almacenar datos estructurados
  
- **chromadb** - Base de datos vectorial para embeddings
  - Instalación: `pip install chromadb`
  - Uso: Memoria semántica del asistente

### Serialización
- **json** - Trabajar con archivos JSON
  - Instalación: Incluida
  - Uso: Guardar configuraciones
  
- **pickle** - Serialización de objetos Python
  - Instalación: Incluida
  - Uso: Guardar objetos complejos

---

## 🎤 Voz (Futuro - Fase 2)

- **speechrecognition** - Reconocimiento de voz
  - Instalación: `pip install SpeechRecognition`
  - Uso: Convertir voz a texto
  
- **pyttsx3** - Text-to-Speech offline
  - Instalación: `pip install pyttsx3`
  - Uso: Que el asistente "hable"
  
- **pyaudio** - Entrada/salida de audio
  - Instalación: `pip install pyaudio`
  - Uso: Capturar audio del micrófono

---

## 🌐 Internet (Futuro - Fase 2)

- **requests** - Hacer peticiones HTTP
  - Instalación: `pip install requests`
  - Uso: Consumir APIs, descargar datos
  
- **beautifulsoup4** - Web scraping y parsing HTML
  - Instalación: `pip install beautifulsoup4`
  - Uso: Extraer información de páginas web
  
- **aiohttp** - Peticiones HTTP asíncronas
  - Instalación: `pip install aiohttp`
  - Uso: Múltiples peticiones simultáneas

---

## 🛠️ Utilidades Generales

- **python-decouple** - Gestión de configuración
  - Instalación: `pip install python-decouple`
  - Uso: Separar configuración del código
  
- **loguru** - Logging mejorado
  - Instalación: `pip install loguru`
  - Uso: Registrar eventos del asistente
  
- **pytest** - Framework de testing
  - Instalación: `pip install pytest`
  - Uso: Crear tests automatizados

---

## 📋 Orden de Aprendizaje Recomendado

### Fase 1: Fundamentos
1. `pathlib`, `os`, `shutil` - Manejo de archivos
2. `json` - Persistencia básica
3. `python-dotenv` - Configuración segura

### Fase 2: Interfaz Básica
4. `tkinter` o `customtkinter` - GUI simple
5. `rich` - Feedback en terminal

### Fase 3: IA
6. `openai` o `anthropic` - API de IA
7. `langchain` - Framework para LLMs

### Fase 4: Memoria
8. `sqlite3` - Base de datos
9. `chromadb` - Memoria vectorial
10. `pydantic` - Validación

### Fase 5: Avanzado
11. `watchdog` - Monitoreo de archivos
12. `cryptography` - Seguridad avanzada
13. `pytest` - Testing

### Fase 6: Voz e Internet (Futuro)
14. `speechrecognition`, `pyttsx3` - Voz
15. `requests`, `beautifulsoup4` - Internet

---

## 💡 Notas Importantes

- **Entornos virtuales**: Siempre usa `venv` para cada proyecto
- **Versiones**: Documenta las versiones que usas (`pip freeze > requirements.txt`)
- **API Keys**: NUNCA subas tus API keys a GitHub
- **Testing**: Prueba cada librería con ejemplos pequeños antes de integrar

---

## 🔗 Documentación Oficial

- [Python Docs](https://docs.python.org/3/)
- [OpenAI API](https://platform.openai.com/docs)
- [Anthropic API](https://docs.anthropic.com/)
- [LangChain Docs](https://python.langchain.com/)
- [ChromaDB Docs](https://docs.trychroma.com/)
