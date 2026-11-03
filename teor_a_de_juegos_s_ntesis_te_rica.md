# Teoría de Juegos
## Fundamentos matemáticos, evolución epistémica y aplicaciones contemporáneas
**Síntesis de la parte teórica**

**Definición.** La teoría de juegos es el estudio matemático de las interacciones estratégicas entre agentes racionales, donde las decisiones interdependientes de varios individuos producen resultados que dependen de las preferencias (funciones de utilidad) de todos los involucrados. Es hoy un lenguaje transversal a la economía, las ciencias sociales, la biología evolutiva, la informática y la física cuántica.

## 1. Fundamentos históricos

*   **von Neumann y Morgenstern (1944).** *Theory of Games and Economic Behavior*: primera formalización general del conflicto y la cooperación, centrada en juegos de suma cero (lo que gana uno lo pierde el otro).
*   **Nash (década de 1950).** Extiende el análisis a juegos de suma no cero y demuestra que todo juego finito tiene al menos un equilibrio de estrategias mixtas: ningún jugador gana desviándose unilateralmente, dadas las estrategias de los demás. La disciplina se centra así en la elección racional interdependiente.
*   **Shapley (1953).** Valor de Shapley para juegos cooperativos: reparte el excedente total según la contribución marginal de cada jugador (promediada sobre todas las coaliciones posibles). Se basa en cuatro axiomas: eficiencia, simetría, jugador nulo y aditividad.

## 2. Fundamentos epistémicos y conocimiento común

La teoría epistémica hace explícitos los supuestos sobre conocimiento y creencias de los jugadores que la teoría clásica da por sentados, y modela formalmente la incertidumbre estratégica y la información de orden superior (lo que otros piensan que uno piensa).

*   **Harsanyi (1967) - tipos:** Toda incertidumbre sobre preferencias, pagos u opciones de otros se resuelve asignando una distribución de probabilidad sobre "tipos" que es conocimiento común; un juego de información incompleta pasa a ser uno de información imperfecta pero completa.
*   **Mertens y Zamir (1985) - espacio de tipos universal:** Construcción jerárquica infinita de creencias de orden superior que contiene todos los tipos posibles; permite modelar cualquier juego bayesiano sin pérdida de generalidad.
*   **Aumann (1976) - Teorema del Acuerdo:** Si dos agentes bayesianos comparten un *prior* común y sus creencias posteriores sobre un evento son conocimiento común, esas creencias deben ser idénticas: no pueden "acordar estar en desacuerdo". Variantes posteriores relajan el supuesto (creencias comunes con margen de error, Monderer y Samet; múltiples *priors* bajo ambigüedad).

$$ \text{Si } q_{1} \text{ y } q_{2} \text{ son las posteriores de los agentes 1 y 2 y son conocimiento común, entonces } q_{1}=q_{2} $$

## 3. Juegos repetidos, negociación y secuencialidad

### Teorema Popular (Folk Theorem)
**Fudenberg y Maskin (1986):** en juegos infinitamente repetidos con descuento, cualquier vector de pagos factible e individualmente racional que domine en el sentido de Pareto el pago minimax puede sostenerse como equilibrio perfecto en subjuegos (SPE), siempre que los jugadores sean suficientemente pacientes (factor de descuento $\delta\rightarrow1$). Para tres o más jugadores se requiere una condición de "dimensionalidad completa" del conjunto de pagos, que permite castigar a quien se desvía sin perjudicar a quienes castigan. La amenaza creíble de caer al nivel minimax supera cualquier ganancia momentánea por desviarse.

Fudenberg, Levine y Maskin extendieron el resultado a información pública imperfecta: la cooperación persiste aunque las acciones no sean observables, castigando según la distribución estadística de los resultados.

### Negociación de Rubinstein (1982)
Regateo alternando ofertas sobre la división de un excedente (juego extensivo con información perfecta). Por inducción hacia atrás, con jugadores impacientes existe un único SPE: el acuerdo se logra en el primer período, sin demoras ineficientes, y el poder de negociación depende inversamente de la tasa de descuento (quien tolera menos la espera obtiene una porción menor).

### Paradoja de la Cadena de Tiendas (Selten)
Un monopolista enfrenta a 20 competidores potenciales que entran uno a uno. La inducción hacia atrás dice que en la última etapa el monopolista acomoda al entrante, y por lo tanto la disuasión se desmorona hacia atrás hasta la primera etapa: todos entran. Sin embargo, intuitivamente al monopolista le conviene pelear al inicio para construir reputación y disuadir al resto. Selten lo explica con tres niveles de decisión humana (rutina, imaginación y razonamiento lógico): la amenaza no creíble triunfa en la práctica sobre la lógica algorítmica.

