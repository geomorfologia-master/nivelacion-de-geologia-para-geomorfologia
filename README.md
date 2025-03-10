Práctica de aula 0 (PA00). Nivelación de Geología para
Geomorfología<small><br>Geomorfología (GEO-114)<br>Universidad Autónoma
de Santo Domingo (UASD)<br>Semestre 2025-01</small>
================
El Tali
2025-03-10

Versión HTML (quizá más legible),
[aquí](https://geomorfologia-master.github.io/nivelacion-de-geologia-para-geomorfologia/README.html)

# Fecha/hora de entrega

**3 de febrero de 2025, 7:59 pm.**

# Introducción

La geomorfología estudia las formas del relieve terrestre, sus procesos
formativos y la interacción con el medio físico. Para comprender estos
procesos, es esencial tener conocimientos básicos de geología. Esta
práctica se centra en los minerales, las rocas y el tiempo geológico,
conceptos fundamentales para entender los materiales y procesos que
moldean el paisaje.

## Objetivos

1.  Identificar minerales y rocas relevantes para los procesos
    geomorfológicos.
2.  Comprender las relaciones entre los materiales geológicos y los
    procesos externos.
3.  Introducir el tiempo geológico como base para la dinámica de las
    formas del relieve.

------------------------------------------------------------------------

# Parte 1: Minerales y su relación con la geomorfología

### Concepto

Los minerales son los bloques básicos de las rocas, y sus propiedades
influyen en la resistencia y el modelado del paisaje.

1.  **Ejercicio 1.1:** Identificación de minerales  
    Elige dos minerales y completa la tabla con las características
    principales de minerales comunes que influyen en la geomorfología.
    En el ejemplo verás cuarzo, así que elige otros dos minerales.

    | Mineral | Dureza | Color                                           | Reacción con HCl | Relevancia geomorfológica     |
    |---------|--------|-------------------------------------------------|------------------|-------------------------------|
    | Cuarzo  | 7      | Variable, transparente, o color según impurezas | No               | Alta resistencia a la erosión |

2.  **Ejercicio 1.2:** ¿Cómo influye la dureza de un mineral en la
    erosión diferencial de un paisaje? Proporciona un ejemplo.

3.  **Ejercicio 1.3:** Elige una de las rocas mostradas en clase, y
    descríbela en un párrafo, indicando su relevancia geomorfológica.
    Las rocas mostradas en el aula fueron caliza, tonalita, arenisca,
    basalto y mármol.

------------------------------------------------------------------------

# Parte 2: Rocas y procesos geomorfológicos

### Concepto

Las rocas determinan la estructura y composición del paisaje. Sus
características afectan la velocidad de los procesos erosivos y la
formación de formas del relieve.

1.  **Ejercicio 2.1:** Clasificación de rocas relevantes para la
    geomorfología  
    Haz una tabla con dos ejemplos (ver columna “Ejemplo”) de rocas y
    sus ambientes de formación, indicando su relación con procesos
    geomorfológicos:

    | Tipo de Roca | Ejemplo | Ambiente de Formación | Relevancia Geomorfológica |
    |--------------|---------|-----------------------|---------------------------|
    | Sedimentaria | Caliza  | Depósitos marinos     | Propensa a karstificación |

2.  **Ejercicio 2.2:** Relaciona las siguientes características con el
    tipo de roca predominante en el paisaje o morfosistema:

    - **Paisaje kárstico:**
    - **Pendientes abruptas de origen tectónico:**
    - **Formaciones volcánicas:**

3.  **Ejercicio 2.3:** Dibuja el “ciclo” de las rocas y señala dónde
    ocurren procesos relevantes para la geomorfología.

------------------------------------------------------------------------

# Parte 3: Tiempo geológico y dinámicas del paisaje

### Concepto

El tiempo geológico es fundamental para entender cómo los procesos
geomorfológicos han moldeado el paisaje a lo largo de millones de años.
La [Tabla Cronoestratigráfica
Internacional](https://stratigraphy.org/ICSchart/ChronostratChart2022-02SpanishAmer.pdf)
es clave para entender cómo están ordenados.

1.  **Ejercicio 3.1:** Ordena las divisiones del tiempo geológico, de
    mayor a menor escala: Período, Época, Eón, Era.

2.  **Ejercicio 3.2:** Identifica los Períodos que abarcan la historia
    geológica de RD, selecciona dos Épocas que contengan rocas de RD,
    indicando qué rocas son (Formación, descripción) y en que lugar o
    lugares del país se encuentran.

3.  **Ejercicio 3.3:** Fechamiento geológico básico  
    Un perfil sedimentario tiene cuatro capas superpuestas, de las
    cuales las capas 1 y 3 contienen fósiles indicadores. La capa 1 se
    depositó hace 120 millones de años y la capa 3 hace 90 millones de
    años. ¿Cuánto tiempo pasó entre ambos eventos? ¿Qué procesos
    geomorfológicos pudieron ocurrir en ese intervalo?

4.  **Ejercicio 3.4:** Cálculo de tasas geomorfológicas Calcula la
    profundidad aproximada de un valle fluvial tras un tiempo
    determinado y conocida la tasa de incisión, asumiendo que el proceso
    de profundización es debido fundamentalmente a la tasa de incisión
    de su río principal, y que ésta se mantiene constante en el tiempo.
    Ejemplo. Un río ha incisionado un valle a una tasa de 2 mm/año
    durante 1 millón de años. Calcula la profundidad aproximada del
    valle.

``` r
# Código en R para calcular la incisión del río
tasa <- 2 # mm/año
tiempo <- 1e6 # años
profundidad_mm <- tasa * tiempo
profundidad_m <- profundidad_mm / 1000 # Convertir a metros
profundidad_m
```

    ## [1] 2000
