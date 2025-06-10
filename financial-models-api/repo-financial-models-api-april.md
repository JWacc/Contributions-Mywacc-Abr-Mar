# Informe de contribuciones – financial-models-api

## Vista general
- Total de horas estimadas: 32.6 h
- Total de commits: 47
- Total de PRs: 1
- Total de issues: 0

## Detalles de contribuciones

### Commits (Agrupados por Sesiones de Trabajo)

#### Sesión 1: 5 Commits Consecutivos
- **Período:** 17:07 - 18:09
- **Tiempo máximo disponible:** 3.0 h
- **Tiempo estimado total:** 3.2 h

##### Commit: a82117db
- Fecha: 2025-04-14T17:07:05Z
- Rama: dataScienceBranch
- Mensaje: updating send mailing info
- Cambios: +320/-2 líneas en 3 archivos
- Estimación:
  - Implementación: 0.49 h
  - Testing: 0.29 h
  - Debug: 0.19 h
  - **Total estimado**: 0.97 h
  - ⏰ **Restricción temporal:** Limited by session time: 3.0h
- URL: https://github.com/MyWacc/financial-models-api/commit/a82117dbacfa5d95c3e69798bd83227cc09919ac

##### Commit: 2c9539ef
- Fecha: 2025-04-14T17:44:27Z
- Rama: dataScienceBranch
- Mensaje: Mejorado endpoint de confirmación de pago para verificar suscripciones
- Cambios: +39/-9 líneas en 1 archivos
- Estimación:
  - Implementación: 0.16 h
  - Testing: 0.1 h
  - Debug: 0.06 h
  - **Total estimado**: 0.32 h
  - ⏰ **Restricción temporal:** Limited by session time: 3.0h
- URL: https://github.com/MyWacc/financial-models-api/commit/2c9539efe7abbc9420f788c6d4cf50ec040e2b5d

##### Commit: b686d661
- Fecha: 2025-04-14T17:58:53Z
- Rama: dataScienceBranch
- Mensaje: getUserSuscription
- Cambios: +22/-39 líneas en 1 archivos
- Estimación:
  - Implementación: 0.24 h
  - Testing: 0.15 h
  - Debug: 0.1 h
  - **Total estimado**: 0.49 h
  - ⏰ **Restricción temporal:** Limited by session time: 3.0h
- URL: https://github.com/MyWacc/financial-models-api/commit/b686d66174018a1986681ffa47e3f1e35117d477

##### Commit: 7bfbfc53
- Fecha: 2025-04-14T18:05:20Z
- Rama: dataScienceBranch
- Mensaje: Implementado sistema de autenticación JWT para validar estado de pago
- Cambios: +294/-10 líneas en 5 archivos
- Estimación:
  - Implementación: 0.58 h
  - Testing: 0.35 h
  - Debug: 0.23 h
  - **Total estimado**: 1.17 h
  - ⏰ **Restricción temporal:** Limited by session time: 3.0h
- URL: https://github.com/MyWacc/financial-models-api/commit/7bfbfc535d799858ca5e900342a8f5c73e0f8ed9

##### Commit: e8e3a18b
- Fecha: 2025-04-14T18:09:10Z
- Rama: dataScienceBranch
- Mensaje: Agregada dependencia PyJWT para autenticación
- Cambios: +2/-1 líneas en 1 archivos
- Estimación:
  - Implementación: 0.12 h
  - Testing: 0.07 h
  - Debug: 0.05 h
  - **Total estimado**: 0.25 h
  - ⏰ **Restricción temporal:** Limited by session time: 3.0h
- URL: https://github.com/MyWacc/financial-models-api/commit/e8e3a18bfa4a21dbced4de6f2f7e79eb3ea0388c

#### Sesión 2: 7 Commits Consecutivos
- **Período:** 22:30 - 01:37
- **Tiempo máximo disponible:** 5.1 h
- **Tiempo estimado total:** 5.2 h

