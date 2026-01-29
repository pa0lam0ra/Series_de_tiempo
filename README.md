# Series_de_tiempo
# 📈 Series de Tiempo – Fundamentos y Aplicaciones

Repositorio académico para el estudio **teórico y aplicado de series de tiempo**, con énfasis en modelos clásicos y financieros.  
El objetivo es comprender los **procesos estocásticos**, la **identificación, estimación y validación de modelos**, y su aplicación en **datos económicos y financieros**.

---

## 📚 Contenido del curso

### 1️⃣ Introducción a Series de Tiempo
- ¿Qué es una serie de tiempo?
- Componentes:
  - Tendencia
  - Estacionalidad
  - Ciclo
  - Ruido
- Estacionariedad:
  - Estricta
  - Débil
- Transformaciones comunes:
  - Diferenciación
  - Logaritmos
  - Desestacionalización

---

### 2️⃣ Procesos Estocásticos y Modelos ARIMA

#### 🔹 Modelos ARIMA(p, d, q)
- **AR (Autorregresivo)**
- **MA (Media Móvil)**
- **Integración (diferenciación)**
- Interpretación económica y estadística
- Condiciones de estacionariedad e invertibilidad

#### 🔹 Modelos SARIMA(p, d, q)(P, D, Q)<sub>s</sub>
- Extensión estacional de ARIMA
- Componentes estacionales
- Periodicidad \( s \)
- Casos típicos (mensual, trimestral)

---

### 📊 Identificación y Diagnóstico
- Función de autocorrelación (**ACF**)
- Función de autocorrelación parcial (**PACF**)
- Correlogramas
- Diagnóstico de residuos

---

### 📐 Estimación y Selección de Modelos
- Función de **log-verosimilitud**
- **ECF** (Empirical Characteristic Function)
- Criterios de información:
  - **AIC (Akaike Information Criterion)**
  - **BIC (Bayesian Information Criterion)**
- Comparación de modelos

---

### 3️⃣ Series de Tiempo Financieras

#### 💰 Características de series financieras
- Rendimientos
- Volatilidad
- Clustering de volatilidad
- No normalidad
- Leptocurtosis

---

### 📉 Modelos de Volatilidad

#### 🔹 GARCH
- ARCH
- GARCH(p, q)
- Interpretación financiera
- Persistencia de volatilidad

#### 🔹 EGARCH
- Efecto apalancamiento
- Asimetría
- Ventajas frente a GARCH clásico

---

## 🧠 Objetivos del repositorio
- Entender la teoría detrás de los modelos de series de tiempo
- Aplicar modelos ARIMA/SARIMA a datos reales
- Modelar y analizar volatilidad financiera
- Comparar modelos usando criterios estadísticos
- Desarrollar intuición econométrica

---

## 🛠️ Tecnologías y Herramientas
- Python / R
- NumPy / pandas
- statsmodels
- arch
- Jupyter Notebooks

---

## 📂 Estructura sugerida del repositorio
