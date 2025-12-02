# Taller Python para la Ciencia, Tecnología e Ingeniería

## Descripción del Proyecto

Este repositorio contiene el trabajo desarrollado durante el taller de Python para la Ciencia, Tecnología e Ingeniería. El proyecto incluye ejercicios prácticos que cubren conceptos fundamentales de Python y su aplicación en el análisis de datos científicos e ingeniería.

### Contenido del Taller

El cuaderno Jupyter incluye los siguientes temas:

1. **Entrada y Salida de Datos en Python**
   - Uso de la función `input()`
   - Conversión de tipos de datos (`int()`, `float()`)
   - Captura y visualización de datos numéricos

2. **Estructuras Básicas**
   - Declaración y asignación de variables
   - Operaciones aritméticas (suma, resta, multiplicación, división, módulo)
   - Aplicaciones prácticas (cálculo de IMC)

3. **Importación de Módulos**
   - Uso de la sentencia `import`
   - Módulos estándar: `math`, `random`, `datetime`

4. **Paquetes Científicos**
   - **NumPy**: Computación numérica y operaciones con arrays
   - **Matplotlib**: Visualización de datos (gráficos de línea, barras, histogramas, dispersión)
   - **Pandas**: Análisis y manipulación de datos estructurados

5. **Proyecto Integrador**
   - Simulación de datos de sensores
   - Análisis estadístico
   - Visualización avanzada
   - Análisis de correlación

## Estructura del Repositorio

```
taller2/
│
├── src/                    # Código fuente principal
│   ├── main.py            # Script principal
│   ├── funciones.py       # Funciones auxiliares
│   └── ...                # Otros módulos
│
├── data/                  # Archivos de datos
│   ├── ejemplo.csv
│   └── ejemplo.xlsx
│
├── notebooks/             # Cuadernos Jupyter
│   └── taller.ipynb      # Cuaderno principal del taller
│
├── docs/                  # Documentación adicional
│   └── manual.md
│
├── requirements.txt       # Lista de dependencias
├── README.md             # Este archivo
├── .gitignore           # Archivos excluidos de git
└── LICENSE              # Licencia del proyecto
```

## Instrucciones de Instalación

### Requisitos Previos

- Python 3.8 o superior
- pip (gestor de paquetes de Python)
- Git

### Clonar el Repositorio

Para clonar este repositorio en tu máquina local, ejecuta el siguiente comando en tu terminal:

```bash
git clone https://github.com/tu-usuario/taller2.git
cd taller2
```

### Instalar Dependencias

Una vez clonado el repositorio, instala todas las dependencias necesarias usando:

```bash
pip install -r requirements.txt
```

**Nota:** Se recomienda usar un entorno virtual para evitar conflictos con otras instalaciones de Python:

```bash
# Crear entorno virtual
python -m venv venv

# Activar entorno virtual
# En Windows:
venv\Scripts\activate
# En Linux/Mac:
source venv/bin/activate

# Instalar dependencias
pip install -r requirements.txt
```

## Cómo Ejecutar el Código

### Ejecutar el Cuaderno Jupyter

1. Asegúrate de tener Jupyter instalado (incluido en `requirements.txt`)
2. Inicia Jupyter Notebook o JupyterLab:

```bash
# Opción 1: Jupyter Notebook
jupyter notebook

# Opción 2: JupyterLab
jupyter lab
```

3. Navega a la carpeta `notebooks/` y abre `taller.ipynb`
4. Ejecuta las celdas secuencialmente usando `Shift + Enter`

### Ejecutar Scripts de Python

Si has desarrollado scripts en la carpeta `src/`, puedes ejecutarlos desde la terminal:

```bash
python src/main.py
```

## Uso en Google Colab

También puedes ejecutar el cuaderno en Google Colab:

1. Ve a [Google Colab](https://colab.research.google.com/)
2. Selecciona "Archivo" > "Abrir cuaderno"
3. Ve a la pestaña "GitHub" y pega la URL de este repositorio
4. Selecciona el archivo `notebooks/taller.ipynb`

**Nota:** En Google Colab las librerías básicas (numpy, pandas, matplotlib) ya están preinstaladas.

## Estructura de los Ejercicios

Cada sección del cuaderno está organizada de la siguiente manera:

- **Título descriptivo**: Indica el tema a tratar
- **Comentarios explicativos**: Cada bloque de código incluye comentarios que describen su propósito
- **Ejemplos prácticos**: Aplicaciones reales en ciencia e ingeniería
- **Salidas visualizadas**: Resultados y gráficos que facilitan la comprensión

## Tecnologías Utilizadas

- **Python 3.x**: Lenguaje de programación principal
- **NumPy**: Computación numérica
- **Pandas**: Análisis de datos
- **Matplotlib**: Visualización de datos
- **Jupyter**: Entorno interactivo de desarrollo

## Créditos y Referencias

Este proyecto fue desarrollado como parte del taller **"Python para la Ciencia, Tecnología e Ingeniería"**.

### Instructor
- [Nombre del Instructor/Institución]

### Estudiante
- **Nombre:** [Tu Nombre Completo]
- **Fecha:** [Fecha de Entrega]
- **Materia:** [Nombre de la Materia]

### Referencias

- [Documentación oficial de Python](https://docs.python.org/3/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Jupyter Documentation](https://jupyter.org/documentation)

## Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## Contacto

Para preguntas o sugerencias, por favor contacta a:
- **Email:** tu.email@example.com
- **GitHub:** [@tu-usuario](https://github.com/tu-usuario)

---

**Nota:** Este es un proyecto educativo desarrollado con fines académicos.