##### Commit: 30710d69
- Fecha: 2025-04-14T22:30:00Z
- Rama: dataScienceBranch
- Mensaje: Modificado endpoint getUserSubscription para verificar suscripciones directamente en Stripe por email
- Cambios: +61/-7 líneas en 1 archivos
- Estimación:
  - Implementación: 0.42 h
  - Testing: 0.25 h
  - Debug: 0.17 h
  - **Total estimado**: 0.84 h
  - ⏰ **Restricción temporal:** Limited by session time: 5.1h
- URL: https://github.com/MyWacc/financial-models-api/commit/30710d69ebc7b8e0d78a2b8513d8209d8845fcda

##### Commit: 0e174887
- Fecha: 2025-04-14T22:50:27Z
- Rama: dataScienceBranch
- Mensaje: Corregido error en confirmStripePayment para manejar correctamente las excepciones y verificar suscripciones
- Cambios: +30/-2 líneas en 1 archivos
- Estimación:
  - Implementación: 0.36 h
  - Testing: 0.22 h
  - Debug: 0.15 h
  - **Total estimado**: 0.73 h
  - ⏰ **Restricción temporal:** Limited by session time: 5.1h
- URL: https://github.com/MyWacc/financial-models-api/commit/0e17488759c58aceea1656e97ce631f922ddaadf

##### Commit: 407e0e33
- Fecha: 2025-04-14T23:00:18Z
- Rama: dataScienceBranch
- Mensaje: Eliminada referencia a User.PLAN_ACTIVE y modificado confirmStripePayment para mostrar todos los atributos sin actualizar el usuario
- Cambios: +23/-10 líneas en 1 archivos
- Estimación:
  - Implementación: 0.28 h
  - Testing: 0.17 h
  - Debug: 0.11 h
  - **Total estimado**: 0.56 h
  - ⏰ **Restricción temporal:** Limited by session time: 5.1h
- URL: https://github.com/MyWacc/financial-models-api/commit/407e0e33e90c7653ab6e4d621849e1ad267f577d

##### Commit: 789d2001
- Fecha: 2025-04-15T00:24:29Z
- Rama: dataScienceBranch
- Mensaje: Mejorado el endpoint confirmStripePayment para manejar correctamente las suscripciones y actualizar el usuario
- Cambios: +95/-27 líneas en 1 archivos
- Estimación:
  - Implementación: 0.56 h
  - Testing: 0.34 h
  - Debug: 0.22 h
  - **Total estimado**: 1.12 h
  - ⏰ **Restricción temporal:** Limited by session time: 5.1h
- URL: https://github.com/MyWacc/financial-models-api/commit/789d2001d75ae425e689c764569dcae001ee1951

##### Commit: 191b33b9
- Fecha: 2025-04-15T00:52:57Z
- Rama: dataScienceBranch
- Mensaje: Añadidos logs detallados para depurar el flujo de verificación de suscripción y middleware JWT
- Cambios: +76/-2 líneas en 2 archivos
- Estimación:
  - Implementación: 0.42 h
  - Testing: 0.25 h
  - Debug: 0.17 h
  - **Total estimado**: 0.84 h
  - ⏰ **Restricción temporal:** Limited by session time: 5.1h
- URL: https://github.com/MyWacc/financial-models-api/commit/191b33b9b76d79105dd2fb5d0b462a8cd1635683

##### Commit: a588dfc1
- Fecha: 2025-04-15T01:15:18Z
- Rama: dataScienceBranch
- Mensaje: Añadidos logs detallados para depurar el flujo de verificación de suscripción
- Cambios: +51/-4 líneas en 1 archivos
- Estimación:
  - Implementación: 0.42 h
  - Testing: 0.25 h
  - Debug: 0.17 h
  - **Total estimado**: 0.84 h
  - ⏰ **Restricción temporal:** Limited by session time: 5.1h
- URL: https://github.com/MyWacc/financial-models-api/commit/a588dfc1f8e1785e3a2a2a3997ee811a2a6d925d

##### Commit: fd0e91ce
- Fecha: 2025-04-15T01:37:08Z
- Rama: dataScienceBranch
- Mensaje: Corregido error en confirmStripePayment: eliminada referencia a request.body después de leer request.data
- Cambios: +1/-1 líneas en 1 archivos
- Estimación:
  - Implementación: 0.12 h
  - Testing: 0.07 h
  - Debug: 0.05 h
  - **Total estimado**: 0.25 h
  - ⏰ **Restricción temporal:** Limited by session time: 5.1h
