# Scoutly — descárgalo e instálalo

Repositorio espejo **público** para el feed de actualizaciones de [Scoutly](https://github.com/ocastrodempere/Scoutly) (código privado).

Contiene solo releases con `latest.json` y los artefactos firmados por el updater de Tauri.
No se desarrolla aquí: las releases se publican con `pnpm ship` desde la máquina del desarrollador.

## ¿Qué tengo que descargar?

Entra en la [última release publicada](https://github.com/ocastrodempere/Scoutly-updates/releases/latest) y busca el archivo de tu sistema:

| Tu sistema | Busca este archivo |
| --- | --- |
| 🍎 macOS Apple Silicon (M1–M4) | `Scoutly_<versión>_aarch64.dmg` |
| 🍎 macOS Intel | `Scoutly_<versión>_x64.dmg` |
| 🪟 Windows 10/11 (64 bits) | `Scoutly_<versión>_x64-setup.exe` |

El cuerpo de cada release te dice qué hay disponible hoy y te da el enlace directo de cada sistema.

Los `.app.tar.gz` y los `.sig` **no** son para instalar a mano: son los artefactos del actualizador automático. El paquete ML (`ml-v1`) tampoco se instala desde aquí: lo descarga la propia app al activarlo.

## Cómo instalarlo (macOS)

1. Abre el `.dmg` descargado y arrastra **Scoutly** a la carpeta **Aplicaciones**.
2. **Primer arranque:** macOS bloqueará la app porque se distribuye sin certificado de Apple (decisión del proyecto). Haz **clic derecho (o ⌘-clic) sobre Scoutly → Abrir → vuelve a pulsar Abrir**. Solo pasa esa primera vez.
   Alternativa: **Ajustes del Sistema → Privacidad y seguridad → Abrir igualmente**.

## Y después

Las actualizaciones llegan solas: la app comprueba si hay versión nueva al abrirse y cada 4 horas, la descarga con firma verificada y se reinicia. Ninguna actualización vuelve a pedir el paso de Gatekeeper.
