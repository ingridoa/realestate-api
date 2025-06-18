### Practico 8: Automatización de Pruebas en una API de Inmobiliaria
=====================================
### Grupo N°10: Ingrid Oñate , Victor Diaz, Gabriel Balbontin 
=====================================
#### ¿Qué importancia tiene probar en múltiples entornos de Node.js?
- Probar en múltiples versiones de Node.js (como 16.x, 18.x)
- Es compatible con versiones estables ampliamente usadas.
- Funciona tras actualizaciones del entorno (por ejemplo, si un cliente o servidor cambia de Node 16 a 18).
-  Detecta errores relacionados con el entorno de ejecución (por ejemplo, cambios en APIs internas, comportamiento de fs, soporte de ES modules, etc.).
  
#### ¿Por qué es importante validar la salida de una API desde un workflow?

- Responde correctamente a las rutas esperadas (GET, POST, etc.).
- No rompe nada al hacer un cambio (regresión).
- Cumple con los contratos esperados por el frontend u otros servicios.
  
#### ¿Qué pasos podrías agregar si fueras a hacer despliegue a producción?
Después de los tests exitosos,
Build del proyecto (si aplica)