- URL: https://github.com/MyWacc/financial-models-api/commit/fd0e91ce936ccf792e8783a88467da1ae9e70f63

#### Sesión 3: 16 Commits Consecutivos
- **Período:** 18:34 - 22:48
- **Tiempo máximo disponible:** 6.2 h
- **Tiempo estimado total:** 7.3 h

##### Commit: fe2dd22d
- Fecha: 2025-04-26T18:34:12Z
- Rama: dataScienceBranch
- Mensaje: Implementación del servicio OCR para extracción de información financiera de documentos PDF
- Cambios: +798/-1 líneas en 15 archivos
- Estimación:
  - Implementación: 0.65 h
  - Testing: 0.39 h
  - Debug: 0.26 h
  - **Total estimado**: 1.31 h
  - ⏰ **Restricción temporal:** Limited by session time: 6.2h
- URL: https://github.com/MyWacc/financial-models-api/commit/fe2dd22df2f84abc76d1a5da0ac525610eb37474

##### Commit: 85a71208
- Fecha: 2025-04-26T18:41:51Z
- Rama: dataScienceBranch
- Mensaje: Implementación del servicio de carga de archivos a Azure Blob Storage
- Cambios: +174/-6 líneas en 7 archivos
- Estimación:
  - Implementación: 0.35 h
  - Testing: 0.21 h
  - Debug: 0.14 h
  - **Total estimado**: 0.7 h
  - ⏰ **Restricción temporal:** Limited by session time: 6.2h
- URL: https://github.com/MyWacc/financial-models-api/commit/85a7120821a68c50df132c39be45db3b374e19b6

##### Commit: dbded2ab
- Fecha: 2025-04-26T18:46:02Z
- Rama: dataScienceBranch
- Mensaje: Implementación de WaccBot con Azure AI Projects como servicio principal y WaccBot original como respaldo
- Cambios: +229/-57 líneas en 4 archivos
- Estimación:
  - Implementación: 0.42 h
  - Testing: 0.25 h
  - Debug: 0.17 h
  - **Total estimado**: 0.83 h
  - ⏰ **Restricción temporal:** Limited by session time: 6.2h
- URL: https://github.com/MyWacc/financial-models-api/commit/dbded2ab9083a20352f689c761585abf61bb1e5c

##### Commit: 1bc7ae72
- Fecha: 2025-04-26T18:48:54Z
- Rama: dataScienceBranch
- Mensaje: Actualización del archivo .env.example con todas las variables de entorno necesarias
- Cambios: +49/-9 líneas en 1 archivos
- Estimación:
  - Implementación: 0.18 h
  - Testing: 0.11 h
  - Debug: 0.07 h
  - **Total estimado**: 0.36 h
  - ⏰ **Restricción temporal:** Limited by session time: 6.2h
- URL: https://github.com/MyWacc/financial-models-api/commit/1bc7ae7278bd0cb98493ed199dbbd83fef02ad85

##### Commit: f847d3ba
- Fecha: 2025-04-26T19:31:48Z
- Rama: dataScienceBranch
- Mensaje: Fix: Importar FileUploadSerializer y BlobResponseSerializer en views.py
- Cambios: +1/-1 líneas en 1 archivos
- Estimación:
  - Implementación: 0.12 h
  - Testing: 0.07 h
  - Debug: 0.05 h
  - **Total estimado**: 0.25 h
  - ⏰ **Restricción temporal:** Limited by session time: 6.2h
- URL: https://github.com/MyWacc/financial-models-api/commit/f847d3bac224c435ff09b5ad0602b54f471c03c1

##### Commit: 9fdbf0f1
- Fecha: 2025-04-26T20:04:21Z
- Rama: dataScienceBranch
- Mensaje: Deshabilitar temporalmente la verificación de plan activo en el middleware de pago
- Cambios: +8/-7 líneas en 1 archivos
- Estimación:
  - Implementación: 0.12 h
  - Testing: 0.07 h
  - Debug: 0.05 h
  - **Total estimado**: 0.25 h
  - ⏰ **Restricción temporal:** Limited by session time: 6.2h
