Aquí guardo apuntes personales del proyecto, weás pa no olvidarme básicamente

# Estructura proyecto

├── data                # Bases de datos
├── scripts             # Scripts sueltos que hagan cosas puntuales fuera de la aplicación en si misma
├── src                 # Núcleo de la aplicación
│   └── nombreApp       # Nombre de la app, así es más intuitivo llamarla, tipo `python -m src.nombreApp.core.dataAnalysis` o qué sé yo
│       ├── core        # Donde están las cosas importantes de la app.
│       └── utils       # Módulos extra que se llaman desde `core`. La idea es que estos sean independientes y puedan funcionar en otros proyectos.
└── tests               # Espejo del `src` para hacer pruebas
# Como subir weás a git
1. `git checkout main` y `git pull` (Empezar siempre actualizado).
2. `git checkout -b mi-mejora` (Crear rama).
3. Escribir código + tests.
4. `git add .` y `git commit -S -m "tipo: descripción"`.
5. `git push -u origin mi-mejora`.
6. Abrir PR en GitHub -> Revisar -> Merge