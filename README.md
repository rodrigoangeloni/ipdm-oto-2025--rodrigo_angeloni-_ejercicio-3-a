# 📱 Jetpack Compose - Ejercicio 3A

[![Kotlin](https://img.shields.io/badge/Kotlin-1.9.0-blue.svg)](https://kotlinlang.org)
[![Compose](https://img.shields.io/badge/Jetpack%20Compose-1.5.0-orange.svg)](https://developer.android.com/jetpack/compose)

Aplicación Android que muestra un artículo sobre Jetpack Compose, desarrollada como parte del curso IPDM 2025.

<div align="center">
  <img src="https://github.com/rodrigoangeloni/ipdm-oto-2025--rodrigo_angeloni-_ejercicio-3-a/raw/main/app/src/main/res/drawable-nodpi/captura_ejercicio_3_a.png?raw=true" width="300" alt="Captura de pantalla">
</div>

## 🚀 Características principales
- Interfaz 100% declarativa con Jetpack Compose
- Diseño responsive para todos los dispositivos
- Imagen de cabecera adaptable
- Texto justificado con tipografía accesible
- Integración con Material Design 3

## 🛠 Estructura técnica
```kotlin
@Composable
fun ComposeArticleScreen() {
    Column {
        Image(
            painter = painterResource(R.drawable.bg_compose_background),
            contentDescription = "Header",
            modifier = Modifier.fillMaxWidth()
        )
        // Contenido del artículo...
    }
}