- URL: https://github.com/MyWacc/financial-models-api/commit/9fdbf0f160355738d4553f63af02f95936110fdb

##### Commit: 15f47ab4
- Fecha: 2025-04-26T20:10:29Z
- Rama: dataScienceBranch
- Mensaje: Agregar ruta para Waccy manteniendo compatibilidad con WaccBot
- Cambios: +1/-0 líneas en 1 archivos
- Estimación:
  - Implementación: 0.12 h
  - Testing: 0.07 h
  - Debug: 0.05 h
  - **Total estimado**: 0.25 h
  - ⏰ **Restricción temporal:** Limited by session time: 6.2h
- URL: https://github.com/MyWacc/financial-models-api/commit/15f47ab49bd21c7c3fe5f30b877db789e57c3abb

##### Commit: 093f7d39
- Fecha: 2025-04-26T20:13:03Z
- Rama: dataScienceBranch
- Mensaje: Corregir autenticación de Azure AI Projects para Waccy
- Cambios: +1/-2 líneas en 1 archivos
- Estimación:
  - Implementación: 0.12 h
  - Testing: 0.07 h
  - Debug: 0.05 h
  - **Total estimado**: 0.25 h
  - ⏰ **Restricción temporal:** Limited by session time: 6.2h
- URL: https://github.com/MyWacc/financial-models-api/commit/093f7d39ac300a9000783f4a4fba9d99eede1382

##### Commit: fd57ecb3
- Fecha: 2025-04-26T20:40:35Z
- Rama: dataScienceBranch
- Mensaje: Corregir autenticación de Azure AI Projects y deshabilitar verificación de token en upload-file-to-blob
- Cambios: +16/-9 líneas en 1 archivos
- Estimación:
  - Implementación: 0.12 h
  - Testing: 0.07 h
  - Debug: 0.05 h
  - **Total estimado**: 0.25 h
  - ⏰ **Restricción temporal:** Limited by session time: 6.2h
- URL: https://github.com/MyWacc/financial-models-api/commit/fd57ecb349cfa48edad69df0f78d20d158e917d1

##### Commit: 540a79a0
- Fecha: 2025-04-26T20:44:19Z
- Rama: dataScienceBranch
- Mensaje: Implementar nuevo servicio WaccBot con conexión directa al Financial-Agent RAG
- Cambios: +320/-3 líneas en 2 archivos
- Estimación:
  - Implementación: 0.44 h
  - Testing: 0.26 h
  - Debug: 0.17 h
  - **Total estimado**: 0.87 h
  - ⏰ **Restricción temporal:** Limited by session time: 6.2h
- URL: https://github.com/MyWacc/financial-models-api/commit/540a79a04ace3e7322284272b641f3a589741624

##### Commit: e46cee6d
- Fecha: 2025-04-26T21:02:19Z
- Rama: dataScienceBranch
- Mensaje: Implementar soporte multiidioma en WaccBot
- Cambios: +19/-2 líneas en 1 archivos
- Estimación:
  - Implementación: 0.15 h
  - Testing: 0.09 h
  - Debug: 0.06 h
  - **Total estimado**: 0.29 h
  - ⏰ **Restricción temporal:** Limited by session time: 6.2h
- URL: https://github.com/MyWacc/financial-models-api/commit/e46cee6d030185790c2c5b75bbf8df94b322a94f

##### Commit: a306b83b
- Fecha: 2025-04-26T21:55:28Z
- Rama: dataScienceBranch
- Mensaje: Fix Azure Blob Storage authentication issue and improve error handling
- Cambios: +27/-4 líneas en 2 archivos
- Estimación:
  - Implementación: 0.16 h
  - Testing: 0.09 h
  - Debug: 0.06 h
  - **Total estimado**: 0.31 h
  - ⏰ **Restricción temporal:** Limited by session time: 6.2h
- URL: https://github.com/MyWacc/financial-models-api/commit/a306b83bf6ead30a3b65b96c475c0c1f9d3f8ae1

