# FCD-20252-GeraldineAcevedoRestrepo

## Universidad de Antioquia · Facultad de Ingeniería

Curso: Fundamentos de Ciencia de Datos

Docente: María Bernarda Salazar Sánchez, Ph.D.

Estudiante: Geraldine Acevedo Restrepo

Correo: geraldine.acevedo@udea.edu.co

## Descripción General del Proyecto

Este proyecto utiliza un dataset correspondiente a los **registros de campañas de marketing directo de una institución bancaria portuguesa**.  
Las campañas se realizaron principalmente a través de **llamadas telefónicas**, con el objetivo de convencer a los clientes de **suscribir un depósito a plazo fijo**.  

Cada fila del dataset representa un **cliente contactado en una campaña**, e incluye información **personal, financiera y de la interacción de marketing**.

## Objetivo del Proyecto
Analizar las características de los clientes y las campañas de marketing con el fin de **identificar los factores que influyen en la aceptación de un depósito a plazo fijo**, utilizando análisis exploratorio y técnicas de modelado predictivo.

---

## Características del Dataset

- **Número de instancias:** 45.211 registros  
- **Número de variables:** 17 (16 predictoras + 1 objetivo)

### Variable objetivo
- **`y`**: indica si el cliente finalmente suscribió el depósito a plazo fijo (`yes` o `no`).

### Datos del cliente
- `age`: edad  
- `job`: profesión  
- `marital`: estado civil  
- `education`: nivel educativo  
- `default`: si tiene impago de crédito  
- `housing`: si tiene préstamo hipotecario  
- `loan`: si tiene otro préstamo personal  

### Datos de contacto / campaña actual
- `contact`: tipo de comunicación (fijo o celular)  
- `month`: mes del último contacto  
- `day`: día del mes del último contacto  
- `duration`: duración de la llamada en segundos  
- `campaign`: número de contactos durante esta campaña  

### Historial de campañas previas
- `pdays`: días desde el último contacto previo (`-1` si nunca fue contactado)  
- `previous`: número de contactos previos  
- `poutcome`: resultado de la campaña anterior  

### Variable financiera
- `balance`: saldo medio anual en euros en la cuenta bancaria del cliente  

---

## Descripción primera entrega proyecto aula
El colab py_Geraldine_Acevedo_Restrepo_01_avances que se encuentra en la carpeta proyecto_aula corresponde al primer entregable del curso Fundamentos de Ciencia de Datos  para el Proyecto Aula.
El trabajo desarrolla un Análisis Exploratorio de Datos (EDA) sobre el dataset público Bank Marketing, proveniente de campañas de marketing directo de una institución bancaria portuguesa.

## Objetivo primera entrega proyecto aula
Analizar las características de los clientes y las campañas de marketing con el fin de identificar los factores que influyen en la aceptación del depósito a plazo fijo, aplicando técnicas de análisis exploratorio, visualización y detección de valores atípicos.

## Estructura del repositorio

📂 FCD-20252-GeraldineAcevedoRestrepo/

📁 articulo/ – Recursos teóricos o artículos de referencia

📁 datos/ – Dataset original

📁 proyecto_aula/ – Notebook principal con el EDA completo

📁 recursos/ – Imágenes, gráficos y recursos visuales del informe

📁 sesiones_practicas/ – Prácticas previas realizadas en Colab

📄 README.md – Descripción, objetivo y estructura del proyecto

## Variables seleccionadas primera entrega proyecto aula

| Variable      | Tipo                 | Definición                                                                  | Fuente             |
| ------------- | -------------------- | --------------------------------------------------------------------------- | ------------------ |
| **age**       | Continua (años)      | Edad del cliente en años.                                                   | UCI Bank Marketing |
| **balance**   | Continua (euros)     | Saldo promedio anual de la cuenta bancaria (puede ser negativo o positivo). | UCI Bank Marketing |
| **duration**  | Continua (segundos)  | Duración de la última llamada de contacto en la campaña.                    | UCI Bank Marketing |
| **marital**   | Discreta (categoría) | Estado civil del cliente (*single*, *married*, *divorced*).                 | UCI Bank Marketing |
| **education** | Discreta (categoría) | Nivel educativo (*primary*, *secondary*, *tertiary*, *unknown*).            | UCI Bank Marketing |
| **housing**   | Discreta (binaria)   | Indica si el cliente tiene un préstamo de vivienda (*yes* / *no*).          | UCI Bank Marketing |

## Contenido del notebook py_Geraldine_Acevedo_Restrepo_01_avances

🔹 Selección y documentación de variables

Identificación de 3 variables continuas y 3 categóricas.

Tabla de metadatos (nombre, tipo, definición y fuente).

🔹 Análisis univariado

Estadísticos descriptivos.

Histogramas y boxplots por variable.

Interpretación de forma, asimetría y dispersión.

🔹 Análisis bivariado y multivariado

Matriz de correlación y diagramas de dispersión.

Tablas cruzadas y pruebas Chi² entre variables categóricas.

Interpretaciones sobre relaciones socioeconómicas y financieras.

🔹 Detección de valores atípicos

Métodos aplicados: IQR (3×IQR), DBSCAN, Isolation Forest.

Identificación, análisis e interpretación de outliers.

Decisiones sobre conservación o transformación de los datos.

🔹 Comunicación de resultados

Síntesis de hallazgos por dimensión (sociodemográfica, financiera, conductual, relacional y anomalías).

Conclusiones globales del EDA.

## Conclusiones generales

Predominan clientes adultos casados con educación media o superior, perfil demográficamente estable.

Se evidencia una alta desigualdad en los saldos bancarios, con pocos clientes de gran capital.

Las llamadas más largas podrían reflejar mayor interés o efectividad comercial.

Existen asociaciones débiles pero coherentes entre educación, estado civil y préstamos.

Entre el 2–5 % de los registros son outliers reales; se recomienda conservarlos y aplicar escalado robusto o transformaciones para modelado.

##Referencias

Dataset original: UCI Machine Learning Repository – Bank Marketing Dataset

Docente: María Bernarda Salazar Sánchez, Ph.D. – Departamento de Ingeniería de Sistemas

Universidad de Antioquia, Facultad de Ingeniería, 2025-2
---

## Instrucciones para ejecutar los notebooks

El análisis se encuentra implementado en un **Google Colab Notebook**.  
No es necesario descargar el dataset manualmente, ya que se **extrae automáticamente desde la fuente oficial** durante la ejecución.

### Pasos para ejecutar:
1. Abrir el notebook en **Google Colab**.  
2. Asegurarse de estar logueado en una **cuenta de Google**.  
3. Ejecutar todas las celdas **de arriba hacia abajo** (menú: *Runtime > Run all* o *Entorno de ejecución > Ejecutar todo*).  
4. El proceso descargará automáticamente los datos y generará todas las visualizaciones y resultados.


## Nombres y correo del estudiante
- Geraldine Acevedo Restrepo
- geraldine.acevedo@udea.edu.co


