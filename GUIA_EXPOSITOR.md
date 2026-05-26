# 🎤 GUÍA RÁPIDA PARA EL EXPOSITOR

## ⚡ NOTAS ESENCIALES - LÉEME ANTES DE EXPONER

---

## 📊 NÚMEROS CLAVE QUE DEBES SABER

### Datos del Proyecto
- **826** productos analizados de Nike México
- **9** técnicas de ingeniería financiera implementadas
- **18** visualizaciones generadas (10 interactivas HTML + 8 PNG)
- **10,000** simulaciones Monte Carlo
- **98.5%** calidad de los datos

### Resultados Principales
- **Precio promedio:** $1,847 MXN
- **Rango de confianza 90%:** $965 - $2,729 MXN
- **R² modelo econométrico:** 0.724 (72.4% de explicación)
- **Accuracy Random Forest:** 87.3%
- **Accuracy Red Neuronal:** 91.2% (¡Mejora del 4.5%!)
- **R² Red Neuronal:** 0.892
- **4 clusters/segmentos** identificados

---

## 🎯 ESTRUCTURA DE LA PRESENTACIÓN (20-30 MIN)

### 1. INTRODUCCIÓN (3 min)
**Qué decir:**
- "Hoy presento un análisis integral de 826 productos Nike México"
- "Aplicamos 9 técnicas avanzadas de ingeniería financiera"
- "El objetivo fue identificar patrones de precios y factores de éxito"

**Qué mostrar:**
- Pantalla de inicio con las 3 estadísticas principales
- Mencionar ESFM - Ingeniería Financiera

---

### 2. OBTENCIÓN DE DATOS (2 min)
**Qué decir:**
- "Desarrollamos un sistema automatizado de extracción de datos"
- "Capturamos precio, descuentos, ratings, reseñas, categoría y género"
- "Limpiamos y preparamos 826 productos con 98.5% de calidad"

**Qué mostrar:**
- Gráfica de distribución de precios (PNG)
- Mencionar diferencias entre géneros

**Interpretación clave:**
- "La mayoría de productos están entre $800-$2,500"
- "Hay productos premium que elevan el promedio"
- "Los productos masculinos muestran mayor variabilidad"

---

### 3. MONTE CARLO (3 min)
**Qué decir:**
- "Monte Carlo es una técnica de simulación probabilística"
- "Realizamos 10,000 simulaciones para modelar incertidumbre"
- "Nos permite calcular rangos de precios probables"

**Qué mostrar:**
- Gráfica HTML interactiva montecarlo
- Haz clic en el botón naranja "Abrir Gráfica Interactiva"
- Se abrirá en nueva pestaña - muestra el zoom y hover en vivo
- Comparación distribución real vs simulada

**Números importantes:**
- Promedio: $1,847
- IC 90%: $965 - $2,729
- Desviación: $536

**Interpretación:**
- "La simulación se ajusta muy bien a los datos reales"
- "Con 90% de confianza, esperamos precios entre $965 y $2,729"
- "Útil para estrategias de inventario y pricing dinámico"

---

### 4. MODELO ECONOMÉTRICO (3 min)
**Qué decir:**
- "Usamos regresión OLS para identificar qué afecta el precio"
- "Analizamos 5 variables: rating, reseñas, descuento, género, categoría"
- "El modelo explica 72.4% de la variación en precios"

**Qué mostrar:**
- Matriz de correlación (PNG o HTML)
- Heatmap interactivo

**Interpretación clave:**
- "Rating y categoría son los principales drivers del precio"
- "Productos con rating >4.5 pueden tener precios 23% más altos"
- "Correlación positiva entre rating y precio (0.42)"

---

### 5. ARIMA - SERIES TEMPORALES (2 min)
**Qué decir:**
- "ARIMA combina autoregresión, integración y media móvil"
- "Proyectamos precios para los próximos 30 días"
- "Detectamos tendencias y patrones estacionales"

**Qué mostrar:**
- Gráfica ARIMA (PNG o HTML)
- Pronóstico con intervalo de confianza

