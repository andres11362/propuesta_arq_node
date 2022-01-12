# Estructura base para un proyecto NodeJS

Basado en dos principios basicos de la programación.

1. Modelo - Vista - Controlador
2. Principios SOLID.

```
src
│   app.js          # Punto de entrada de la aplicación
└───api             # Controladores de express con rutas y los endpoints de la app
└───config          # Variables de entorno y configuración de otras herramientas
└───jobs            # Jobs definidos para agenda.js
└───loaders         # División de procesos dentro de modulos
└───models          # Modelos de la base de datos
└───services        # Toda la logica del negocio iria aca
└───subscribers     # Controladores de eventos para tareas asíncronas 
└───types           # Declaracion de archivos para Typescript (.ts)

```

La idea es realizar un codigo que sea escalable y mantenible a través del tiempo.
