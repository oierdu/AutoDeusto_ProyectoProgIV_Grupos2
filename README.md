# AutoDeusto

Proyecto de Programación IV — Universidad de Deusto
Sistema de gestión de concesionario con arquitectura cliente/servidor en C.

---

## Integrantes

| Nombre | GitHub |
|--------|--------|
|        |        |
|        |        |
|        |        |
|        |        |

---

## Descripción

AutoDeusto es un sistema de gestión de concesionario de coches.
El proyecto sigue una arquitectura **cliente/servidor**: el servidor gestiona los datos
y los clientes se conectan a él para realizar operaciones.

---

## Estructura del proyecto

```
AutoDeusto_ProyectoProgIV/
├── include/     → cabeceras (.h): definición de structs y funciones
├── src/         → código fuente (.c): implementación
├── data/        → archivos de datos (ej. coches.dat)
├── docs/        → documentación del proyecto
├── .gitignore   → archivos a ignorar por Git
└── README.md    → este archivo
```

---

## Normas de trabajo con Git

- **No trabajar directamente sobre `main`.**
  La rama `main` es la rama estable. Solo se fusiona código revisado.

- **Cada integrante trabaja en su propia rama.**
  Ejemplo: `git checkout -b feature/gestion-vehiculos`

- **Hacer `pull` antes de empezar a trabajar.**
  ```bash
  git pull origin main
  ```

- **Commits claros y descriptivos.**
  Mal: `git commit -m "cambios"`
  Bien: `git commit -m "Añadir struct Vehiculo en vehiculo.h"`

- **No subir ejecutables ni archivos temporales.**
  El `.gitignore` ya los excluye. No lo modifiques sin avisar al equipo.

---

## Compilación

> *Se añadirá cuando el código esté listo.*
