# Generador de apuestas — Descargas

Descargas oficiales del **Generador de apuestas** para Windows.

Genera apuestas de La Primitiva, Bonoloto, Euromillones, El Gordo, Lotería Nacional,
Navidad y El Niño, comprueba boletos escaneando el código QR del resguardo y controla
tu cuenta de Loterías y Apuestas del Estado desde la propia aplicación.

## Descargas

| Versión | Instalador | Portable (sin instalar) |
|---|---|---|
| 2.10.0 | [GeneradorDeApuestas-2.10.0-Instalador.exe](https://github.com/erfae/generador-apuestas-releases/releases/download/v2.10.0/GeneradorDeApuestas-2.10.0-Instalador.exe) | [Generador de apuestas-2.10.0-portable.zip](https://github.com/erfae/generador-apuestas-releases/releases/download/v2.10.0/Generador_de_apuestas-2.10.0-portable.zip) |
| 2.10.0 (MSI) | [Generador de apuestas-2.10.0.msi](https://github.com/erfae/generador-apuestas-releases/releases/download/v2.10.0/Generador_de_apuestas-2.10.0.msi) | |
| 2.9.0 | [GeneradorDeApuestas-2.9.0-Instalador.exe](https://github.com/erfae/generador-apuestas-releases/releases/download/v2.9.0/GeneradorDeApuestas-2.9.0-Instalador.exe) | [Generador de apuestas-2.9.0-portable.zip](https://github.com/erfae/generador-apuestas-releases/releases/download/v2.9.0/Generador.de.apuestas-2.9.0-portable.zip) |
| 2.9.0 (MSI) | [Generador de apuestas-2.9.0.msi](https://github.com/erfae/generador-apuestas-releases/releases/download/v2.9.0/Generador.de.apuestas-2.9.0.msi) | |

- **Instalador**: instala la aplicación en `Archivos de programa`, crea el acceso directo y
  permite desinstalarla desde Windows. Pide permisos de administrador.
- **MSI**: se instala desde `Programas y características` y permite desinstalar desde ahí.
- **Portable**: descomprime el zip y ejecuta `Generador de apuestas.exe`; no instala nada.

## Novedades de la 2.10.0

- **IA local gratuita**: la aplicacion analiza el historico real de todas las modalidades y
  decide la combinacion con mas probabilidades de premio. Usa un modelo de lenguaje local
  (gratis) instalado en un servidor propio: `https://web.gadirtv.vip/ia`. Si no hay motor
  disponible, la propia aplicacion resuelve el analisis con su motor estadistico.
- **Reparto de reintegros**: con 10 boletos y reintegros repartidos la probabilidad de
  cobrar alguno pasa del 10 % al 65,1 %.
- **Apostar con la IA**: eliges modalidad, numero de apuestas y si es sencilla o multiple;
  la aplicacion genera las combinaciones y con un boton **COMPRAR** se pagan.
- **Cargar Lotobolsa**: con la tarjeta que ya tienes en la cuenta, con una guardada en el
  PC o introduciendo los datos a mano (preguntando si se quieren guardar). Con PayPal se
  abre la pantalla de pago en el navegador.
- **Camara en cuadrado** para el escaner de boletos, con el motivo real si no responde.
- Fuente e iconos mas grandes; el saldo se actualiza solo al comprar o recargar.

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
