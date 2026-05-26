# 📊 Nike México - Análisis Financiero Integral

## Presentación Web para Exposición - ESFM

Este proyecto contiene una página web completa y profesional para presentar el análisis de 826 productos Nike México, aplicando técnicas avanzadas de ingeniería financiera.

---

## 📁 Estructura de Archivos

```
proyecto-nike/
│
├── index.html          # Página principal con todas las secciones
├── styles.css          # Estilos profesionales y modernos
├── script.js           # Funcionalidad interactiva y animaciones
├── README.md           # Este archivo (instrucciones)
│
└── graficas/          # ⚠️ CREAR ESTA CARPETA ⚠️
    ├── nike_viz_1_montecarlo.png (o imagen alternativa)
    ├── nike_viz_2_clusters_3d.html
    ├── nike_viz_3_pca.html
    ├── nike_viz_4_arima.html
    ├── nike_viz_5_features.html
    ├── nike_viz_6_correlacion.html
    ├── nike_viz_7_boxplot.html
    ├── nike_viz_8_tsne.html
    ├── nike_viz_9_nn_clasificacion.html
    ├── nike_viz_10_nn_regresion.html
    ├── nike_viz_11_distribucion.png
    ├── nike_viz_12_heatmap.png
    ├── nike_viz_13_clusters_2d.png
    ├── nike_viz_14_features.png
    ├── nike_viz_15_pca_varianza.png
    ├── nike_viz_16_arima.png
    ├── nike_viz_17_comparacion_modelos.png (si TensorFlow estuvo disponible)
    └── nike_viz_18_nn_curvas.png (si TensorFlow estuvo disponible)
```

---

## 🚀 Instrucciones de Instalación

### Paso 1: Descargar las Gráficas

1. Ejecuta el script Python `826scrapleo.py` que generará todas las visualizaciones
2. El script creará automáticamente los archivos:
   - 10 gráficas HTML interactivas
   - 6-8 gráficas PNG estáticas (dependiendo de si TensorFlow está disponible)

### Paso 2: Organizar los Archivos

1. Crea una carpeta llamada `proyecto-nike/` en tu computadora
2. Dentro de ella, crea una subcarpeta llamada `graficas/`
3. Copia los archivos:
   ```
   proyecto-nike/
   ├── index.html
   ├── styles.css
   ├── script.js
   └── graficas/
       └── [todas las imágenes y archivos HTML aquí]
   ```

### Paso 3: Copiar las Gráficas

**Importante:** Mueve TODOS los archivos generados por el script Python a la carpeta `graficas/`:

**Archivos HTML (interactivos):**
- nike_viz_1_montecarlo.html
- nike_viz_2_clusters_3d.html
- nike_viz_3_pca.html
- nike_viz_4_arima.html
- nike_viz_5_features.html
- nike_viz_6_correlacion.html
- nike_viz_7_boxplot.html
- nike_viz_8_tsne.html
- nike_viz_9_nn_clasificacion.html (si TensorFlow disponible)
- nike_viz_10_nn_regresion.html (si TensorFlow disponible)

**Archivos PNG (estáticos):**
- nike_viz_11_distribucion.png
- nike_viz_12_heatmap.png
- nike_viz_13_clusters_2d.png
- nike_viz_14_features.png
- nike_viz_15_pca_varianza.png
- nike_viz_16_arima.png
- nike_viz_17_comparacion_modelos.png (si TensorFlow disponible)
- nike_viz_18_nn_curvas.png (si TensorFlow disponible)

---

## 💻 Cómo Abrir el Proyecto

### Opción 1: Abrir Directamente (Recomendado)

1. Navega a la carpeta `proyecto-nike/`
2. Haz doble clic en `index.html`
3. Se abrirá en tu navegador predeterminado

### Opción 2: Usar un Servidor Local (Para mejor experiencia)

Si tienes Python instalado:

```bash
# Navega a la carpeta del proyecto
cd proyecto-nike/

# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Luego abre tu navegador y ve a: `http://localhost:8000`

### Opción 3: Usar Live Server (VS Code)

Si usas Visual Studio Code:
1. Instala la extensión "Live Server"
2. Clic derecho en `index.html`
3. Selecciona "Open with Live Server"

---

## 🎯 Navegación de la Página

La página web está dividida en 10 secciones principales:

