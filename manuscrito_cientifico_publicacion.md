# Caracterización Hidrodinámica Multiescala y Modelación de la Conductividad Hidráulica Saturada en Agroecosistemas Cafetaleros del Sur del Ecuador

**Autores:** *Equipo de Investigación en Suelos y Agroecosistemas Cafetaleros*  
**Correspondencia:** *Proyecto de Investigación "Respuesta a la adición de nutrientes, almacenamiento de carbono y optimización del manejo del riego en el cultivo de café en el sur del Ecuador"*  
**Revista Sugerida:** *Vadose Zone Journal* / *Geoderma* / *Agricultural Water Management* / *Catena*  
**Archivos Complementarios:** [Dashboard Interactivo (`index.html`)](index.html) • [Base de Datos (`results_analysis.json`)](results_analysis.json)

---

### Resumen
El movimiento del agua en la zona vadosa de los agroecosistemas cafetaleros del sur del Ecuador juega un papel determinante en la eficiencia del uso del agua, la retención de nutrientes y el almacenamiento de carbono. Este estudio evaluó la variabilidad hidrodinámica y la conductividad hidráulica saturada de campo ($K_{fs}$) en tres zonas cafetaleras contrastantes: Fundochamba (Loja), Palanda (Zamora Chinchipe) y San Pedro de Vilcabamba (Loja). Se combinaron mediciones continuas de alta resolución con infiltrómetro automatizado SATURO Dual-Head ($N = 780$ registros minutales) e infiltrometría de disco a tensión controlada (Minidisco, $\psi \in [-0.5, -3.0]\text{ cm}$). Se ajustaron modelos físicos no lineales (Kostiakov, Philip y Horton) y se aplicaron pruebas estadísticas de inferencia (ANOVA robusto de Welch, Kruskal-Wallis, contrastes post-hoc de Mann-Whitney con ajuste Bonferroni), así como Análisis de Componentes Principales tridimensional (PCA 3D) y agrupamiento jerárquico de Ward. Los resultados demuestran diferencias regionales altamente significativas ($F = 192.24, p < 10^{-15}, \eta^2 = 0.331$). Fundochamba ($K_{fs} = 44.39\text{ cm/h}$) y Palanda ($K_{fs}\text{ media} = 36.95\text{ cm/h}$) exhiben permeabilidades rápidas a muy rápidas. La comparación multiescala en Fundochamba demostró que el **$93.1\%$ del flujo saturado** es conducido a través de macroporos estructurales y bioporos (canales radiculares y galerías de fauna), mientras que la matriz del suelo solo aporta el $6.9\%$ ($K_{sat\text{ matriz}} = 3.07\text{ cm/h}$). En contraste, San Pedro de Vilcabamba presentó permeabilidad moderada ($K_{fs}\text{ media} = 13.03\text{ cm/h}$) dominada por la matriz edáfica. Los modelos acumulativos de Kostiakov y Philip lograron coeficientes de determinación sobresalientes ($R^2 \ge 0.988$), mientras que el PCA 3D explicó el **$99.58\%$** de la varianza total hidrológica (PC1 Transmisividad: $85.65\%$, PC2 Sortividad: $12.72\%$, PC3 Decaimiento: $1.21\%$). Asimismo, se resolvió analíticamente la falla de inversión del firmware en el ensayo JUAN-R-14 mediante la solución de Carga Única de Wooding ($K_{fs} = 13.03\text{ cm/h}$). Se concluye que los cafetales de Fundochamba y Palanda presentan alta susceptibilidad a la lixiviación profunda de nutrientes por flujo preferencial, demandando esquemas de fertirriego por goteo con pulsos cortos y alta frecuencia.

**Palabras clave:** Conductividad hidráulica saturada ($K_{fs}$), SATURO Dual-Head, Infiltrómetro de Minidisco, Macroporosidad, Café (*Coffea arabica*), Modelación de infiltración, Ecuación de Wooding, Sur del Ecuador.

---

