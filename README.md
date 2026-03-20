# 📦 Dashboard de Inventario – Industria Alimenticia / Heladería

**Herramientas:** Power BI · Excel · DAX  
**Sector:** Industria alimenticia – producción y distribución de helados  
**Tipo de análisis:** Control de inventario, clasificación ABC, alertas de stock crítico

---

## 🎯 Problema que resuelve

En entornos de producción de alimentos, la falta de visibilidad sobre el stock genera dos problemas críticos: sobrestock de productos de bajo valor y desabastecimiento de insumos clave. Este proyecto simula un escenario real de una heladería industrial para responder tres preguntas concretas:

- ¿Qué productos terminados representan el mayor valor del inventario?
- ¿Qué materias primas están en estado crítico y requieren reposición urgente?
- ¿Cómo se distribuye el valor económico entre insumos y productos terminados?

---

## 📊 Estructura del dashboard

El proyecto está compuesto por tres hojas interactivas:

### Hoja 1 – Inventario de productos terminados (Industria Alimenticia)
- KPIs principales: total de productos, stock total en latas, productos críticos y valor del inventario
- Gráfico de barras: ranking de productos por cantidad de latas
- Tabla de control: stock actual vs. stock mínimo con indicador de estado (OK / Crítico)
- Tabla de clasificación ABC: valor económico por producto y porcentaje sobre el total
- Filtros interactivos por producto y por clasificación ABC

### Hoja 2 – Control de materias primas (Heladería)
- KPIs: total de insumos, stock total, promedio por insumo, mayor cantidad registrada e insumos críticos
- Gráfico de barras: stock actual por insumo ordenado de mayor a menor
- Tabla de control de stock mínimo con semáforo de estado (OK / Crítico)
- Filtro interactivo por estado de stock

### Hoja 3 – Vista consolidada (Insumos vs. Productos)
- Comparación lado a lado del stock de insumos y productos terminados
- Gráfico de valor de stock por tipo, mostrando la proporción económica entre ambas categorías
- Vista ejecutiva para toma de decisiones de reposición

---

## ⚙️ Técnicas y herramientas aplicadas

- **Modelado de datos** en Power BI con relaciones entre tablas de productos, insumos y stock mínimo
- **Medidas DAX** para KPIs dinámicos: total de stock, valor de inventario, conteo de críticos y clasificación ABC
- **Formato condicional** para identificar visualmente el estado del stock (verde = OK, rojo = Crítico)
- **Segmentadores interactivos** para filtrado por producto, clasificación ABC y estado
- **Clasificación ABC** basada en valor económico acumulado: A (top 80%), B (siguiente 15%), C (restante 5%)
- **Diseño coherente** con paleta de colores personalizada y tipografía consistente en las tres hojas

---

## 💡 Principales hallazgos

- De 39 productos terminados, **7 se encuentran en estado crítico** de stock, representando un riesgo operativo inmediato
- **Chocolate Marroc X 7.3 KG** lidera el inventario en cantidad (71 latas) y también encabeza la clasificación A por valor económico
- En materias primas, **29 de 52 insumos están en estado crítico**, con Baldes de Helado Plásticos y Azúcar como los de mayor volumen
- Los insumos representan significativamente más valor de inventario que los productos terminados, lo que indica que la mayor inversión está en la etapa de producción

---

## 🗂️ Archivos del repositorio

```
📁 dashboard-inventario-heladeria/
├── 📊 dashboard_inventario.pbix       # Archivo Power BI principal
├── 📁 capturas/
│   ├── hoja1_productos_terminados.png
│   ├── hoja2_materias_primas.png
│   └── hoja3_vista_consolidada.png
└── 📄 README.md
```

---

## 👤 Sobre el autor

**Guido Maximiliano González**  
Data Analyst Jr. | Power BI · Excel · SQL  
Experiencia en logística, control de stock y gestión de inventarios en industria alimenticia .

[LinkedIn](https://www.linkedin.com/in/guido-gonzalez-/) · [gonzalezguidolujan@gmail.com](mailto:gonzalezguidolujan@gmail.com)