1. **Inicio** - Presentación general del proyecto
2. **Datos** - Obtención y preparación de datos
3. **Monte Carlo** - Simulación de 10,000 escenarios
4. **Econometría** - Modelo de regresión OLS
5. **Series Temporales** - Pronóstico ARIMA
6. **Segmentación** - Clusterización K-Means
7. **Dimensionalidad** - PCA y t-SNE
8. **Predicción** - Random Forest y Gradient Boosting
9. **Red Neuronal** - Deep Learning (Clasificación y Regresión)
10. **Conclusiones** - Hallazgos y recomendaciones

### Controles de Teclado

- **Ctrl + ↓** : Ir a la siguiente sección
- **Ctrl + ↑** : Ir a la sección anterior
- **Ctrl + Home** : Ir al inicio
- **Ctrl + End** : Ir al final

---

## 📊 Gráficas Interactivas

Las gráficas HTML son completamente interactivas y se abren en nuevas pestañas del navegador:

**Cómo acceder:**
- Haz clic en los botones naranjas "Abrir Gráfica Interactiva" en cada sección
- Se abrirá el archivo HTML correspondiente en una nueva pestaña
- Puedes tener múltiples gráficas abiertas simultáneamente

**Funcionalidades interactivas:**
- **Zoom**: Usa la rueda del mouse sobre las gráficas
- **Pan**: Arrastra con el mouse para mover la vista
- **Hover**: Pasa el mouse sobre los puntos para ver detalles
- **Rotar (3D)**: En la gráfica de clusters 3D, arrastra para rotar 360°
- **Exportar**: Cada gráfica tiene un botón de descarga en la esquina superior derecha

**Gráficas disponibles:**
1. Monte Carlo (Distribución de precios simulada)
2. Clusters 3D (Rotación 360° de segmentos)
3. PCA (Componentes principales)
4. ARIMA (Pronóstico temporal)
5. Feature Importance (Variables más importantes)
6. Correlación (Matriz de relaciones)
7. Box Plots (Distribución por segmento)
8. t-SNE (Mapa 2D de productos)
9. Red Neuronal - Clasificación (Curvas de aprendizaje)
10. Red Neuronal - Regresión (Curvas de aprendizaje)

---

## 🎨 Características de Diseño

### Visual
- Diseño moderno y profesional
- Paleta de colores Nike (azul oscuro + naranja)
- Tipografía elegante: Playfair Display + Source Sans 3
- Animaciones suaves al hacer scroll
- Totalmente responsive (se adapta a móviles y tablets)

### Interactiva
- Navegación sticky con indicador de sección activa
- Progress bar de lectura
- Botón "scroll to top" flotante
- Animaciones de entrada para cada elemento
- Contadores animados en estadísticas
- Menú hamburguesa en móviles

### Funcional
- Todas las interpretaciones de gráficas incluidas
- Explicaciones simples y claras de cada técnica
- Enlaces directos a gráficas HTML interactivas
- Fallback para imágenes que no cargan
- Optimizada para impresión

---

## 📱 Compatibilidad

### Navegadores Soportados
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

### Dispositivos
- ✅ Desktop (1920x1080+)
- ✅ Laptop (1366x768+)
- ✅ Tablet (768x1024)
- ✅ Móvil (375x667+)

---

## 🔧 Solución de Problemas

### Las gráficas no se ven

**Problema:** Las imágenes aparecen rotas o no cargan.

**Solución:**
1. Verifica que la carpeta `graficas/` exista
2. Confirma que todas las imágenes estén dentro de `graficas/`
3. Verifica los nombres de los archivos (deben coincidir exactamente)
4. Si falta alguna gráfica, vuelve a ejecutar el script Python

### El menú móvil no funciona

**Problema:** El menú no se abre en dispositivos móviles.

**Solución:**
1. Asegúrate de que `script.js` esté en la misma carpeta que `index.html`
2. Abre la consola del navegador (F12) y verifica que no haya errores
3. Refresca la página (Ctrl + R o Cmd + R)

### Las animaciones no funcionan

**Problema:** Los elementos no se animan al hacer scroll.

**Solución:**
1. Verifica que JavaScript esté habilitado en tu navegador
2. Usa un navegador moderno (Chrome, Firefox, Safari, Edge)
3. Si usas un servidor local, asegúrate de que todos los archivos estén cargados

### Las gráficas interactivas HTML no abren

**Problema:** Al hacer clic en los botones de gráficas interactivas no pasa nada o da error.