##### Commit: c452e9dc
- Fecha: 2025-04-26T22:17:04Z
- Rama: dataScienceBranch
- Mensaje: Mejorar logs y manejo de errores en la subida de archivos a Azure Blob Storage
- Cambios: +105/-17 líneas en 1 archivos
- Estimación:
  - Implementación: 0.31 h
  - Testing: 0.19 h
  - Debug: 0.13 h
  - **Total estimado**: 0.63 h
  - ⏰ **Restricción temporal:** Limited by session time: 6.2h
- URL: https://github.com/MyWacc/financial-models-api/commit/c452e9dc0ac0ee7dfb1b990931b85eb0dbe1205e

##### Commit: f6c14945
- Fecha: 2025-04-26T22:17:39Z
- Rama: dataScienceBranch
- Mensaje: Actualizar clave de Azure Blob Storage con la clave correcta
- Cambios: +2/-2 líneas en 1 archivos
- Estimación:
  - Implementación: 0.12 h
  - Testing: 0.07 h
  - Debug: 0.05 h
  - **Total estimado**: 0.25 h
  - ⏰ **Restricción temporal:** Limited by session time: 6.2h
- URL: https://github.com/MyWacc/financial-models-api/commit/f6c149454ec9ac598d22370d11db72b4d12a2b3e

##### Commit: c9f05d94
- Fecha: 2025-04-26T22:42:40Z
- Rama: dataScienceBranch
- Mensaje:  updating core
- Cambios: +2/-2 líneas en 1 archivos
- Estimación:
  - Implementación: 0.12 h
  - Testing: 0.07 h
  - Debug: 0.05 h
  - **Total estimado**: 0.25 h
  - ⏰ **Restricción temporal:** Limited by session time: 6.2h
- URL: https://github.com/MyWacc/financial-models-api/commit/c9f05d9417780cbd927803986429a0dcddd43177

##### Commit: d70241c7
- Fecha: 2025-04-26T22:48:19Z
- Rama: dataScienceBranch
- Mensaje: Añadir logs detallados para depurar problemas de autenticación con Azure Blob Storage
- Cambios: +35/-3 líneas en 1 archivos
- Estimación:
  - Implementación: 0.12 h
  - Testing: 0.07 h
  - Debug: 0.05 h
  - **Total estimado**: 0.25 h
  - ⏰ **Restricción temporal:** Limited by session time: 6.2h
- URL: https://github.com/MyWacc/financial-models-api/commit/d70241c7ab5eabab2540e6438fbe6be834a6e65e

#### Sesión 4: 7 Commits Consecutivos
- **Período:** 14:51 - 17:26
- **Tiempo máximo disponible:** 4.6 h
- **Tiempo estimado total:** 4.7 h

##### Commit: c7b7f21e
- Fecha: 2025-04-28T14:51:10Z
- Rama: dataScienceBranch
- Mensaje: updating
- Cambios: +7/-7 líneas en 6 archivos
- Estimación:
  - Implementación: 0.18 h
  - Testing: 0.11 h
  - Debug: 0.07 h
  - **Total estimado**: 0.37 h
  - ⏰ **Restricción temporal:** Limited by session time: 4.6h
- URL: https://github.com/MyWacc/financial-models-api/commit/c7b7f21e51d659a71ae26c553f79aca844c5fa1f

##### Commit: 7506787a
- Fecha: 2025-04-28T15:49:49Z
- Rama: dataScienceBranch
- Mensaje: Mejora la autenticación de Azure para OCR Service
- Cambios: +385/-4 líneas en 5 archivos
- Estimación:
  - Implementación: 0.92 h
  - Testing: 0.55 h
  - Debug: 0.37 h
  - **Total estimado**: 1.85 h
  - ⏰ **Restricción temporal:** Limited by session time: 4.6h
- URL: https://github.com/MyWacc/financial-models-api/commit/7506787ad41d9ea5377c9f4e4be253aff4d22d80

##### Commit: 17f80ac1
- Fecha: 2025-04-28T15:59:11Z
- Rama: dataScienceBranch
- Mensaje: Actualiza .env.example con configuración de autenticación de Azure
- Cambios: +12/-0 líneas en 1 archivos
- Estimación:
  - Implementación: 0.15 h
  - Testing: 0.09 h
  - Debug: 0.06 h
  - **Total estimado**: 0.31 h
  - ⏰ **Restricción temporal:** Limited by session time: 4.6h
