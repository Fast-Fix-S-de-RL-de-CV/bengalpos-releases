# Bengal POS — descargas

Instaladores oficiales de **Bengal POS**, el punto de venta de [bengalpos.com](https://bengalpos.com). Aquí solo hay instaladores y el archivo de versiones; el código de la app no se publica.

**[Descargar la última versión →](https://github.com/Fast-Fix-S-de-RL-de-CV/bengalpos-releases/releases/latest)**

| Equipo | Archivo |
| --- | --- |
| Windows 10 u 11 | `BengalPOS-Setup-*.exe` |
| Mac con Apple Silicon (M1 o más nuevo) | `BengalPOS-*-mac-arm64.dmg` (hasta 1.0.6: `-mac-apple-silicon.dmg`) |
| Mac con Intel | `BengalPOS-*-mac-x64.dmg` (hasta 1.0.6: `-mac-intel.dmg`) |
| Android (terminales y celulares, fuera de Google Play) | `BengalPOS-*-android.apk` |
| iPhone y iPad | [App Store](https://apps.apple.com/mx/app/bengal-pos/id6762742229) |

Las apps revisan solas si hay una versión nueva y avisan con una burbuja para actualizar.

- **Mac:** firmada con Developer ID y notarizada por Apple.
- **Windows:** si SmartScreen pregunta, «Más información» → «Ejecutar de todas formas».
- **Android:** al abrir el APK, Android pide permitir la instalación desde el navegador.

## Para el equipo

- `latest.json`: última versión de cada plataforma; lo leen las apps para mostrar la burbuja de actualización.
- `desktop/latest.yml` y `desktop/latest-mac.yml`: los usa el actualizador automático de Windows y Mac.
- Cada versión vive en un *release* con sus instaladores. El proceso está en `docs/lanzar-version.md` del repo privado de la app; `script/publish-public-release.mjs` publica aquí.
