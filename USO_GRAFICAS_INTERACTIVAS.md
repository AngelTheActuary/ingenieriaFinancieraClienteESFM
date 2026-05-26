# 🎯 GUÍA RÁPIDA: USO DE GRÁFICAS INTERACTIVAS

## 📊 CÓMO FUNCIONAN LOS BOTONES

Cada sección de la página web tiene **botones naranjas** que dicen cosas como:
- "Abrir Gráfica Interactiva"
- "Abrir Visualización 3D Interactiva"
- "Abrir PCA Interactivo"
- etc.

### ¿Qué hacen estos botones?

Al hacer clic en cualquier botón naranja:
1. ✅ Se abre una **nueva pestaña** del navegador
2. ✅ Carga el archivo HTML con la gráfica interactiva
3. ✅ Puedes **interactuar** con la gráfica (zoom, pan, hover, rotar)
4. ✅ La pestaña principal (index.html) **permanece abierta**
5. ✅ Puedes **cambiar entre pestañas** para mostrar diferentes gráficas

---

## 🚀 PREPARACIÓN ANTES DE EXPONER

### Opción 1: Pre-abrir todas las gráficas (RECOMENDADO)

**Antes de empezar tu exposición:**

1. Abre `index.html` en tu navegador
2. Recorre todas las secciones y haz clic en cada botón naranja
3. Deja que se abran todas las gráficas en pestañas separadas
4. Organiza las pestañas en el orden que las usarás
5. Durante la exposición, solo necesitas cambiar de pestaña

**Ventajas:**
- ✅ No hay tiempo de carga durante la exposición
- ✅ Cambio instantáneo entre gráficas
- ✅ No hay riesgo de errores en vivo
- ✅ Puedes practicar el orden antes

**Pestañas sugeridas (abre en este orden):**
1. index.html (página principal)
2. nike_viz_1_montecarlo.html (Monte Carlo)
3. nike_viz_2_clusters_3d.html (Clusters 3D) ⭐ IMPORTANTE
4. nike_viz_3_pca.html (PCA)
5. nike_viz_4_arima.html (ARIMA)
6. nike_viz_5_features.html (Feature Importance)
7. nike_viz_6_correlacion.html (Correlación)
8. nike_viz_7_boxplot.html (Box plots)
9. nike_viz_8_tsne.html (t-SNE)
10. nike_viz_9_nn_clasificacion.html (Red Neuronal - Clasificación)
11. nike_viz_10_nn_regresion.html (Red Neuronal - Regresión)

### Opción 2: Abrir en vivo durante la exposición

**Durante cada sección:**
- Haz clic en el botón naranja correspondiente
- Espera 1-2 segundos a que cargue la nueva pestaña
- Cambia a la pestaña recién abierta
- Muestra la gráfica interactiva
- Regresa a la pestaña principal para continuar

**Ventajas:**
- ✅ Flujo más natural
- ✅ Muestra cómo funciona el sistema

**Desventajas:**
- ❌ Pequeñas pausas entre secciones
- ❌ Riesgo de error si algo no carga

---

## 🎬 DURANTE LA EXPOSICIÓN

### Secuencia Recomendada por Sección:

#### 1. Monte Carlo (Sección 3)
```
1. Explica qué es Monte Carlo (en index.html)
2. Haz clic en "Abrir Gráfica Interactiva" (o cambia a pestaña pre-abierta)
3. Muestra la gráfica interactiva
4. Pasa el mouse sobre las barras para mostrar valores exactos
5. Haz zoom en una región de interés
6. Regresa a index.html y continúa con la interpretación
```

#### 2. Clusters 3D (Sección 6) ⭐⭐ MOMENTO ESTELAR
```
1. Explica la clusterización K-Means (en index.html)
2. Haz clic en "Abrir Visualización 3D Interactiva"
3. ¡AQUÍ VIENE LO IMPRESIONANTE!
4. Arrastra con el mouse para ROTAR la gráfica 360°
5. Muestra cómo los clusters están separados en 3D
6. Acércate (zoom) a un cluster específico
7. Los colores representan los 4 segmentos
8. Di: "Como pueden ver, los segmentos están perfectamente separados"
9. Regresa a index.html
```

#### 3. ARIMA (Sección 5)
```
1. Explica series temporales (en index.html)
2. Abre la gráfica ARIMA interactiva
3. Muestra la línea histórica (azul)
4. Señala el pronóstico (roja punteada)
5. Pasa el mouse sobre puntos para ver valores exactos
6. Regresa a index.html
```

#### 4. PCA (Sección 7)
```
1. Explica reducción dimensional
2. Abre PCA interactivo
3. Señala cómo los productos se agrupan por color (categoría de precio)
4. Usa hover para ver productos específicos
5. Regresa a index.html
```

#### 5. Red Neuronal (Sección 9) ⭐ IMPORTANTE
```
1. Explica la arquitectura de la red
2. Abre "Clasificación: Curvas de Entrenamiento"
3. Señala cómo el loss disminuye (mejora)
4. Muestra cómo accuracy aumenta
5. Cambia a "Regresión: Curvas de Entrenamiento"
6. Compara con los resultados en la página principal
7. Regresa a index.html
```

---

## 💻 ATAJOS DE TECLADO ÚTILES

### Navegación entre pestañas (funciona en todos los navegadores):

**Windows/Linux:**
- `Ctrl + Tab` = Siguiente pestaña
- `Ctrl + Shift + Tab` = Pestaña anterior
- `Ctrl + 1` = Primera pestaña
- `Ctrl + 2` = Segunda pestaña
- `Ctrl + 3` = Tercera pestaña
- ... hasta `Ctrl + 8`
- `Ctrl + 9` = Última pestaña

