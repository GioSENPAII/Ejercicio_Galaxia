# Aplicación del Sistema Solar

## Descripción
Esta aplicación permite explorar el sistema solar y la galaxia. Los usuarios pueden hacer clic en los nombres de los planetas o el Sol para ver una imagen detallada de cada uno.

## Transiciones entre Actividades
- **Galaxia a Sistema Solar**: Al hacer clic en el `TextView` de la galaxia, se abre `SolarSystemActivity`.
- **Sistema Solar a Planetas**: Al hacer clic en el nombre de un planeta o el Sol, se abre `PlanetActivity`(con esto me refiero a cualquier activity con el nombre del planeta correspondiente) y se muestra la imagen correspondiente.
- **Botón de Regreso**: Cada actividad tiene un botón "Regresar" que permite volver a la actividad anterior.

## Instrucciones para Ejecutar y Probar
1. Clona el repositorio o descarga el código fuente.
2. Abre el proyecto en Android Studio.
3. Conecta un dispositivo Android o inicia un emulador.
4. Haz clic en el botón **Run** (▶️) para compilar y ejecutar la aplicación.
5. Desde la pantalla de la galaxia, haz clic en el enlace para ir al sistema solar.
6. En el sistema solar, haz clic en el nombre de un planeta o el Sol para ver su imagen detallada.
7. Usa el botón "Regresar" para volver a la pantalla anterior.
