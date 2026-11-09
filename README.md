# 📊 Sales Executive Dashboard

Dashboard ejecutivo de ventas orientado a la toma de decisiones estratégicas: KPIs claros, análisis por vendedor, categoría y medio de pago, y pronóstico de ventas a 3, 6 y 12 meses con escenarios.

**▶ Demo en vivo:** https://TU-USUARIO.github.io/Sales-Executive-Dashboard/reports/dashboard-ventas-ejecutivo.html

![Vista general del dashboard](images/dashboard-overview.png)

> Los datos son sintéticos y se generan con fines demostrativos. No corresponden a ninguna empresa real.

---

## Objetivos

1. Analizar el rendimiento general de ventas.
2. Detectar tendencias, estacionalidad y oportunidades futuras.
3. Identificar categorías de alto y bajo rendimiento.
4. Evaluar el desempeño de vendedores y sucursales.
5. Analizar el uso de métodos de pago.
6. Anticipar la facturación con modelos de pronóstico.

## KPIs principales

| KPI | Descripción |
|---|---|
| Ventas totales | Facturación del período seleccionado |
| Transacciones | Cantidad de operaciones |
| Ticket promedio | Ventas / transacciones |
| Margen de ganancia | Ganancia bruta en valor |
| Rentabilidad % | Margen / ventas |
| Clientes activos y nuevos | Base de clientes del período |
| Crecimiento mensual y anual | Variación vs. mes anterior y vs. año anterior |
| Cumplimiento de objetivos | Ventas reales / objetivo |

## Contenido del dashboard

- **Segmentadores:** año, sucursal y escenario de pronóstico.
- **Pronóstico:** tendencia lineal × estacionalidad mensual, con intervalo de confianza del 80 % y escenarios optimista, normal y pesimista.
- **Categorías:** ventas, rentabilidad, categorías emergentes y en declive.
- **Vendedores:** Top 5 y Bottom 5.
- **Métodos de pago:** participación por medio (efectivo, débito, crédito, transferencia, billeteras virtuales, financiación).
- **Alertas automáticas:** anomalías, riesgos estacionales y oportunidades.
- **Tendencias de futuro:** IA en ventas, medios de pago, omnicanalidad, e-commerce y automatización.

## Modelo de datos

Modelo dimensional en estrella con la tabla de hechos `Ventas` y las dimensiones `Clientes`, `Productos`, `Categorías`, `Vendedores`, `Calendario`, `MétodosPago` y `Sucursales`. El detalle de columnas estará en `docs/diccionario-de-datos.md`.

## Tecnologías

- HTML, CSS y JavaScript (dashboard interactivo sin dependencias externas)
- Power BI y DAX (versión `.pbix`, en desarrollo)
- Python (generación del dataset)
- Git y GitHub Pages

## Estructura del repositorio

```
Sales-Executive-Dashboard
├── data            Datasets de ejemplo (CSV)
├── reports         Dashboard (HTML y .pbix)
├── docs            Diccionario de datos, documentación técnica y manual de usuario
├── images          Capturas de pantalla
├── presentation    Presentación ejecutiva
├── README.md
└── LICENSE
```

## Cómo usarlo

1. Descargá o cloná el repositorio.
2. Abrí `reports/dashboard-ventas-ejecutivo.html` en cualquier navegador.
3. Usá los segmentadores superiores para filtrar y los botones de horizonte para el pronóstico.

```bash
git clone https://github.com/TU-USUARIO/Sales-Executive-Dashboard.git
```

## Beneficios para empresas

- Una sola vista para directivos, gerentes y equipos comerciales.
- Detección temprana de caídas de facturación y anomalías.
- Decisiones basadas en datos y no en intuición.
- Planificación con escenarios de pronóstico.

## Roadmap

- [x] Dashboard interactivo con KPIs y pronóstico
- [ ] Dataset completo en CSV con las 8 tablas
- [ ] Versión Power BI (.pbix) con medidas DAX
- [ ] Curva ABC, segmentación RFM y CLV
- [ ] Drill down, drill through y bookmarks
- [ ] Presentación ejecutiva en PowerPoint
- [ ] Conexión a datos reales

## Licencia

Distribuido bajo licencia MIT. Ver `LICENSE`.

## Autor

**TU NOMBRE** · [LinkedIn](https://www.linkedin.com/in/TU-PERFIL) · [GitHub](https://github.com/TU-USUARIO)