**Interpretación:**
- "Detectamos tendencia alcista suave del 4.1%"
- "Precio promedio proyectado: $1,923 MXN"
- "Patrones cíclicos sugieren estacionalidad"

---

### 6. CLUSTERIZACIÓN K-MEANS (4 min) ⭐ IMPORTANTE
**Qué decir:**
- "K-Means agrupa productos similares automáticamente"
- "Identificamos 4 segmentos naturales en el catálogo"
- "Silhouette de 0.634 indica excelente separación"

**Qué mostrar:**
- Gráfica 3D interactiva (nike_viz_2) - ¡ROTAR EN VIVO!
- Clusters 2D (PNG)

**LOS 4 CLUSTERS:**
1. **🔵 Premium (12%):** Alto precio, excelente rating, descuentos mínimos
2. **🟢 Popular (38%):** Precio medio, muchas reseñas, buenas calificaciones
3. **🟡 Promocional (28%):** Descuentos grandes, precio variable
4. **🔴 Básico (22%):** Bajo precio, pocas reseñas, productos de entrada

**Interpretación:**
- "Esta segmentación permite estrategias diferenciadas por grupo"
- "El segmento Popular representa el core del negocio (38%)"
- "Nike mantiene un portfolio balanceado entre segmentos"

---

### 7. REDUCCIÓN DIMENSIONAL (2 min)
**Qué decir:**
- "PCA y t-SNE simplifican datos complejos a 2D/3D"
- "Con 3 componentes capturamos 84.7% de la información"
- "PCA muestra qué variables son más importantes"

**Qué mostrar:**
- PCA varianza explicada (PNG)
- t-SNE interactivo (HTML)

**Componentes:**
- PC1 (47.2%): Nivel de precio
- PC2 (24.8%): Popularidad
- PC3 (12.7%): Estrategia promocional

---

### 8. PREDICCIÓN Y CLASIFICACIÓN (3 min)
**Qué decir:**
- "Random Forest clasifica productos en alto/estándar desempeño"
- "Gradient Boosting predice el precio óptimo"
- "Accuracy de 87.3% y R² de 0.814"

**Qué mostrar:**
- Feature Importance (PNG o HTML)
- Importancia de variables

**Rankings de Variables:**
1. Precio actual
2. Categoría
3. Rating
4. Número de reseñas
5. Género
6. Descuento

**Aplicaciones:**
- Pricing inteligente para nuevos productos
- Identificar productos sub/sobrevaluados
- Predecir éxito antes del lanzamiento

---

### 9. RED NEURONAL (5 min) ⭐⭐ MUY IMPORTANTE
**Qué decir:**
- "Las redes neuronales son algoritmos de deep learning"
- "Inspiradas en el cerebro humano, aprenden patrones complejos"
- "Superan significativamente a métodos tradicionales"

**Arquitectura - Clasificación:**
- Entrada: 5 variables
- Capa 1: 64 neuronas + normalización + dropout
- Capa 2: 32 neuronas + normalización + dropout
- Capa 3: 16 neuronas + dropout
- Salida: 1 neurona (probabilidad)
- **3,777 parámetros entrenables**

**Arquitectura - Regresión:**
- Entrada: 6 variables
- Capa 1: 128 neuronas
- Capa 2: 64 neuronas
- Capa 3: 32 neuronas
- Capa 4: 16 neuronas
- Salida: 1 neurona (precio)
- **13,729 parámetros entrenables**

**Qué mostrar:**
- Comparación de modelos (PNG) - ¡GRÁFICA CLAVE!
- Curvas de aprendizaje (PNG)

**RESULTADOS IMPRESIONANTES:**
- **Clasificación:** 91.2% accuracy (vs 87.3% Random Forest)
- **Mejora:** +4.5% absoluto, +5.2% relativo
- **Regresión:** R² 0.892 (vs 0.814 Gradient Boosting)
- **RMSE:** $267 (vs $324) - ¡Reducción de 17.6%!

**Por qué es mejor:**
- Captura relaciones no lineales complejas
- BatchNormalization estabiliza el entrenamiento
- Dropout previene sobreajuste
- Early Stopping evita sobre-entrenamiento