## 4. Teoría de juegos conductual

Reemplaza al *Homo economicus* con modelos empíricos que reflejan límites cognitivos, heurísticas y sesgos. Herbert Simon introdujo la racionalidad acotada: las personas son *satisficers*, no maximizadores perfectos.

*   **Jerarquía cognitiva (Level-k):** los jugadores razonan solo de uno a tres pasos por delante de un nivel base ingenuo (Level-0).
*   **Equilibrio de Respuesta Cuantal (QRE):** los jugadores evalúan utilidades esperadas pero cometen errores; los errores costosos son menos frecuentes que los baratos (respuesta suavizada).
*   **Concurso de belleza p (Nagel, 1995):** cada participante elige un número que sea una fracción $p$ (p. ej. $2/3$) del promedio de todas las elecciones. El único equilibrio de Nash (dominancia iterada) es $0$, pero los promedios empíricos están muy por encima.
*   **Juego del Ultimátum (Henrich et al., 2001):** en 15 sociedades de pequeña escala, las ofertas y rechazos variaron con las instituciones, la integración al mercado y la cooperación local. Los Machiguenga (Perú, poco integrados al mercado) ofrecieron poco y casi no rechazaron, cerca del equilibrio de Nash; los Lamalera (Indonesia, cazadores de ballenas dependientes de la cooperación) hacían ofertas hiperequitativas, a menudo rechazadas para evitar deudas sociales. Conclusión: las preferencias sociales y la noción de justicia no son fijas, sino que coevolucionan con la cultura y el entorno ecológico.

## 5. Teoría de juegos evolutiva

Introducida por Maynard Smith y Price (Nature, 1973). El equilibrio ya no exige racionalidad cognitiva: la selección natural sustituye a la elección deliberada. Los jugadores son organismos con estrategias fenotípicas preprogramadas y el pago es la aptitud (*fitness*) reproductiva.

### Estrategia Evolutivamente Estable (ESS)
Estrategia (o perfil mixto) que, adoptada por toda una población grande, resiste la invasión de cualquier mutante que aparezca en proporción marginal. Con $u(a,b) = \text{aptitud de jugar a contra b}$, la estrategia $\sigma$ es ESS frente a un mutante $\mu$ si:
1. $u(\sigma,\sigma) > u(\mu,\sigma)$ o bien 
2. $u(\sigma,\sigma) = u(\mu,\sigma) \text{ y } u(\sigma,\mu) > u(\mu,\mu)$

### Ecuación del replicador
Modela la dinámica poblacional continua: la frecuencia de una estrategia crece en proporción a la diferencia entre su aptitud y la aptitud promedio de la población. Toda ESS es un atractor asintóticamente estable bajo el replicador, pero el recíproco no siempre se cumple.

$$ \frac{dx_i}{dt} = x_{i} \cdot [f_{i}(x) - f(x)] $$

**Aplicaciones:** ritualización de conflictos territoriales sin derramamiento de sangre (juego Halcón-Paloma), invasiones biológicas de especies no nativas y, con Axelrod, la emergencia del altruismo recíproco: en su torneo computarizado, la estrategia simple Tit-for-Tat ("ojo por ojo") favoreció la cooperación en poblaciones egoístas.

### Oncología evolutiva: terapia adaptativa y juegos de Stackelberg
Un tumor se interpreta como un ecosistema dinámico y heterogéneo: subpoblaciones celulares con distintos fenotipos compiten por espacio, oxígeno y vascularización.

*   **Problema de la Dosis Máxima Tolerada (MTD):** elimina las células sensibles y provoca liberación competitiva: las células resistentes, que sin fármaco están en desventaja metabólica, quedan libres de competencia y proliferan, causando la recaída con un tumor refractario.
*   **Terapia adaptativa:** se modela como un juego de Stackelberg (líder-seguidor). El oncólogo es el líder que fija la dosificación y el tumor es el seguidor que se adapta por selección natural (dinámicas Lotka-Volterra extendidas o funciones generadoras de aptitud).
*   **Objetivo:** contener, no erradicar. Se interrumpe o reduce la dosis para conservar una subpoblación sensible manejable que, al recuperar su ventaja competitiva, suprime a las resistentes.
*   **Evidencia:** ensayos de fase 2 en cáncer de próstata metastásico resistente a la castración (abiraterona), reteniendo y reactivando la dosis según el PSA, prolongaron el tiempo hasta la progresión con menor toxicidad y costo. El aprendizaje por refuerzo profundo (DRL) busca políticas de dosificación personalizadas.

