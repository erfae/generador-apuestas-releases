# Generador de apuestas — Descargas

Descargas oficiales del **Generador de apuestas** para Windows.

Genera apuestas de La Primitiva, Bonoloto, Euromillones, El Gordo, Lotería Nacional,
Navidad y El Niño, comprueba boletos escaneando el código QR del resguardo y controla
tu cuenta de Loterías y Apuestas del Estado desde la propia aplicación.

## Descargas

| Versión | Instalador | Portable (sin instalar) |
|---|---|---|
| 2.8.2 | [GeneradorDeApuestas-2.8.2-Instalador.exe](https://github.com/erfae/generador-apuestas-releases/releases/download/v2.8.2/GeneradorDeApuestas-2.8.2-Instalador.exe) | [Generador de apuestas-2.8.2-portable.zip](https://github.com/erfae/generador-apuestas-releases/releases/download/v2.8.2/Generador.de.apuestas-2.8.2-portable.zip) |
| 2.8.2 (MSI) | [Generador de apuestas-2.8.2.msi](https://github.com/erfae/generador-apuestas-releases/releases/download/v2.8.2/Generador.de.apuestas-2.8.2.msi) | |

- **Instalador**: instala la aplicación en `Archivos de programa`, crea el acceso directo y
  permite desinstalarla desde Windows. Pide permisos de administrador.
- **MSI**: se instala desde `Programas y características` y permite desinstalar desde ahí.
- **Portable**: descomprime el zip y ejecuta `Generador de apuestas.exe`; no instala nada.

## Novedades de la 2.8.0

- **Acceso a SELAE dentro de la aplicación**: el login con la web oficial se resuelve con un
  navegador interno que no abre ninguna ventana; si SELAE pide un código por SMS, la app lo
  pide en un diálogo y lo envía sola.
- **Pantallas propias con los controles reales de la web**: la pantalla de acceso y la tabla
  de apuestas se construyen con los campos, botones y textos que usa SELAE.
- **Escaneo de boletos arreglado**: el lector de QR prueba recortes, escalas, contraste e
  inclinaciones (sirve con fotos torcidas) y entiende el código de resguardo de SELAE, con
  sus números, reintegro y joker.
- **Tabla de apuestas de la cuenta**: juego, origen, estado, fechas, precio y números, tal
  y como aparecen en el listado de SELAE.

## Requisitos

- Windows 10 o superior (64 bits).
- El instalador incluye el entorno de Java, no hace falta instalar nada más.
- Para leer el QR con la cámara hace falta el complemento de captura de vídeo; la app te
  avisa si falta.

## Más información

- Código fuente: <https://github.com/erfae/loteria-app> (privado).