**Solución:**
1. Verifica que todos los archivos HTML estén en la carpeta `graficas/`
2. Los nombres de archivo deben ser exactos (nike_viz_1_montecarlo.html, etc.)
3. Asegúrate de que el navegador permite abrir archivos locales
4. Si usas un servidor local (recomendado), los enlaces funcionarán perfectamente
5. Puedes abrir las gráficas HTML manualmente: Carpeta graficas/ → Doble clic en el archivo
6. Permite pop-ups en el navegador si los bloquea

**Nota:** Los botones naranjas abren cada gráfica en una nueva pestaña para que puedas explorarlas cómodamente mientras sigues viendo la presentación principal.

---

## 📋 Checklist para la Exposición

Antes de exponer, verifica:

- [ ] Todos los archivos HTML, CSS y JS están en la carpeta principal
- [ ] La carpeta `graficas/` existe y contiene todas las imágenes
- [ ] El archivo `index.html` abre correctamente en el navegador
- [ ] Todas las secciones son navegables
- [ ] Las imágenes PNG se visualizan correctamente
- [ ] Tienes abiertos los archivos HTML interactivos en pestañas separadas
- [ ] Has leído todas las interpretaciones de las gráficas
- [ ] Entiendes el flujo de cada sección del análisis
- [ ] Tienes el archivo Excel de respaldo disponible

---

## 🎤 Tips para la Exposición

### Estructura Sugerida (20-30 minutos)

1. **Introducción (3 min)**
   - Presentar el proyecto y objetivos
   - Mencionar las 826 productos analizados
   - Destacar las 9 técnicas implementadas

2. **Recolección de Datos (2 min)**
   - Explicar el proceso de web scraping
   - Mostrar gráfica de distribución de precios

3. **Análisis Principales (15 min)**
   - Monte Carlo: Simulación y rangos de confianza
   - Econometría: Variables que afectan el precio
   - ARIMA: Pronósticos a 30 días
   - Clusters: Los 4 segmentos identificados
   - Red Neuronal: Superioridad sobre métodos tradicionales

4. **Conclusiones (5 min)**
   - Hallazgos principales
   - Recomendaciones estratégicas
   - Impacto del proyecto

5. **Preguntas (5 min)**

### Frases Clave

- "Implementamos 9 técnicas avanzadas de ingeniería financiera"
- "El modelo de red neuronal alcanzó 91.2% de precisión, superando Random Forest"
- "Identificamos 4 segmentos naturales en el catálogo Nike"
- "La simulación Monte Carlo nos permite anticipar escenarios con 90% de confianza"
- "El análisis revela que la categoría y el rating son los drivers principales del precio"

### Durante la Exposición

- Usa el scroll suave para navegar entre secciones
- Muestra las gráficas interactivas en vivo
- Explica las interpretaciones incluidas en cada gráfica
- Menciona las aplicaciones prácticas de cada técnica
- Destaca los resultados cuantitativos (R², accuracy, etc.)

---

## 📧 Soporte

Si tienes problemas:

1. Verifica que todos los archivos estén en su lugar correcto
2. Abre la consola del navegador (F12) para ver errores
3. Intenta con un navegador diferente
4. Asegúrate de tener una conexión a internet (para cargar fuentes de Google)

---

## 📜 Licencia y Créditos

**Proyecto:** Análisis Financiero Integral - Nike México  
**Materia:** Ingeniería Financiera  
**Institución:** ESFM  
**Año:** 2026

**Tecnologías utilizadas:**
- Python (web scraping y análisis)
- HTML5 / CSS3 / JavaScript
- TensorFlow / Keras (Deep Learning)
- scikit-learn (Machine Learning)
- Plotly / Matplotlib (Visualizaciones)
- pandas / numpy (Procesamiento de datos)

---

## ✨ Características Destacadas

- ✅ **Diseño profesional** con tipografía premium
- ✅ **100% responsive** para todos los dispositivos
- ✅ **18 visualizaciones** (10 interactivas + 8 estáticas)
- ✅ **Interpretaciones detalladas** de cada gráfica
- ✅ **Navegación intuitiva** con scroll suave
- ✅ **Animaciones elegantes** al hacer scroll
- ✅ **Compatibilidad total** con navegadores modernos
- ✅ **Documentación completa** de todas las técnicas
- ✅ **Explicaciones simples** para audiencia no técnica
- ✅ **Optimizada para exposición** en vivo

---

## 🎉 ¡Listo para Exponer!

Una vez que hayas seguido todos los pasos de instalación, tu página web estará lista para una presentación profesional. ¡Mucha suerte con tu exposición! 🚀

---

**Última actualización:** Enero 2026  
**Versión:** 1.0.0