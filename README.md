# 🧹 SpotiClean Music Bot

![Python](https://img.shields.io/badge/python-3.12+-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Spotify](https://img.shields.io/badge/Spotify-1DB954?style=for-the-badge&logo=spotify&logoColor=white)
![Automation](https://img.shields.io/badge/Automation-Cleanup-BD93F9?style=for-the-badge&logo=probot&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

---

**SpotiClean Music Bot** es una herramienta de automatización diseñada para mantener tu biblioteca de Spotify impecable. Utiliza la API oficial de Spotify para organizar listas de reproducción, eliminar duplicados y gestionar el contenido de forma inteligente, ahorrándote horas de edición manual.

---

## 🛠️ Stack Tecnológico

| Herramienta | Función |
|---|---|
| **Python 3.12+** | Lenguaje principal del bot. |
| **Spotipy** | Librería cliente para una integración fluida con la Web API de Spotify. |
| **JSON/Env** | Gestión segura de credenciales y tokens de acceso. |
| **OAuth 2.0** | Protocolo de autenticación para acceso seguro a la cuenta del usuario. |

---

## 🚀 Funcionalidades Principales

| Categoría | Descripción |
|---|---|
| **Deduplicación** | Escaneo automático de playlists para eliminar canciones repetidas. |
| **Limpieza de Títulos** | Normalización de nombres (eliminación de "Remastered", "Live Version", etc.). |
| **Filtros Avanzados** | Posibilidad de filtrar canciones por género, popularidad o fecha de lanzamiento. |
| **Gestión de Playlists** | Creación y actualización automática de listas basadas en tus hábitos de escucha. |

---

## 📦 Instalación y Configuración

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/Fontihate/SpotiClean-Music-Bot.git
   cd SpotiClean-Music-Bot
   ```

2. **Instala las dependencias:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configuración de API de Spotify:**
   Crea una aplicación en el [Spotify Developer Dashboard](https://developer.spotify.com/dashboard) y añade tus credenciales a un archivo `.env`:
   ```env
   SPOTIPY_CLIENT_ID='tu_client_id'
   SPOTIPY_CLIENT_SECRET='tu_client_secret'
   SPOTIPY_REDIRECT_URI='http://localhost:8888/callback'
   ```

---

## 📖 Modo de Uso

Una vez configuradas las credenciales, lanza el script para empezar la limpieza:

```bash
python main.py
```

> [!NOTE]
> La primera vez que lo ejecutes, se abrirá una ventana en tu navegador para que autorices al bot a gestionar tus listas de reproducción.

---

## 📈 Roadmap de Desarrollo

- [ ] Implementación de un **algoritmo de recomendación** basado en limpieza de géneros.
- [ ] Creación de un **Dashboard web** con Flask para gestionar el bot visualmente.
- [ ] Dockerización del proyecto para despliegue en la nube (AWS/Azure).
- [ ] Programación de limpiezas automáticas semanales (Cron jobs).

---

## 🤝 Contribuciones

¿Quieres ayudar a que SpotiClean sea aún mejor?

1. Haz un **Fork**.
2. Crea una rama para tu mejora (`git checkout -b feature/MejoraSpotify`).
3. Envía un **Pull Request**.

---

Hecho con 🎵 por [Fontihate](https://github.com/Fontihate)
