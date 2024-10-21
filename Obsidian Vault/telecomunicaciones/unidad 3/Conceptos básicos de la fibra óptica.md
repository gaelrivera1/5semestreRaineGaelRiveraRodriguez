Las fibras ópticas son guías de ondas dieléctricas circulares que pueden transportar energía óptica e información. Tienen un núcleo central rodeado por un revestimiento concéntrico con un índice de refracción ligeramente inferior (en aproximadamente un 1 %). [Las fibras ópticas](https://www.newport.com/c/optical-fibers) suelen estar hechas de sílice con dopantes que modifican el índice, como GeO 2 . Se utiliza un revestimiento protector de una o dos capas de material de amortiguación (como acrilato) para reducir la diafonía entre fibras adyacentes y la micro curvatura que aumenta la pérdida que se produce cuando las fibras se presionan contra superficies rugosas.

![[Pasted image 20241010073821.png]]

### La fibra como guía de ondas dieléctrica: modos de fibra

Dado que el núcleo tiene un índice de refracción más alto que el revestimiento, la luz se limitará al núcleo si se cumple la condición angular de reflectancia interna total. La geometría y la composición de la fibra determinan el conjunto discreto de campos electromagnéticos, o modos de fibra, que pueden propagarse en la fibra.

Existen dos grandes clasificaciones de modos: modos de radiación y modos guiados. Los modos de radiación transportan energía fuera del núcleo; la energía se disipa rápidamente. Los modos guiados están confinados en el núcleo y propagan energía a lo largo de la fibra, transportando información y potencia. Si el núcleo de la fibra es lo suficientemente grande, puede admitir muchos modos guiados simultáneos. Cada modo guiado tiene su propia velocidad distintiva y puede descomponerse en componentes polarizados linealmente ortogonales.

![Distribución modal LP<sub>01</sub>](https://www.newport.com/medias/sys_master/images/images/he6/h65/8921536233502/LP10-Mode-Dist-1-S-400w.jpg)   ![Distribución de modos LP<sub>11</sub>](https://www.newport.com/medias/sys_master/images/images/h43/h4d/8921537347614/LP11-Mode-Dist-2-S-400w.jpg)

Cuando se lanza luz a una fibra, los modos se excitan en distintos grados según las condiciones del lanzamiento (ángulo del cono de entrada, tamaño del punto, centrado axial, etc.). La distribución de energía entre los modos evoluciona con la distancia a medida que se intercambia energía entre ellos. En particular, la energía se puede acoplar de los modos guiados a los modos de radiación mediante perturbaciones como la micro curvatura y la torsión de la fibra, lo que aumenta la atenuación.

### Limitaciones de ancho de banda

El ancho de banda de una fibra óptica determina la velocidad de transmisión de datos. El mecanismo que limita el ancho de banda de una fibra se conoce como dispersión. La dispersión es la dispersión de los pulsos ópticos a medida que viajan por la fibra. El resultado es que los pulsos comienzan a dispersarse entre sí y los símbolos se vuelven indistinguibles. Existen dos categorías principales de dispersión: intermodal e intramodal.

![Dispersión en una fibra óptica](https://www.newport.com/medias/sys_master/images/images/hea/hb0/8797971906590/Dispersion-diagram-S-400w.gif)

### Dispersión intermodal

La dispersión intramodal, a veces llamada dispersión material, es el resultado de las propiedades materiales de la fibra óptica y se aplica tanto a las fibras monomodo como a las multimodo. Existen dos tipos distintos de dispersión intramodal: dispersión cromática y dispersión por modo de polarización

Como su nombre lo indica, la dispersión intermodal es un fenómeno entre diferentes modos en una fibra óptica. Por lo tanto, esta categoría de dispersión solo se aplica a la fibra multimodo. Dado que todos los diferentes modos de propagación tienen diferentes velocidades de grupo, el tiempo que tarda cada modo en recorrer una distancia fija también es diferente. Por lo tanto, a medida que un pulso óptico viaja por una fibra multimodo, los pulsos comienzan a propagarse, hasta que finalmente se propagan entre sí. Este efecto limita tanto el ancho de banda de la fibra multimodo como la distancia que puede transportar datos.

### Dispersión cromática y por modo de polarización

El índice de refracción varía según la longitud de onda. Por lo tanto, distintas longitudes de onda viajarán por una fibra óptica a distintas velocidades. Esto se conoce como dispersión cromática.

Este principio implica que un pulso con un ancho de banda más amplio se propagará más que un pulso con un ancho de banda más estrecho. La dispersión limita tanto el ancho de banda como la distancia a la que se puede transmitir la información. Por eso, para enlaces de comunicaciones largos, es conveniente utilizar un láser con un ancho de línea muy estrecho. Los láseres de retroalimentación distribuida (DFB) son populares para las comunicaciones porque tienen un solo modo longitudinal con un ancho de línea muy estrecho.

### Dispersión cromática y por modo de polarización

El índice de refracción varía según la longitud de onda. Por lo tanto, distintas longitudes de onda viajarán por una fibra óptica a distintas velocidades. Esto se conoce como dispersión cromática.

Este principio implica que un pulso con un ancho de banda más amplio se propagará más que un pulso con un ancho de banda más estrecho. La dispersión limita tanto el ancho de banda como la distancia a la que se puede transmitir la información. Por eso, para enlaces de comunicaciones largos, es conveniente utilizar un láser con un ancho de línea muy estrecho. Los láseres de retroalimentación distribuida (DFB) son populares para las comunicaciones porque tienen un solo modo longitudinal con un ancho de línea muy estrecho.

### Atenuación

La potencia luminosa que se propaga por una fibra óptica decae exponencialmente con la longitud debido a las pérdidas por absorción y dispersión. La atenuación es el factor más importante que determina el coste de los sistemas de telecomunicaciones por fibra óptica, ya que determina el espaciamiento de los repetidores necesario para mantener niveles de señal aceptables.

En las regiones del infrarrojo cercano y del espectro visible, las pequeñas pérdidas de absorción de la sílice pura se deben a las colas de las bandas de absorción en el infrarrojo lejano y el ultravioleta. Las impurezas (en particular el agua en forma de iones hidroxilo) son causas mucho más dominantes de absorción en las fibras comerciales. Las recientes mejoras en la pureza de las fibras han reducido las pérdidas por atenuación. Los sistemas de última generación pueden tener una atenuación del orden de 0,1 dB/km.![[Pasted image 20241010075514.png]]

### Apertura numérica (NA)

La apertura numérica (NA) de una fibra se define como el seno del ángulo más grande que un rayo incidente puede tener para la reflectancia interna total en el núcleo. Los rayos lanzados fuera del ángulo especificado por la NA de una fibra excitarán los modos de radiación de la fibra. Un índice de núcleo más alto, con respecto al revestimiento, significa una NA más grande. Sin embargo, aumentar la NA causa una mayor pérdida por dispersión debido a mayores concentraciones de dopante. La NA de una fibra se puede determinar midiendo el ángulo de divergencia del cono de luz que emite cuando se excitan todos sus modos.

![Apertura numérica de una fibra óptica](https://www.newport.com/medias/sys_master/images/images/h81/h40/8921545408542/Numerical-Aperture-S-400w.gif)

### “Número V”

El parámetro de frecuencia normalizada de una fibra, también llamado número V, es una especificación útil. Muchos parámetros de la fibra se pueden expresar en términos de V, como: el número de modos en una longitud de onda dada, las condiciones de corte de modo y las constantes de propagación. Por ejemplo, el número de modos guiados en una fibra multimodo de índice escalonado se da por V 2 /2, y una fibra de índice escalonado se convierte en monomodo para una longitud de onda dada cuando V < 2,405. Matemáticamente, V = 2 π·NA·a/λ donde “a” es el radio del núcleo de la fibra.

### Pelado de fibras

La cubierta exterior de los cables de fibra se puede quitar con herramientas para pelar cables eléctricos, y las tijeras o una cuchilla de afeitar pueden cortar el elemento de refuerzo de Kevlar. Sin embargo, el revestimiento de la fibra debe quitarse con mucho cuidado para evitar dañar la fibra: los defectos de la superficie y los rayones son la causa de la mayoría de las fallas de la fibra. El revestimiento se puede quitar con nuestros [pelacables de fibra óptica](https://www.newport.com/f/fiber-optic-strippers) .

### Terminación de fibra

La calidad de la superficie de los extremos es uno de los factores más importantes que afectan las pérdidas de empalme y de conectores de fibra. Se pueden obtener superficies de terminación de calidad mediante pulido o utilizando una [cuchilla de fibra](https://www.newport.com/f/manual-fiber-cleavers) . El pulido se emplea en terminaciones de conectores cuando la fibra está asegurada en una férula con epoxi. A continuación se describen los conectores más populares y sus estilos de preparación de superficies de terminación.

### Tipos de conectores de fibra óptica

![Ejemplos de diferentes tipos de conectores de fibra óptica](https://www.newport.com/medias/sys_master/images/images/h1e/h62/8801645428766/17-095-S-400w.jpg)

**SMA** : debido a su estructura de acero inoxidable y su mecanismo de bloqueo de fibra roscada de baja precisión, este conector se utiliza principalmente en aplicaciones que requieren el acoplamiento de rayos láser de alta potencia en fibras multimodo de núcleo grande. Las aplicaciones típicas incluyen sistemas de transmisión de rayos láser en aplicaciones médicas, biomédicas e industriales. La pérdida de inserción típica de un conector SMA es superior a 1 dB.

**ST** : el conector ST se utiliza ampliamente tanto en aplicaciones de red de área local (LAN) de fibra óptica en interiores como en el campo. Su casquillo cerámico de alta precisión permite su uso con fibras monomodo y multimodo. El mecanismo de acoplamiento con llave de tipo bayoneta, que cuenta con bloqueo por presión y giro del conector, evita el apriete excesivo y el daño del extremo de la fibra. La pérdida de inserción del conector ST es inferior a 0,5 dB, y se alcanzan valores típicos de 0,3 dB de manera habitual. Los conectores ST metálicos perforados, con pérdidas de inserción de >1 dB, se utilizan con las fibras de núcleo grande (>140 µm) de Newport.

**FC** : el FC se ha convertido en el conector de elección para fibras monomodo y se utiliza principalmente en instrumentos de fibra óptica, componentes de fibra óptica SM y en enlaces de comunicación de fibra óptica de alta velocidad. Este conector de casquillo cerámico de alta precisión está equipado con una llave antirrotación, que reduce el daño en los extremos de la fibra y la sensibilidad de alineación rotacional de la fibra. La llave también se utiliza para la alineación repetible de las fibras en la posición óptima con mínima pérdida. También hay versiones multimodo de este conector. La pérdida de inserción típica del conector FC es de alrededor de 0,3 dB. Los conectores FC metálicos perforados, que tienen pérdidas de inserción de >1 dB, se utilizan con las fibras de núcleo grande (>140 µm) de Newport.

**SC** : el conector SC se está volviendo cada vez más popular en telecomunicaciones de fibra óptica monomodo y CATV analógica, enlaces implementados en campo. La construcción de casquillo cerámico de alta precisión es óptima para alinear fibras ópticas monomodo. El perfil cuadrado exterior de los conectores combinado con su mecanismo de acoplamiento push-pull, permite una mayor densidad de empaquetado de conectores en instrumentos y paneles de conexión. El cuerpo exterior enchavetado evita la sensibilidad rotacional y el daño en los extremos de la fibra. También hay versiones multimodo de este conector. La pérdida de inserción típica del conector SC es de alrededor de 0,3 dB.

### Acoplamiento de la luz en fibras

Una buena eficiencia de acoplamiento requiere un posicionamiento preciso de la fibra para centrar el núcleo en el haz láser enfocado. En el caso de las fibras multimodo, con sus núcleos grandes, los posicionadores de fibra óptica pueden lograr una buena eficiencia de acoplamiento. Las fibras monomodo requieren acopladores más elaborados con una resolución de posicionamiento submicrónica, como los acopladores de fibra óptica [F-915](https://www.newport.com/p/F-915) y [F-1015 de](https://www.newport.com/p/F-1015) [ULTRAlign](https://www.newport.com/f/ultralign-precision-fiber-optic-alignment-stages) y los posicionadores de acero inoxidable 562F . Estos también son útiles con [fibras multimodo](https://www.newport.com/c/multi-mode-optical-fibers) cuando se requiere la máxima eficiencia de acoplamiento.

![[Pasted image 20241010080019.png]]

