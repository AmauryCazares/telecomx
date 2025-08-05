# telecomx
Implementación de analisis de datos en un caso real

# Análisis de Evasión de Clientes (Churn)

Este proyecto tiene como objetivo analizar los factores que influyen en la cancelación de servicios por parte de los clientes. A través del uso de Python, pandas y matplotlib, se realiza un análisis exploratorio de datos para encontrar patrones que permitan predecir y reducir la tasa de *Churn*.

## Estructura del Proyecto

.
├── datos/
│ └── clientes.csv # Dataset original con información de clientes
├── visualizaciones/
│ ├── genero_churn.png
│ ├── tipo_contrato_churn.png
│ ├── forma_pago_churn.png
│ └── servicio_internet_churn.png
├── churn_analisis.ipynb # Notebook principal con el análisis de datos
├── informe_churn.pdf # Informe final estructurado con conclusiones
└── README.md # Este archivo

markdown
Copiar
Editar

## Objetivo

Identificar patrones y características comunes entre los clientes que cancelan el servicio para proponer estrategias de retención más efectivas.

## Tecnologías Utilizadas

- Python 3.x
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

## Pasos del Proyecto

### 1. Limpieza de Datos
- Se eliminaron valores nulos y duplicados.
- Se convirtieron variables categóricas al tipo adecuado.
- Se filtraron estados no válidos.

### 2. Análisis Exploratorio
- Se generaron visualizaciones para comparar clientes que **permanecieron** vs **cancelaron**.
- Se analizaron variables clave: género, tipo de contrato, forma de pago y servicio de internet.

### 3. Conclusiones
- Los contratos mensuales y pagos en efectivo presentan mayor probabilidad de *Churn*.
- Clientes con pagos automáticos y contratos a largo plazo tienen mayor fidelidad.

### 4. Recomendaciones
- Promover contratos anuales/bianuales.
- Incentivar el uso de tarjetas o pagos automáticos.
- Mejorar la experiencia del servicio de Internet.


## Requisitos

- Python 3.8 o superior
- Jupyter Notebook
- Librerías: `pandas`, `matplotlib`, `seaborn`

Puedes instalar las dependencias necesarias con:

```bash
pip install pandas matplotlib seaborn
