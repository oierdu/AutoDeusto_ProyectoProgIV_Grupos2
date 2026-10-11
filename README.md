# AutoDeusto

Base inicial de un proyecto académico en **C** para la gestión de un concesionario, desarrollado en la Universidad de Deusto.

## Estado del código

El repositorio público está en una fase inicial. El único programa implementado, `src/prueba.c`, imprime `Prueba` en la consola. Se puede compilar y ejecutar; todavía no implementa gestión de vehículos, clientes o ventas ni comunicación cliente/servidor.

La arquitectura cliente/servidor descrita en la propuesta original es un objetivo de desarrollo, no una funcionalidad disponible. No hay una aplicación comercial ni una demostración de ese sistema completo.

## Estructura disponible

```text
AutoDeusto_ProyectoProgIV_Grupos2/
├── src/
│   └── prueba.c
├── .gitignore
└── README.md
```

## Compilar y ejecutar

Se necesita un compilador de C. Comprobado con GCC/MinGW en Windows:

```powershell
gcc -Wall -Wextra -Wpedantic src/prueba.c -o autodeusto.exe
.\autodeusto.exe
```

En Linux o macOS con GCC:

```sh
gcc -Wall -Wextra -Wpedantic src/prueba.c -o autodeusto
./autodeusto
```

Salida actual: `Prueba`. La compilación y ejecución se comprobaron el 11 de octubre de 2026 en Windows. La variante Linux/macOS se proporciona como instrucción equivalente y no se ha ejecutado en esos sistemas en esta revisión.

## Próximos pasos

- Definir estructuras de datos y operaciones del dominio.
- Implementar y probar la persistencia.
- Diseñar la comunicación cliente/servidor cuando exista una base funcional.

Estos pasos son planificación; no se presentan como funcionalidades terminadas.

## Colaboración

Se conserva íntegro el historial existente. El README original no identifica a los integrantes del grupo, por lo que esta documentación no añade nombres ni atribuye módulos a colaboradores sin confirmar.

Las mejoras se preparan en ramas y se revisan mediante pull requests. No se deben subir ejecutables ni archivos temporales. El repositorio no declara actualmente una licencia general de reutilización.
