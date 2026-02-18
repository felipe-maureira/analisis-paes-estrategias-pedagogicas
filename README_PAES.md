# 📊 Análisis Comparativo PAES 2022-2025 - Estrategias Pedagógicas en Matemáticas

## Descripción
Análisis de datos educativos reales que evalúa el impacto de estrategias pedagógicas aplicadas en matemáticas, combinando resultados históricos PAES oficiales (2022-2025) con ensayos internos del año 2025.

## Contexto
Este análisis nace de una iniciativa pedagógica implementada en un establecimiento educacional de Chile, donde se aplicaron estrategias de refuerzo matemático como operatoria básica combinada, resolución de problemas y preparación específica para la PAES en 3° y 4° medio.

## Datos utilizados
- **Resultados oficiales PAES Matemática:** 219 registros entre 2022 y 2025
- **Ensayos internos 2025:** 136 estudiantes de 3°A, 3°B, 4°A y 4°B
- Datos anonimizados para proteger la identidad de los estudiantes

## Estructura del proyecto
```
├── Puntajes_Paes.xlsx                    # Resultados oficiales PAES 2022-2025
├── PAES_2025.xlsx                        # Ensayos internos 2025
├── analisis_comparativo_paes.ipynb       # Análisis completo con visualizaciones
└── README.md
```

## Tecnologías utilizadas
- Python 3.x
- pandas
- matplotlib
- seaborn
- numpy

## Análisis realizados

### 📈 Evolución histórica PAES (2022-2025)
- Promedio por año con identificación del año 2025
- Distribución de puntajes mediante boxplot comparativo

### 🔍 Comparación ensayos internos vs resultado oficial 2025
- Promedio Ensayo 1 vs Ensayo 2 vs PAES oficial
- Análisis exclusivo de 4° medio (quienes rindieron la PAES)

### 📉 Tendencia histórica
- Gráfico de línea con evolución 2022-2025
- Identificación visual de la mejora sostenida

## Principales hallazgos

| Año | Promedio PAES | Estudiantes |
|-----|--------------|-------------|
| 2022 | 522 pts | 47 |
| 2023 | 523 pts | 29 |
| 2024 | 578 pts | 52 |
| 2025 | 599 pts | 53 |

- El promedio PAES subió **+76 puntos** entre 2022 y 2025
- Mayor concentración de estudiantes sobre 500 puntos en 2025
- Los ensayos internos demostraron ser una herramienta predictiva válida

## Cómo ejecutar
1. Clonar el repositorio
```bash
git clone https://github.com/tu_usuario/analisis-paes-estrategias-pedagogicas.git
```
2. Instalar dependencias
```bash
pip install pandas matplotlib seaborn numpy openpyxl
```
3. Colocar los archivos `.xlsx` en la misma carpeta que el notebook
4. Abrir y ejecutar el notebook
```bash
jupyter notebook analisis_comparativo_paes.ipynb
```

## Autor
**Felipe Maureira** — Profesor de Matemática y Computación | Estudiante de Ingeniería en Ciencia de Datos  
Este proyecto combina 6 años de experiencia docente con análisis de datos para medir el impacto real de estrategias pedagógicas.