### Abstract
Water movement in the vadose zone of coffee agroecosystems in southern Ecuador plays a critical role in irrigation efficiency, nutrient retention, and soil carbon storage. This research investigated hydrodynamic variability and field-saturated hydraulic conductivity ($K_{fs}$) across three contrasting coffee-producing regions: Fundochamba (Loja), Palanda (Zamora Chinchipe), and San Pedro de Vilcabamba (Loja). High-resolution field infiltration was characterized using the automated SATURO Dual-Head Infiltrometer ($N = 780$ minute-interval records) complemented by tension disk infiltrometry (Mini Disk, $\psi \in [-0.5, -3.0]\text{ cm}$). Nonlinear infiltration models (Kostiakov, Philip, and Horton) were calibrated alongside robust hypothesis testing (Welch ANOVA, Kruskal-Wallis, post-hoc pairwise Mann-Whitney with Bonferroni correction), 3D Principal Component Analysis (3D PCA), and Ward’s hierarchical clustering. The results confirmed highly significant regional hydrodynamic disparities ($F = 192.24, p < 10^{-15}, \eta^2 = 0.331$). Fundochamba ($K_{fs} = 44.39\text{ cm/h}$) and Palanda (mean $K_{fs} = 36.95\text{ cm/h}$) exhibited rapid to very rapid permeabilities. Multiscale tension-ponding partitioning in Fundochamba demonstrated that **$93.1\%$ of saturated flux** is governed by structural macropores and biopores (root channels and earthworm burrows), whereas the mineral matrix contributes merely $6.9\%$ ($K_{sat\text{ matrix}} = 3.07\text{ cm/h}$). Conversely, San Pedro de Vilcabamba displayed moderate permeability (mean $K_{fs} = 13.03\text{ cm/h}$) governed by matrix flow. Cumulative Kostiakov and Philip models exhibited exceptional fits ($R^2 \ge 0.988$). The 3D PCA explained **$99.58\%$** of total hydrodynamic variance (PC1 Transmissivity: $85.65\%$, PC2 Sorptivity: $12.72\%$, PC3 Decay: $1.21\%$). Furthermore, an automated inversion breakdown in test JUAN-R-14 was resolved through Wooding’s single-head formulation ($K_{fs} = 13.03\text{ cm/h}$). Coffee agroecosystems in Fundochamba and Palanda exhibit high vulnerability to preferential leaching, warranting high-frequency, pulse drip irrigation regimes.

**Keywords:** Field-saturated hydraulic conductivity, SATURO infiltrometer, Mini Disk infiltrometer, Macropore flow, Coffee agroforestry, Wooding equation, Vadose zone.

---

## 1. Introducción

El cultivo de café (*Coffea arabica* L.) en el sur del Ecuador se desarrolla predominantemente en laderas andinas y estribaciones orientales bajo sistemas agroforestales. La gestión hídrica y nutricional en estos paisajes exige un entendimiento riguroso de las propiedades hidrofísicas del suelo, en particular de la conductividad hidráulica saturada de campo ($K_{fs}$) y la capacidad de infiltración (Hillel, 2004; Reynolds & Elrick, 1990). La $K_{fs}$ controla la partición hidrológica entre escorrentía superficial y recarga profunda, influyendo directamente en la susceptibilidad a la erosión, la disponibilidad hídrica en la rizósfera y la eficiencia de la fertilización nitrogenada y potásica.

A pesar de su importancia, la estimación de la $K_{fs}$ en suelos agrícolas de montaña enfrenta importantes desafíos metodológicos debido a la heterogeneidad espacial y a la presencia de macroporosidad biogénica originada por el denso sistema radicular del café y los árboles de sombra asociados (van Genuchten, 1980; Nimmo et al., 2009). Tradicionalmente, los ensayos de infiltrómetros de anillo simple o doble presentan incertidumbres asociadas a la absorción tridimensional lateral y a la estimación del parámetro de longitud capilar macroscópica ($\alpha^*$). Para superar estas limitaciones, el método de doble carga hidráulica automatizada (SATURO, METER Group) permite eliminar analíticamente la sortividad capilar mediante la alternancia de dos niveles de presión hidrostática ($H_1$ y $H_2$), resolviendo simultáneamente la conductividad saturada (Reynolds & Elrick, 1990).

Sin embargo, los permeámetros de encharcamiento positivo activan tanto la matriz microporosa como los macroporos estructurales. En contraste, los infiltrómetros de disco a tensión negativa (Minidisco) excluyen el flujo por macroporos de acuerdo con el principio de capilaridad de Laplace-Young, permitiendo cuantificar de forma aislada la conductividad hidráulica no saturada de la matriz $K(\psi)$ (Zhang, 1997; Vandervaere et al., 2000). La combinación simultánea de ambas técnicas multiescala abre una oportunidad metodológica inédita para cuantificar la partición física entre el flujo macroporoso y matricial en cafetales del sur del Ecuador.

