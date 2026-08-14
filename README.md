# ✨ LumiBook

Aplicación web interactiva bilingüe (Inglés–Español) para que mamás y sus hijas/os 
de 4-6 años aprendan jugando.

## 🎯 Características

- 🤖 Avatar "Lumi" con animaciones empáticas
- 🎤 Reto fonético con reconocimiento de voz
- ✏️ Taller de cuentos: crean en español, Lumi lo repite en inglés
- 🎨 Área de dibujo con colores que se desbloquean al pronunciar
- 🏆 Sistema de estrellas y celebración
- 📱 Responsive (móvil, tablet, PC)
- 🔔 Música y efectos con Web Audio API (cero latencia)

## 🚀 Deploy en Render

Este proyecto se despliega automáticamente como **Static Site** en Render.com.

## 🛠️ Desarrollo local

Solo abre `public/index.html` en tu navegador (usa servidor local para el micrófono):

```bash
# Con Python 3
cd public && python -m http.server 8080

# Con Node
npx serve public