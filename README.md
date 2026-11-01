# Serenidad

Aplicación móvil de bienestar emocional desarrollada con Kotlin, Jetpack Compose y Firebase para dispositivos Android.

## Descripción

Serenidad es una aplicación móvil desarrollada como proyecto académico, cuyo propósito es ofrecer herramientas digitales para el bienestar emocional y el seguimiento personal del estado de ánimo.

La aplicación permite registrar estados de ánimo, realizar ejercicios de respiración, acceder a meditaciones guiadas y consultar el progreso personal. Su desarrollo utiliza Kotlin y Jetpack Compose para la construcción de interfaces, siguiendo el patrón de arquitectura MVVM.

Además, integra servicios de Firebase para la autenticación y el almacenamiento de información en la nube.

## Funcionalidades

- Registro del estado de ánimo.
- Seguimiento del estado emocional.
- Ejercicios de respiración.
- Acceso a meditaciones guiadas.
- Consulta del progreso personal.
- Autenticación de usuarios mediante Firebase Authentication.
- Almacenamiento y consulta de información mediante Cloud Firestore.
- Persistencia de datos local mediante Room.
- Interfaz desarrollada con Jetpack Compose.

## Tecnologías utilizadas

- Kotlin
- Android
- Android Studio
- Jetpack Compose
- Material Design 3
- Arquitectura MVVM
- Navigation Compose
- Firebase Authentication
- Cloud Firestore
- Firebase Analytics
- Room
- Gradle Kotlin DSL
- Git y GitHub

## Estructura del proyecto

```text
serenidad/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/
│   │       │   └── com/example/serenidad/
│   │       ├── res/
│   │       └── AndroidManifest.xml
│   └── build.gradle.kts
│
├── gradle/
│   └── wrapper/
│
├── .gitignore
├── build.gradle.kts
├── gradle.properties
├── gradlew
├── gradlew.bat
├── settings.gradle.kts
└── README.md
```

## Instalación local

1. Instala [Android Studio](https://developer.android.com/studio), junto con el SDK de Android correspondiente.

2. Clona este repositorio:

```bash
git clone https://github.com/7Marilu7/serenidad.git
```

3. Abre Android Studio y selecciona **Open** para cargar la carpeta del proyecto `serenidad`.

4. Espera a que Gradle sincronice el proyecto y descargue las dependencias necesarias.

5. Configura Firebase para el proyecto y agrega el archivo `google-services.json` correspondiente dentro de la carpeta `app/`.

6. Configura un emulador Android o conecta un dispositivo físico compatible.

7. Ejecuta la aplicación desde Android Studio utilizando el botón **Run**.

El proyecto tiene configurado un `minSdk` de 26, por lo que requiere Android 8.0 o superior.

## Base de datos

El proyecto utiliza servicios de Firebase y Room para la gestión y persistencia de información.

- **Firebase Authentication:** gestión de autenticación de usuarios.
- **Cloud Firestore:** almacenamiento y consulta de información en la nube.
- **Room:** persistencia de datos en el dispositivo Android.

## Estado del proyecto

Proyecto académico desarrollado como parte de la formación en desarrollo de aplicaciones móviles.

## Autoría

Desarrollado por **María Guadalupe Cruz Paz**.

[GitHub](https://github.com/7Marilu7)