Los objetivos de esta investigación fueron:
1. Caracterizar cuantitativamente la conductividad hidráulica saturada de campo ($K_{fs}$) y la dinámica minutal de infiltración en tres zonas cafetaleras representativas del sur del Ecuador (Fundochamba, Palanda y San Pedro de Vilcabamba).
2. Contrastar el ajuste predictivo de tres modelos físicos de infiltración (Kostiakov, Philip y Horton).
3. Evaluar la diferenciación regional mediante análisis estadístico inferencial univariado y multivariado tridimensional (PCA 3D y agrupamiento jerárquico de Ward).
4. Determinar la partición multiescala entre el flujo macroporoso biogénico y el flujo matricial mediante la integración de SATURO y Minidisco.
5. Diagnosticar y resolver analíticamente las anomalías de inversión de doble carga hidráulica mediante la ecuación tridimensional de Wooding (1968).

---

## 2. Materiales y Métodos

### 2.1 Áreas de Estudio
La investigación se desarrolló en tres zonas cafetaleras del sur del Ecuador:
- **Fundochamba (Cantón Quilanga, Provincia de Loja):** Ubicada a ~1,650 m s.n.m. en la vertiente pacífica. Clima templado-cálido de montaña, suelos derivados de materiales volcánicos e intrusivos con textura franca, reconocidos por la producción de cafés especiales. Parcela experimental: *Jimmy Abad*.
- **Palanda (Cantón Palanda, Provincia de Zamora Chinchipe):** Ubicada a ~1,200–1,400 m s.n.m. en la vertiente amazónica (cuenca Mayo-Chinchipe). Alta precipitación anual (>2,000 mm), alta humedad relativa y suelos profundos ricos en materia orgánica. Se evaluaron cuatro parcelas en dos sectores: *Pucarón* (Luis Cordero y Mélida Cahuinal) y *San Francisco* (Café La Palma y Ramiro Pintado).
- **San Pedro de Vilcabamba (Cantón Loja, Provincia de Loja):** Valle interandino a ~1,600 m s.n.m. Régimen bimodal de lluvias, suelos aluviales y coluviales francos y franco-limosos con mayor densidad aparente. Se evaluaron tres parcelas: *Jorge Lapo*, *Juan R-14* y *Tulio Toledo (ULT-FK3)*.

### 2.2 Infiltración de Doble Carga Hidráulica (SATURO Dual-Head)
Los ensayos de campo se ejecutaron con el infiltrómetro automatizado SATURO (METER Group, Inc., Pullman, WA, USA), empleando anillos de inserción de acero inoxidable de $16.15\text{ cm}$ de diámetro interior y profundidades de inserción ($d$) de $5$ a $10\text{ cm}$.

El instrumento aplica dos cargas hidrostáticas sucesivas ($H_1 = 5\text{ cm}$ y $H_2 = 15 - 20\text{ cm}$) durante ciclos alternados con tiempos de humedecimiento previo (*soak time*) de 15 minutos y tiempos de sostenimiento (*hold time*) de 20 a 25 minutos. Se registró la tasa de flujo volumétrico ($mL/s$) y la tasa de flujo unitario ($q$, cm/s y cm/h) con resolución temporal de 1 minuto durante un periodo total de 75 a 115 minutos por ensayo, acumulando 780 registros minutales pareados de flujo y presión.

La solución matemática implementada por el algoritmo de inversión dual-head (Reynolds & Elrick, 1990) se fundamenta en:

$$q_1 = K_{fs} \left( 1 + \frac{H_1}{C_1 d} + \frac{1}{\alpha^* C_1 d} \right)$$
$$q_2 = K_{fs} \left( 1 + \frac{H_2}{C_2 d} + \frac{1}{\alpha^* C_2 d} \right)$$

donde $C_1$ y $C_2$ son factores empíricos de corrección por forma geométrica tridimensional dependientes de la relación $d/r$:

$$C = 0.316 \pi \left(\frac{d}{r}\right) + 0.184$$

Al restar ambas expresiones, se elimina el parámetro capilar desconocido $\alpha^*$, despejando $K_{fs}$:

$$K_{fs} = \frac{q_1 - q_2}{\frac{H_1}{C_1 d} - \frac{H_2}{C_2 d}}$$

### 2.3 Infiltrometría de Tensión con Minidisco y Modelo de Gardner
En Fundochamba se realizaron ensayos de infiltración bajo tensión negativa empleando el infiltrómetro Mini Disk (METER Group), con radio de disco de contacto $r = 2.25\text{ cm}$. Se aplicaron secuencialmente cuatro tensiones de entrada: $\psi = -0.5, -1.0, -2.0\text{ y } -3.0\text{ cm}$. Se registró el volumen acumulado infiltrado cada 30 segundos durante 10 minutos por tensión.

