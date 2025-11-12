<div align="center">
    
### 💻 UNIDAD 1: LÓGICA MATEMÁTICA Y PROPOSICIONES ✨
</div>

---

## 📘 Índice de Contenidos

### 1. [CONTENIDOS DE LA UNIDAD](Unidad%201.md#%EF%B8%8F-contenidos-de-la-unidad)

- **1.1.** [LÓGICA Y LÓGICA MATEMÁTICA](Unidad%201.md#-1-lógica-y-lógica-matemática)
- **1.2.** [PROPOSICIONES LÓGICAS Y CONECTIVAS](Unidad%201.md#-2-proposiciones-lógicas-y-conectivas)
- **1.3.** [TABLAS DE VERDAD: TAUTOLOGÍA, CONTRADICCIÓN Y CONTINGENCIA](Unidad%201.md#-3-tablas-de-verdad-tautología-contradicción-y-contingencia)
- **1.4.** [LEYES LÓGICAS](Unidad%201.md#-4-leyes-lógicas)
- **1.5.** [REGLAS DE INFERENCIA](Unidad%201.md#-5-reglas-de-inferencia)
- **1.6.** [APLICACIONES TECNOLÓGICAS](Unidad%201.md#-6-aplicaciones-tecnológicas)

### 2. [TAREAS ENTREGADAS Y ACTIVIDADES ELABORADAS](Unidad%201.md#%EF%B8%8F-tareas-entregadas-y-actividades-elaboradas)

#### ✏️ *Aprendizaje Autónomo*
- **2.1.** [Clasificación de las Proposiciones y Aplicación de Leyes Lógicas]
- **2.2.** [Ejercicios Resueltos de Reglas de Inferencia]

#### 🧪 *Aprendizaje Práctico Experimental*
- **2.3.** [Construcción y Análisis de Tablas de Verdad]
- **2.4.** [Simplificación de Proposiciones Compuestas usando Equivalencias]

### 3. [📎 ANEXOS](Unidad%201.md#%EF%B8%8F-anexos)

---

### 🗂️ CONTENIDOS DE LA UNIDAD

### 🔹 1. LÓGICA Y LÓGICA MATEMÁTICA

* **¿Qué es la Lógica?**
    * [cite_start]Es la ciencia formal que estudia los principios de la demostración y la inferencia válida[cite: 10].
    * [cite_start]Deriva del griego *λογική* (*logiké*), que significa "dotado de razón, intelectual"[cite: 10].

* **¿Qué es la Lógica Matemática?**
    * [cite_start]Es una disciplina que trata de métodos de razonamiento[cite: 22].
    * [cite_start]Proporciona reglas y técnicas para determinar si es o no válido un argumento dado[cite: 22].
    * [cite_start]Se emplea en matemáticas para demostrar teoremas y en ciencias de la computación para verificar la corrección de programas[cite: 23, 24].

---

### 🔹 2. PROPOSICIONES LÓGICAS Y CONECTIVAS

* **Proposición Lógica**
    * [cite_start]Es un enunciado que puede ser **falso (0)** o **verdadero (1)**, pero no ambas a la vez[cite: 32].
    * [cite_start]Es un elemento fundamental de la lógica matemática[cite: 33].

* **Conectivos o Conectores Lógicos**
    * [cite_start]Son expresiones gramaticales ("y", "o", "si...entonces...") que se usan para enlazar proposiciones[cite: 35].
    * [cite_start]El modificador negativo ("no", "no es cierto que...") **no es un conectivo lógico** porque no enlaza proposiciones[cite: 44].

* **Jerarquía de Operadores**
    * [cite_start]Se utiliza para reducir el número de paréntesis[cite: 65].
    * [cite_start]El orden de precedencia es: Mayor Jerarquía $\neg \wedge \vee$ Menor Jerarquía[cite: 66].
    * [cite_start]Ante una disputa de operadores, "gana el que tiene una mayor jerarquía"[cite: 67].

| Conector | Interpretación Común | Símbolo |
| :---: | :---: | :---: |
| Negación | No, No es cierto que... | $\neg p$ |
| Conjunción | y, pero, sin embargo | $p \wedge q$ |
| Disyunción | o, o p o q o ambos | $p \vee q$ |
| Condicional | si p entonces q, q si p | $p \rightarrow q$ |
| Bicondicional | p si y sólo si q, p es necesario y suficiente para q | $p \leftrightarrow q$ |

---

### 🔹 3. TABLAS DE VERDAD: TAUTOLOGÍA, CONTRADICCIÓN Y CONTINGENCIA

[cite_start]Una **tabla de verdad** es una descripción organizada de los valores de verdad de la proposición para todos los valores posibles de las variables proposicionales que aparecen en ella[cite: 91].

| Clasificación | Definición | Valor de Verdad en la Tabla |
| :---: | :---: | :---: |
| **Tautología** | [cite_start]Es verdadera para todas las asignaciones de valores de verdad para sus proposiciones componentes[cite: 117]. | Siempre **V** |
| **Contradicción** | [cite_start]En todos los casos posibles de su tabla de verdad su valor siempre es **F**[cite: 121]. | Siempre **F** |
| **Contingencia** | [cite_start]Puede ser verdadera o falsa (combinación entre tautología y contradicción)[cite: 128]. | Combinación de **V** y **F** |

---

### 🔹 4. LEYES LÓGICAS

[cite_start]Son proposiciones que son **lógicamente equivalentes** ($\Leftrightarrow$ o $\equiv$) y se aplican para simplificar proposiciones grandes[cite: 194].

| Ley | Forma Conjuntiva ($\wedge$) | Forma Disyuntiva ($\vee$) |
| :---: | :---: | :---: |
| **Idempotencia** | [cite_start]$P \wedge P \Leftrightarrow P$ [cite: 198] | [cite_start]$P \vee P \Leftrightarrow P$ [cite: 197] |
| **Conmutativas** | [cite_start]$P \wedge Q \leftrightarrow Q \wedge P$ [cite: 203] | [cite_start]$P \vee Q \Leftrightarrow Q \vee P$ [cite: 202] |
| **Asociativas** | [cite_start]$(P \wedge Q) \wedge R \equiv P \wedge (Q \wedge R)$ [cite: 175] | [cite_start]$(P \vee Q) \vee R \Leftrightarrow P \vee (Q \vee R)$ [cite: 200] |
| **Distributivas** | [cite_start]$P \wedge (Q \vee R) \Leftrightarrow (P \wedge Q) \vee (P \wedge R)$ [cite: 210] | [cite_start]$P \vee (Q \wedge R) \Leftrightarrow (P \vee Q) \wedge (P \vee R)$ [cite: 210] |
| **Identidad** | [cite_start]$P \wedge V \Leftrightarrow P$ [cite: 212] | [cite_start]$P \vee F \Leftrightarrow P$ [cite: 189] |
| **Complemento** | [cite_start]$P \wedge \neg P \Leftrightarrow F$ [cite: 207] | [cite_start]$P \vee \neg P \Leftrightarrow V$ [cite: 208] |
| **Doble Negación** | [cite_start]$\neg (\neg P) \Leftrightarrow P$ [cite: 206] | |
| **De Morgan** | [cite_start]$\neg(P \wedge Q) \Leftrightarrow \neg P \vee \neg Q$ [cite: 215] | [cite_start]$\neg(P \vee Q) \Leftrightarrow \neg P \wedge \neg Q$ [cite: 215] |

---

### 🔹 5. REGLAS DE INFERENCIA

[cite_start]La **Inferencia** es una operación lógica que consiste en concluir una proposición en forma inmediata sobre la base de una o dos proposiciones previamente asumidas llamadas premisas[cite: 221].


| Regla | Esquema Lógico | Nombre | Abreviatura |
| :---: | :---: | :---: | :---: |
| **Modus Ponendo Ponens** | [cite_start]$\begin{aligned} & p \rightarrow q \\ & p \\ \hline & q \end{aligned}$ [cite: 239, 240] | [cite_start]Afirmando - afirma [cite: 237] | [cite_start]M. P. [cite: 242] |
| **Modus Tollendo Tollens** | [cite_start]$\begin{aligned} & p \rightarrow q \\ & \neg q \\ \hline & \neg p \end{aligned}$ [cite: 247, 250, 252] | [cite_start]Negando - niega [cite: 247] | [cite_start]M. T. [cite: 249] |
| **Modus Tollendo Ponens** | [cite_start]$\begin{aligned} & p \vee q \\ & \neg q \\ \hline & p \end{aligned}$ [cite: 258] | [cite_start]Negando - afirma [cite: 254] | M.T. [cite_start]P. [cite: 257] |
| **Silogismo Hipotético** | [cite_start]$\begin{aligned} & p \rightarrow q \\ & q \rightarrow r \\ \hline & p \rightarrow r \end{aligned}$ [cite: 272, 274, 276] | (Similar al axioma transitivo) [cite_start][cite: 278, 279] | [cite_start]S. H. [cite: 280] |
| **Silogismo Disyuntivo** | [cite_start]$\begin{aligned} & p \vee q \\ & p \rightarrow r \\ & q \rightarrow s \\ \hline & r \vee s \end{aligned}$ [cite: 289] | [cite_start]Se concluye la disyunción entre los consecuentes [cite: 287] | [cite_start]S. D. [cite: 290] |

---

### 🔹 6. APLICACIONES TECNOLÓGICAS

[cite_start]La lógica se aplica en tres aspectos[cite: 330]:

* [cite_start]Las **contingencias** se usan para hacer circuitos de control y automatismo[cite: 332].
* [cite_start]Las **tautologías** y **contradicciones** se usan para probar la consistencia lógica interna en los algoritmos de computación[cite: 333]. [cite_start]Las **reglas de inferencia** se utilizan como *test de prueba* de esta consistencia[cite: 334].
* [cite_start]Las propiedades algebraicas y transformaciones de las sentencias lógicas se utilizan para la **construcción de circuitos integrados (CI)**, usando los operadores NOT, AND y OR[cite: 335].

---
### 🗂️ TAREAS ENTREGADAS Y ACTIVIDADES ELABORADAS

*Añade aquí los enlaces y las descripciones concisas de tus trabajos.*

#### ✏️ *Aprendizaje Autónomo*
- **2.1.** [Clasificación de las Proposiciones y Aplicación de Leyes Lógicas]
- **2.2.** [Ejercicios Resueltos de Reglas de Inferencia]

#### 🧪 *Aprendizaje Práctico Experimental*
- **2.3.** [Construcción y Análisis de Tablas de Verdad]
- **2.4.** [Simplificación de Proposiciones Compuestas usando Equivalencias]

---
### 📎 ANEXOS

* [**ANEXO 1**]
* [**ANEXO 2**]


