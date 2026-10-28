# Limpieza TV y Radio

Asistente interactivo que, según las respuestas, arma la guía paso a paso para limpiar una TV (Google TV, Android TV o Fire TV), un TV Box o stick, o un radio de auto (Android o Android Automotive) desde un computador con Windows o Mac.

- Página única estática: `index.html` (sin dependencias ni build; solo carga tipografías de Google Fonts).
- El avance y las respuestas de cada visitante se guardan solo en su navegador (localStorage).
- Los comandos de TV se apoyan en el proyecto abierto [CleanYourTV](https://github.com/Gathin23/cleanyourtv). Los de radio de auto usan adb estándar.

## Despliegue

Proyecto Vercel `guia-radio-android` (sin framework, sin build). Cada cambio en `main` se publica solo.

La versión anterior (guía de diagnóstico para radios Android 2 DIN) quedó en el historial de Git.