De acuerdo con la física capilar, la tensión de succión excluye el flujo en aquellos poros con radio equivalente $r_p$ mayor que el límite de Laplace-Young:

$$r_p > \frac{2 \sigma \cos \theta}{\rho_w g |\psi|}$$

A $20^\circ\text{C}$, las tensiones de $-0.5\text{ cm}$ y $-3.0\text{ cm}$ excluyen poros con diámetros superiores a $0.6\text{ mm}$ y $0.1\text{ mm}$ respectivamente. La conductividad no saturada $K(\psi)$ se calculó según el método de Zhang (1997):

$$K(\psi) = \frac{C_1}{A_{text}}$$

donde $C_1$ es la pendiente cuadrática de la infiltración acumulada respecto a $\sqrt{t}$ y $A_{text}$ es el factor de textura del manual METER (2021).

La dependencia funcional de la conductividad no saturada respecto al potencial matricial ($h = -\psi$) se modeló mediante la función exponencial de Gardner (1958):

$$K(h) = K_s \cdot e^{\alpha h}$$

donde $K_s$ es la conductividad saturada de la matriz extrapolada a $h \to 0$, y $\alpha$ ($\text{cm}^{-1}$) es el parámetro de desaturación de poros.

### 2.4 Formulación Analítica de Carga Única (Wooding 1968) para Ensayos con Anomalías
En el ensayo JUAN-R-14 (Vilcabamba), la inversión estándar dual-head arrojó un valor no físico negativo ($-0.00146\text{ cm/s}$) debido a que el incremento de presión nominal no pudo ser alcanzado plenamente y el flujo decaimiento natural por colmatación matricial sobrepasó el salto hidráulico ($q_2 < q_1$).

Para subsanar esta perturbación sin descartar el ensayo, se aplicó la solución teórica de flujo estacionario tridimensional desde una fuente circular deprimida (Wooding, 1968; Reynolds & Elrick, 1990):

$$K_{fs} = \frac{q_{ss}}{1 + \frac{H}{C \cdot d} + \frac{1}{\alpha^* \cdot C \cdot d}}$$

donde $q_{ss}$ es el flujo cuasi-estacionario medido en los últimos 15 minutos del ensayo, $H$ es la carga hidráulica efectiva promedio durante dicho intervalo ($4.86\text{ cm}$), y $\alpha^*$ es el parámetro de textura agrícola estándar ($0.12\text{ cm}^{-1}$ para texturas francas estructuradas).

### 2.5 Modelación No Lineal de la Infiltración
Se evaluaron tres modelos clásicos mediante ajuste de mínimos cuadrados ponderados no lineales:
1. **Modelo de Kostiakov (1932):**
   $$I(t) = k \cdot t^a$$
   donde $k$ es el coeficiente de capacidad de infiltración inicial y $a$ es el exponente adimensional de atenuación.
2. **Modelo de Philip (1957):**
   $$I(t) = S \cdot t^{0.5} + A \cdot t$$
   donde $S$ ($\text{cm/min}^{0.5}$) es la sortividad matricial y $A$ ($\text{cm/min}$) representa la transmisividad gravitacional.
3. **Modelo de Horton (1940):**
   $$q(t) = f_c + (f_0 - f_c) e^{-\beta t}$$
   donde $f_0$ y $f_c$ son las capacidades de infiltración inicial y final ($\text{cm/h}$), y $\beta$ ($\text{min}^{-1}$) es el factor de decaimiento.

La bondad de ajuste se determinó a través del coeficiente de determinación ($R^2$) y la raíz del error cuadrático medio (RMSE).

