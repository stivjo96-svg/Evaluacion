# Sistema de Gestión de Estudiantes

## Descripción del proyecto

Este proyecto corresponde al desarrollo de una aplicación en Python orientada al registro y administración de estudiantes. El sistema permite ingresar información académica, validar los datos proporcionados por el usuario y clasificar automáticamente el desempeño de cada estudiante de acuerdo con la suma de sus calificaciones.

Durante el desarrollo se aplicaron técnicas de refactorización para mejorar la organización del código, facilitar su mantenimiento y preparar la aplicación para futuras modificaciones.

---

# Objetivos

- Registrar estudiantes junto con sus calificaciones.
- Validar los datos ingresados antes de almacenarlos.
- Calcular automáticamente la suma de las notas.
- Clasificar el rendimiento académico de cada estudiante.
- Organizar el código siguiendo buenas prácticas de programación.
- Implementar pruebas unitarias para verificar el funcionamiento del sistema.

---

# Funcionalidades

El sistema permite realizar las siguientes operaciones:

- Registro de estudiantes.
- Validación del nombre del estudiante.
- Validación de las calificaciones.
- Cálculo de la suma de notas.
- Clasificación académica del estudiante.
- Consulta de estudiantes registrados.
- Búsqueda de estudiantes por nombre.

---

# Organización del proyecto

```
Evaluacion-Sistemas-Agiles/
│
├── main.py
├── gestor_estudiantes.py
├── README.md
├── pytest.ini
├── .gitignore
│
└── tests/
    └── test_main.py
```

---

# Herramientas utilizadas

- Python 3
- Visual Studio Code
- Git
- GitHub
- Pytest

---

# Ejecución del programa

Para iniciar la aplicación ejecutar:

```bash
python main.py
```

---

# Ejecución de las pruebas

Las pruebas unitarias pueden ejecutarse mediante:

```bash
pytest
```

---

# Mejoras implementadas

Durante el proceso de desarrollo se realizaron varias modificaciones orientadas a mejorar la calidad del software:

- Se renombraron variables y funciones para aumentar la claridad del código.
- Se separó la validación de datos en funciones independientes.
- Se creó una función específica para calcular la suma de calificaciones.
- Se implementó una función para determinar el estado académico.
- Se definió una constante para la nota mínima de aprobación.
- Se reorganizó el código en módulos para separar responsabilidades.
- Se incorporaron pruebas unitarias utilizando Pytest.
- Se añadieron archivos de configuración como `.gitignore` y `pytest.ini`.

---

# Evolución del sistema

Como parte de la evolución del proyecto se amplió la clasificación académica incorporando una nueva categoría denominada **EXCELENTE**, quedando la evaluación de la siguiente manera:

| Puntaje total | Resultado |
|---------------|-----------|
| 28 - 30 | EXCELENTE |
| 24 - 27 | APROBADO |
| Menor a 24 | REPROBADO |

Esta mejora demuestra que la estructura del sistema permite incorporar nuevos requerimientos sin afectar el funcionamiento general del programa.

---

# Autor

**Stiven Vallejo**

Evaluación de la asignatura **Sistemas Ágiles**.