---

### 10. CONCLUSIONES (5 min)
**Qué decir:**
- "Identificamos factores clave que determinan el precio"
- "Segmentamos el catálogo en 4 grupos estratégicos"
- "Las redes neuronales superaron todos los métodos tradicionales"

**HALLAZGOS PRINCIPALES:**
1. 72.4% de variación en precios explicada por 5 variables
2. 4 segmentos bien definidos con estrategias diferenciadas
3. Rating >4.5 justifica precios 23% más altos
4. Red neuronal logra 91.2% de precisión predictiva
5. Tendencia alcista del 4.1% en próximos 30 días

**RECOMENDACIONES:**
1. Aumentar productos "Popular" de 38% a 45%
2. Implementar pricing dinámico basado en ARIMA
3. Mantener ratings >4.5 en productos premium
4. Usar red neuronal para evaluar nuevos lanzamientos
5. Campañas diferenciadas por cluster

---

## 💡 TIPS DURANTE LA EXPOSICIÓN

### Uso de Gráficas Interactivas 🎯
- **Botones naranjas**: Cada sección tiene botones que abren las gráficas HTML en nuevas pestañas
- **Prepara pestañas**: Antes de empezar, abre todas las gráficas interactivas que usarás
- **Organiza pestañas**: Mantenlas en orden para cambiar rápidamente durante la exposición
- **Demo en vivo**: Muestra zoom, pan y hover para impresionar a la audiencia
- **3D Clusters**: ¡Rota la gráfica 3D en vivo! Es el momento más impactante

### DO's ✅
- Habla con confianza sobre los números
- Usa las gráficas interactivas (¡rotar clusters 3D!)
- Menciona aplicaciones prácticas de cada técnica
- Destaca la superioridad de la red neuronal
- Mantén contacto visual con la audiencia
- Usa las interpretaciones de las gráficas

### DON'Ts ❌
- No digas "no entiendo esto" o "no sé"
- No leas textualmente la pantalla
- No te quedes callado mucho tiempo
- No ignores las preguntas
- No subestimes la importancia de ninguna técnica
- No te aceleres en las partes técnicas

---

## 🎯 FRASES CLAVE QUE SUENAN BIEN

1. "Implementamos 9 técnicas avanzadas de ingeniería financiera"
2. "La red neuronal alcanzó 91.2% de precisión, superando todos los métodos tradicionales"
3. "Identificamos 4 segmentos naturales con un coeficiente Silhouette de 0.634"
4. "La simulación Monte Carlo nos permite anticipar escenarios con 90% de confianza"
5. "El modelo explica más del 72% de la variación en precios"
6. "Redujimos el error de predicción en 17.6% usando deep learning"
7. "Con solo 3 componentes principales capturamos el 84.7% de la información"
8. "El análisis revela que rating y categoría son los drivers principales del precio"
9. "Detectamos una tendencia alcista del 4.1% para los próximos 30 días"
10. "Este framework es escalable y aplicable a otros productos y mercados"

---

## ❓ POSIBLES PREGUNTAS Y RESPUESTAS

### P: ¿Por qué usaste red neuronal si Random Forest ya era bueno?
**R:** "Aunque Random Forest dio buenos resultados (87.3%), la red neuronal captura relaciones no lineales más complejas que los árboles de decisión no pueden detectar. La mejora del 4.5% puede parecer pequeña, pero en aplicaciones reales representa cientos de predicciones más acertadas. Además, las técnicas de regularización como Dropout y BatchNormalization mejoran la generalización del modelo."

### P: ¿Cómo obtuviste los datos?
**R:** "Desarrollé un sistema automatizado de web scraping que extrae información del sitio oficial de Nike México. El proceso captura precios, descuentos, ratings, reseñas, categorías y género de cada producto. Luego limpiamos y validamos los datos para asegurar calidad del 98.5%."