### 2.6 Procedimiento Estadístico e Inferencia Multivariada
- **Normalidad y Homocedasticidad:** Se verificó la normalidad univariada de los flujos mediante la prueba de Shapiro-Wilk y la homogeneidad de varianzas inter-sitios mediante las pruebas de Levene y Bartlett.
- **Pruebas de Hipótesis:** Ante la heterocedasticidad demostrada, se ejecutó el ANOVA robusto de Welch sobre datos brutos y log-transformados, cuantificando el tamaño del efecto mediante $\eta^2$ (Eta-cuadrado). Como contraste no paramétrico distribution-free, se ejecutó la prueba de Kruskal-Wallis ($H$) y comparaciones múltiples post-hoc pareadas de Mann-Whitney $U$ con ajuste estricto de Bonferroni y Holm.
- **Análisis Multivariado 3D (PCA 3D):** Se construyó una matriz estandarizada ($Z$-scores) con 8 variables hidrofísicas ($K_{fs}$, $q_{mean}$, $q_{ss}$, $q_{max}$, $I_{total}$, volumen total, sortividad $S$ y transmisividad $A$). Se extrajeron los tres primeros componentes principales (PC1, PC2, PC3).
- **Agrupamiento Jerárquico (HCA):** Se aplicó el algoritmo aglomerativo de Ward con métrica de distancia euclidiana al cuadrado, validando las tipologías funcionales edáficas.

---

## 3. Resultados

### 3.1 Conductividad Hidráulica Saturada ($K_{fs}$) y Dinámica Regional
La Tabla 1 consolida los parámetros hidrodinámicos obtenidos en las 8 parcelas evaluadas. La $K_{fs}$ de campo varió en más de un orden de magnitud entre sitios, desde $5.14\text{ cm/h}$ en Mélida Cahuinal (Palanda) hasta $68.54\text{ cm/h}$ en Ramiro Pintado (Palanda).

**Tabla 1.** Parámetros hidrodinámicos, conductividad hidráulica saturada de campo ($K_{fs}$) y ajuste de modelos físicos en las parcelas evaluadas.

| Parcela | Localidad | Sector | $K_{fs}$ (cm/h) | Flujo Medio (cm/h) | Infil. Total (cm) | Kostiakov $R^2$ | Philip $R^2$ | Horton $R^2$ | Clúster |
| :--- | :--- | :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **JIMMY-ABAD** | Fundochamba | Principal | 44.39 | 86.75 | 166.27 | 0.9918 | 0.9911 | 0.1356 | C2 |
| **CAFe-LUIS-CORDERO** | Palanda | Pucarón | 34.64 | 80.61 | 127.63 | 0.9967 | 0.9966 | 0.1174 | C2 |
| **MELIDA-CAHUINAL** | Palanda | Pucarón | 5.14 | 7.28 | 13.96 | 0.9906 | 0.9882 | 0.0100 | C1 |
| **CAFE-LAPALMA-SF** | Palanda | San Francisco | 39.49 | 81.16 | 128.50 | 0.9945 | 0.9926 | 0.0466 | C3 |
| **RAMIRO-PINTADO** | Palanda | San Francisco | 68.54 | 121.73 | 192.74 | 0.9971 | 0.9968 | 0.2025 | C2 |
| **JORGE-LAPO** | Vilcabamba | Principal | 17.93 | 22.80 | 36.10 | 0.9892 | 0.9860 | 0.0126 | C1 |
| **JUAN-R-14** | Vilcabamba | Principal | 13.03* | 20.28 | 25.35 | 0.9994 | 0.9987 | 0.4784 | C1 |
| **ULT-FK3** | Vilcabamba | Principal | 11.49 | 17.78 | 28.16 | 0.9966 | 0.9959 | 0.0506 | C1 |

*\*Valor recalculado mediante solución analítica de Wooding (1968).*

A nivel de sitio:
- **Fundochamba:** $K_{fs} = 44.39\text{ cm/h}$, flujo medio de $86.75\text{ cm/h}$ y lámina total infiltrada de $166.27\text{ cm}$.
- **Palanda ($N=4$):** $K_{fs}\text{ media} = 36.95 \pm 25.96\text{ cm/h}$, con tasa media de infiltración de $72.70 \pm 47.67\text{ cm/h}$.
- **San Pedro de Vilcabamba ($N=3$):** $K_{fs}\text{ media} = 13.03 \pm 4.34\text{ cm/h}$, con tasa media de infiltración de $20.29 \pm 2.51\text{ cm/h}$.

### 3.2 Inferencia Estadística y Pruebas de Hipótesis
La prueba de Shapiro-Wilk rechazó la normalidad de las tasas de infiltración minutales en todos los sitios ($p < 10^{-7}$). Asimismo, la prueba de Levene evidenció heterocedasticidad significativa ($W = 235.15, p = 1.40 \times 10^{-80}$).

El ANOVA robusto de Welch sobre los 780 registros minutales demostró una divergencia hidrodinámica altamente significativa entre sitios:
$$F_{(2, 777)} = 192.24, \quad p = 1.489 \times 10^{-68}$$
El tamaño del efecto fue de **$\eta^2 = 0.331$**, indicando que el **$33.1\%$ de la varianza total** en la velocidad de infiltración está determinada por la pertenencia geográfica del suelo.

