# Análisis de Ventas

Este proyecto realiza un análisis exhaustivo de un conjunto de datos de ventas para extraer la mayor cantidad de información posible. Utiliza técnicas de agrupación, segmentación y visualización para identificar patrones y tendencias en los datos de ventas.

## Descripción

El objetivo de este proyecto es analizar los datos de ventas para obtener información valiosa sobre el comportamiento de los clientes, los productos más vendidos, los descuentos aplicados y la frecuencia de compra. Se utilizan técnicas de clustering para segmentar a los clientes en diferentes grupos según su comportamiento de compra.

## Requisitos

- Python 3.7 o superior
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook (opcional, para ejecutar el análisis en un entorno interactivo)

## Instalación

1. Clona este repositorio en tu máquina local:
    ```sh
    git clone (https://github.com/jhonta77/analicis_ventas.git)
    ```

2. Navega al directorio del proyecto:
    ```sh
    cd analisis_ventas
    ```

3. Instala las dependencias necesarias:
    ```sh
    pip install -r requirements.txt
    ```

## Uso

1. Asegúrate de tener el archivo de datos `Prueba Técnica - Contexto - CC.xlsx` en el directorio del proyecto.
2. Ejecuta el script principal para realizar el análisis:
    ```sh
    python analisis_ventas.py
    ```

## Análisis Realizados

### 1. Segmentación de Clientes

Se utiliza el algoritmo K-Means para segmentar a los clientes en tres grupos según su frecuencia de compra:
- **Baja Frecuencia**
- **Media Frecuencia**
- **Alta Frecuencia**

### 2. Análisis de Descuentos

Se identifican las transacciones que se realizaron con descuento comparando el precio real de cada transacción con el precio de lista de los productos.

### 3. Visualización de Resultados

Se generan gráficos para visualizar la distribución de los segmentos de clientes, los días con mayor porcentaje de descuentos y la frecuencia de compra de los clientes en esos días.

### 4. Suma de Volúmenes de Venta Positiva por Segmento

Se calcula la suma de los volúmenes de venta positiva para cada segmento de clientes.

## Ejemplo de Resultados

### Distribución de Segmentos

```plaintext
               Porcentaje  Valores  VolumenTotal
Segmento                                       
Baja Frecuencia       50.0       50       500000
Media Frecuencia      30.0       30       300000
Alta Frecuencia       20.0       20       200000
