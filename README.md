# Caracterización Hidrodinámica y Modelación de Conductividad Hidráulica Saturada ($K_{fs}$) en Agroecosistemas Cafetaleros del Sur del Ecuador

[![Status](https://img.shields.io/badge/Status-Listo%20para%20Publicación-success.svg)](#)
[![Peer-Review](https://img.shields.io/badge/Peer--Review-IMRyD%20Manuscript-blue.svg)](#)
[![Dashboard](https://img.shields.io/badge/Interactive%20Dashboard-HTML5%20%7C%20Plotly%203D-1E3A8A.svg)](#)
[![License](https://img.shields.io/badge/Data%20License-CC%20BY%204.0-lightgrey.svg)](#)

Repositorio oficial de datos, modelos hidrodinámicos, figuras de alta resolución y tablero interactivo de la investigación:
> **"Respuesta a la adición de nutrientes, almacenamiento de carbono y optimización del manejo del riego en el cultivo de café en el sur del Ecuador"**

---

## 📑 Contenido del Repositorio

| Archivo / Carpeta | Descripción | Enlace Directo |
| :--- | :--- | :--- |
| **`index.html`** | Tablero interactivo principal (Landing page para GitHub Pages / Hosting Web). Estilo editorial sobrio, visores WebGL 3D y 7 módulos de análisis. | [Ver archivo](index.html) |
| **`manuscrito_cientifico_publicacion.md`** | Artículo científico completo en formato IMRyD listo para arbitraje (Vadose Zone Journal, Geoderma, Catena). | [Ver manuscrito](manuscrito_cientifico_publicacion.md) |
| **`dashboard_hidrologia_suelos.html`** | Copia local idéntica del tablero interactivo para ejecución *offline*. | [Ver dashboard](dashboard_hidrologia_suelos.html) |
| **`results_analysis.json`** | Base de datos consolidada (780 registros minutales pareados, parámetros hidrodinámicos, ajustes de modelos físicos y PCA 3D). | [Ver datos JSON](results_analysis.json) |
| **`figures/`** | 6 figuras científicas vectorizadas / rasterizadas a 300 DPI listas para imprenta. | [Explorar figuras](figures/) |
| **`Ks proyecto café/`** | Archivos brutos originales de campo de los infiltrómetros SATURO y Minidisco. | [Explorar datos crudos](Ks%20proyecto%20café/) |

---

## 🚀 Despliegue en la Web (Publicación Online Gratuita)

El archivo `index.html` está configurado para ejecutarse sin necesidad de un servidor backend (100% *client-side* con Tailwind CSS y Plotly.js).

### Opción A: Despliegue en GitHub Pages (Recomendado, 2 minutos)
1. Cree un nuevo repositorio en su cuenta de GitHub (ejemplo: `hidrologia-cafetales-ecuador`).
2. Suba los archivos de esta carpeta a su repositorio:
   ```bash
   git init
   git add .
   git commit -m "Publicación de investigación hidrodinámica y dashboard"
   git branch -M main
   git remote add origin https://github.com/SU_USUARIO/hidrologia-cafetales-ecuador.git
   git push -u origin main
   ```
3. En GitHub, ingrese a **Settings** > pestaña **Pages** (menú izquierdo).
4. En **Build and deployment > Branch**, elija `main` y en la carpeta seleccione `/ (root)`.
5. Presione **Save**. En 1 a 2 minutos su dashboard estará accesible públicamente a nivel mundial en:  
   `https://SU_USUARIO.github.io/hidrologia-cafetales-ecuador/`

### Opción B: Despliegue Inmediato sin Git (Netlify Drop / Vercel)
1. Ingrese a [Netlify Drop](https://app.netlify.com/drop).
2. Arrastre y suelte la carpeta de este proyecto (`Soil_research`).
3. Su sitio se publicará instantáneamente con una URL segura HTTPS.

### Opción C: Uso Local Offline
Haga doble clic directamente sobre `index.html` o `dashboard_hidrologia_suelos.html` en su computadora. Se abrirá en cualquier navegador moderno (Chrome, Edge, Firefox, Safari) con interactividad 3D completa.

---

## 📊 Síntesis de Resultados Científicos

### 1. Parámetros Hidrodinámicos por Sitio

| Sitio de Estudio | Provincia | Altitud | $N$ Ensayos | $K_{fs}$ Media ($cm/h$) | Rango ($cm/h$) | Clase Hidráulica (USDA/FAO) | Mecanismo Dominante |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| **Fundochamba** | Loja | ~1,650 m | 1 | **$44.39$** | — | Rápida ($>36\text{ cm/h}$) | **$93.1\%$ flujo por macroporos**; matriz $3.07\text{ cm/h}$ |
| **Palanda** | Zamora Chinchipe | ~1,200–1,400 m | 4 | **$36.95$** | $5.14 - 68.54$ | Mod-Rápida a Muy Rápida | Alta conductividad gravitacional en raíces |
| **San Pedro de Vilcabamba** | Loja | ~1,600 m | 3 | **$13.03$** | $9.66 - 17.93$ | Moderada ($3.6 - 18\text{ cm/h}$) | Matriz franco-limosa con balance drenaje-retención |

### 2. Inferencia Estadística
- **ANOVA de Welch:** $F = 192.24, \quad p = 1.49 \times 10^{-68}, \quad \eta^2 = 0.331$ (El $33.1\%$ de la varianza en infiltración es explicada por la localidad).
- **Prueba Kruskal-Wallis:** $H = 184.88, \quad p = 7.13 \times 10^{-41}$.
- **Pruebas Post-hoc (Mann-Whitney con corrección Bonferroni):** Todos los pares exhiben diferencias estadísticamente significativas ($p < 0.005$).

### 3. Ajuste de Modelos Físicos de Infiltración
- **Kostiakov ($I = k \cdot t^a$):** $R^2 \ge 0.989$ en todos los sitios. Excelente representatividad del flujo no lineal temprano.
- **Philip ($I = S \cdot t^{0.5} + A \cdot t$):** $R^2 \ge 0.986$. Separación física robusta entre sortividad capilar ($S$) y transmisividad gravitacional ($A$).
- **Horton:** Modela el decaimiento exponencial hacia la tasa estable ($f_c$).

### 4. Análisis de Componentes Principales Tridimensional (PCA 3D)
- **Varianza Explicada Acumulada: $99.58\%$**
  - **PC1 ($85.65\%$):** Eje de Transmisividad y Flujo Macroporoso.
  - **PC2 ($12.72\%$):** Eje de Sortividad Capilar y Retención Matricial.
  - **PC3 ($1.21\%$):** Dinámica de decaimiento temporal.

### 5. Control de Calidad y Corrección de JUAN-R-14
Se diagnosticó el valor negativo de firmware ($-0.00146\text{ cm/s}$) ocasionado por sello superficial y carga incompleta. Se aplicó la formulación tridimensional de **Wooding (1968)** para carga única con flujo estacionario final ($q_{ss} = 18.29\text{ cm/h}$):
$$K_{fs} = \frac{q_{ss}}{1 + \frac{4}{\pi r \alpha^*}} = 13.03\text{ cm/h} \quad (0.00362\text{ cm/s})$$
restituyendo la coherencia física con el grupo edáfico de Vilcabamba ($9.66 - 17.93\text{ cm/h}$).

---

## 🖼️ Figuras de Publicación (300 DPI)

Las figuras generadas se encuentran en [`figures/`](figures/):
1. **`fig1_comparativa_kfs_sitios.png`**: Distribución de $K_{fs}$ por sitio y clasificación de permeabilidad FAO/USDA.
2. **`fig2_series_temporales_infiltracion.png`**: Cinética minutal de flujo ($q$) y presión hidrostática ($H$) durante ciclos SATURO.
3. **`fig3_modelos_infiltracion_ajuste.png`**: Infiltración acumulada experimental vs. modelos de Kostiakov y Philip.
4. **`fig4_pca_biplot_clustering.png`**: Espacio multivariado biplot y separación por clústeres de Ward.
5. **`fig5_fundochamba_multiescala_macroporos.png`**: Partición física multiescala (SATURO vs. Minidisco) y curvas $K(\psi)$ de Gardner.
6. **`fig6_diagnostico_juan_r14.png`**: Diagnóstico de la anomalía experimental y validación de la corrección analítica de Wooding.

---

## 📖 Cómo Citar este Trabajo

### Formato APA (7ª edición)
> Equipo de Investigación en Suelos y Agroecosistemas Cafetaleros. (2026). *Caracterización Hidrodinámica Multiescala y Modelación de la Conductividad Hidráulica Saturada en Agroecosistemas Cafetaleros del Sur del Ecuador* (Informe Técnico-Científico de Proyecto). Universidad Nacional de Loja / Proyecto Café Sur del Ecuador.

### Formato BibTeX
```bibtex
@article{hidrologia_cafe_ecuador_2026,
  title = {Caracterización Hidrodinámica Multiescala y Modelación de la Conductividad Hidráulica Saturada en Agroecosistemas Cafetaleros del Sur del Ecuador},
  author = {Equipo de Investigación en Suelos},
  journal = {Vadose Zone Journal (Enviado / En Revisión)},
  year = {2026},
  url = {https://github.com/SU_USUARIO/hidrologia-cafetales-ecuador}
}
```

---

## 📄 Licencia
Los datos y el código de este repositorio se distribuyen bajo la licencia [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
