# Optimización y Análisis de Redes: Programas de Ordenador y Laboratorios en Python

**Material docente en abierto de la Universidad Rey Juan Carlos**

* **Título:** Optimización y Análisis de Redes - Programas de Ordenador (Laboratorios Prácticos en Python)
* **Autores:** Víctor Aceña Gil, Antonio Alonso Ayuso, Javier Martínez Moguerza y Emilio López Cano
* **Asignatura:** Optimización y Análisis de Redes (Asignatura optativa de 4.º curso)
* **Titulación:** Grado en Matemáticas (Escuela Técnica Superior de Ingeniería Informática, Universidad Rey Juan Carlos)
* **Fecha:** Curso académico 2026-2027 (Junio 2026)
* **Lugar de depósito:** Archivo Abierto Institucional de la URJC (**BURJC Digital**) - <https://burjcdigital.urjc.es/>
* **Identificador persistente / Handle:** [`https://hdl.handle.net/10115/[PENDIENTE]`](https://burjcdigital.urjc.es/) *(pendiente de asignación tras el depósito)*
* **Preservación de código fuente (Software Heritage):**
  * Código fuente depositado y preservado en [Software Heritage](https://www.softwareheritage.org/) para garantizar el acceso abierto permanente, la reproducibilidad computacional y la integridad del software científico.
  * **Identificador persistente (SWHID):** [`swh:1:dir:85b3015deeb96b2949cfbeea61e1558c1c8b9504`](https://archive.softwareheritage.org/swh:1:dir:85b3015deeb96b2949cfbeea61e1558c1c8b9504;origin=https://github.com/URJCDSLab/OptimizacionAnalisisRedes_software;visit=swh:1:snp:ebc85597ce189b4bf17381fae325419b947cdb24;anchor=swh:1:rev:a16debd4c8b8c2d4c16f297bfd3d401fbee0f2af)
  * **Identificador contextual completo:** `swh:1:dir:85b3015deeb96b2949cfbeea61e1558c1c8b9504;origin=https://github.com/URJCDSLab/OptimizacionAnalisisRedes_software;visit=swh:1:snp:ebc85597ce189b4bf17381fae325419b947cdb24;anchor=swh:1:rev:a16debd4c8b8c2d4c16f297bfd3d401fbee0f2af`
  * **Enlace permanente al archivo:** <https://archive.softwareheritage.org/swh:1:dir:85b3015deeb96b2949cfbeea61e1558c1c8b9504;origin=https://github.com/URJCDSLab/OptimizacionAnalisisRedes_software;visit=swh:1:snp:ebc85597ce189b4bf17381fae325419b947cdb24;anchor=swh:1:rev:a16debd4c8b8c2d4c16f297bfd3d401fbee0f2af>

[![Archived on Software Heritage](https://archive.softwareheritage.org/badge/swh:1:dir:85b3015deeb96b2949cfbeea61e1558c1c8b9504/)](https://archive.softwareheritage.org/swh:1:dir:85b3015deeb96b2949cfbeea61e1558c1c8b9504;origin=https://github.com/URJCDSLab/OptimizacionAnalisisRedes_software;visit=swh:1:snp:ebc85597ce189b4bf17381fae325419b947cdb24;anchor=swh:1:rev:a16debd4c8b8c2d4c16f297bfd3d401fbee0f2af)

---

## 1. Descripción General del Software Docente

Este repositorio reúne la colección completa de **programas de ordenador y cuadernos interactivos de laboratorio** desarrollados en **Python** y **Quarto** (`.qmd` y `.html`) para la asignatura **Optimización y Análisis de Redes** del Grado en Matemáticas de la Universidad Rey Juan Carlos (Categoría 6: *Programas de ordenador*).

El material ha sido diseñado de forma modular y autónoma para cubrir el **100% del temario oficial de la asignatura** (los 10 capítulos divididos en el *Bloque I: Optimización no lineal* y el *Bloque II: Optimización en redes*). Cada laboratorio combina:

1. **Implementaciones algorítmicas desde cero (*from scratch*)**: Programación paso a paso de métodos numéricos y estructuras de datos fundamentales (descenso de gradiente, Símplex de Wolfe, estructura *Union-Find*, algoritmos de Kruskal, Prim, Dijkstra, Bellman-Ford, Floyd-Warshall, heurísticas constructivas y búsqueda local 2-Opt).
2. **Modelado mediante bibliotecas científicas de referencia**: Uso avanzado de `SymPy` (cálculo simbólico exacto), `Autograd` (diferenciación automática), `NumPy` (álgebra lineal numérica), `SciPy` (`scipy.optimize.minimize`, `milp`, `linear_sum_assignment`), `CVXPY` (Programación Convexa Disciplinada y extracción de variables duales), `NetworkX` (teoría algorítmica de grafos y flujos) y `PuLP` (Programación Lineal Entera).
3. **Ejercicios prácticos guiados y propuestos**: Problemas computacionales orientados al aprendizaje activo, análisis de sensibilidad mediante multiplicadores de Lagrange (precios sombra) y visualización geométrica con `Matplotlib`.

---

## 2. Relación de Programas y Correspondencia con el Temario

La siguiente tabla sintetiza los diez laboratorios que componen el repositorio, los archivos fuente y compilados correspondientes, el capítulo del libro teórico para el que son relevantes y las bibliotecas empleadas:

| Laboratorio | Fichero Fuente (`.qmd`) | Versión Compilada (`.html`) | Capítulo Relevante del Libro | Bibliotecas Principales |
| :--- | :--- | :--- | :--- | :--- |
| **Laboratorio 1** | `lab1_introduccion_sympy.qmd` | `lab1_introduccion_sympy.html` | **Tema 1**: Introducción a la investigación operativa y modelado | `SymPy`, `Autograd`, `NumPy` |
| **Laboratorio 2** | `lab2_opt_no_lineal.qmd` | `lab2_opt_no_lineal.html` | **Tema 2**: Optimización no lineal y métodos numéricos | `SciPy` (`BFGS`, `SLSQP`), `CVXPY`, `NumPy`, `Matplotlib` |
| **Laboratorio 3** | `lab3_analisis_convexo.qmd` | `lab3_analisis_convexo.html` | **Tema 3**: Análisis convexo | `SymPy`, `NumPy`, `CVXPY` (DCP) |
| **Laboratorio 4** | `lab4_condiciones_optimalidad.qmd` | `lab4_condiciones_optimalidad.html` | **Tema 4**: Condiciones de optimalidad y KKT | `SymPy`, `CVXPY`, `NumPy` |
| **Laboratorio 5** | `lab5_duales_lp_qp.qmd` | `lab5_duales_lp_qp.html` | **Tema 5**: Dualidad KKT en programación lineal y cuadrática | `CVXPY`, `NumPy`, `Matplotlib` |
| **Laboratorio 6** | `lab6_grafos_arboles.qmd` | `lab6_grafos_arboles.html` | **Tema 6**: Grafos y árboles soporte de mínimo peso | `NetworkX`, `NumPy`, `Matplotlib` |
| **Laboratorio 7** | `lab7_caminos_minimos.qmd` | `lab7_caminos_minimos.html` | **Tema 7**: Problema del camino mínimo | `NetworkX`, `CVXPY`, `NumPy` |
| **Laboratorio 8** | `lab8_flujos_redes.qmd` | `lab8_flujos_redes.html` | **Tema 8**: Flujos en redes | `NetworkX`, `CVXPY`, `NumPy` |
| **Laboratorio 9** | `lab9_emparejamientos.qmd` | `lab9_emparejamientos.html` | **Tema 9**: Emparejamientos en redes | `NetworkX`, `SciPy` (`milp`, `linear_sum_assignment`), `NumPy` |
| **Laboratorio 10** | `lab10_rutas.qmd` | `lab10_rutas.html` | **Tema 10**: Rutas eulerianas, hamiltonianas, TSP y VRP | `NetworkX`, `PuLP`, `SciPy`, `NumPy`, `Matplotlib` |

---

## 3. Descripción Detallada de los Laboratorios

### Bloque I: Optimización No Lineal

* **Laboratorio 1: Introducción al Modelado y Cálculo Simbólico con SymPy (`lab1_introduccion_sympy.qmd`)**
  * **Contenido:** Introduce al estudiante en el uso del cálculo simbólico en Python mediante `SymPy` para obtener gradientes y matrices hessianas analíticas de forma exacta en funciones univariables, multivariantes y paramétricas. Asimismo, se enseña el uso de `Autograd` para diferenciación automática numérica con precisión de máquina. Por último, se aborda la clasificación de la curvatura y la convexidad local y global mediante el criterio de autovalores con `NumPy` y de menores principales simbólicos.
  * **Relevancia:** Tema 1 y fundamentos diferenciales del Tema 2.

* **Laboratorio 2: Optimización No Lineal con Python (`lab2_opt_no_lineal.qmd`)**
  * **Contenido:** Se centra en la implementación y resolución de algoritmos de optimización continua sin y con restricciones. El estudiante programa manualmente el bucle del algoritmo de descenso de gradiente para analizar su tasa de convergencia lineal. Posteriormente, utiliza `scipy.optimize.minimize` (comparando el método Cuasi-Newton `BFGS` con y sin jacobiano analítico, y el método `SLSQP` para restricciones no lineales). Finalmente, introduce el modelado en `CVXPY` destacando la obtención directa de multiplicadores de Lagrange.
  * **Relevancia:** Tema 2 (Optimización no lineal y métodos numéricos).

* **Laboratorio 3: Análisis de Convexidad y Modelado con CVXPY (`lab3_analisis_convexo.qmd`)**
  * **Contenido:** Profundiza en la verificación simbólica y numérica de la convexidad de conjuntos y funciones mediante `SymPy` y `NumPy`, y en el modelado bajo las reglas de la Programación Convexa Disciplinada (DCP) con `CVXPY`. Se estudian las causas de la excepción `DCPError` ante formulaciones no válidas, la reformulación convexa mediante átomos como la media geométrica (`cp.geo_mean`), y el análisis de sensibilidad mediante precios sombra (`.dual_value`).
  * **Relevancia:** Tema 3 (Análisis convexo).

* **Laboratorio 4: Condiciones de Optimalidad y KKT en Python (`lab4_condiciones_optimalidad.qmd`)**
  * **Contenido:** Aborda el análisis computacional de las condiciones necesarias y suficientes de Karush-Kuhn-Tucker (KKT). El alumno implementa rutinas simbólicas en `SymPy` para verificar la cualificación de restricciones de independencia lineal (LICQ) mediante el rango de la matriz jacobiana activa, formula el sistema de Fritz-John en casos degenerados y programa la búsqueda combinatoria exacta de puntos candidatos KKT a partir de la holgura complementaria, validando los resultados numéricamente con `CVXPY`.
  * **Relevancia:** Tema 4 (Condiciones de optimalidad y KKT).

* **Laboratorio 5: Dualidad KKT y Programación Cuadrática en Python (`lab5_duales_lp_qp.qmd`)**
  * **Contenido:** Estudia la dualidad lagrangiana en Programación Lineal (LP) y Programación Cuadrática (QP). El estudiante extrae e interpreta económicamente los multiplicadores duales en `CVXPY` ante perturbaciones del vector de recursos. Además, implementa en Python el algoritmo del **Símplex de Wolfe** con regla de entrada restringida para mantener la holgura complementaria y visualiza la trayectoria sobre la región factible poliédrica.
  * **Relevancia:** Tema 5 (Dualidad KKT en programación lineal y cuadrática).

### Bloque II: Optimización en Redes

* **Laboratorio 6: Grafos y Árboles Soporte de Mínimo Peso en Python (`lab6_grafos_arboles.qmd`)**
  * **Contenido:** Introduce la representación matricial (incidencia y adyacencia) y el análisis topológico de redes valoradas con `NetworkX`, `NumPy` y `Matplotlib`. Verifica computacionalmente el Lema del Apretón de Manos (*Handshaking Lemma*) y calcula métricas de distancia geodésica, excentricidad, radio, diámetro y centro. El estudiante implementa desde cero la estructura de datos *Union-Find* (con compresión de caminos y unión por rango) para programar los algoritmos voraces de **Kruskal** y **Prim**, aplicándolos finalmente al agrupamiento de datos no convexos (*clustering Single-Linkage*).
  * **Relevancia:** Tema 6 (Grafos y árboles soporte).

* **Laboratorio 7: Problemas de Camino Mínimo en Python (`lab7_caminos_minimos.qmd`)**
  * **Contenido:** Desarrolla la formulación e implementación algorítmica de caminos mínimos sobre redes dirigidas valoradas. El alumno programa desde cero el algoritmo de **Dijkstra** para pesos no negativos y el algoritmo de **Bellman-Ford** con detección de circuitos absorbentes (ciclos de coste negativo). Asimismo, modela el problema primal de flujo en `CVXPY` para extraer los potenciales nodales duales óptimos y programa el algoritmo matricial de **Floyd-Warshall** para caminos mínimos entre todos los pares.
  * **Relevancia:** Tema 7 (Problema del camino mínimo).

* **Laboratorio 8: Flujos en Redes en Python (`lab8_flujos_redes.qmd`)**
  * **Contenido:** Aborda el problema de Flujo Máximo y el problema de Flujo de Coste Mínimo. Mediante `NetworkX`, se resuelve el flujo máximo (`nx.maximum_flow`) y se verifica empíricamente el **Teorema de Flujo Máximo - Corte Mínimo** (`nx.minimum_cut`). Se estudian redes con demandas y transbordo mediante el Símplex de Redes (`nx.network_simplex` y `nx.min_cost_flow`) y se contrasta con su formulación matricial explícita en `CVXPY` analizando las variables duales de conservación de flujo y saturación de arcos.
  * **Relevancia:** Tema 8 (Flujos en redes).

* **Laboratorio 9: Emparejamientos en Redes en Python (`lab9_emparejamientos.qmd`)**
  * **Contenido:** Se centra en los problemas de emparejamiento (*matching*), asignación y recubrimiento en grafos bipartitos y generales. Utiliza `nx.bipartite.maximum_matching` y el método Húngaro en `scipy.optimize.linear_sum_assignment` para asignación de coste mínimo. En grafos no bipartitos con ciclos impares, aplica el algoritmo de la Flor (*Blossom*) de Edmonds (`nx.max_weight_matching`), comprueba la identidad de dualidad de Gallai con recubrimientos mínimos de aristas (`nx.min_edge_cover`) y compara la relajación lineal continua frente a la solución entera con `scipy.optimize.milp`.
  * **Relevancia:** Tema 9 (Emparejamientos en redes).

* **Laboratorio 10: Rutas Eulerianas, Hamiltonianas, TSP y VRP en Python (`lab10_rutas.qmd`)**
  * **Contenido:** Aborda problemas de rutas sobre aristas y sobre vértices. Incluye la comprobación y extracción de circuitos eulerianos y la resolución completa del **Problema del Cartero Chino (CPP)** mediante reducción a emparejamiento perfecto de peso mínimo sobre nodos de grado impar. Para el **Problema del Viajante (TSP)**, implementa el modelo entero de Miller-Tucker-Zemlin (MTZ) en `PuLP`, programa heurísticas de Vecino más Cercano y mejora local **2-Opt**, evalúa la aproximación de **Christofides** (garantía 3/2) y modela el Problema de Rutas de Vehículos con Capacidad (**CVRP**).
  * **Relevancia:** Tema 10 (Rutas eulerianas, hamiltonianas, TSP y VRP).

---

## 4. Requisitos e Instrucciones de Uso

Los programas pueden consultarse directamente abriendo los ficheros `.html` en cualquier navegador web moderno (no requieren instalación previa), o bien ejecutarse y modificarse de forma interactiva a través de los ficheros fuente `.qmd` utilizando **Python** y **Quarto**.

### 4.1. Creación del entorno de Python (Conda)

Se recomienda utilizar un entorno aislado de Conda con Python 3.11 o superior:

```bash
conda create -n oar_env python=3.11 -y
conda activate oar_env
```

### 4.2. Instalación de bibliotecas necesarias

```bash
pip install numpy scipy matplotlib networkx cvxpy sympy autograd pulp jupyter
```

### 4.3. Ejecución y renderizado de los cuadernos

Puedes abrir y ejecutar los archivos `.qmd` directamente en **Visual Studio Code** (con la extensión oficial de Quarto y Jupyter), en **RStudio**, o compilarlos desde la terminal mediante [Quarto CLI](https://quarto.org/):

```bash
# Renderizar un laboratorio específico a formato HTML interactivo
quarto render lab1_introduccion_sympy.qmd --to html

# Renderizar todos los laboratorios del repositorio
quarto render
```

---

## 5. Declaración sobre Uso de Herramientas de Inteligencia Artificial Generativa

En cumplimiento de lo dispuesto en el Anexo III.4 y el Anexo VI de la *Convocatoria para el reconocimiento de la publicación en acceso abierto de materiales docentes del curso 2026-2027* de la Universidad Rey Juan Carlos, se realiza la siguiente declaración sobre el uso de herramientas de inteligencia artificial generativa en la elaboración de este material:

1. **Tipo de herramientas utilizado:** Se han empleado modelos de lenguaje de gran tamaño (LLM) y asistentes de codificación y estilo (herramientas de asistencia a la edición de código en Python y formateo técnico en Quarto/Markdown).
2. **Forma de uso:** Dichas herramientas se han utilizado como soporte auxiliar para la estructuración de las plantillas de cuadernos Quarto (`.qmd`), la redacción de comentarios explicativos dentro de los bloques de código, la revisión ortotipográfica y la verificación de consistencia en la notación matemática en LaTeX.
3. **Grado de uso:** Uso de carácter parcial y de apoyo técnico y estilístico, partiendo íntegramente del diseño pedagógico, los modelos matemáticos, los algoritmos y los enunciados elaborados por los autores.

**Manifiesto de responsabilidad:** Todo el contenido y el código fuente incluido en este repositorio ha sido cuidadosamente diseñado, ejecutado, revisado, validado y aprobado por los autores, que asumen la plena responsabilidad sobre la versión final de la obra.

---

## 6. Derechos de Autor y Licencia

**Copyright © 2026 Víctor Aceña Gil, Antonio Alonso Ayuso, Javier Martínez Moguerza, Emilio López Cano.**

<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/deed.es"><img src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Licencia de Creative Commons" style="border-width:0"/></a>

**Algunos derechos reservados. Esta obra se distribuye bajo la licencia Creative Commons Atribución-CompartirIgual 4.0 Internacional (CC BY-SA 4.0)**, cuyo texto legal completo está disponible en: <https://creativecommons.org/licenses/by-sa/4.0/deed.es>.