## 6. Diseño de mecanismos y mercados de emparejamiento

Mientras la teoría de juegos predice resultados dadas ciertas reglas, el diseño de mecanismos hace ingeniería inversa: diseña las reglas para lograr un resultado socialmente deseable (bienestar, eficiencia paretiana, compatibilidad de incentivos), asumiendo asimetrías de información y agentes egoístas.

*   **Gale y Shapley (1962) - Algoritmo de Aceptación Diferida:** Genera un emparejamiento estable en un mercado de dos lados: no existe ninguna pareja que prefiera mutuamente estar junta antes que con su asignación.
*   **Alvin Roth - médicos residentes (NRMP, EE. UU.):** el mercado sufría *unraveling* (adelantamiento de contrataciones) y volatilidad, en parte por parejas que buscaban la misma ubicación. Roth rediseñó el algoritmo con propuestas del lado estudiantil y restauró estabilidad y eficiencia.
*   **Alvin Roth - intercambio pareado de riñones:** pares paciente-donante incompatibles se tratan como recursos indivisibles; usando el algoritmo de Ciclos de Intercambio Principales (Top Trading Cycles, Shapley y Scarf) se creó una cámara de compensación centralizada. Con donantes altruistas no dirigidos se generan cadenas de donación no simultáneas, que ampliaron enormemente los trasplantes posibles. Roth y Shapley recibieron el Premio Nobel de Economía 2012 por este paso de la teoría al diseño práctico.

## 7. Subastas digitales: VCG y GSP

El diseño de mecanismos sustenta la publicidad online y la búsqueda patrocinada. Dos paradigmas de subasta:

| Característica | Vickrey-Clarke-Groves (VCG) | Generalized Second Price (GSP) |
| :--- | :--- | :--- |
| **Plataformas** | Facebook (Meta), Google (red contextual) | Google Search, Bing, Yahoo!, Taobao |
| **Asignación** | Maximiza el bienestar social: ordena de mayor a menor valor. | El espacio $k$ se asigna al $k$-ésimo postor más alto. |
| **Pago** | Cada postor paga la externalidad que impone al desplazar a otros de su posición óptima. | El postor de rango $k$ paga por clic la puja del postor siguiente (rango $k+1$). |
| **Estrategia** | A prueba de estrategias: pujar sinceramente es estrategia dominante. | Pujar sinceramente no es dominante; hay *bid shading* y vulnerabilidad a colusión de agencias. |

**Bid shading en GSP:** pujar por debajo del valor real puede ser rentable si bajar de posición reduce el pago más de lo que reduce el tráfico esperado. Edelman, Ostrovsky y Schwarz (2007) modelaron GSP como juego estático de información completa: tiene múltiples equilibrios ineficientes, pero refinan el conjunto a los Equilibrios Libres de Envidia Local (LEFE); el LEFE de menores ingresos reproduce exactamente las asignaciones y los ingresos de VCG. En mercados saturados de agencias que pujan por delegación, la evidencia reciente sugiere que VCG supera a GSP en ingresos y eficiencia asignativa.

## 8. Financiamiento cuadrático, blockchain y bienes públicos

El Financiamiento Cuadrático (QF), propuesto en 2018 por Buterin, Hitzig y Weyl (*Liberal Radicalism*), es un mecanismo para asignar fondos a bienes públicos (software abierto, investigación, ecología). Concilia la eficiencia de precios del mercado ("un dólar, un voto", que lleva al problema del polizón o *free-rider*) con la legitimidad democrática ("una persona, un voto", que puede ignorar minorías intensas), mediante un fondo de contrapartida (*matching pool*) externo. El subsidio crece con el número de contribuyentes únicos, no con el monto:

$$ Fondos_{j} = \left( \sum_{i=1}^{N} \sqrt{c_{i}} \right)^{2} $$
*(Donde $c_{i}$ = aporte del contribuyente $i$; $N$ = número de financiadores)*

