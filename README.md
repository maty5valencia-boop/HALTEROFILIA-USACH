# Halterofilia USACH · app del equipo

Versión de la app BARRA para el equipo de Halterofilia USACH (profe Robinson), **sin agenda de horarios**.
Incluye: planis (Excel o fotos), registro de entrenamientos con video, marcas/RM, sensaciones, ranking,
competencias, herramientas (% del RM, discos, Sinclair) y análisis de la barra. Sin mensualidades ni tienda.

## Puesta en marcha

1. **Backend** – en https://script.google.com crea un **proyecto nuevo** (no uses el de Halteros, así queda con su propia planilla).
   Pega `Code.gs`, guarda, elige la función `inicioUSACH` y presiona **Ejecutar** (autoriza los permisos).
   Crea la planilla, al profe **Robinson (clave 1234)** y a los 23 atletas (PIN **1234**). El registro muestra el resultado.
2. **Implementar** → Nueva implementación → *Aplicación web* · Ejecutar como: **Yo** · Acceso: **Cualquier usuario**. Copia el link que termina en `/exec`.
3. **Frontend** – en `index.html` busca `API_URL` y pega ese link. Sube `index.html`, `manifest.json`, `sw.js`, `icon-192.png` e `icon-512.png` a este repo
   y activa GitHub Pages (Settings → Pages → rama `main`, carpeta `/`).
4. Comparte el link de GitHub Pages con el equipo. Robinson debería cambiar su clave desde la app (Equipo → Cambiar mi contraseña).

Si cambias `Code.gs` después, recuerda: Implementar → Gestionar implementaciones → editar → *Nueva versión*.
