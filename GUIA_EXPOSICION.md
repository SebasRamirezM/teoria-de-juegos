# Guía de exposición

Qué decir en cada sección de la página, cómo usar cada interacción y cómo pasar a la siguiente. Los textos entre comillas son un guion sugerido: úsenlo como base y díganlo con sus palabras.

## Plan general

**Duración sugerida:** 30 a 35 minutos más preguntas.

**Idea que la clase debe llevarse:** la teoría de juegos estudia decisiones que dependen unas de otras. Su concepto central es el equilibrio de Nash, y sus ideas hoy se aplican en biología, medicina, mercados, internet, computación y física.

**Reparto sugerido para 4 integrantes** (ajústenlo al tamaño del equipo):

| Bloque | Secciones | Tiempo |
| :--- | :--- | :--- |
| 1. Bases | Portada, Qué es, Cap. 1, Cap. 2 | 8 min |
| 2. Estrategia y comportamiento | Cap. 3 (con el juego), Cap. 4 | 10 min |
| 3. Evolución y diseño | Cap. 5, Cap. 6, Cap. 7 | 9 min |
| 4. Fronteras y cierre | Cap. 8, Cap. 9, Cap. 10, Resumen | 8 min |

**Consejos generales**
- Cada interacción tiene una pregunta para la clase. Pregunten *antes* de pulsar el botón: la predicción del público es lo que hace interesante el resultado.
- No lean las tarjetas. La página resume; ustedes explican.
- Cuando aparezca el color **dorado**, digan "equilibrio". La clase aprende rápido ese código.
- Colores: **coral** es el jugador A (o "tú") y **verde azulado** el jugador B (o el rival).

---

## Portada: el Dilema del Prisionero

**Objetivo:** enganchar con un ejemplo y presentar el equilibrio de Nash antes de definirlo.

**Qué decir**
> "Dos sospechosos son interrogados por separado. Cada uno puede cooperar con el otro, es decir callar, o desertar, es decir delatarlo. En cada casilla, el número de abajo es lo que gana A y el de arriba lo que gana B."

**Interacción**
1. Pregunten: *"¿Qué harían ustedes?"*
2. Pulsen **Buscar el equilibrio**. La animación hace tres pasos:
   - A marca su mejor respuesta en cada columna: siempre desertar (5 > 3 y 1 > 0).
   - B hace lo mismo en cada fila.
   - La casilla donde coinciden se vuelve dorada: (D, D) es el **equilibrio de Nash**.
3. Señalen la casilla punteada (C, C): "Los dos estarían mejor ahí, con 3 cada uno, pero no es estable porque a cada uno le conviene traicionar".
4. Opcional: toquen cualquier casilla para leer su explicación.

**Transición:** "Este juego tan pequeño ya tiene todas las piezas de la teoría. Veámoslas."

---

## Qué es: las cuatro piezas

**Objetivo:** dar la definición formal.

**Qué decir**
> "La teoría de juegos es el estudio matemático de las interacciones estratégicas entre agentes racionales. Las decisiones son interdependientes: lo que obtengo depende de lo que yo elijo y de lo que eligen los demás."

Recorran las cuatro tarjetas usando el dilema como ejemplo:
- **Jugadores:** los dos sospechosos.
- **Estrategias:** cooperar o desertar.
- **Pagos:** los números de la matriz, que representan funciones de utilidad.
- **Interdependencia:** lo que me conviene depende de lo que haga el otro.

Cierren con los chips de abajo: es un lenguaje común a la economía, las ciencias sociales, la biología evolutiva, la informática y la física cuántica. Todas aparecen más adelante.

---

## Capítulo 1: Fundamentos históricos

**Objetivo:** presentar a los tres fundadores.

**Qué decir**
- **von Neumann y Morgenstern (1944):** con su libro *Theory of Games and Economic Behavior* formalizaron el conflicto y la cooperación. Se centraron en juegos de **suma cero**, donde lo que uno gana el otro lo pierde, como el ajedrez.
- **Nash (años 50):** extendió el análisis a juegos de **suma no cero**, como el dilema, donde los dos pueden ganar o perder a la vez. Demostró que todo juego finito tiene al menos un equilibrio en estrategias mixtas: un punto donde nadie gana cambiando solo su estrategia.
- **Shapley (1953):** para juegos cooperativos, propuso repartir la ganancia de un equipo según la contribución marginal de cada miembro, promediada sobre todas las coaliciones posibles. Se apoya en cuatro axiomas: eficiencia, simetría, jugador nulo y aditividad.

