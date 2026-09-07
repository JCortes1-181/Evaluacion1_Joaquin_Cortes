# Implementación de Lógica en MainActivity

Este plan detalla los pasos para agregar la funcionalidad a los botones de `MainActivity` para que abran una pantalla de registro.

## Cambios Propuestos

### Actividades

#### [MODIFY] [MainActivity.java](file:///C:/Users/Alumnos/Desktop/ComidaCompartida_Joaquin_Cortes/app/src/main/java/com/example/comidacompartida_joaquin_cortes/MainActivity.java)
- Vincular los botones `BTN_Donador` y `BTN_Receptor` del layout.
- Configurar `OnClickListener` para cada botón.
- Implementar un `Intent` explícito para navegar a `RegistroActivity`.

#### [NEW] [RegistroActivity.java](file:///C:/Users/Alumnos/Desktop/ComidaCompartida_Joaquin_Cortes/app/src/main/java/com/example/comidacompartida_joaquin_cortes/RegistroActivity.java)
- Crear una actividad básica que servirá como destino del registro.

#### [NEW] [activity_registro.xml](file:///C:/Users/Alumnos/Desktop/ComidaCompartida_Joaquin_Cortes/app/src/main/res/layout/activity_registro.xml)
- Crear un layout simple para la pantalla de registro.

### Configuración

#### [MODIFY] [AndroidManifest.xml](file:///C:/Users/Alumnos/Desktop/ComidaCompartida_Joaquin_Cortes/app/src/main/AndroidManifest.xml)
- Registrar `RegistroActivity` para que el sistema pueda encontrarla al iniciar el Intent.

## Plan de Verificación

### Verificación Manual
- Ejecutar la aplicación.
- Presionar el botón "Ingresar como Donador" y verificar que se abre la pantalla de registro.
- Presionar el botón "Ingresar como Receptor" y verificar que se abre la pantalla de registro.