- URL: https://github.com/MyWacc/financial-models-api/commit/17f80ac1a80ceb032be48d149713a728fee492a0

##### Commit: e8366c6c
- Fecha: 2025-04-28T16:01:42Z
- Rama: dataScienceBranch
- Mensaje: Corrige importación circular en api/utils.py
- Cambios: +5/-7 líneas en 1 archivos
- Estimación:
  - Implementación: 0.15 h
  - Testing: 0.09 h
  - Debug: 0.06 h
  - **Total estimado**: 0.31 h
  - ⏰ **Restricción temporal:** Limited by session time: 4.6h
- URL: https://github.com/MyWacc/financial-models-api/commit/e8366c6c7791dda56deabad5d49c5bdf49cbfa85

##### Commit: 56b01607
- Fecha: 2025-04-28T16:09:39Z
- Rama: dataScienceBranch
- Mensaje: Corrige error 'BlobClient' object has no attribute 'generate_sas' y mejora manejo de errores
- Cambios: +78/-12 líneas en 2 archivos
- Estimación:
  - Implementación: 0.6 h
  - Testing: 0.36 h
  - Debug: 0.24 h
  - **Total estimado**: 1.2 h
  - ⏰ **Restricción temporal:** Limited by session time: 4.6h
- URL: https://github.com/MyWacc/financial-models-api/commit/56b01607aa76ebc5f373d824b397a1cfa7a28a48

##### Commit: f0ce9cc0
- Fecha: 2025-04-28T16:10:04Z
- Rama: dataScienceBranch
- Mensaje: Corrige error 'BlobClient' object has no attribute 'generate_sas'
- Cambios: +5/-3 líneas en 1 archivos
- Estimación:
  - Implementación: 0.2 h
  - Testing: 0.12 h
  - Debug: 0.08 h
  - **Total estimado**: 0.4 h
  - ⏰ **Restricción temporal:** Limited by session time: 4.6h
- URL: https://github.com/MyWacc/financial-models-api/commit/f0ce9cc0f3e266a66fda4d806463a723bdbe0702

##### Commit: 907f7036
- Fecha: 2025-04-28T17:26:06Z
- Rama: dataScienceBranch
- Mensaje: changing document poller
- Cambios: +2/-2 líneas en 1 archivos
- Estimación:
  - Implementación: 0.12 h
  - Testing: 0.07 h
  - Debug: 0.05 h
  - **Total estimado**: 0.25 h
  - ⏰ **Restricción temporal:** Limited by session time: 4.6h
- URL: https://github.com/MyWacc/financial-models-api/commit/907f7036515ec5e876cbbc0ba074a0faa426f461

#### Sesión 5: 3 Commits Consecutivos
- **Período:** 20:25 - 20:33
- **Tiempo máximo disponible:** 2.1 h
- **Tiempo estimado total:** 2.3 h

##### Commit: b3e6c44a
- Fecha: 2025-04-28T20:25:55Z
- Rama: dataScienceBranch
- Mensaje: Refactorizar servicio OCR para procesar un único PDF sin guardar en disco
- Cambios: +283/-0 líneas en 1 archivos
- Estimación:
  - Implementación: 0.55 h
  - Testing: 0.33 h
  - Debug: 0.22 h
  - **Total estimado**: 1.1 h
  - ⏰ **Restricción temporal:** Limited by session time: 2.1h
- URL: https://github.com/MyWacc/financial-models-api/commit/b3e6c44a1fad9c46c2f0290d535f15d90e2b3cda

##### Commit: 7b268479
- Fecha: 2025-04-28T20:26:20Z
- Rama: dataScienceBranch
- Mensaje: Actualizar credenciales de Azure Document Intelligence
- Cambios: +1/-0 líneas en 1 archivos
- Estimación:
  - Implementación: 0.12 h
  - Testing: 0.07 h
  - Debug: 0.05 h
  - **Total estimado**: 0.25 h
  - ⏰ **Restricción temporal:** Limited by session time: 2.1h
