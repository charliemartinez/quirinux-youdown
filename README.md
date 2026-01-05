# 📥 YouDownloader!

(c) Charlie Martínez – Quirinux GNU/Linux, GPLv2  

## 🇪🇸 Español  
Una sencilla aplicación gráfica y multilingüe para descargar videos de YouTube en formato **MP4 (video)** o **MP3 (audio)**.  
Desarrollada en **Python 3** con **Tkinter**, y utilizando **[yt-dlp](https://github.com/yt-dlp/yt-dlp)** como motor de descarga.

✅ Características:

- Descargar vídeos como MP4  
- Extraer audio como MP3 (requiere `ffmpeg`)  
- Barra de progreso en tiempo real  
- Elegir carpeta de destino antes de descargar  
- Interfaz en varios idiomas: Español, Inglés, Alemán, Francés, Italiano, Portugués y Gallego  
- Se adapta automáticamente al idioma del sistema  
- Funciona sin conexión (no requiere pip)  
- Diseñada especialmente para sistemas basados en Debian  

🔧 Requisitos:

```bash
sudo apt install python3-tk ffmpeg
```

📦 yt-dlp en Debian/Ubuntu:  
El paquete oficial suele estar desactualizado. Usa esta versión recomendada:

```bash
sudo curl -L https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp -o /usr/local/bin/yt-dlp
sudo chmod a+rx /usr/local/bin/yt-dlp
```

🌀 En Quirinux:  
`yt-dlp` ya está actualizado en los repositorios oficiales. Puedes verificarlo aquí:  
🔗 https://repo.quirinux.org/pool/main/y/yt-dlp/

▶️ Ejecutar la aplicación:

```bash
git clone https://github.com/quirinux-so/youtube-down-gui.git
cd youtube-downloader-gui
python3 youtubedownload.py
```

📦 Instalación alternativa (solo en Quirinux):

```bash
su root
apt install quirinux-youtubedownloader
```

También disponible desde el **Centro de Software de Quirinux**.  
🔗 https://repo.quirinux.org/pool/main/q/quirinux-youtubedown

### ⚠️ Aviso legal  
Este proyecto forma parte del ecosistema **Quirinux**, pero es compatible con cualquier distribución moderna de GNU/Linux.  
Publicado bajo licencia **GPLv2**.  
(c) Charlie Martínez – Quirinux GNU/Linux  
ℹ️ Más información:  
🔗 [https://www.quirinux.org/aviso-legal](https://www.quirinux.org/aviso-legal)

---

## 🇬🇧 English  
A simple, multilingual graphical application to download YouTube videos in **MP4 (video)** or **MP3 (audio)** format.  
Built with **Python 3** and **Tkinter**, using **[yt-dlp](https://github.com/yt-dlp/yt-dlp)** as its backend.

✅ Features:

- Download videos as MP4  
- Extract audio as MP3 (requires `ffmpeg`)  
- Real-time progress bar  
- Select output folder before download  
- Multilingual interface: Spanish, English, German, French, Italian, Portuguese, Galician  
- Automatically adapts to your system language  
- Works offline (no pip required)  
- Designed for Debian-based systems  

🔧 Requirements:

```bash
sudo apt install python3-tk ffmpeg
```

📦 yt-dlp on Debian/Ubuntu:  
The official package may be outdated. Recommended installation:

```bash
sudo curl -L https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp -o /usr/local/bin/yt-dlp
sudo chmod a+rx /usr/local/bin/yt-dlp
```

🌀 On Quirinux:  
`yt-dlp` is updated and available in the official repositories.  
🔗 https://repo.quirinux.org/pool/main/y/yt-dlp/

▶️ Run the application:

```bash
git clone https://github.com/quirinux-so/youtube-down-gui.git
cd youtube-downloader-gui
python3 youtubedownload.py
```

📦 Alternative install (only on Quirinux):

```bash
su root
apt install quirinux-youtubedownloader
```

Also available from the **Quirinux Software Center**.  
🔗 https://repo.quirinux.org/pool/main/q/quirinux-youtubedown

### ⚠️ Legal notice  
This project is part of the **Quirinux** ecosystem but is compatible with any modern GNU/Linux distribution.  
Released under the **GPLv2 license**.  
(c) Charlie Martínez – Quirinux GNU/Linux  
ℹ️ More info:  
🔗 [https://www.quirinux.org/aviso-legal](https://www.quirinux.org/aviso-legal)