*   **Ejemplo:** un multimillonario que aporta $\$10.000$ produce $(\sqrt{10.000})^{2} = \$10.000$ es decir ningún subsidio adicional; $10.000$ personas que aportan $\$1$ cada una (el mismo total) producen $(10.000 \cdot \sqrt{1})^{2} = 100.000.000$ de fondos teóricos, limitados en la práctica por el tamaño del fondo de contrapartida. La coordinación de la base popular pesa más que la profundidad de las billeteras.

**Vulnerabilidades en entornos reales (p. ej. Gitcoin Grants):**
*   **Ataque Sybil:** como QF premia el número de cuentas, un actor puede dividir su capital en miles de identidades falsas para captar el fondo de contrapartida.
*   **Colusión:** coordinación entre cuentas para manipular artificialmente los aportes.
*   **MEV (Maximal Extractable Value):** riqueza que proponentes de bloques y *searchers* extraen reordenando o inyectando transacciones (*frontrunning*, "Gas Wars"); degrada el bienestar del usuario y motiva subastas de prioridad *off-chain* como Flashbots.

## 9. Complejidad computacional y aprendizaje algorítmico

### Intratabilidad del equilibrio de Nash: PPAD
Daskalakis, Goldberg y Papadimitriou (2006) demostraron que calcular un equilibrio de Nash es PPAD-completo (extendido después a juegos de dos jugadores por Chen y Deng). La clase PPAD (*Polynomial Parity Arguments on Directed graphs*, Papadimitriou, 1994) reúne problemas de búsqueda total cuya solución siempre existe (teoremas existenciales no constructivos) pero sin camino algorítmico eficiente para hallarla. Es tan difícil como encontrar los puntos fijos de Brouwer. Implicación: si ni siquiera una supercomputadora puede hallar el equilibrio de un modelo estilizado en tiempo razonable, es implausible suponer que agentes reales lo alcancen espontáneamente.