- URL: https://github.com/MyWacc/financial-models-api/commit/7b2684792526554ab6015a860db6b9297e19bd2d

##### Commit: fdccfaf1
- Fecha: 2025-04-28T20:33:10Z
- Rama: dataScienceBranch
- Mensaje: Implementar procesamiento directo de archivos PDF con OCR y descarga de resultados JSON
- Cambios: +125/-1 líneas en 3 archivos
- Estimación:
  - Implementación: 0.46 h
  - Testing: 0.28 h
  - Debug: 0.19 h
  - **Total estimado**: 0.93 h
  - ⏰ **Restricción temporal:** Limited by session time: 2.1h
- URL: https://github.com/MyWacc/financial-models-api/commit/fdccfaf17575be38aca2d0de567abc827a1413ff

#### Sesión 6: 3 Commits Consecutivos
- **Período:** 05:21 - 06:08
- **Tiempo máximo disponible:** 2.8 h
- **Tiempo estimado total:** 2.8 h

##### Commit: f938b86a
- Fecha: 2025-04-29T05:21:23Z
- Rama: ocr-jesus
- Mensaje: fixing sintax errors
- Cambios: +3/-6 líneas en 1 archivos
- Estimación:
  - Implementación: 0.14 h
  - Testing: 0.09 h
  - Debug: 0.06 h
  - **Total estimado**: 0.29 h
  - ⏰ **Restricción temporal:** Limited by session time: 2.8h
- URL: https://github.com/MyWacc/financial-models-api/commit/f938b86a8b6c7aa99d081c0c0e02aacd542c433a

##### Commit: c274ea93
- Fecha: 2025-04-29T06:02:04Z
- Rama: ocr-jesus
- Mensaje: gettin name
- Cambios: +30/-15 líneas en 2 archivos
- Estimación:
  - Implementación: 0.22 h
  - Testing: 0.13 h
  - Debug: 0.09 h
  - **Total estimado**: 0.44 h
  - ⏰ **Restricción temporal:** Limited by session time: 2.8h
- URL: https://github.com/MyWacc/financial-models-api/commit/c274ea93e39d1e0145a2ec1f9931398f7d65445f

