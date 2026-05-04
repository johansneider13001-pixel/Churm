# Proyecto de Business Intelligence: Análisis de Cancelación de Clientes (Churn Analytics)

## 1. Descripción del Proyecto
Este proyecto de análisis de datos y Business Intelligence se enfoca en comprender la rotación de clientes (Churn) en una empresa de servicios de telecomunicaciones. El objetivo es identificar por qué los clientes cancelan su suscripción y qué perfiles son más vulnerables.

### 📋 Objetivos del Negocio
* **Analizar la tasa de cancelación:** Medir el impacto económico de la pérdida de clientes.
* **Identificar factores de riesgo:** Determinar el comportamiento según tipo de contrato, servicios y métodos de pago.
* **Proponer estrategias de retención:** Crear acciones orientadas a los segmentos con mayor riesgo de abandono.

---

## 2. Indicadores Clave (KPIs)
A partir de la exploración de los datos, los principales indicadores del dashboard son:
* **Total de Clientes:** 7,042
* **Clientes de Abandono (Churn):** 1,869
* **Tasa de Abandono (Churn Rate):** 26.54%
* **Ingreso Promedio Mensual (ARPU):** $64.76

---

## 3. Hallazgos y Storytelling (Análisis Visual)

### 3.1. Contrato y Relación con el Abandono
* **Month-to-month:** Es el tipo de contrato donde se concentra la mayor cantidad de cancelaciones (1,655 de los 1,869 casos). Los clientes sin un compromiso a largo plazo son los más propensos a dejar el servicio.
* **Larga duración:** Los clientes con contratos de 1 o 2 años presentan niveles de abandono mínimos.

### 3.2. Servicios Contratados
* **Fibra Óptica:** Representa el 69.4% de los abandonos en servicios de internet (1,297 clientes), lo que sugiere que existe un problema de satisfacción, valor percibido o fallas en este servicio específico frente a los usuarios de DSL o sin internet.

### 3.3. Método de Pago
* **Electronic Check:** Es el método de pago más utilizado por los clientes que deciden cancelar (1,071 abandonos), superando con creces a otros métodos de pago.

---

## 4. Conclusiones y Recomendaciones

### Conclusiones
* La tasa de abandono del 26.54% es significativa y afecta directamente los ingresos de la compañía.
* Los clientes nuevos, con contratos de mes a mes y aquellos con Internet por fibra óptica son los de mayor riesgo.

### Recomendaciones
1. **Incentivar contratos a largo plazo:** Ofrecer promociones o descuentos para migrar a los clientes *Month-to-month* a contratos de 1 o 2 años y asegurar su retención.
2. **Revisar el servicio de Fibra Óptica:** Investigar la calidad, latencia y precio del servicio de fibra óptica, dado que concentra la mayor cantidad de bajas.
3. **Simplificar la experiencia de pago:** Evitar fricciones en los cobros realizados por *Electronic Check* o incentivar el uso de métodos automatizados que reducen el churn.
