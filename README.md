# XenoRecomp
Cedeño Chronicles – Aplicación independiente para Linux y SteamOS, preparada para Steam Deck.
# Cedeño Chronicles

### Proyecto independiente para Linux, SteamOS y Steam Deck

**Cedeño Chronicles** es una aplicación basada en XenoRecomp, preparada para ejecutar el proyecto en sistemas Linux y SteamOS mediante una aplicación AppImage.

El objetivo es ofrecer una forma práctica de utilizar el proyecto en Steam Deck y otros equipos Linux compatibles.

---

## Características

- Aplicación en formato AppImage.
- Compatibilidad con sistemas Linux x86_64.
- Preparada para SteamOS y Steam Deck.
- Configuración gráfica mediante `xcde.ini`.
- Archivos del juego separados de la aplicación.
- Gestión independiente de datos y partidas guardadas.
- Posibilidad de agregar la aplicación a Steam.

## Requisitos

Para utilizar Cedeño Chronicles necesitas:

- Un Steam Deck o equipo Linux compatible de arquitectura x86_64.
- La aplicación `Cedeño-Chronicles-x86_64.AppImage`.
- Una copia legal del juego en la versión **2.0.0**.
- Los archivos necesarios del juego extraídos y organizados correctamente.

## Instalación

1. Descarga Cedeño Chronicles.
2. Obtén los archivos necesarios de tu propia copia legal del juego, versión 2.0.0.
3. Extrae los archivos requeridos.
4. Organiza los archivos dentro de la carpeta `targets`.
5. Coloca la carpeta `targets` junto a la aplicación AppImage.

La estructura esperada es:

```text
Cedeño Chronicles/
├── Cedeño-Chronicles-x86_64.AppImage
├── xcde.ini
├── targets/
│   ├── exefs/
│   └── romfs/
└── XenoRecompData/
```

**Importante:** la carpeta `targets` debe estar junto a la AppImage para que el lanzador pueda localizar los archivos del juego.

## Cómo ejecutar

1. Haz clic derecho sobre la AppImage.
2. Entra en Propiedades.
3. Activa el permiso de ejecución.
4. Haz doble clic sobre la aplicación para iniciarla.

También puedes agregarla a Steam como juego externo:

1. Abre Steam.
2. Selecciona Agregar un juego.
3. Elige Añadir un juego que no es de Steam.
4. Busca la AppImage.
5. Agrégala a tu biblioteca.

## Configuración gráfica

El proyecto utiliza el archivo `xcde.ini` para las opciones de configuración disponibles.

Entre ellas se encuentran:

- Resolución.
- Escalado FSR.
- Antialiasing SMAA.
- Calidad de escalado.
- Límite de FPS.
- Sincronización vertical.
- Contador de FPS.

Los valores disponibles dependen de la versión del proyecto.

## Datos y partidas guardadas

Cedeño Chronicles puede crear una carpeta llamada `XenoRecompData` junto a la AppImage para almacenar datos y partidas guardadas, siempre que la ubicación permita escribir archivos.

Si no puede escribir en esa ubicación, utiliza la carpeta de datos del usuario configurada por el sistema.

## Portabilidad

Puedes trasladar la carpeta completa de Cedeño Chronicles a otra ubicación.

Para mantener el funcionamiento:

- Conserva la AppImage junto a `targets`.
- No cambies los nombres de las carpetas requeridas.
- Mantén los archivos del juego completos.
- Comprueba que la ubicación permita guardar datos y partidas.

La portabilidad debe comprobarse en cada instalación y dispositivo.

---

## Servicio opcional de instalación y configuración

¿No quieres realizar todo el proceso de preparación y configuración por tu cuenta?

Puedes solicitar nuestro servicio de asistencia técnica por:

# $15 USD

El servicio incluye ayuda para:

- Preparar los archivos de tu propia copia legal del juego.
- Extraer y organizar los archivos necesarios.
- Configurar la actualización correspondiente.
- Preparar Cedeño Chronicles para Steam Deck y SteamOS.
- Comprobar que la instalación funcione correctamente.

### Contacto por Telegram

**@lospolloshermanos9596**

https://t.me/lospolloshermanos9596

### Pago por PayPal

https://paypal.me/vvshopdavid

El servicio consiste en asistencia técnica. El cliente debe proporcionar su propia copia legal del juego. No se venden ni distribuyen archivos originales del juego.

---

## Aviso legal

Cedeño Chronicles es un proyecto independiente y no oficial.

No está afiliado, patrocinado ni respaldado por los titulares de los derechos del juego.

Este repositorio no incluye ni distribuye los archivos originales del juego. Cada usuario debe obtener y utilizar su propia copia legal.

---

## Créditos

**Proyecto:** XenoRecomp  
**Aplicación:** Cedeño Chronicles  
**Desarrollado y preparado para:** Linux, SteamOS y Steam Deck.

**Cedeño Chronicles — Una marca propia, un proyecto propio.**