**Mac:**
- `Cmd + Shift + ]` = Siguiente pestaña
- `Cmd + Shift + [` = Pestaña anterior
- `Cmd + 1` = Primera pestaña
- `Cmd + 2` = Segunda pestaña
- etc.

### En la página principal (index.html):

- `Ctrl + ↓` = Ir a siguiente sección
- `Ctrl + ↑` = Ir a sección anterior
- `Ctrl + Home` = Ir al inicio
- `Ctrl + End` = Ir al final

---

## 🎨 INTERACCIONES DISPONIBLES EN CADA GRÁFICA

### Todas las gráficas HTML interactivas permiten:

1. **Hover (pasar el mouse):**
   - Muestra valores exactos
   - Resalta el elemento seleccionado
   - Muestra tooltips con información detallada

2. **Zoom:**
   - Rueda del mouse hacia arriba = Acercar
   - Rueda del mouse hacia abajo = Alejar
   - También hay botones de zoom en la esquina superior derecha

3. **Pan (arrastrar):**
   - Haz clic y arrastra para mover la vista
   - Útil cuando estás en zoom

4. **Reset:**
   - Doble clic en la gráfica = Resetear zoom
   - Botón "Reset axes" en la esquina superior derecha

5. **Exportar:**
   - Botón de cámara en la esquina = Descargar como PNG
   - Útil si quieres guardar una vista específica

### Gráfica especial - Clusters 3D:

Además de lo anterior, permite:
- **Rotar**: Arrastra para girar en cualquier dirección
- **Orbitar**: Haz girar la gráfica 360° completos
- **Inclinar**: Cambia el ángulo de vista vertical

---

## 🚨 SOLUCIÓN RÁPIDA DE PROBLEMAS

### El botón no hace nada al hacer clic
**Causas:**
- Pop-ups bloqueadas por el navegador
- Archivo HTML no está en la carpeta graficas/
- Nombre de archivo incorrecto

**Solución inmediata:**
1. Abre manualmente: Carpeta graficas/ → Doble clic en el archivo
2. Durante exposición, di: "Aquí tenemos la versión interactiva" y muéstrala

### La gráfica se ve pero no responde a interacciones
**Causa:** La página no cargó completamente

**Solución:**
1. Refresca la pestaña (F5 o Cmd+R)
2. Espera 2-3 segundos
3. Intenta de nuevo

### La página principal se cerró accidentalmente
**Solución:**
1. Abre de nuevo index.html
2. Usa las pestañas de gráficas que ya tienes abiertas
3. Navega usando los enlaces de la barra superior

---

## 🎯 CHECKLIST PRE-EXPOSICIÓN

Antes de empezar, verifica:

- [ ] index.html abre correctamente
- [ ] Todos los archivos están en la carpeta graficas/
- [ ] Has hecho clic en cada botón para verificar que funciona
- [ ] Las gráficas interactivas cargan correctamente
- [ ] Puedes rotar la gráfica 3D de clusters
- [ ] El navegador no bloquea pop-ups de esta página
- [ ] Sabes usar Ctrl+Tab (o Cmd+Shift+]) para cambiar pestañas
- [ ] Has practicado cambiar entre pestañas fluidamente
- [ ] Conoces el orden de las gráficas que mostrarás
- [ ] Tienes todas las pestañas organizadas antes de empezar

---

## 💡 TIPS PROFESIONALES

### Para impresionar a la audiencia:

1. **Smooth transitions:**
   - Usa Ctrl+Tab para cambiar pestañas rápidamente
   - No cierres pestañas durante la exposición
   - Mantén el flujo natural

2. **Demuestra interactividad:**
   - "Como pueden ver, puedo acercarme aquí..." (zoom)
   - "Si paso el mouse vemos los valores exactos..." (hover)
   - "Y puedo rotar para ver desde otro ángulo..." (3D clusters)

3. **Manejo del tiempo:**
   - Pre-abre las gráficas para no perder tiempo
   - Decide cuáles mostrarás en vivo y cuáles solo mencionarás
   - Las 3 gráficas IMPRESCINDIBLES: Monte Carlo, Clusters 3D, Red Neuronal

4. **Backup plan:**
   - Si algo falla, tienes las imágenes PNG en la página principal
   - Puedes explicar verbalmente y señalar los números clave
   - El archivo Excel también tiene toda la información

---

## 📱 SI PRESENTAS EN PANTALLA EXTERNA

### Configuración recomendada:

**Laptop (tu pantalla):**
- Pestaña: index.html
- Sirve como "guión" para ti
- Lees las notas de interpretación

**Proyector/Pantalla externa:**
- Pestañas: Gráficas HTML interactivas
- Aquí haces las demostraciones
- La audiencia ve las interacciones

### Cómo configurar:

1. Conecta la pantalla externa
2. Configura en modo "Extender" (no duplicar)
3. Arrastra las pestañas de gráficas a la pantalla externa
4. Mantén index.html en tu laptop

---

## ✨ RESUMEN: LO MÁS IMPORTANTE

1. ✅ Los **botones naranjas** abren gráficas en nuevas pestañas
2. ✅ **Pre-abre** todas las gráficas antes de empezar
3. ✅ Usa **Ctrl+Tab** para cambiar entre pestañas
4. ✅ Demuestra **interactividad** (hover, zoom, rotar)
5. ✅ El momento estelar es **rotar Clusters 3D** en vivo
6. ✅ Si algo falla, tienes **plan B** (PNG, Excel)

---

**¡Éxito en tu exposición! 🚀**

El sistema de botones está diseñado para ser intuitivo y profesional. Solo haz clic y deja que las gráficas hablen por sí mismas.