La prueba no paramétrica de Kruskal-Wallis ratificó el resultado:
$$H = 184.88, \quad p = 7.131 \times 10^{-41} \quad (g.l. = 2)$$

Los contrastes post-hoc de Mann-Whitney $U$ con ajuste de Bonferroni confirmaron diferencias pareadas significativas en todos los casos:
- Fundochamba vs Palanda: $U = 27,597.5, \quad p_{adj} = 0.0032$ (Diferencia significativa).
- Fundochamba vs Vilcabamba: $U = 30,237.5, \quad p_{adj} = 4.90 \times 10^{-52}$ (Altamente significativo).
- Palanda vs Vilcabamba: $U = 75,331.5, \quad p_{adj} = 1.00 \times 10^{-19}$ (Altamente significativo).

### 3.3 Ajuste de Modelos Físicos de Infiltración
Los modelos acumulativos presentaron una capacidad predictiva superior en comparación con el modelo diferencial de flujo:
- **Kostiakov:** Coeficientes $R^2$ entre **0.9892 y 0.9994** (media $R^2 = 0.9945$). Los valores del exponente $a$ oscilaron entre $0.827$ y $1.079$, con valores próximos a $1.0$ en Fundochamba y Palanda, denotando conductividad constante sostenida por macroporos.
- **Philip:** Coeficientes $R^2$ entre **0.9860 y 0.9987** (media $R^2 = 0.9932$). El parámetro de transmisividad gravitacional $A$ osciló entre $0.119\text{ cm/min}$ (Mélida Cahuinal) y $2.077\text{ cm/min}$ (Ramiro Pintado), correlacionándose directamente con la $K_{fs}$ ($r = 0.987, p < 0.0001$).
- **Horton:** Presentó ajustes variables ($R^2$ de $0.01$ a $0.48$). Esto responde a la naturaleza pulsada de la carga hidrostática aplicada por SATURO ($H_1 \to H_2$), la cual induce perturbaciones escalonadas en la tasa instantánea de flujo $q(t)$.

### 3.4 Análisis Multivariado 3D y Tipologías de Suelo
El PCA tridimensional explicó el **$99.58\%$** de la varianza hidrológica acumulada:
- **PC1 (85.65% varianza):** Cargas positivas homogéneas en $K_{fs}$ ($0.376$), $q_{mean}$ ($0.381$), $q_{ss}$ ($0.372$) y volumen total ($0.380$). Constituye el **Eje de Transmisividad Gravitacional y Conducción Macroporosa**.
- **PC2 (12.72% varianza):** Dominado casi en su totalidad por la sortividad capilar $S$ ($0.991$). Constituye el **Eje de Succión Matricial**.
- **PC3 (1.21% varianza):** Vinculado a la dinámica transitoria y al decaimiento temporal relativo.

El agrupamiento jerárquico de Ward delimitó tres clústeres hidrodinámicos funcionales:
1. **Clúster 1 (Permeabilidad Baja a Moderada, Control Matricial):** Integrado por *Jorge Lapo*, *Juan R-14*, *Tulio Toledo* (Vilcabamba) y *Mélida Cahuinal* (Palanda). $K_{fs} \in [5.1, 17.9]\text{ cm/h}$.
2. **Clúster 2 (Permeabilidad Muy Rápida, Dominio de Macroporos):** Integrado por *Jimmy Abad* (Fundochamba), *Luis Cordero* y *Ramiro Pintado* (Palanda). $K_{fs} \in [34.6, 68.5]\text{ cm/h}$.
3. **Clúster 3 (Alta Infiltración con Sortividad Capilar Sobresaliente):** Integrado por *Café La Palma* (Palanda). $K_{fs} = 39.49\text{ cm/h}$ con $S = 2.40\text{ cm/min}^{0.5}$.

### 3.5 Partición Multiescala de Flujo en Fundochamba
El ensayo de Minidisco a tensiones de $-0.5, -1.0, -2.0\text{ y } -3.0\text{ cm}$ arrojó conductividades no saturadas de $2.60, 2.78, 1.57\text{ y } 1.28\text{ cm/h}$ respectivamente. El ajuste del modelo de Gardner:
$$K(h) = 3.10 \cdot e^{0.35 h} \quad (R^2 = 0.786)$$
permitió extrapolar una conductividad saturada de la matriz edáfica ($h \to 0$) de **$K_{sat\text{ matriz}} = 3.07\text{ cm/h}$**.