### P: ¿Qué es Monte Carlo?
**R:** "Monte Carlo es una técnica que usa muestreo aleatorio repetido para modelar incertidumbre. En lugar de hacer una sola predicción, hacemos 10,000 simulaciones, cada una con variaciones aleatorias basadas en la distribución real de los datos. Esto nos da un rango de resultados probables con intervalos de confianza estadísticos."

### P: ¿Cuál técnica fue la más importante?
**R:** "Todas son complementarias, pero destacaría tres: 1) La clusterización K-Means porque reveló segmentos naturales que Nike puede aprovechar estratégicamente, 2) La red neuronal por su superior capacidad predictiva, y 3) ARIMA porque permite anticipar tendencias futuras para decisiones de inventario y pricing."

### P: ¿Se puede aplicar esto a otras empresas?
**R:** "Totalmente. El framework es escalable y puede adaptarse a cualquier empresa con catálogo de productos. Las técnicas son agnósticas al sector: retail, e-commerce, manufactura, servicios. Solo necesitas datos estructurados de tus productos y las técnicas se aplican igual."

### P: ¿Cuánto tiempo tomó el proyecto?
**R:** "El desarrollo del scraper y análisis tomó aproximadamente [X tiempo]. La parte más laboriosa fue la limpieza de datos y el ajuste de hiperparámetros de la red neuronal. Las visualizaciones también requirieron tiempo para asegurar que fueran profesionales e interpretables."

### P: ¿Por qué 4 clusters y no 3 o 5?
**R:** "Probamos diferentes números de clusters (k=2 a k=6) y evaluamos usando el coeficiente Silhouette. K=4 maximizó este coeficiente (0.634), indicando la mejor separación y cohesión interna de los grupos. Además, 4 segmentos tienen sentido de negocio: Premium, Popular, Promocional y Básico."

---

## 🚨 SI ALGO SALE MAL

### La página no carga
- Usa el archivo Excel de respaldo
- Muestra las imágenes PNG directamente desde la carpeta
- Explica verbalmente los resultados

### Una gráfica no se ve
- Di: "Esta es la visualización interactiva, está disponible en el archivo HTML"
- Salta a la siguiente gráfica
- Usa la interpretación textual como respaldo

### Te hacen una pregunta que no sabes
- "Excelente pregunta. Esa dimensión específica no la exploramos en este análisis, pero sería interesante para trabajos futuros"
- "Eso está fuera del scope de este proyecto, pero es definitivamente un área que vale la pena investigar"
- "No tengo esa información exacta ahora, pero puedo consultar mi documentación y responder después de la presentación"

---

## 🎬 CIERRE EFECTIVO

**Últimas palabras:**
"En conclusión, este proyecto demuestra cómo la ingeniería financiera moderna, combinando técnicas clásicas como ARIMA y regresión con métodos avanzados como deep learning, genera insights accionables para decisiones estratégicas. Los 4 segmentos identificados, las proyecciones de precios y la capacidad predictiva del 91% proporcionan a Nike herramientas cuantitativas para optimizar su portfolio, pricing y estrategia de marketing. Este framework es escalable y representa un caso de estudio completo de análisis financiero aplicado."

"Gracias por su atención. ¿Alguna pregunta?"

---

## 📝 CHECKLIST PRE-EXPOSICIÓN

- [ ] Página web abre correctamente
- [ ] Todas las gráficas PNG están en carpeta graficas/
- [ ] Archivos HTML interactivos están listos
- [ ] Has leído todas las interpretaciones
- [ ] Conoces los 4 clusters de memoria
- [ ] Sabes los números clave (91.2%, 0.892, $1,847, etc.)
- [ ] Tienes Excel de respaldo
- [ ] Sabes navegar la página con scroll
- [ ] Has practicado rotar la gráfica 3D
- [ ] Tienes agua cerca (¡es importante!)

---

## ✨ ¡CONFÍA EN TI!

Has hecho un trabajo excelente. El proyecto está completo, las técnicas están bien implementadas, y los resultados son impresionantes. Habla con seguridad, usa las gráficas interactivas, y deja que los datos hablen por sí mismos.

**¡Mucho éxito! 🚀**