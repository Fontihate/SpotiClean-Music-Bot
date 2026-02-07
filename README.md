# 🎧 SpotiClean: El Juez Musical Bot

![Python](https://img.shields.io/badge/python-3.12+-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)
![Spotify](https://img.shields.io/badge/Spotify-1DB954?style=for-the-badge&logo=spotify&logoColor=white)
![Scraper](https://img.shields.io/badge/Scraper-Cloudflare--Bypass-orange?style=for-the-badge&logo=google-cloud&logoColor=white)

---

**SpotiClean** no es solo un bot de información; es tu crítico musical personal en Telegram. Envíale un enlace de Spotify y el bot extraerá los metadatos, buscará una previsualización de audio en iTunes y, lo más importante, **¡juzgará tu gusto musical!** con una opinión basada en el género.

---

## 🛠️ Stack Tecnológico

| Herramienta | Función |
|---|---|
| **pyTelegramBotAPI** | Gestión de la interfaz del bot y comandos de Telegram. |
| **Cloudscraper** | Bypass avanzado para extraer datos de Spotify sin ser bloqueado. |
| **BeautifulSoup4** | Scraping y parseo de metadatos (títulos, artistas, portadas). |
| **iTunes API** | Integración externa para obtener géneros y previews de audio (.mp3). |

---

## 🚀 Funcionalidades Principales

| Categoría | Descripción |
|---|---|
| **⚖️ El Juez Musical** | Sistema de opinión automática que reacciona según el género (Metal, Pop, Jazz, etc.). |
| **🎵 Enriquecimiento** | No solo da texto; envía la portada del álbum y una nota de voz con la preview. |
| **🌍 Multi-plataforma** | Genera botones automáticos para buscar la canción en YouTube o Songlink. |
| **🛡️ Anti-Tracking** | Limpia automáticamente los parámetros de rastreo de los enlaces de Spotify. |

---

## 📦 Instalación

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/Fontihate/SpotiClean-Music-Bot.git
   cd SpotiClean-Music-Bot
   ```

2. **Instala las dependencias necesarias:**
   ```bash
   pip install pyTelegramBotAPI cloudscraper beautifulsoup4 requests
   ```

---

## ⚙️ Configuración

Para que el bot funcione, debes editar el archivo principal (`main.py` o el nombre que tenga tu script) y añadir tu token de Telegram:

```python
# 🔐 CONFIGURACIÓN
TOKEN_TELEGRAM = "TU_TELEGRAM_TOKEN_AQUÍ"
```

---

## 📖 Cómo Funciona

1. Inicia el bot con `/start`.
2. Pega cualquier enlace de canción o álbum de Spotify.
3. El bot hará el scraping, consultará iTunes y te responderá con:
   - La carátula del álbum.
   - Datos del artista y género.
   - **La opinión (a veces un poco dura) del bot.**
   - Un archivo de audio para escuchar un avance.
   - Botones directos a YouTube.

---

## 📈 Roadmap

- [ ] Integración de base de datos para recordar los gustos de cada usuario.
- [ ] Comandos para buscar por texto en lugar de solo por enlace.
- [ ] Modo "Crítico Agresivo" configurable.

---

Hecho con 🤘 por [Fontihate](https://github.com/Fontihate)
