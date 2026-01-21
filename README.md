# 🥗 NutriApp

![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=android&logoColor=white)

**NutriApp** es una aplicación nativa de Android diseñada para ayudar a los usuarios a llevar un control detallado de su salud, nutrición e hidratación diaria. Desarrollada con tecnologías modernas de Android y una arquitectura limpia.

## 📱 Funcionalidades Principales

* **Autenticación Segura:** Login y Registro de usuarios mediante **Firebase Authentication**.
* **Gestión de Calorías:**
    * Cálculo automático de TMB (Tasa Metabólica Basal).
    * Seguimiento en tiempo real de calorías consumidas vs. quemadas.
    * Gráficos de progreso diario interactivos.
* **Registro de Alimentos:** Base de datos local y en la nube para guardar el historial de comidas.
* **Tracker de Hidratación:** Contador de vasos de agua con persistencia diaria.
* **Registro de Ejercicio:** Botones rápidos para registrar actividad física y ajustar el balance calórico.
* **Perfil Inteligente:** Cálculo automático de **IMC** (Índice de Masa Corporal) y recomendaciones de proteínas.
* **Sincronización Híbrida:**
    * **Room Database:** Para funcionamiento offline y caché local.
    * **Firestore:** Para respaldo en la nube y recuperación de datos al cambiar de dispositivo.

## 🛠️ Tecnologías y Arquitectura

El proyecto sigue la arquitectura **MVVM (Model-View-ViewModel)** para separar la lógica de negocio de la interfaz de usuario.

* **Lenguaje:** Kotlin.
* **UI:** Jetpack Compose (Material Design 3).
* **Backend:** Firebase (Auth & Firestore).
* **Base de Datos Local:** Room Database.
* **Inyección de Dependencias:** (Si usaste Hilt o manual, menciónalo aquí, si no, omite esta línea).
* **Corrutinas & Flow:** Para manejo de hilos y datos reactivos.

## 📸 Capturas de Pantalla

| Inicio | Registro de Comidas | Perfil |
|:---:|:---:|:---:|
| ![Home](ruta/a/tu/imagen_home.png) | ![Meals](ruta/a/tu/imagen_meals.png) | ![Profile](ruta/a/tu/imagen_profile.png) |
*(Asegúrate de subir tus capturas a una carpeta en el repo y enlazarla aquí)*

## 🚀 Instalación y Configuración

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/](https://github.com/)[TuUsuario]/NutriApp.git
    ```
2.  **Abrir en Android Studio:**
    Abre el proyecto y espera a que Gradle sincronice las dependencias.
3.  **Configuración de Firebase:**
    * Crea un proyecto en [Firebase Console](https://console.firebase.google.com/).
    * Descarga el archivo `google-services.json`.
    * Colócalo en la carpeta `app/` de tu proyecto.
4.  **Ejecutar:**
    Conecta tu dispositivo o usa un emulador y presiona Run.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - mira el archivo [LICENSE.md](LICENSE.md) para detalles.

---
Desarrollado con ❤️ por [Tu Nombre]
