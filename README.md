# Menú VR con Meta XR All-in-One SDK

Este proyecto implementa un menú principal en realidad virtual utilizando el **Meta XR All-in-One SDK** en Unity 2022.3.42f1. Es una interfaz pensada para Oculus Quest 2/3, que permite navegar entre pantallas de inicio, opciones y cerrar la aplicación, todo en un entorno 3D inmersivo.

## Funcionalidades principales

- 🎮 **Inicio de juego**: Botón "Start" que carga la escena principal del juego (`EjemploUI`).
- ⚙️ **Opciones**: Botón "Options" que oculta el menú principal y muestra un canvas de configuración.
- 🚪 **Salir**: Botón "Exit" que cierra la aplicación y muestra un mensaje en consola.
- 🔁 **Volver al menú**: Desde el menú de opciones, se puede regresar al menú principal.

La interfaz está construida utilizando **FlatUnityCanvas** provistos por el SDK, aprovechando los Building Blocks nativos del paquete de Meta para VR.

## Requisitos

- Unity **2022.3.42f1**
- Meta XR All-in-One SDK (disponible desde el **Meta XR Hub** o importando desde el Unity Package Manager)
- Dispositivo Meta Quest 2 o 3 (opcional para pruebas en visor)

## Instalación

1. **Clonar el repositorio**:

   ```bash
   git clone https://github.com/tuusuario/tu-repo.git
   ```

2. **Abrir en Unity Hub**:
   - Abrí Unity Hub.
   - Click en **"Add"**.
   - Seleccioná la carpeta del proyecto que clonaste.
   - Asegurate de usar la versión **Unity 2022.3.42f1**.

3. **Importar el Meta XR All-in-One SDK**:
   - Desde Unity, abrí el **Package Manager**.
   - Seleccioná "My Assets" o usá el archivo `.unitypackage` provisto por Meta.
   - Importá el paquete completo.

4. **Configurar XR Plugin** (si no está listo):
   - Ir a `Edit > Project Settings > XR Plugin Management`.
   - Activar **OpenXR** para Android.
   - En "OpenXR Features", asegurate de habilitar el plugin de Meta Quest.

5. **Ejecutar la escena**:
   - Abrí la escena `Menulinicio`.
   - Ejecutala en modo Play o compilá el APK para Quest.

## Uso en visor

Si se ejecuta en un Quest:
- Usá los controles para interactuar con los botones.
- Asegurate de que el `OVRCameraRig` esté bien posicionado y habilitado.

## Créditos

Este proyecto fue desarrollado como ejercicio práctico de VR con interfaz en Unity, orientado a la integración de menús interactivos con el **Meta XR All-in-One SDK**.
