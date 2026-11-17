# Pausa

Web app de una sola página, en español y pensada para celular, que ayuda a superar un impulso en 6 pasos:

1. Escala de intensidad (1 a 10)
2. Respiración guiada 4-4-6 durante 1 minuto
3. Tus razones, escritas por ti
4. Una acción (caminar, ducha, flexiones, comer algo, llamar a alguien) con temporizador de 20 minutos
5. ¿Pasaron las ganas? (opción de 10 minutos más)
6. Registro del detonante

En la pantalla principal se ven los impulsos superados y los soles ahorrados (S/ 100 por victoria).

## Privacidad

Todo se guarda **solo** en el `localStorage` del navegador del teléfono. No hay servidor, backend ni analítica, y el repositorio contiene únicamente el código.

## Publicar en GitHub Pages

1. Crea un repositorio (por ejemplo `pausa`) y sube estos archivos a la rama `main`.
2. En el repositorio: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `(root)`** → Save.
3. Espera 1–2 minutos. La app queda en `https://TU-USUARIO.github.io/pausa/`.

## Instalar en el celular

- **Android (Chrome):** abre la URL → menú ⋮ → *Instalar aplicación* / *Agregar a pantalla de inicio*.
- **iPhone (Safari):** abre la URL → botón Compartir → *Agregar a pantalla de inicio*.

## Actualizar

Si cambias archivos, sube el número de versión en `sw.js` (`pausa-v1` → `pausa-v2`) para que los teléfonos descarguen la nueva versión.