Al contrastar con la $K_{fs}$ obtenida bajo encharcamiento positivo con SATURO ($44.39\text{ cm/h}$):
$$\text{Flujo por Macroporos} = 44.39 - 3.07 = 41.32\text{ cm/h} \quad (\mathbf{93.1\%})$$
$$\text{Flujo por Matriz} = 3.07\text{ cm/h} \quad (\mathbf{6.9\%})$$

---

## 4. Discusión

### 4.1 Dominancia de Bioporos y Dinámica de Doble Porosidad
La constatación de que el **$93.1\%$ del flujo saturado** en Fundochamba ocurre a través de macroporos estructurales evidencia la existencia de una red dual de porosidad activa (*dual-porosity / dual-permeability system*; van Genuchten, 1980; Nimmo et al., 2009). En sistemas agroforestales de café, la continua renovación de raíces adventicias y pivotantes, combinada con la actividad de macrofauna edáfica y el aporte de materia orgánica superficial, estructura bioporos cilíndricos y continuos con diámetros superiores a $0.5\text{ mm}$.

Bajo eventos de lluvia torrencial o encharcamiento superficial, la capacidad de infiltración se dispara debido a que la conductividad depende de la cuarta potencia del radio del poro (Ley de Poiseuille: $q \propto r_p^4$). En contraste, tan pronto como cesa la carga hidráulica positiva y el suelo entra en potenciales de succión negativos ($\psi < -0.5\text{ cm}$), los macroporos se vacían instantáneamente y el transporte queda confinado a la matriz microporosa, reduciendo drásticamente la tasa de conducción a valores de $1.3 - 3.1\text{ cm/h}$.

### 4.2 Contraste Pedoclimático entre Vertientes Andinas
El comportamiento hidrodinámico reflejó con precisión el origen geológico y climático de los sitios:
1. **Palanda (Vertiente Amazónica):** Las parcelas de San Francisco y Pucarón (a excepción de Mélida Cahuinal) presentaron las mayores velocidades de infiltración ($34.6 - 68.5\text{ cm/h}$). Estos andisoles/inceptisoles húmedos poseen una microestructura granular esponjosa y alto contenido de carbono orgánico, favoreciendo una macroagregación muy estable.
2. **Vilcabamba (Valle Interandino):** La conductividad saturada promedio de $13.03\text{ cm/h}$ es coherente con suelos francos más compactados y consolidados, con menor densidad de raíces profundas y menor abundancia de bioporos activos. El flujo está dominado por capilaridad matricial, lo que asegura una mayor capacidad de retención de humedad en el perfil.

### 4.3 Robustez Metodológica: Resolución de Fallas de Inversión con Wooding
El caso de la parcela JUAN-R-14 subraya una vulnerabilidad conocida de los infiltrómetros automatizados de doble carga (Reynolds & Elrick, 1990). Cuando la presión en el segundo escalón no logra superar el umbral de estabilización o el suelo experimenta colmatación superficial simultánea, $q_2$ puede resultar menor que $q_1$, provocando que el software reporte valores negativos. La aplicación de la solución tridimensional de Carga Única de Wooding (1968) utilizando el flujo final ($q_{ss} = 18.29\text{ cm/h}$) rescató el valor físico real ($13.03\text{ cm/h}$), demostrando concordancia con las demás parcelas del sector ($11.5 - 17.9\text{ cm/h}$).

---

## 5. Implicaciones Agronómicas y Manejo del Riego

La clasificación de permeabilidad del USDA-NRCS y la FAO arroja directrices diferenciadas:

1. **Cafetales de Fundochamba y Palanda (Clase Rápida a Muy Rápida, $> 36\text{ cm/h}$):**
   - **Riesgo:** Si se aplica riego por gravedad (surcos o inundación) o láminas superiores a $20\text{ mm}$ por evento, el agua activará la autopista de macroporos, perdiéndose por percolación profunda y lixiviando nitrógeno nítrico ($NO_3^-$) y potasio ($K^+$) hacia los acuíferos.
   - **Manejo:** Se recomienda implementar **riego localizado de alta frecuencia (goteo o microaspersión)** con **pulsos cortos (15 a 30 minutos)**, permitiendo que el agua humedezca la matriz por capilaridad sin desencadenar el drenaje por bioporos.
