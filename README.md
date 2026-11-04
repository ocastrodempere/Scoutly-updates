# Scoutly

Repositori espill **públic** per al feed d'actualitzacions de [Scoutly](https://github.com/ocastrodempere/Scoutly) (codi privat). Només hi ha releases amb `latest.json` i els artefactes firmats per l'actualitzador de Tauri; no es desenvolupa aquí: les releases es publiquen amb `pnpm ship` des de la màquina del desenvolupador.

---

## Català

**On el baixo?** A la [darrera release publicada](https://github.com/ocastrodempere/Scoutly-updates/releases/latest), buscant el fitxer del teu sistema:

| Sistema | Fitxer |
| --- | --- |
| 🍎 macOS Apple Silicon (M1–M4) | `Scoutly_<versió>_aarch64.dmg` |
| 🍎 macOS Intel | `Scoutly_<versió>_x64.dmg` |
| 🪟 Windows 10/11 (64 bits) | `Scoutly_<versió>_x64-setup.exe` |

El cos de cada release et diu què hi ha disponible avui i et dona l'enllaç directe.

Els `.app.tar.gz` i els `.sig` **no** són per instal·lar a mà: són els artefactes de l'actualitzador automàtic. El paquet ML (`ml-v1`) tampoc no s'instal·la des d'aquí: el descarrega la pròpia app en activar-lo.

**Com instal·lar-lo (macOS):** obre el `.dmg` descarregat i arrossega **Scoutly** a la carpeta **Aplicacions**. El primer cop, macOS bloquejarà l'app (es distribueix sense certificat d'Apple, decisió del projecte): fes **clic dret (o ⌘-clic) sobre Scoutly → Obre → torna a prémer Obre**. Només passa aquesta primera vegada. Alternativa: **Ajustos del Sistema → Privacitat i seguretat → Obre igualment**.

**I després:** les actualitzacions arriben soles (en obrir l'app i cada 4 hores, amb signatura verificada). Cap actualització torna a demanar el pas de Gatekeeper.

---

## English

**Where do I get it?** From the [latest published release](https://github.com/ocastrodempere/Scoutly-updates/releases/latest), looking for your system's file:

| System | File |
| --- | --- |
| 🍎 macOS Apple Silicon (M1–M4) | `Scoutly_<version>_aarch64.dmg` |
| 🍎 macOS Intel | `Scoutly_<version>_x64.dmg` |
| 🪟 Windows 10/11 (64-bit) | `Scoutly_<version>_x64-setup.exe` |

The body of each release tells you what is available today and gives you the direct link.

The `.app.tar.gz` and `.sig` files are **not** for manual installs: they are the auto-updater's artifacts. The ML package (`ml-v1`) is not installed from here either: the app itself downloads it when you enable it.

**How to install it (macOS):** open the downloaded `.dmg` and drag **Scoutly** into the **Applications** folder. The first time, macOS will block the app (it ships without an Apple certificate, a deliberate project decision): **right-click (or ⌘-click) Scoutly → Open → press Open again**. It only happens that first time. Alternative: **System Settings → Privacy & Security → Open Anyway**.

**After that:** updates arrive on their own (when the app opens and every 4 hours, with a verified signature). No update will ask for the Gatekeeper step again.

---

## Castellano

**¿Dónde lo descargo?** En la [última release publicada](https://github.com/ocastrodempere/Scoutly-updates/releases/latest), buscando el archivo de tu sistema:

| Sistema | Archivo |
| --- | --- |
| 🍎 macOS Apple Silicon (M1–M4) | `Scoutly_<versión>_aarch64.dmg` |
| 🍎 macOS Intel | `Scoutly_<versión>_x64.dmg` |
| 🪟 Windows 10/11 (64 bits) | `Scoutly_<versión>_x64-setup.exe` |

El cuerpo de cada release te dice qué hay disponible hoy y te da el enlace directo.

Los `.app.tar.gz` y los `.sig` **no** son para instalar a mano: son los artefactos del actualizador automático. El paquete ML (`ml-v1`) tampoco se instala desde aquí: lo descarga la propia app al activarlo.

**Cómo instalarlo (macOS):** abre el `.dmg` descargado y arrastra **Scoutly** a la carpeta **Aplicaciones**. El primer arranque, macOS bloqueará la app (se distribuye sin certificado de Apple, decisión del proyecto): haz **clic derecho (o ⌘-clic) sobre Scoutly → Abrir → vuelve a pulsar Abrir**. Solo pasa esa primera vez. Alternativa: **Ajustes del Sistema → Privacidad y seguridad → Abrir igualmente**.

**Y después:** las actualizaciones llegan solas (al abrir la app y cada 4 horas, con firma verificada). Ninguna actualización vuelve a pedir el paso de Gatekeeper.
