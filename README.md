# Clear Shares

Micro app Android que abre TikTok (con tu sesión ya iniciada) y recorre
Perfil → Ajustes y privacidad → Centro de actividades → Compartidos → Seleccionar todo → Eliminar,
usando un Servicio de Accesibilidad limitado a los paquetes de TikTok.

- No pide ni guarda contraseñas, no tiene permiso de internet.
- Si TikTok cambia sus menús, edita la lista `PATH` en `ShareCleanerService.kt`.

## Obtener el APK
1. Sube este proyecto a un repositorio de GitHub (rama `main`).
2. Pestaña **Actions** → "Build APK" → entra al último run → **Artifacts** → `ClearShares-apk`.
3. Instala `app-debug.apk` en el teléfono (permite "instalar apps desconocidas").
4. Android 13+: Ajustes → Apps → Clear Shares → ⋮ → "Permitir ajustes restringidos".
5. Abre la app → "Activar accesibilidad" → activa Clear Shares → "Borrar compartidos".