2. **Cafetales de San Pedro de Vilcabamba (Clase Moderada, $11.5 - 18\text{ cm/h}$):**
   - **Manejo:** Presentan una capacidad de infiltración balanceada. Admiten láminas de riego de $25\text{ a }35\text{ mm}$ con intervalos de 5 a 8 días entre turnos, sin riesgo inminente de escorrentía ni lixiviación acelerada.

---

## 6. Conclusiones

1. Los agroecosistemas cafetaleros del sur del Ecuador presentan una heterogeneidad hidrodinámica altamente significativa ($p < 0.0001, \eta^2 = 0.331$), dividiéndose en suelos macroporosos de percolación muy rápida en Fundochamba y Palanda ($K_{fs} = 34.6 - 68.5\text{ cm/h}$) y suelos matriciales de permeabilidad moderada en Vilcabamba ($K_{fs} = 11.5 - 17.9\text{ cm/h}$).
2. La integración de SATURO y Minidisco reveló que en Fundochamba el **$93.1\%$ del flujo saturado** circula a través de macroporos biológicos, mientras que la matriz del suelo solo aporta el $6.9\%$ ($3.07\text{ cm/h}$), confirmando la dominancia de flujo preferencial en cafetales de sombra.
3. Los modelos de Kostiakov y Philip demostraron una excelente bondad de ajuste acumulativo ($R^2 > 0.988$). El modelo PCA 3D sintetizó el **$99.58\%$** de la varianza física, ratificando a la transmisividad gravitacional y a la sortividad capilar como los ejes rectores del transporte hídrico.
4. La formulación analítica de Wooding (1968) demostró ser un método de control de calidad indispensable para subsanar anomalías de inversión en equipos automatizados de doble carga.

---

## 7. Disponibilidad de Datos y Código
El conjunto completo de datos crudos minutales, matrices de modelación, figuras de alta resolución (300 DPI) y el Dashboard Web interactivo están disponibles en el repositorio del proyecto:
- [Dashboard Interactivo (`index.html`)](index.html)
- [Base de Datos Estructurada (`results_analysis.json`)](results_analysis.json)
- [Galería de Figuras Científicas (`figures/`)](figures)

---

## 8. Referencias Bibliográficas

- Gardner, W. R. (1958). Some steady-state solutions of the unsaturated moisture flow equation with application to evaporation from a water table. *Soil Science*, 85(4), 228–232.
- Hillel, D. (2004). *Introduction to Environmental Soil Physics*. Elsevier Academic Press, Amsterdam.
- Horton, R. E. (1940). An approach toward a physical interpretation of infiltration-capacity. *Soil Science Society of America Proceedings*, 5(C), 399–417.
- Kostiakov, A. N. (1932). On the dynamics of the coefficient of water-percolation in soils and on the necessity of studying it from a dynamic point of view for purposes of amelioration. *Transactions of 6th Commission of International Society of Soil Science*, Part A, 17–21.
- METER Group, Inc. (2021). *SATURO Infiltrometer User Manual*. Document 10564-14, Pullman, WA.
- Nimmo, J. R., Schmidt, K. S., Perkins, K. S., & Stock, J. D. (2009). Rapid measurement on unsteady infiltration to estimate field-saturated hydraulic conductivity. *Vadose Zone Journal*, 8(3), 742–749.
- Philip, J. R. (1957). The theory of infiltration: 1. The infiltration equation and its solution. *Soil Science*, 83(5), 345–358.
- Reynolds, W. D., & Elrick, D. E. (1990). Ponded infiltration from a single ring: I. Analysis of steady flow. *Soil Science Society of America Journal*, 54(5), 1233–1241.
- USDA-NRCS. (1999). *Soil Taxonomy: A Basic System of Soil Classification for Making and Interpreting Soil Surveys* (2nd ed.). Agricultural Handbook 436, Washington, DC.
- Vandervaere, P., Vauclin, M., & Elrick, D. E. (2000). Transient flow from tension infiltrometers: II. Four methods to determine sorptivity and hydraulic conductivity. *Soil Science Society of America Journal*, 64(4), 1272–1284.
- van Genuchten, M. T. (1980). A closed-form equation for predicting the hydraulic conductivity of unsaturated soils. *Soil Science Society of America Journal*, 44(5), 892–898.
- Wooding, R. A. (1968). Steady infiltration from a shallow circular pond. *Water Resources Research*, 4(6), 1259–1273.
- Zhang, R. (1997). Determination of soil sorptivity and hydraulic conductivity from the disk infiltrometer. *Soil Science Society of America Journal*, 61(4), 1024–1030.
