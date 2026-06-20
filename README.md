# Paicor

Asistente inteligente para Android que automatiza tareas, gestiona
WhatsApp, busca empleo automáticamente y responde preguntas con IA
local — todo sin conexión a internet.

## Funcionalidades

**Automatizaciones**
Crea tareas repetitivas con fecha, hora y anticipación. El asistente
las ejecuta automáticamente y te notifica el resultado.

**Chat con IA local**
Asistente conversacional con Qwen2.5 (modelo de lenguaje ejecutado
en el dispositivo). Responde preguntas, mantiene contexto y funciona
sin internet.

**WhatsApp Web**
Conecta tu WhatsApp para leer y enviar mensajes desde la app.
Respuestas automáticas configurables por contacto, con modos:
libre, asistido y automático.

**Reconocimiento de voz**
Entrada por voz con ecualizador visual en tiempo real. Ideal para
usar manos libres mientras manejas o trabajas.

**Búsqueda de empleo inteligente**
Scrapea LinkedIn, Computrabajo y Elempleo cada 12 horas. Filtra
automáticamente las ofertas donde el perfil del postulante cumple
todos los requisitos usando IA. Notifica solo las que realmente
aplican.

**Notificaciones**
Historial de ofertas nuevas y notificaciones push con indicador
de leído.

## Tecnologías

| Categoría | Tecnologías |
|---|---|
| Lenguaje | Kotlin |
| UI | Jetpack Compose, Material 3, Navigation Compose |
| Arquitectura | MVVM, Hilt (DI), Repository Pattern |
| Base de datos | Room, SQLCipher |
| Red | Retrofit, OkHttp |
| Asincronía | Coroutines, Flow, StateFlow |
| Background | WorkManager, Service |
| IA local | Qwen2.5 (modelo on-device) |
| Voz | Android SpeechRecognizer |
| Almacenamiento | DataStore, EncryptedSharedPreferences |
| Seguridad | Android KeyStore, AES-256 GCM, SQLCipher |
| Compilación | KSP, ProGuard / R8 |

## Repositorios relacionados

- [Bitmapcore](https://github.com/corportafolio/Bitmapcore) — Explorador blockchain Bitcoin Ordinals
- [Profactura](https://github.com/corportafolio/Profactura) — Facturación automatizada con códigos personalizados

## Contacto

- GitHub: [@corportafolio](https://github.com/corportafolio)
- X: [@bitmapcorp](https://x.com/bitmapcorp) · [@candelacorp__](https://x.com/candelacorp__)
- Email: corportafolio@gmail.com
