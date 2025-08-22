# FCD-20252-GeraldineAcevedoRestrepo

## Descripción General del Proyecto

Este proyecto utiliza un dataset correspondiente a los **registros de campañas de marketing directo de una institución bancaria portuguesa**.  
Las campañas se realizaron principalmente a través de **llamadas telefónicas**, con el objetivo de convencer a los clientes de **suscribir un depósito a plazo fijo**.  

Cada fila del dataset representa un **cliente contactado en una campaña**, e incluye información **personal, financiera y de la interacción de marketing**.

---

## Características del Dataset

- **Número de instancias:** 45.211 registros  
- **Número de variables:** 17 (16 predictoras + 1 objetivo)

### Variable objetivo
- **`y`**: indica si el cliente finalmente suscribió el depósito a plazo fijo (`yes` o `no`).

### 👤 Datos del cliente
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

## Objetivo del Proyecto
Analizar las características de los clientes y las campañas de marketing con el fin de **identificar los factores que influyen en la aceptación de un depósito a plazo fijo**, utilizando análisis exploratorio y técnicas de modelado predictivo.


## Instrucciones para ejecutar los notebooks

El análisis se encuentra implementado en un **Google Colab Notebook**.  
No es necesario descargar el dataset manualmente, ya que se **extrae automáticamente desde la fuente oficial** durante la ejecución.

### Pasos para ejecutar:
1. Abrir el notebook en **Google Colab**.  
2. Asegurarse de estar logueado en una **cuenta de Google**.  
3. Ejecutar todas las celdas **de arriba hacia abajo** (menú: *Runtime > Run all* o *Entorno de ejecución > Ejecutar todo*).  
4. El proceso descargará automáticamente los datos y generará todas las visualizaciones y resultados.


## Nombres y correo del estudiante
Geraldine Acevedo Restrepo
geraldine.acevedo@udea.edu.co


