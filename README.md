# 🚨 Protección Civil Coahuayana · Sistema SEM

Sistema digital de gestión de emergencias médicas para Protección Civil del municipio de Coahuayana, Michoacán.

## ¿Qué es?

Una aplicación web de página única (Single Page Application) que funciona **sin servidor ni base de datos externa**. Toda la información se guarda localmente en el navegador mediante `localStorage`.

## Funcionalidades

- 📋 **Registro de incidentes** — folio automático, tipo de emergencia, prioridad, reportante y dirección
- ⏱️ **Tiempos operacionales** — captura de llamada, despacho, llegada, salida a hospital y regreso a base
- 🚑 **Gestión de unidades** — estado de cada ambulancia/vehículo en tiempo real
- 🧑‍⚕️ **Datos del paciente** — nombre, edad, sexo, consciencia y respiración
- 📜 **Historial** — búsqueda y filtrado de servicios anteriores con detalle completo
- 🗒️ **Bitácora** — registro cronológico de todas las acciones del turno
- 📊 **Estadísticas** — totales del turno en tiempo real

## Uso

No requiere instalación. Solo abre el archivo `index.html` en cualquier navegador moderno.

```
Abrir index.html → listo
```

También puede desplegarse gratis en **GitHub Pages** activando la opción en Settings → Pages → Branch: `main` / `/ (root)`.

## Tecnologías

- HTML5 / CSS3 / JavaScript puro (sin frameworks)
- Google Fonts (Oswald, Source Sans 3, Share Tech Mono)
- `localStorage` para persistencia de datos

## Despliegue en GitHub Pages

1. Sube este repositorio a GitHub
2. Ve a **Settings → Pages**
3. En "Branch" selecciona `main` y carpeta `/ (root)`
4. Haz clic en **Save**
5. En unos minutos estará disponible en `https://TU_USUARIO.github.io/NOMBRE_REPO/`

---

*Desarrollado para uso interno de Protección Civil Coahuayana.*
