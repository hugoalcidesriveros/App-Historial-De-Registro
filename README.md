# 🎮 Historial de Partidas - PWA

[![Firebase](https://img.shields.io/badge/Firebase-Backend-orange)](https://firebase.google.com/)
[![PWA](https://img.shields.io/badge/PWA-Instalable-blueviolet)](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)
[![Realtime](https://img.shields.io/badge/Datos-Tiempo%20Real-green)](https://firebase.google.com/products/realtime-database)

Una Progressive Web App para registrar y seguir el historial de partidas entre amigos, con sincronización en tiempo real.

## 🌐 Demo en Producción
**URL oficial:** 🛠️ Demo [https://historialpartidas.web.app]

## ✨ Características Principales

- **📱 PWA Instalable**: Funciona como app nativa en móviles y desktop
- **⚡ Tiempo Real**: Sincronización instantánea entre dispositivos
- **🔐 Acceso Controlado**: Solo usuarios autorizados pueden modificar datos
- **📊 Historial Persistente**: Datos almacenados en la nube
- **📴 Funcionalidad Offline**: Funciona sin conexión a internet

## 🛠️ Stack Tecnológico

| Tecnología | Uso |
|------------|-----|
| **Firebase Realtime Database** | Base de datos en tiempo real |
| **Firebase Hosting** | Deployment y hosting de la PWA |
| **Firebase Authentication** | Control de acceso y seguridad |
| **JavaScript** | Lógica de la aplicación |
| **HTML & CSS** | UI/UX y responsive design |
| **Service Workers** | Funcionalidad offline y caching |

## 🏗️ Arquitectura del Proyecto
```
src/
├── index.html # Página principal
├── manifest.json # Configuración PWA
├── sw.js # Service Worker
├── css/
│ └── styles.css # Estilos principales
├── js/
│ ├── app.js # Lógica principal de la app
│ ├── firebase.js # Configuración e inicialización
│ ├── auth.js # Manejo de autenticación
│ └── database.js # Operaciones con la base de datos
└── images/ # Íconos y assets visuales
```

## 🔐 Sistema de Seguridad Implementado

La aplicación cuenta con reglas de seguridad robustas en Firebase:

## 📊 Estructura de Datos

```javascript
{
  "partidas": {
    "partida_001": {
      "jugador": "nombre_jugador",
      "juego": "nombre_del_juego",
      "puntaje": 150,
      "resultado": "victoria",
      "fecha": "2024-03-20T18:30:00Z",
      "uid": "user_id_del_creador"
    }
  }
}
```

🚀 Flujo de Uso
Acceso: Los usuarios ingresan via invitación

Autenticación: Login mediante Firebase Auth

Registro: Creación de nuevas partidas

Visualización: Consulta del historial en tiempo real

Sincronización: Datos actualizados across dispositivos

📊 Estructura de Datos
```javascript
{
  "partidas": {
    "partida_001": {
      "jugador": "nombre_jugador",
      "juego": "nombre_del_juego",
      "puntaje": 150,
      "resultado": "victoria",
      "fecha": "2024-03-20T18:30:00Z",
      "uid": "user_id_del_creador"
    }
  }
}

```
🔧 Configuración para Desarrollo
Clonar repositorio

Crear archivo .env con configuración de Firebase

Instalar dependencias (si aplica)

Ejecutar servidor local

Realizar pruebas con proyecto de Firebase de desarrollo

👥 Audience Objetivo
Grupo cerrado de amigos

- **Comunidades gaming pequeñas

- **Sesiones de juego privadas

🎯 Próximas Mejoras
Sistema de rankings y líderboards

- **Estadísticas avanzadas por jugador

- **Notificaciones push para nuevas partidas

- **Modo torneo con fases eliminatorias

👨‍💻 Desarrollado por
Hugo Alcides Riveros
📧 [Alcides.mza@gmail.com]