**Interacción:** la **línea de tiempo**. No recorran todos los puntos: muestren 1944 y luego salten a un año llamativo (2012, Nobel de Roth y Shapley; o 2018, financiamiento cuadrático) para mostrar que el tema sigue vivo.

> "Esta línea de tiempo es también el mapa de la exposición: cada punto lleva a su capítulo."

---

## Capítulo 2: Fundamentos epistémicos y conocimiento común

**Objetivo:** explicar que los jugadores no solo deciden, también *creen* cosas sobre los demás.

**Qué decir** (apoyándose en los anillos)
> "En el centro está el conocimiento común: no basta con que yo sepa algo, necesito saber que tú lo sabes, que tú sabes que yo lo sé, y así sin fin."

- **Harsanyi (1967), tipos:** cuando no sé qué prefiere el otro, le asigno probabilidades a sus posibles "tipos". Así un juego de información *incompleta* pasa a ser uno de información *imperfecta pero completa*, que sí sabemos analizar.
- **Mertens y Zamir (1985):** construyeron un espacio que contiene todas esas cadenas infinitas de creencias. Con él se puede modelar cualquier juego bayesiano.
- **Aumann (1976), Teorema del Acuerdo:** si dos personas racionales parten de la misma creencia inicial (el *prior* común) y sus conclusiones son conocimiento común, sus conclusiones tienen que ser iguales. No pueden "acordar estar en desacuerdo".

**Pregunta para la clase:** *"Si en la vida real la gente sí está en desacuerdo, ¿qué supuesto se rompe?"* (Respuesta: el prior común o el conocimiento común. Por eso existen variantes que relajan esos supuestos.)

---

## Capítulo 3: Juegos repetidos, negociación y secuencialidad

Es el capítulo con **el juego principal**. Denle tiempo.

### El dilema repetido

**Qué decir**
> "En la portada vimos que en una sola ronda lo racional es traicionar. ¿Qué pasa si jugamos diez rondas contra la misma persona?"

**Interacción**
1. Dejen el rival en **Rival sorpresa** (su estrategia está oculta).
2. Pidan a la clase que vote cada jugada a mano alzada: Cooperar o Desertar. Pulsen el botón ganador.
3. Tras algunas rondas pregunten: *"¿Qué estrategia creen que tiene el rival?"*
4. Al final la página revela la estrategia. Comparen el puntaje con los 30 puntos que da cooperar siempre.

**Teorema Popular (tarjeta de la derecha)**
> "Fudenberg y Maskin (1986) demostraron que si el juego se repite indefinidamente y los jugadores son pacientes, con un factor de descuento δ cercano a 1, casi cualquier resultado razonable, incluida la cooperación, puede ser un equilibrio. La razón es que la amenaza creíble de castigo pesa más que la ganancia de traicionar una vez."

Mencionen que Fudenberg, Levine y Maskin lo extendieron a casos donde las acciones no se observan directamente: se castiga según la estadística de los resultados.

**Torneo de Axelrod:** pulsen **Ver el torneo de Axelrod**. Tit-for-Tat queda primero.
> "Siempre deserta nunca pierde un duelo, pero en el torneo acumula poco. Ganan las estrategias amables que castigan la traición y perdonan."

### Negociación de Rubinstein (1982)

**Qué decir**
> "Dos personas se reparten algo alternando ofertas. Esperar cuesta, porque el valor se descuenta. Rubinstein demostró que existe un único equilibrio y que el acuerdo llega de inmediato, sin demoras."

**Interacción:** bajen la paciencia de A (δ<sub>A</sub>) y muestren que su parte se reduce.
> "Quien tolera menos la espera obtiene menos. Por eso en una negociación conviene no mostrar prisa."

### Paradoja de la cadena de tiendas (Selten)

**Interacción**
1. Pulsen **Inducción hacia atrás**: las tiendas se marcan de la 20 a la 1 y todas entran.
   > "En la última etapa al monopolista ya no le sirve pelear, así que acomoda. Sabiendo eso, tampoco pelea en la penúltima, y el razonamiento se desmorona hasta la primera."