### Counterfactual Regret Minimization (CFR)
Zinkevich et al. (2007). Técnica dominante para aproximar el equilibrio de Nash en juegos de información imperfecta como el póker (base de Libratus y Pluribus, vencedores en No-Limit Texas Hold'em). Funciona por autojuego iterativo: en cada nodo de información acumula el arrepentimiento contrafactual (cuánta utilidad adicional se habría obtenido tomando siempre una acción dada, con el resto de la política fija). Con Regret Matching (Blackwell), la probabilidad de cada acción en la siguiente iteración es proporcional a su arrepentimiento positivo acumulado. Para árboles enormes se combina con redes neuronales (Deep CFR) y muestreo de Monte Carlo (MCCFR).

*   **GANs (Goodfellow, 2014):** un Generador y un Discriminador compiten en un juego de suma cero cuyo punto de equilibrio es el minimax de un juego continuo no convexo de alta dimensión.

### Colusión algorítmica autónoma
Algoritmos de fijación dinámica de precios con aprendizaje por refuerzo (Q-learning, en el marco de procesos de decisión de Markov) en entornos tipo Bertrand aprenden a sostener precios supracompetitivos de forma tácita, sin pactos ni cárteles explícitos: castigan mutuamente las desviaciones a la baja, de manera similar a Tit-for-Tat. Esto desafía el derecho antimonopolio y plantea la necesidad de nuevas salvaguardas, incluso ante sistemas basados en grandes modelos de lenguaje.

### Precio de la Anarquía (Price of Anarchy, PoA)
Definido por Koutsoupias y Papadimitriou (1999) y desarrollado para redes congestionadas por Roughgarden y Tardos (2002). Mide la ineficiencia de un sistema descentralizado y egoísta:

$$ POA = \frac{\text{costo social del peor equilibrio de Nash}}{\text{costo social óptimo (planificador central)}} $$

Para redes de tráfico con funciones de latencia afines (equilibrio de Wardrop, flujo divisible), el PoA es como máximo $4/3$; el enrutamiento egoísta genera a lo sumo un $33\%$ más de costo que el óptimo centralizado. Relacionada está la Paradoja de Braess: añadir una vía a la red puede aumentar el tiempo promedio de viaje de todos, porque el enrutamiento egoísta desbalancea los flujos.

## 10. Teoría de juegos cuántica y cooperación climática

El protocolo EWL (Eisert, Wilkens y Lewenstein, Physical Review Letters, 1999) fue la primera cuantificación completa de un juego canónico: el Dilema del Prisionero. Cada jugador opera un qubit mediante operaciones unitarias; un árbitro aplica un operador de entrelazamiento antes y después de las jugadas y mide el resultado.

| Aspecto | Dilema del Prisionero clásico | Versión cuántica (EWL) |
| :--- | :--- | :--- |
| **Espacio de estrategias** | Acciones discretas: cooperar (C) o desertar (D); o estrategias mixtas. | Espacio de Hilbert complejo de dos dimensiones; qubits entrelazados en superposición. |
| **Mecánica** | Los jugadores eligen sin canal para comprometerse a cooperar. | Un entrelazador $J$ crea un estado inicial entrelazado; los jugadores aplican puertas unitarias; se aplica $J^\dagger$ y se mide. |
| **Resultado** | Equilibrio de Nash subóptimo (D, D), con pago (1, 1). | Con entrelazamiento máximo aparece una estrategia "milagrosa" Q que da el óptimo de Pareto (3, 3) de forma estable. |

**Idea central:** el entrelazamiento actúa como una restricción estructural que evita el equilibrio de deserción sin contratos ni comunicación clásica. Resultados análogos se estudian en juegos multijugador como el *Quantum Volunteer's Dilemma*.

### Clubes climáticos (Nordhaus)
Propuestos por William Nordhaus (Nobel de Economía; American Economic Review) para combatir el problema del *free-rider* en acuerdos climáticos como el de París: un arancel uniforme a los países que no participan funciona como sanción coordinada solo contra los desertores. Los modelos y experimentos indican que una penalización pequeña puede sostener una cooperación amplia entre los miembros del club.

## Cuadro resumen de conceptos clave

| Concepto | Autor / Año | Idea esencial |
| :--- | :--- | :--- |
| **Juegos de suma cero** | von Neumann y Morgenstern, 1944 | Formalización general del conflicto; lo que uno gana lo pierde el otro. |
| **Equilibrio de Nash** | Nash, años 50 | Nadie gana desviándose unilateralmente; existe en todo juego finito (en mixtas). |
| **Valor de Shapley** | Shapley, 1953 | Reparto justo según contribución marginal (4 axiomas). |
| **Tipos / espacio universal** | Harsanyi 1967; Mertens-Zamir 1985 | Modelar información incompleta mediante jerarquías de creencias. |
| **Teorema del Acuerdo** | Aumann, 1976 | Con *prior* común y posteriores de conocimiento común, no hay desacuerdo racional. |
| **Folk Theorem** | Fudenberg y Maskin, 1986 | En juegos repetidos, con paciencia, casi todo pago factible y racional es equilibrio. |
| **Negociación alternada** | Rubinstein, 1982 | SPE único; acuerdo inmediato; poder según impaciencia. |
| **Cadena de tiendas** | Selten | Inducción hacia atrás vs. reputación y disuasión. |
| **Racionalidad acotada / Level-k / QRE / ESS y replicador** | Simon; Nagel 1995 / Maynard Smith y Price, 1973 | Razonamiento limitado y errores proporcionales al costo. Estabilidad evolutiva sin racionalidad; dinámica por aptitud relativa. |
| **Terapia adaptativa** | Juegos de Stackelberg | Contener el tumor en lugar de erradicarlo para evitar la liberación competitiva. |
| **Aceptación diferida / TTC** | Gale-Shapley 1962; Roth | Emparejamientos estables e intercambios de riñones. |
| **VCG vs. GSP** | Vickrey-Clarke-Groves; EOS 2007 | VCG es veraz; GSP no, pero su LEFE de menor ingreso replica a VCG. |
| **Financiamiento cuadrático** | Buterin, Hitzig y Weyl, 2018 | Subsidio crece geométricamente con los aportes; vulnerable a Sybil y colusión. |
| **PPAD-completitud** | Daskalakis, Goldberg, Papadimitriou, 2006 | Calcular un Nash es computacionalmente intratable. |
| **CFR** | Zinkevich et al., 2007 | Autojuego con arrepentimiento contrafactual para juegos de información imperfecta. |
| **Price of Anarchy** | Koutsoupias-Papadimitriou 1999; Roughgarden-Tardos 2002 | Razón peor Nash / óptimo; $4/3$ en redes con latencias afines. |
| **Juegos cuánticos (EWL)** | Eisert, Wilkens y Lewenstein, 1999 | El entrelazamiento permite cooperar de forma estable en el Dilema del Prisionero. |
| **Clubes climáticos** | Nordhaus | Arancel uniforme a no miembros para sostener la cooperación. |