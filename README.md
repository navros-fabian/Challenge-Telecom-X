# 📖 Challenge Telecom X – Análisis de Evasión de Clientes
## 📌 Descripción del Proyecto
Este proyecto corresponde al Challenge Telecom X de Alura Latam, cuyo objetivo es analizar la evasión de clientes (churn) en una empresa de telecomunicaciones.
El análisis busca identificar patrones de cancelación y generar recomendaciones estratégicas basadas en datos.

## ⚙️ Instalación y Dependencias
Para ejecutar el proyecto necesitas:

Python 3.10+

Google Colab o Jupyter Notebook

Librerías:

bash
pip install pandas numpy matplotlib seaborn
## 🚀 Ejecución
Clona este repositorio:

bash
git clone https://github.com/navros-fabian/Challenge-Telecom-X.git
Abre el notebook Untitled2.ipynb en Colab o Jupyter.

Ejecuta las celdas paso a paso para reproducir el análisis.

## 📊 Flujo del Análisis
Exploración inicial de datos: revisión de columnas, tipos y estructura.

Limpieza de datos: detección y corrección de valores nulos, duplicados e inconsistencias.

Transformaciones: creación de la columna Cuentas_Diarias y estandarización de categorías.

Análisis descriptivo: métricas como media, mediana y desviación estándar.

Visualización de churn: distribución general y por variables categóricas.

Informe final: gráficos y conclusiones.

## 📈 Resultados Visuales
Distribución general de churn
 
Se observa la proporción de clientes que permanecen frente a los que se dieron de baja.

Churn por género  
El gráfico muestra diferencias en la evasión según género, aunque la tendencia es relativamente equilibrada.

Churn por tipo de contrato
  
Los clientes con contrato mensual presentan una tasa de churn significativamente mayor que aquellos con contratos de mayor duración.

## 📌 Conclusiones
La evasión está concentrada en clientes con contratos mensuales.

El método de pago también influye: ciertos perfiles muestran mayor tendencia a cancelar.

La creación de métricas como Cuentas_Diarias permite observar el comportamiento con mayor granularidad.

## 🛠️ Posibles Mejoras
Implementar modelos predictivos de churn.

Profundizar en la segmentación de clientes.

Automatizar reportes visuales para stakeholders.
