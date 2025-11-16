<div align="center">

### 💻✨ UNIDAD 1: LÓGICA ✨💻

</div>

---

## 📘 Índice de Contenidos

### 1. CONTENIDOS DE LA UNIDAD

* **1.1.** Lógica y Lógica Matemática
* **1.2.** Proposiciones Lógicas y Conectivas
* **1.3.** Tablas de Verdad: Tautología, Contradicción y Contingencia
* **1.4.** Leyes Lógicas
* **1.5.** Reglas de Inferencia
* **1.6.** Aplicaciones Tecnológicas

### 2. TAREAS ENTREGADAS Y ACTIVIDADES ELABORADAS

- **2.1. [Aprendizaje Práctico Experimental (APE)](Unidad%201.md#%EF%B8%8F21-aprendizaje-pr%C3%A1ctico-experimental-ape)**
- **2.2. [Aprendizaje en Contacto con el Docente (ACD)](Unidad%201.md#%EF%B8%8F-22-aprendizaje-en-contacto-con-el-docente-acd)**
- **2.3. [Aprendizaje Autónomo (AA)](Unidad%201.md#%EF%B8%8F-23-aprendizaje-aut%C3%B3nomo-aa)**

### 3. CONCLUSIONES PERSONALES

---

## 🗂️ 1. CONTENIDOS DE LA UNIDAD

### ✨ Pequeña introducción general

A lo largo de la unidad se desarrollaron conceptos esenciales de la lógica matemática que permiten razonar con precisión y estructurar ideas de manera formal, especialmente útil en la ingeniería en computación. Para fortalecer el aprendizaje, también se trabajaron ejercicios prácticos de **tablas de verdad**, **leyes lógicas** y **reglas de inferencia**, los cuales ayudaron a comprender cómo se validan argumentos y cómo se pueden simplificar expresiones lógicas.


### 🔹 1.1. Lógica y Lógica Matemática

* **Lógica:** ciencia formal que estudia la inferencia válida y la estructura de los argumentos.
* **Lógica matemática:** aplica métodos formales (proposiciones, tablas, reglas) para razonar y verificar argumentos; fundamental en demostraciones, algoritmos y verificación de programas.



### 🔹 1.2. Proposiciones Lógicas y Conectivas

* **Proposición:** enunciado que puede ser **verdadero (V)** o **falso (F)**.
* **Conectivos básicos:**

  * Negación: ¬p
  * Conjunción: p ∧ q
  * Disyunción: p ∨ q
  * Condicional: p → q
  * Bicondicional: p ↔ q
* **Jerarquía de operadores:**
  **Paréntesis** ➝ **Negación (¬)** ➝ **Conjunción (∧)** ➝ **Disyunción (∨)** ➝ **Condicional**



### 🔹 1.3. Tablas de Verdad: Tautología, Contradicción y Contingencia

* **Tabla de verdad:** muestra todos los valores posibles para una proposición compuesta.
* **Tautología:** siempre verdadera. Ejemplo: p ∨ ¬p.
* **Contradicción:** siempre falsa. Ejemplo: p ∧ ¬p.
* **Contingencia:** puede ser verdadera o falsa dependiendo del caso.

 ***Ejemplo de ejercicio***

 Averiguar si son equivalentes las proposiciones:
 
 **(p ∧ q) → r**     *Y*    **(p → r) ∧  (q → r)**
 
 <p align= "center"><img width="642" height="300" alt="image" src="https://github.com/user-attachments/assets/ee80e3e0-285c-4607-b316-39898c90ebdc" />
</p>



### 🔹 1.4. Leyes Lógicas 

* **Doble negación:** ¬(¬P) ⇔ P
* **De Morgan:**

  * ¬(P ∧ Q) ⇔ ¬P ∨ ¬Q
  * ¬(P ∨ Q) ⇔ ¬P ∧ ¬Q
* **Conmutativa:**

  * P ∧ Q ⇔ Q ∧ P
  * P ∨ Q ⇔ Q ∨ P
* **Asociativa:**

  * (P ∧ Q) ∧ R ⇔ P ∧ (Q ∧ R)
  * (P ∨ Q) ∨ R ⇔ P ∨ (Q ∨ R)
* **Distributiva:**

  * P ∧ (Q ∨ R) ⇔ (P ∧ Q) ∨ (P ∧ R)
  * P ∨ (Q ∧ R) ⇔ (P ∨ Q) ∧ (P ∨ R)
* **Idempotencia:**

  * P ∧ P ⇔ P
  * P ∨ P ⇔ P
* **Complemento:**

  * P ∧ ¬P ⇔ F
  * P ∨ ¬P ⇔ V
* **Identidad:**

  * P ∧ T ⇔ P
  * P ∨ F ⇔ P



### 🔹 1.5. Reglas de Inferencia (principales)

* **Modus Ponens (M.P.):** si (p → q) y p son verdaderos, entonces q.
* **Modus Tollens (M.T.):** si (p → q) y ¬q, entonces ¬p.
* **Modus Tollendo Ponens:** si (p ∨ q) y ¬p, entonces q.
* **Silogismo Hipotético:** de p → q y q → r se deduce p → r.
* **Silogismo Disyuntivo:** combina disyunciones con condicionales para obtener conclusiones lógicas válidas.

 ***📌 Ejemplo de ejercicio***

<div align = "center">

 **Premisa 1: p → S**<br>
**Premisa 2: ~S**<br>
**Premisa 3: ~p - t**<br>      
Premisa 4: ~p          (M.T.T. (1,2))<br>
Premisa 5: t           (M.P.P. (3,4))<br>

**∴ t**
<div>

### 🔹 1.6. Aplicaciones Tecnológicas

* Diseño y simplificación de **circuitos digitales** (NOT, AND, OR, NAND, NOR, XOR).
* Verificación lógica de **algoritmos y programas**.
* Automatización y control en **sistemas electrónicos y PLCs**.
* Base para **inteligencia artificial**, toma de decisiones y validación de procesos.

---

## 🗂️ 2. TAREAS ENTREGADAS Y ACTIVIDADES ELABORADAS

### ✏️2.1. [**APRENDIZAJE PRÁCTICO EXPERIMENTAL (APE)**](Unidad%201/APE)

#### ⭐ *APE 1: Resolución de Ejercicios*

En esta actividad se desarrollaron ejercicios de práctica aplicando proposiciones, negaciones, conectivos lógicos y tablas de verdad.
Se formaron los grupos de trabajo para todo el ciclo, y mi grupo se llamó **NeoCore**.
Las tareas consistieron en:

* Identificar y clasificar proposiciones.
* Escribir negaciones correctamente.
* Construir tablas de verdad.
* Traducir entre lenguaje natural y simbólico.
* Evaluar expresiones con valores de verdad.

### ✏️ 2.2. [**APRENDIZAJE EN CONTACTO CON EL DOCENTE (ACD)**](Unidad%201/ACD)

#### ⭐ *ACD 1: Lógica Proposicional, Conectores y Tablas de Verdad*

Este archivo corresponde a la presentación utilizada durante la exposición de los temas introductorios.
Contiene definiciones, ejemplos aplicados y esquemas visuales que resumen la información más importante.
Refleja el trabajo colaborativo, la capacidad de síntesis y la comprensión general de la unidad.

#### ⭐ *ACD 2: Implicaciones, Equivalencias y Razonamiento Deductivo*

Incluye explicaciones detalladas de cada ley lógica, acompañadas de ejemplos prácticos que muestran cómo se aplican para simplificar expresiones y validar argumentos.
Los ejercicios resueltos permiten observar cómo las leyes y reglas de inferencia ayudan a obtener conclusiones válidas.

### ✏️ 2.3. [**APRENDIZAJE AUTÓNOMO (AA)**](Unidad%201/AA)

#### ⭐ *AA 1: Lectura y Ejercicios*

Se desarrollaron dos ejercicios aplicando reglas de inferencia.
El primero consistió en extraer premisas de un texto y deducir su conclusión.
El segundo fue un ejercicio enviado por el docente.
Esta práctica permitió reforzar el razonamiento lógico para obtener una buena calificación en el examen de la unidad.

---

## 🗂️ 3. CONCLUSIONES PERSONALES

En esta unidad quedó claro que las **matemáticas discretas** son un pilar fundamental en la ingeniería en computación. A partir del trabajo realizado, concluyo que:

* 📌 **Es indispensable dominar sus conceptos** para lograr un desempeño sólido en la carrera.
* 🧠 **El uso de tablas de verdad y reglas de inferencia fortalece el razonamiento lógico**, clave en la resolución de problemas.
* 👩‍🏫 **La metodología de aula invertida fue muy útil**, ya que permitió prepararnos previamente y comprender mejor los temas.
* 🎤 **Ayudó a perder el miedo a exponer** y a desenvolvernos con mayor seguridad frente a los compañeros.
* ⭐ **El método de calificación del docente impulsa a la mejora continua y a la excelencia.**

