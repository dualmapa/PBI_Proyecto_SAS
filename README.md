# PBI_Proyecto_SAS
Proyecto Power BI, empresa SAS, análisis de datos



# Proyecto Power BI: Análisis de Pedidos Comerciales

## 📊 Descripción del Proyecto
Dashboard interactivo desarrollado en Power BI para analizar patrones de pedidos comerciales en Colombia, abarcando múltiples años, categorías de productos y distribuidores.

## 🎯 Objetivos
- Identificar tendencias temporales en pedidos y ventas
- Analizar la distribución geográfica de pedidos por departamento
- Evaluar el rendimiento de productos y distribuidores
- Detectar patrones estacionales y variaciones mensuales

## 📈 Características Principales

### Página 1: Consolidados de Pedidos por Años
- **Filtros interactivos**: Por año (2015-2017) y categorías de producto
- **Top 5 distribuidores**: Ranking por cantidad de pedidos y antigüedad
- **Mapa geográfico**: Distribución de pedidos por departamento
- **Análisis de costos**: Evolución histórica de costos por año
- **Segmentación por categoría**: Análisis detallado por tipo de producto
<img width="1626" height="766" alt="image" src="https://github.com/user-attachments/assets/24c0da54-d8cb-4a4d-8244-6331dbb8af41" />

### Página 2: Variación de Pedidos
- **Análisis temporal**: Variaciones mensuales y anuales
- **Top productos**: Los 3 productos más pedidos con desglose mensual
- **Análisis de rentabilidad**: Productos con mayor y menor costo
- **Tendencias estacionales**: Patrones de demanda a lo largo del año
<img width="1598" height="762" alt="image" src="https://github.com/user-attachments/assets/5fae3e4a-3387-47aa-bb09-b37de0cae286" />

## 🔧 Tecnologías Utilizadas
- **Power BI Desktop**: Desarrollo del dashboard
- **DAX**: Cálculos y medidas personalizadas
- **Power Query**: Transformación y limpieza de datos
- **Modelado de datos**: Esquema estrella optimizado

## 📊 Modelo de Datos
El proyecto utiliza un modelo estrella con las siguientes tablas:
- `BD_Pedidos` (Tabla de hechos)
- `M_Productos` (Dimensión de productos)
- `M_Distribuidores` (Dimensión de distribuidores)
- `M_Zonas` (Dimensión geográfica)
- `Calendario` (Dimensión de tiempo)
- `BD_Historico_Costos` (Tabla de hechos históricos)
- `MedidasGenerales` (Tabla de medidas DAX)
<img width="1061" height="461" alt="image" src="https://github.com/user-attachments/assets/54abe833-8b86-4e76-ad73-a9490382b9cf" />

## 📋 Insights Principales
- **Crecimiento sostenido**: Los pedidos muestran una tendencia ascendente del 2015 al 2017
- **Concentración geográfica**: Antioquia lidera en volumen de pedidos
- **Estacionalidad**: Se observan picos de demanda en ciertos meses del año
- **Diversificación de productos**: 4 categorías principales con diferentes patrones de demanda

## 🚀 Cómo Usar
1. Descargar el archivo .pbix
2. Abrir en Power BI Desktop
3. Actualizar las conexiones de datos si es necesario
4. Explorar las diferentes páginas y filtros interactivos

## 📊 Próximas Mejoras
- [ ] Implementar alertas automáticas para variaciones significativas
- [ ] Agregar análisis predictivo con tendencias futuras
- [ ] Incluir análisis de correlación entre variables
- [ ] Desarrollar versión móvil optimizada


**Alexander Marín**
https://www.linkedin.com/in/alexander-marin-pavas-bbb728a5/


---

*Este proyecto demuestra habilidades en análisis de datos, visualización, modelado dimensional y storytelling con Power BI.*