2. Pulsen **Reputación**: el monopolista pelea con las tres primeras y el resto no entra.
   > "La intuición dice que pelear al principio crea reputación. Selten lo explica con tres niveles de decisión humana: rutina, imaginación y razonamiento lógico. En la práctica, la amenaza no creíble funciona."

**Transición:** "Esto ya muestra que las personas reales no siempre siguen la lógica perfecta. De eso trata la teoría conductual."

---

## Capítulo 4: Teoría de juegos conductual

**Qué decir**
> "La teoría conductual reemplaza al Homo economicus, el ser perfectamente racional, por modelos basados en cómo decide la gente de verdad. Herbert Simon lo llamó racionalidad acotada: buscamos una opción suficientemente buena, no la óptima."

- **Level-k:** la gente razona solo uno a tres pasos por delante de un jugador ingenuo.
- **QRE:** la gente comete errores, pero los errores caros son menos frecuentes que los baratos.

### Concurso de belleza (Nagel, 1995)

Es la segunda actividad para toda la clase.

**Interacción**
1. Antes de mostrar nada, pidan a todos que escriban en un papel un número de 0 a 100. Gana quien más se acerque a los **2/3 del promedio**.
2. Pidan a un voluntario su número y escríbanlo en **Tu número**. La página indica qué nivel de razonamiento usó.
3. Expliquen la escalera: el nivel 0 elige al azar (promedio 50); el nivel 1 responde con 2/3 de 50 ≈ 33; el nivel 2 con ≈ 22, y así hasta llegar a 0, el único equilibrio de Nash.
4. Pulsen **Simular 30 compañeros** y vean quién gana.

> "El equilibrio es 0, pero quien elige 0 casi nunca gana, porque los demás no razonan tan lejos. Ser perfectamente racional no sirve si los otros no lo son."

### Juego del Ultimátum (Henrich et al., 2001)

**Qué decir**
> "Uno propone cómo repartir una suma y el otro acepta o rechaza; si rechaza, nadie recibe nada. La teoría dice que el que responde debería aceptar cualquier cosa. En 15 sociedades de pequeña escala los resultados cambiaron según la cultura."

- **Machiguenga (Perú):** poco integrados al mercado. Ofrecían poco y casi nadie rechazaba: muy cerca del equilibrio de Nash.
- **Lamalera (Indonesia):** cazadores de ballenas que dependen de cooperar. Ofrecían más de la mitad y a veces se rechazaba para no quedar en deuda social.

**Conclusión:** la noción de justicia no es fija; coevoluciona con la cultura y el entorno.

---

## Capítulo 5: Teoría de juegos evolutiva

**Qué decir**
> "Maynard Smith y Price (1973) llevaron la teoría de juegos a la biología. Aquí nadie razona: los organismos tienen estrategias programadas y la selección natural decide cuáles sobreviven. El pago es la aptitud reproductiva."

### Halcón y Paloma

**Interacción**
1. Expliquen: los halcones siempre pelean, las palomas amenazan y ceden. V es el valor del recurso y C el costo de pelear.
2. Con los valores iniciales (V = 4, C = 10), la población termina con 40 % de halcones, justo en la línea dorada V/C.
3. Suban V por encima de C: la población termina toda de halcones.
4. Cambien "Halcones al inicio": el final es el mismo. Eso es lo que hace estable a la estrategia.

**Conceptos de las tarjetas**
- **Estrategia Evolutivamente Estable (ESS):** si toda la población la usa, ningún mutante puede invadirla. Lean las dos condiciones: el mutante gana menos contra la población, o gana igual pero pierde contra sí mismo.
- **Ecuación del replicador:** una estrategia crece si su aptitud está por encima del promedio. Es lo que dibuja la gráfica.
- Aplicaciones: conflictos territoriales ritualizados, invasiones biológicas y el altruismo recíproco de Tit-for-Tat que vimos en el torneo.

### Terapia adaptativa contra el cáncer

**Qué decir**
> "Un tumor es un ecosistema donde compiten células sensibles al fármaco y células resistentes. Se modela como un juego de Stackelberg: el oncólogo es el líder que fija la dosis y el tumor es el seguidor que se adapta."

**Interacción**
1. **Dosis máxima (MTD):** la línea verde (sensibles) cae, pero la coral (resistentes) crece hasta dominar.
   > "Al eliminar a las sensibles, liberamos a las resistentes de su competencia. Es la liberación competitiva, y causa la recaída."
