# IPTVTunerForPlex — descargas

Instaladores de **IPTVTunerForPlex**, la app de macOS que convierte una lista IPTV (M3U/M3U8) en un tuner para Plex Live TV y en un servidor para la app de Fire TV / Android TV incluida. Más información, precio y compra de la licencia en **[plexiplabs.es](https://plexiplabs.es)**.

## Descargar

- **[Última versión (DMG para macOS)](../../releases/latest)** — `IPTVTunerForPlex-<versión>.dmg`
- **[Manual de usuario (PDF)](../../releases/latest/download/IPTVTunerForPlex-Manual.pdf)**

## Requisitos

- macOS 26.5 o superior.
- Una lista IPTV en formato M3U/M3U8 (la app no incluye contenido ni proveedor).
- `ffmpeg` para remuxear canales HLS: `brew install ffmpeg`. Solo si los usas: `openvpn` (VPN), `sshpass` y `privoxy` (túnel SSH) y `adb` (instalar la app en el Fire TV).

## Instalación

1. Abre el DMG y arrastra `IPTVTunerForPlex.app` a **Aplicaciones**.
2. La app está firmada pero **no notarizada por Apple**. La primera vez, haz clic derecho sobre ella → **Abrir** → **Abrir**. Si aun así no abre:
   ```bash
   xattr -dr com.apple.quarantine /Applications/IPTVTunerForPlex.app
   ```
3. Sigue el manual de usuario para los primeros pasos.

## Licencia de uso

Sin licencia, cada reproducción entra en modo demo y se corta a los 20 segundos, y "Compartir" con Plex o el Fire TV permite 5 minutos de uso acumulado. La licencia es un pago único por Mac y se compra en [plexiplabs.es](https://plexiplabs.es/generar-licencia.php).

## Soporte

Escribe a [mgoreiro@gmail.com](mailto:mgoreiro@gmail.com). Este repositorio solo distribuye los instaladores; no contiene el código fuente.
