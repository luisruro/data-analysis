## **Supermarket Sales Project**

### **1. Python**
#### **Descripción**
Análisis de datos enfocado en limpieza, transformación, estadística descriptiva y visualización.

#### **Requerimientos**
1. **Limpieza y transformación de datos**:
   - Eliminar datos duplicados en el dataset.
   - Rellenar filas con valores en blanco utilizando valores promedio o medianos.
   - Estandarizar nombres de columnas a un formato consistente (por ejemplo, en minúsculas y sin espacios).
   - Convertir el formato de la columna de fecha a un `datetime` adecuado.

2. **Análisis de ventas**:
   - Calcular el total de ventas por sucursal y tipo de cliente (miembro/no miembro).
   - Identificar los días con mayores ingresos.
   - Calcular el ticket promedio por cliente.
   - Analizar la distribución de métodos de pago.

3. **Estadísticas descriptivas**:
   - Obtener el promedio, mediana, moda y desviación estándar de las ventas totales por sucursal.
   - Comparar el comportamiento de ventas entre géneros (femenino/masculino).

4. **Visualización de datos**:
   - Crear gráficos de barras para comparar ingresos por sucursal.
   - Crear un gráfico de pastel que muestre la distribución de métodos de pago.
   - Crear una gráfica de línea para analizar la tendencia de ingresos diarios.

---

### **2. SQL**
#### **Descripción**
Gestión de una base de datos relacional para almacenar y analizar información de ventas y generar reportes empresariales.

#### **Requerimientos**
1. **Modelado y creación de base de datos**:
   - Diseñar una base de datos con las siguientes tablas:
     - **ventas**: Contiene la fecha, sucursal, cliente, producto, cantidad, método de pago y total de la venta.
     - **clientes**: Incluye información de género, tipo (miembro/no miembro) y región.
     - **productos**: Detalles como nombre, categoría y precio.
     - **finanzas**: Datos de ingresos, costos e impuestos.

2. **Consultas y reportes**:
   - Calcular el total de ingresos por sucursal y categoría de producto.
   - Identificar los productos más vendidos por categoría.
   - Obtener el número de transacciones por género y método de pago.
   - Reportar ingresos mensuales totales e impuestos generados por sucursal.

3. **Gestión de inventario**:
   - Listar los productos con menos de 50 unidades en stock.
   - Predecir los niveles de stock necesarios para los próximos 3 meses basado en las ventas actuales.

---

### **3. Excel**
#### **Descripción**
Generación de reportes, análisis financiero y visualización de datos utilizando hojas de cálculo.

#### **Requerimientos**
1. **Carga y estructuración**:
   - Dividir el dataset en hojas de Excel por categoría: ventas, clientes, productos, y finanzas.
   - Aplicar formato condicional para resaltar valores atípicos en los ingresos.

2. **Análisis financiero**:
   - Crear una tabla dinámica para calcular el total de ventas por sucursal y tipo de cliente.
   - Calcular el ingreso promedio por transacción y el margen bruto por categoría de producto.
   - Analizar los impuestos generados por mes.

3. **Visualización**:
   - Crear gráficos dinámicos:
     - Barras apiladas para mostrar ventas por sucursal y género.
     - Líneas para analizar la tendencia de ingresos mensuales.

4. **Automatización**:
   - Implementar macros para actualizar los reportes dinámicos automáticamente.

---

### **4. Power BI**
#### **Descripción**
Creación de dashboards interactivos para presentar los datos de manera visual y efectiva.

#### **Requerimientos**
1. **Integración de datos**:
   - Conectar Power BI con la base de datos SQL creada previamente.
   - Limpiar y transformar datos para que sean compatibles con el modelo visual.

2. **Creación de dashboards**:
   - Crear un tablero principal con:
     - Total de ventas por sucursal.
     - Distribución de métodos de pago.
     - Comparación de ingresos por tipo de cliente.
   - Un tablero financiero que incluya:
     - Márgenes brutos.
     - Impuestos generados por sucursal.
     - Ingresos mensuales.

3. **Análisis avanzado**:
   - Implementar filtros interactivos para analizar datos por categoría, sucursal y cliente.
   - Visualizar la distribución geográfica de las ventas.

4. **Predicción visual (opcional)**:
   - Usar líneas de tendencia para estimar los ingresos en los próximos meses.

---

## **Información a Extraer y Analizar**

### **Ventas**
- Total de ingresos por sucursal, método de pago y tipo de cliente.
- Tendencias de ventas diarias y mensuales.
- Comparación entre sucursales y días de mayor actividad.

### **Clientes**
- Distribución de género y tipo de cliente.
- Métodos de pago preferidos por región.
- Comportamiento de compra según categorías de productos.

### **Productos**
- Productos más vendidos por sucursal.
- Categorías con menos ventas (oportunidad de promociones).
- Análisis de inventarios.

### **Finanzas**
- Ingresos brutos, costos e impuestos generados.
- Márgenes por categoría y sucursal.
- Comparación de desempeño financiero mensual.

---

## **Cómo Usar Este Repositorio**
1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/luisruro/data-analysis.git
   cd supermarket_sales