2. **Terapia adaptativa:** la barra dorada muestra que el fármaco se apaga y se enciende. Las sensibles sobreviven y mantienen a raya a las resistentes.
   > "El objetivo cambia de erradicar a contener."

Aclaren que la gráfica es un modelo ilustrativo y citen la evidencia real: ensayos de fase 2 en cáncer de próstata metastásico con abiraterona, dosificada según el PSA, prolongaron el tiempo hasta la progresión con menos toxicidad y costo.

---

## Capítulo 6: Diseño de mecanismos y emparejamiento

**Qué decir** (señalando el diagrama de flechas)
> "Hasta ahora teníamos reglas y predecíamos el resultado. El diseño de mecanismos hace ingeniería inversa: decide qué resultado quiere y diseña las reglas para lograrlo, aunque los participantes sean egoístas y oculten información."

### Aceptación diferida (Gale y Shapley, 1962)

**Interacción:** pulsen **Siguiente propuesta** seis veces y lean cada paso.
- Los estudiantes se postulan en orden de preferencia (las letras junto a cada nodo).
- Cada hospital retiene al mejor candidato que ha recibido y rechaza a los demás. Las líneas doradas son las retenciones; las punteadas, los rechazos.
- Al final el emparejamiento es **estable**: no hay un estudiante y un hospital que prefieran estar juntos antes que con lo que obtuvieron.

**Aplicaciones reales**
- **Médicos residentes en EE. UU. (Roth):** las contrataciones se adelantaban cada vez más (*unraveling*) y el mercado era inestable, en parte por parejas que querían la misma ciudad. Roth rediseñó el algoritmo con propuestas del lado estudiantil.
- **Intercambio de riñones:** si mi donante no es compatible conmigo pero sí con otro paciente, se forman ciclos de intercambio (el diagrama). Con donantes altruistas se crean cadenas. Roth y Shapley recibieron el **Nobel de Economía 2012**.

---

## Capítulo 7: Subastas digitales, VCG y GSP

**Qué decir**
> "Cada vez que buscan algo en Google hay una subasta por los anuncios. La regla de pago cambia cómo conviene pujar."

**Interacción**
1. Lean el escenario: cada clic vale $10 para ti, B puja $6 y C $4; el primer espacio recibe 100 clics y el segundo 80.
2. Con la puja en $10, ambas subastas dicen que quedas primero.
3. Pregunten: *"¿Conviene pujar menos que lo que vale?"* Muevan la puja a **$5**:
   - En **GSP** la ganancia sube de $400 a $480: eso es *bid shading*.
   - En **VCG** la ganancia baja de $560 a $480: allí mentir no conviene.
4. Señalen las gráficas: en VCG el punto más alto está en el valor real; en GSP está más abajo.

**Tabla:** VCG cobra a cada uno el daño que causa a los demás (la externalidad), y por eso pujar la verdad es estrategia dominante. GSP cobra la puja del siguiente, y por eso conviene pujar menos. Edelman, Ostrovsky y Schwarz (2007) mostraron que un equilibrio particular de GSP (el LEFE de menor ingreso) reproduce los resultados de VCG.

---

## Capítulo 8: Financiamiento cuadrático y blockchain

**Qué decir**
> "¿Cómo financiar bienes públicos como software libre o investigación? Si cuenta el dinero, deciden los ricos y aparece el polizón. Si cuenta una persona un voto, se ignora a las minorías que más se interesan. Buterin, Hitzig y Weyl (2018) propusieron una mezcla."

**Interacción** (los tres botones en orden)
1. **Un multimillonario:** aporta $10.000 y recibe $10.000. No hay subsidio.
2. **10.000 personas** de $1 cada una: el mismo total, pero los fondos teóricos suben a $100 millones.
   > "El subsidio crece con cuántas personas apoyan, no con cuánto dinero ponen."
3. **Ataque Sybil:** el mismo multimillonario se divide en 100 cuentas falsas y multiplica sus fondos por 100.
   > "Y aquí está la debilidad."

Mencionen las tres vulnerabilidades: **Sybil**, **colusión** entre cuentas y **MEV** (reordenar transacciones para extraer valor, lo que llevó a soluciones como Flashbots).

---

## Capítulo 9: Complejidad computacional y aprendizaje algorítmico

### Paradoja de Braess

