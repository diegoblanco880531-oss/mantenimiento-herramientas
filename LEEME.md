# Cómo publicar tu app y generar el APK

Tienes una carpeta con 5 archivos: `index.html`, `manifest.json`, `service-worker.js`, `icon-192.png`, `icon-512.png`. Sigue estos pasos en orden.

## Paso 1: Crear cuenta en GitHub (si no tienes)

1. Ve a https://github.com/signup
2. Ingresa tu correo, crea una contraseña y un nombre de usuario
3. Verifica tu correo

## Paso 2: Crear un repositorio nuevo

1. Ve a https://github.com/new
2. En "Repository name" escribe: `mantenimiento-herramientas`
3. Marca la opción "Public"
4. Toca "Create repository"

## Paso 3: Subir los archivos de la app

1. Dentro del repositorio recién creado, busca el enlace **"uploading an existing file"**
2. Descomprime el ZIP en tu celular (app de Archivos → mantener presionado el ZIP → Extraer)
3. Sube los 5 archivos: `index.html`, `manifest.json`, `service-worker.js`, `icon-192.png`, `icon-512.png`
4. Baja y toca "Commit changes"

## Paso 4: Activar GitHub Pages

1. En el repositorio, ve a **Settings** (⚙️)
2. En el menú lateral busca **Pages**
3. En "Branch" selecciona `main` y la carpeta `/ (root)`
4. Toca **Save**
5. Espera 1-2 minutos y recarga — te dará una URL como:
   `https://tu-usuario.github.io/mantenimiento-herramientas/`

## Paso 5: Generar el APK

1. Copia esa URL
2. Ve a https://www.pwabuilder.com
3. Pégala y presiona "Start"
4. Haz clic en "Package for stores" → elige "Android" → descarga el paquete
5. Instala el `.apk` en tu celular (permite "instalar apps desconocidas" si Android lo pide)

## Sobre tus datos

La app guarda todo (herramientas, mantenimientos, checklists e historial de inspecciones) directamente en tu dispositivo. Si cambias de celular o borras los datos de la app, ese historial se pierde — no hay respaldo en la nube. Si más adelante quieres una versión con respaldo o para compartir entre varios técnicos, avísame y la ajustamos.

## Actualizar la app más adelante

Si quieres agregar campos, categorías nuevas o ajustar el checklist por defecto, pídemelo y edito `index.html`. Luego sube el archivo actualizado a tu mismo repositorio de GitHub (Settings no cambia, solo reemplazas el archivo).