##### Commit: ac48ddf9
- Fecha: 2025-04-29T06:08:36Z
- Rama: dataScienceBranch
- Mensaje: Ocr jesus (#82)

* Mejora del servicio OCR para procesamiento directo de PDFs financieros

- Eliminadas referencias al almacenamiento de blobs innecesarias
- Optimizada la ruta de procesamiento de PDFs para comunicación directa con el frontend
- Mejorada la configuración CORS para permitir solicitudes desde cualquier origen en desarrollo
- Añadido soporte para SQLite en desarrollo local
- Actualizado el procesador OCR para detectar parámetros financieros específicos
- Simplificada la estructura de URLs para mayor coherencia
- Añadida documentación detallada sobre el flujo de procesamiento de PDFs

* fixing sintax errors

* gettin name

---------

Co-authored-by: openhands <openhands@all-hands.dev>
- Cambios: +332/-281 líneas en 8 archivos
- Estimación:
  - Implementación: 1.03 h
  - Testing: 0.62 h
  - Debug: 0.41 h
  - **Total estimado**: 2.06 h
  - ⏰ **Restricción temporal:** Limited by session time: 2.8h
- URL: https://github.com/MyWacc/financial-models-api/commit/ac48ddf996127504fc815f88ec9992700a0f3817

#### Sesión 7: 6 Commits Consecutivos
- **Período:** 11:14 - 13:09
- **Tiempo máximo disponible:** 3.9 h
- **Tiempo estimado total:** 4.1 h

##### Commit: 723b4e78
- Fecha: 2025-04-29T11:14:04Z
- Rama: dataScienceBranch
- Mensaje: Add quantitative_input endpoint to retrieve valuation data
- Cambios: +61/-2 líneas en 2 archivos
- Estimación:
  - Implementación: 0.4 h
  - Testing: 0.24 h
  - Debug: 0.16 h
  - **Total estimado**: 0.81 h
  - ⏰ **Restricción temporal:** Limited by session time: 3.9h
- URL: https://github.com/MyWacc/financial-models-api/commit/723b4e78d6ea651f684d1f1fd213a5e87eba9a80

##### Commit: f40b6f1e
- Fecha: 2025-04-29T11:30:02Z
- Rama: dataScienceBranch
- Mensaje: Add downloadInputsTemplate endpoint to generate Excel files from quantitative input data
- Cambios: +250/-1 líneas en 3 archivos
- Estimación:
  - Implementación: 0.68 h
  - Testing: 0.41 h
  - Debug: 0.27 h
  - **Total estimado**: 1.35 h
  - ⏰ **Restricción temporal:** Limited by session time: 3.9h
- URL: https://github.com/MyWacc/financial-models-api/commit/f40b6f1efc24c98c11c27c2ac8f4aa7416798f2e

##### Commit: 860cd77d
- Fecha: 2025-04-29T11:35:32Z
- Rama: dataScienceBranch
- Mensaje: Add downloadInputsTemplate endpoint to generate Excel files from quantitative input data
- Cambios: +13/-13 líneas en 1 archivos
- Estimación:
  - Implementación: 0.27 h
  - Testing: 0.16 h
  - Debug: 0.11 h
  - **Total estimado**: 0.54 h
  - ⏰ **Restricción temporal:** Limited by session time: 3.9h
- URL: https://github.com/MyWacc/financial-models-api/commit/860cd77dde5d9213e6ec452b8438e900f4345a8f

##### Commit: 5c099938
- Fecha: 2025-04-29T11:43:25Z
- Rama: dataScienceBranch
- Mensaje:  updating template for mywacc
- Cambios: +0/-0 líneas en 1 archivos
- Estimación:
  - Implementación: 0.12 h
  - Testing: 0.07 h
  - Debug: 0.05 h
  - **Total estimado**: 0.25 h
  - ⏰ **Restricción temporal:** Limited by session time: 3.9h
- URL: https://github.com/MyWacc/financial-models-api/commit/5c099938dc75fa04190382622ed6915b5b8d46f9

##### Commit: 69442307
- Fecha: 2025-04-29T12:13:58Z
- Rama: dataScienceBranch
- Mensaje: Guardar quantitative_input completo en la base de datos para permitir la descarga de plantillas
- Cambios: +11/-0 líneas en 1 archivos
- Estimación:
  - Implementación: 0.12 h
  - Testing: 0.07 h
  - Debug: 0.05 h
  - **Total estimado**: 0.25 h
  - ⏰ **Restricción temporal:** Limited by session time: 3.9h
- URL: https://github.com/MyWacc/financial-models-api/commit/694423074ee29497413c8a9827b73f9060c8a359

##### Commit: ced8ccd1
- Fecha: 2025-04-29T13:09:01Z
- Rama: dataScienceBranch
- Mensaje: Fix: Manejo de valores nulos en la generación de plantilla Excel
- Cambios: +36/-21 líneas en 1 archivos
- Estimación:
  - Implementación: 0.44 h
  - Testing: 0.26 h
  - Debug: 0.18 h
  - **Total estimado**: 0.88 h
  - ⏰ **Restricción temporal:** Limited by session time: 3.9h
- URL: https://github.com/MyWacc/financial-models-api/commit/ced8ccd1e101aa2f3d1de432c615addcf0fd60e1

### Pull Requests

#### PR #82: Ocr jesus
- Fecha: 2025-04-29T06:08:09Z
- Estado: closed
- Estimación: 3.1 h
- URL: https://github.com/MyWacc/financial-models-api/pull/82


## Resumen de Horas
- Commits: 29.5 h
- Pull Requests: 3.1 h
- Issues: 0.0 h
- **Total**: 32.6 h

## Metodología de Coherencia Temporal

✅ **Commits agrupados por sesiones:** Commits realizados con menos de 2h de diferencia se consideran parte de la misma sesión de trabajo.  
✅ **Límite temporal respetado:** La suma de estimaciones nunca excede el tiempo real transcurrido + 2h de buffer.  
✅ **Distribución proporcional:** El tiempo disponible se distribuye según la complejidad relativa de cada commit.  
