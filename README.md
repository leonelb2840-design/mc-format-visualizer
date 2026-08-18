# 🎨 MC Format Visualizer

Visualizador de formato de texto estilo **Minecraft** que interpreta los códigos de color `§` y estilos en tiempo real. Una PWA (Progressive Web App) ligera, rápida y sin dependencias.

![Preview](https://img.shields.io/badge/Minecraft-Format%20%C2%A7-brightgreen?style=flat-square)

## ✨ Características

- 🖌️ **16 colores** de Minecraft (`§0` a `§f`)
- ✍️ **6 estilos** (`§k` ofuscado, `§l` negrita, `§m` tachado, `§n` subrayado, `§o` cursiva, `§r` restablecer)
- 🎮 **Tipografía pixel art** (`Press Start 2P`)
- 📱 **PWA** instalable en móvil y escritorio
- ⚡ **100% offline** gracias al Service Worker
- 🖼️ **Logo SVG** pixel art integrado
- 🖱️ **Paleta interactiva** — haz clic en cualquier color o estilo para insertarlo

## 🚀 Uso

1. Abre `index.html` en cualquier navegador moderno.
2. Escribe tu texto usando los códigos `§`.
3. El resultado se renderiza automáticamente.

### Ejemplos

```
§c¡Hola §lMundo§r!
§b§oTexto en aqua y cursiva
§6§l§oOro, negrita y cursiva
§f§kTexto ofuscado
```

## 📁 Estructura

```
.
├── index.html      # Aplicación principal
├── sw.js           # Service Worker (offline)
├── manifest.json   # Configuración PWA
├── README.md       # Este archivo
├── LICENSE # Licencia
└── .gitignore # Git Configuración Files
```

## 🛠️ Desarrollo

No se necesita build. Solo abre `index.html` con un servidor local si quieres probar el Service Worker:

```bash
npx serve .
# o
python -m http.server 8080
```

## 📲 Instalación

En navegadores compatibles aparecerá el botón **"Instalar App"**. También puedes instalarla desde el menú del navegador → *Agregar a pantalla de inicio*.

## 📄 Licencia

MIT — úsalo, modifícalo y compártelo libremente.

---

Hecho con ❤️ y muchos bloques de pixel.
