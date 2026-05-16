# OMSV – Registro de Velocidad (PWA)

## ¿Qué incluye este paquete?

```
omsv-pwa/
├── index.html       ← App completa
├── manifest.json    ← Configuración PWA
├── sw.js            ← Service Worker (offline + caché)
└── icons/
    ├── icon-192.png ← Ícono para Android / pantalla de inicio
    └── icon-512.png ← Ícono alta resolución
```

---

## ¿Cómo publicarla para usarla en el celular?

La PWA necesita estar en un servidor HTTPS para poder instalarse.
Las opciones más simples (todas gratuitas):

### Opción 1 — GitHub Pages (recomendado)
1. Crear una cuenta en https://github.com
2. Crear un repositorio nuevo (ej: `omsv-app`)
3. Subir todos estos archivos
4. Ir a Settings → Pages → Source: main branch
5. La app quedará en: `https://tu-usuario.github.io/omsv-app`

### Opción 2 — Netlify (drag & drop, el más fácil)
1. Ir a https://netlify.com → Log in con Google
2. Arrastrar la carpeta `omsv-pwa` al área de deploy
3. En segundos tenés una URL tipo `https://algo-random.netlify.app`

### Opción 3 — Vercel
1. Ir a https://vercel.com
2. "New Project" → importar o subir carpeta
3. Deploy automático

---

## Instalación en el celular (una vez publicada)

### Android (Chrome)
1. Abrir la URL en Chrome
2. Aparece un banner automático "Agregar a pantalla de inicio"
3. O ir a menú (⋮) → "Instalar app" / "Agregar a pantalla de inicio"

### iPhone / iPad (Safari)
1. Abrir la URL en Safari
2. Tocar el ícono de compartir (□↑)
3. "Añadir a pantalla de inicio"
4. Confirmar el nombre "OMSV" → Añadir

---

## Características de la PWA

- ✅ Funciona **sin internet** una vez instalada
- ✅ Se ve como una app nativa (sin barra del navegador)
- ✅ Ícono en la pantalla de inicio
- ✅ Datos guardados localmente (localStorage)
- ✅ Sesión se recupera si se cierra la app
- ✅ Exporta a Excel (.xls) compatible con Excel y Google Sheets
- ✅ Diseño marca GCBA (azul #153244, amarillo #FFD200, teal #7FDED9)
- ✅ Detecta días hábiles/inhábiles y feriados nacionales Argentina

---

## Soporte

App desarrollada para el Operativo Municipal de Seguridad Vial (OMSV).
Diseño basado en el Manual de Marca GCBA.
