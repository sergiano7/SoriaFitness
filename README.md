# soriafitness

App de seguimiento de entrenamientos. Funciona entera en el navegador — cada persona que la usa guarda sus datos solo en su propio móvil/navegador (no hay cuentas, no hay contraseñas, no hay base de datos compartida).

## Poner esto en GitHub Pages (gratis)

1. Ve a [github.com](https://github.com) e inicia sesión (o crea una cuenta, es gratis).
2. Arriba a la derecha, pulsa el **+** → **New repository**.
   - Name: `soriafitness` (o el que quieras).
   - Que sea **Public**.
   - Créalo sin marcar ningún checkbox extra.
3. En la página del repo recién creado, pulsa **Add file → Upload files**.
4. Arrastra estos 5 archivos:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
5. Pulsa **Commit changes**.
6. Ve a **Settings** (dentro del repo) → **Pages** (menú de la izquierda).
7. En "Build and deployment" → **Source**, elige **Deploy from a branch**.
8. En **Branch**, elige `main` y carpeta `/ (root)`. Guarda.
9. Espera 1-2 minutos y recarga la página. Arriba te aparecerá la URL pública, algo como:

   `https://tu-usuario.github.io/soriafitness/`

## Invitar a amigos

Solo tienes que pasarles esa URL. Cada persona que la abra:
- Puede usarla directamente desde el navegador, o
- Añadirla a su pantalla de inicio (en iPhone: Safari → compartir → "Añadir a pantalla de inicio"; en Android: Chrome → menú → "Instalar aplicación" o "Añadir a pantalla de inicio").

Cada uno tendrá **sus propios datos**, guardados solo en su dispositivo. No hace falta registrarse ni hay contraseñas, y nadie ve los entrenamientos de otro.

## Ojo con esto

Los datos viven únicamente en el navegador de cada persona. Si alguien borra los datos de navegación de Safari/Chrome, desinstala la app del icono, o el móvil se rompe/se pierde, esos datos se pierden con él — no hay copia en ningún otro sitio.

Si en algún momento quieres guardarte una copia manual, la app tiene un botón **Exportar** (pestaña "Semana") que descarga un `.json` con todo, y un botón **Importar** para recuperarlo.

## Actualizar la app más adelante

Si quieres que le cambie o añada algo, vuelve a subir el `index.html` actualizado al mismo repositorio (Add file → Upload files, sobrescribiendo el existente) y GitHub Pages se actualiza solo en un par de minutos.
