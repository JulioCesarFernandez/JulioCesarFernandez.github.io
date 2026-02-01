---
title: "The Physics of Reliability: 7 Months as an EEE Manager at Airbus Crisa"
layout: single
categories:
  - Tech
tags:
  - Aerospace
  - EEE Components
  - Reliability Engineering
  - ECSS Standards
---

Tras siete meses integrando el equipo de componentes de **Airbus Crisa**, he comprendido que la ingeniería de componentes (EEE Parts Management) es el pilar sobre el que descansa la integridad de cualquier sistema espacial. En este entorno, la selección de un componente no es una decisión administrativa, sino un ejercicio de **Física de Fallos**.

## El Porqué: Teoría de la Fiabilidad y el Entorno Espacial

En el espacio, los componentes se enfrentan a condiciones extremas: radiación (TID, SEE), ciclos térmicos severos y vacío. La base teórica de nuestro trabajo se fundamenta en la **Teoría de la Fiabilidad**. Nuestra meta es garantizar que la función de supervivencia $R(t)$ del sistema se mantenga cercana a la unidad durante el tiempo de vida de la misión ($t_{mission}$):

$$R(t) = e^{-\int_{0}^{t} \lambda(u) \, du}$$

Donde $\lambda$ representa la tasa de fallos. Para minimizar $\lambda$, aplicamos el concepto de **Derating** (reducción de carga), operando los componentes significativamente por debajo de sus límites máximos de catálogo para extender su **MTTF** (Mean Time To Failure).



## El Cómo: Aplicación de Estándares ECSS y Control de Calidad

Mi labor diaria consiste en cerrar el lazo entre los requisitos de diseño y la disponibilidad de componentes que cumplan con la normativa **ECSS-Q-ST-60C**. Este proceso implica:

1.  **Selección y Evaluación:** Análisis de la **SOA (Safe Operating Area)** y cumplimiento de requerimientos de radiación.
2.  **Product Assurance (PA):** Revisión de **PADs** (Part Approval Documents) y coordinación de ensayos técnicos.
3.  **Validación Física:** Supervisión de procesos de **DPA** (Destructive Physical Analysis) y **LAT** (Lot Acceptance Tests) para asegurar que el lote de producción no presenta anomalías estructurales.

## El Qué: La Curva de Aprendizaje como Sistema de Lazo Cerrado

Más allá del hardware, estos 7 meses han sido una lección de **Teoría de Control** aplicada al desarrollo personal. He experimentado lo que denomino el "Ciclo de Convergencia de Conocimiento":

* **Estado de Error Alto:** Al recibir una nueva tarea compleja, el sistema entra en transitorio. La desorientación inicial es simplemente la detección de un error de consigna entre lo que el proyecto exige y mi conocimiento actual.
* **Acción de Control:** Mediante el estudio intensivo y el apoyo de mis compañeros (quienes actúan como el bloque de realimentación positiva), aplico un esfuerzo de aprendizaje para reducir el error.
* **Estado Estacionario:** Una vez dominada la tarea, el sistema se estabiliza... hasta que llega un nuevo reto que cambia el *setpoint* y reinicia el proceso.



[Image of a closed-loop control system block diagram]


## Conclusión y Agradecimientos

Trabajar en **Airbus Crisa** me ha enseñado que la excelencia técnica es un esfuerzo de equipo. La complejidad de un satélite es tal que ninguna mente individual puede abarcarla; la comunicación y el soporte mutuo son tan críticos como la integridad de una señal en un bus CAN. 

Sigo aprendiendo, iterando y ajustando mis parámetros para contribuir a que la tecnología española siga alcanzando el espacio con la máxima fiabilidad.

---
