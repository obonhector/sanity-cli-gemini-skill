# Sanity.io CLI Skill for Gemini CLI 🌑✨

This skill enables **Gemini CLI** to interact with **Sanity.io CMS** directly from the terminal.

---

## 🇪🇸 Descripción (Spanish)
Esta Skill permite a Gemini CLI gestionar el contenido de tu blog o aplicación basada en Sanity.io. Puedes crear documentos, realizar consultas GROQ, listar proyectos y gestionar datasets de forma proactiva.

### Características:
- **Gestión de Contenido:** Crea, lee, actualiza o borra documentos (posts, autores, etc.).
- **Consultas GROQ:** Ejecuta consultas directamente sobre tus datos de producción.
- **Gestión de Proyectos:** Lista tus proyectos activos y sus configuraciones.
- **Soporte API:** Permite la publicación mediante API tokens cuando no se dispone del Studio localmente.

---

## 🇺🇸 Description (English)
This skill allows Gemini CLI to manage content for your Sanity.io-based blog or application. You can create documents, run GROQ queries, list projects, and manage datasets proactively.

### Features:
- **Content Management:** Create, read, update, or delete documents (posts, authors, etc.).
- **GROQ Queries:** Run queries directly against your production data.
- **Project Management:** List your active projects and their configurations.
- **API Support:** Enables publishing via API tokens when local Studio access is unavailable.

---

## 🚀 Installation / Instalación

1.  **Clone the repository / Clona el repositorio:**
    ```bash
    git clone https://github.com/obonhector/sanity-cli-gemini-skill.git
    ```

2.  **Install the skill / Instala la skill:**
    ```bash
    gemini skills install ./sanity-cli-gemini-skill --scope user
    ```

3.  **Reload skills / Recarga las skills:**
    In your Gemini CLI session, run:
    ```
    /skills reload
    ```

---

## 💡 Usage Examples / Ejemplos de Uso

- "Escribe una nueva entrada en mi blog sobre Geopolítica e IA"
- "¿Cuántos posts tengo publicados en Sanity?"
- "Busca el post más reciente y añade una etiqueta 'IA'"
- "Publica este JSON como un nuevo documento de tipo autor"

---

## 🛠️ Security / Seguridad
Esta skill no almacena tus tokens de API ni Project IDs. Debes configurar tu entorno localmente mediante `sanity login` o proporcionando los parámetros necesarios en tus peticiones.

---

## 🤝 Contributing / Contribución
Si tienes ideas para mejorar esta integración, ¡no dudes en abrir un issue o enviar una pull request!