**Interacción**
1. **Sin atajo:** 4.000 autos se reparten 2.000 y 2.000; cada uno tarda 20 + 45 = 65 minutos.
2. Pregunten: *"Si abrimos una vía gratis de A a B, ¿el tráfico mejora o empeora?"*
3. **Con atajo:** todos toman Inicio → A → B → Fin y tardan 40 + 0 + 40 = 80 minutos. Nadie gana cambiando de ruta (las otras tardan 85), pero todos están peor.

**Precio de la Anarquía**
> "Mide cuánto se pierde porque cada uno decide por su cuenta: el costo del peor equilibrio dividido entre el costo óptimo. Aquí es 80/65 ≈ 1,23. Roughgarden y Tardos demostraron que en redes así nunca pasa de 4/3, es decir, como mucho un 33 % más."

**Tarjetas**
- **PPAD:** calcular un equilibrio de Nash es computacionalmente intratable. Si una supercomputadora no puede hallarlo, es difícil creer que las personas lleguen a él solas.
- **CFR:** algoritmos que aprenden jugando contra sí mismos y acumulando el "arrepentimiento" de no haber jugado cada acción. Así Libratus y Pluribus vencieron a profesionales de póker.
- **GANs y colusión algorítmica:** las GAN son un juego de suma cero entre dos redes. Y algoritmos de precios aprenden a cobrar caro sin ponerse de acuerdo, castigando a quien baja precios como Tit-for-Tat, un reto para las leyes de competencia.

---

## Capítulo 10: Juegos cuánticos y cooperación climática

**Interacción**
1. **Clásico:** el dilema de la portada con su equilibrio (D, D) = (1, 1).
2. **Cuántico:** aparece la estrategia **Q** y el equilibrio pasa a (Q, Q) = (3, 3).

**Qué decir**
> "En el protocolo EWL (1999), cada jugador manipula un qubit. Un árbitro entrelaza los qubits antes de que jueguen y deshace el entrelazamiento antes de medir. Con entrelazamiento máximo aparece una estrategia Q contra la que desertar no paga. El entrelazamiento hace el trabajo de un contrato sin que nadie se comunique."

**Clubes climáticos (Nordhaus)**
> "El acuerdo de París tiene el mismo problema del dilema: cada país prefiere que los otros reduzcan emisiones. Nordhaus propuso un club cuyos miembros cobran un arancel uniforme a los que no participan. Es un castigo coordinado solo para los desertores, y una sanción pequeña basta para sostener una cooperación amplia."

**Transición al cierre:** "Empezamos con dos prisioneros y terminamos con qubits y países. El problema de fondo es el mismo: cómo cooperar cuando a cada uno le conviene no hacerlo."

---

## Resumen: conceptos clave

**Objetivo:** repaso rápido y espacio para preguntas.

**Interacción:** pidan a compañeros que elijan una tarjeta y la volteen. Antes de voltearla, pregunten a la clase si recuerda la idea.

**Mensaje final sugerido**
> "La teoría de juegos nos da un lenguaje para pensar cualquier situación donde nuestras decisiones dependen de las de otros: desde un tumor hasta una subasta de Google. Su lección central es que lo que conviene a cada uno no siempre conviene a todos, y que buenas reglas pueden acercar ambas cosas."

---

## Preguntas probables y respuestas cortas

| Pregunta | Respuesta |
| :--- | :--- |
| ¿El equilibrio de Nash es siempre lo mejor? | No. Es estable, no óptimo: en el dilema, (D, D) es Nash y (C, C) es mejor para ambos. |
| ¿Qué es una estrategia mixta? | Elegir entre acciones al azar con ciertas probabilidades, como en piedra, papel o tijera. |
| ¿Por qué cooperar en el dilema repetido? | Porque el futuro importa: traicionar hoy provoca castigo mañana (Teorema Popular). |
| ¿Qué diferencia hay entre la ESS y Nash? | Toda ESS es un equilibrio de Nash, pero además resiste la invasión de mutantes y no requiere razonar. |
| ¿Por qué Google no usa VCG si es veraz? | GSP es más simple de explicar y, en cierto equilibrio, da los mismos resultados; aunque la evidencia reciente sugiere que VCG puede rendir más con agencias. |
| ¿Qué relación tiene con Investigación de Operaciones? | Los juegos de suma cero se resuelven con programación lineal (minimax), y el diseño de mecanismos y los emparejamientos son problemas de optimización y asignación. |
