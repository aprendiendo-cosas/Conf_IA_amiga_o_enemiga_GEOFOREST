# IAs generativas y aprendizaje universitario: versión científica de la conferencia

> + **_Versión_**: 8 de octubre de 2026
> + **_Nombre del evento_**: Inauguración del curso 26-27 del máster GEOFOREST (UCO)
> + **_Autor_**: Curro Bonet-García (fjbonet@uco.es)
> + **Duración**: 35'

![portada](https://github.com/aprendiendo-cosas/Conf_ingenieria_regenerativa_UPM/raw/2025-2026/imagenes/portada.png)







[TOC]

## 1. Introducción: ¿Qué contiene este documento y cómo se ha generado?

El texto que se muestra a continuación procede de una charla que impartí el día 8 de octubre de 2026 en la jornada inaugural de la décima promoción del máster GEOFOREST (Máster universitario en Geomática, Teledetección y modelos espaciales aplicados a la gestión forestal) de la Universidad de Córdoba. La charla se tituló "Las IAs generativas para los estudiantes, ¿aliadas o enemigas del aprendizaje?". Duró unos 30 minutos (me alargué más de lo que me pidieron. Lo siento)

En esta sección introductoria describo cómo se ha generado tanto el contenido de la charla como el texto que se muestra a continuación. Creo que en una época en la que los textos y las ideas pueden ser generadas por una IA, es importante ser transparente. 

Para generar lo que puedes leer a continuación se han dado los siguientes pasos:

1. En primer lugar elaboré un hilo argumental inicial basándome en mi experiencia, en lo que había leído sobre el tema y en [estas](https://aprendiendo-cosas.github.io/competencias_transversales/normas_IA/normas_IA.html) buenas prácticas escribí hace unos meses. Si tienes curiosidad, [aquí](https://raw.githubusercontent.com/aprendiendo-cosas/Conf_IA_amiga_o_enemiga_GEOFOREST/refs/heads/main/1_hilo_argumental_inicial.md) tienes un documento con el hilo argumental inicial. 
2. Después pasé el documento anterior a dos IAs para que identificaran incoherencias y para que aportaran bibliografía sobre las afirmaciones realizadas en el texto. El *prompt* que usé es este: 

> Tengo que preparar una conferencia sobre el modo en el que las IAs pueden usarse para promover el aprendizaje profundo en estudiantes universitarios.
>
> La charla se llama "Las IAs generativas para los estudiantes, ¿aliadas o enemigas?
>
> El archivo markdown adjunto contiene una propuesta de estructura de dichoa charla.
>
> Quiero que la trabajemos juntos. En primer lugar quiero que evalues la coherencia de los mensajes que se plantean en el texto. DEvuélveme el mismo texto que te envío pero añade comentarios entre corchetes cuando identifiques evidencias sólidas que contradigan o maticen lo que yo he escrito. Añade también referencias bibliográficas entre paréntesis para las afirmaciones para las que encuentres evidencias científicas publicadas.

​	En [este](https://raw.githubusercontent.com/aprendiendo-cosas/Conf_IA_amiga_o_enemiga_GEOFOREST/refs/heads/main/2_hilo_argumental_comentado_por_IAs.md) documento se muestra la respuesta que me dieron Claude y Gemini al prompt anterior. 

3. El siguiente paso implicó conciliar en otro documento los comentarios que aportaron las IAs con mi visión del asunto. No hubo cambio significativos en la estructura. [Aquí](https://raw.githubusercontent.com/aprendiendo-cosas/Conf_IA_amiga_o_enemiga_GEOFOREST/refs/heads/main/3_hilo_argumental_conciliado_IAs_fjbonet.md)) se puede ver el hilo argumental "final".
4. Luego me puse a preparar la presentación. Ya tenía en mente una idea sobre cómo organizar la presentación. En esta fase use Nano Banana de Gemini para crear algunas figuras a modo de cliparts. La idea de los esquemas que aparecen en la presentación es toda mía. 0% de IA aquí. En el proceso de transformación del texto anterior a una presentación hubo cambios importantes. [Aquí](https://github.com/aprendiendo-cosas/Conf_IA_amiga_o_enemiga_GEOFOREST/raw/refs/heads/main/presentacion_IAs_geoforest.pptx) está disponible la presentación en formato Powerpoint. 
5. El día de la charla puse el móvil a grabar y se generó un audio. Use Gemini para transcribirlo literalmente. Me da un poco de pudor compartir tanto el audio como la transcripción, así que no lo haré.
6. Después pasé el audio transcrito a Claude y le pedí lo siguiente:

> Ya he impartido la charla. Te adjunto un documentto de markdown que recoge la transcripción literal del audio de dicha charla. También te adjunto la presentación de diapositivas que usé para guiar la charla.
>
> Quiero que, usando el contenido de la presentación y los comentarios que hay en el texto, lo rehagas y generes otro con las siguientes características:
>
> - Debe de estar escrito con un lenguaje científico.
> - Elimina las bromas y comentarios personales hechos por el profesor para capturar la atención de la audiencia.
> - Añade comentarios en negrita después de las afirmaciones que no tengan respaldo científico o que sean directamente incorrectas.
> - Mantén el hilo argumental de la exposición hecha por el profesor.

​	El resultado de este *prompt* es lo que puedes leer a continuación. La IA ha añadido comentarios que se 	muestran en negrita. Yo también he añadido algún comentario que se muestra en cursiva. 



## 1. Planteamiento del problema

La pregunta que da título a la exposición no admite, por el momento, una respuesta concluyente. La inteligencia artificial (IA) generativa es una tecnología reciente y disruptiva, cuyos efectos sobre el aprendizaje apenas han comenzado a estudiarse de forma sistemática. Las valoraciones sociales oscilan entre la expectativa de un deterioro profundo de las capacidades humanas y la de una liberación generalizada de trabajo. **[Comentario: la falta de respuesta concluyente es coherente con el estado de la evidencia. Los metaanálisis disponibles muestran efectos positivos sobre el rendimiento académico, pero se basan mayoritariamente en estudios de corta duración, con alta heterogeneidad y calidad metodológica desigual, y rara vez miden la retención o la transferencia sin la IA disponible (**[**Wang & Fan, 2025**](https://scholar.google.com/scholar?q="The+effect+of+ChatGPT+on+students'+learning+performance%2C+learning+perception%2C+and+higher-order+thinking")**).]**

El objetivo de esta charla no es ofrecer una respuesta definitiva, sino proponer un marco de reflexión. Ese marco se construye a partir de la experiencia docente del autor durante los primeros años de uso de estas herramientas (aproximadamente desde la publicación de ChatGPT, en noviembre de 2022) y de la literatura sobre cómo aprenden los seres humanos. La exposición concluye con una propuesta provisional de criterios de uso.



## 2. Contexto: actitudes individuales, respuesta institucional y efectos de la prohibición



### 2.1. Actitudes individuales

Las actitudes individuales ante la IA generativa pueden agruparse en tres perfiles: los adoptantes tempranos, que la usan de forma intensiva; quienes la rechazan por motivos éticos o ambientales; y un grupo intermedio que la incorpora con cautela. En la consulta informal realizada al público, predominaron los adoptantes y los cautelosos, y ningún asistente se identificó con el rechazo. El autor declara una posición mixta: uso intensivo acompañado de reservas éticas. Estas actitudes dependen de la experiencia y la disposición de cada persona, y pueden coexistir de forma contradictoria en un mismo individuo.

Otras tecnologías hoy plenamente asumidas en las ciencias ambientales y forestales, como los sistemas de información geográfica (SIG) o la teledetección, probablemente suscitaron en su origen una diversidad de actitudes comparable. Hoy forman parte de la práctica cotidiana y su efecto sobre las capacidades cognitivas no se cuestiona. **[Comentario: la analogía es plausible, pero el paralelismo no es completo. Los SIG generaron en los años noventa un debate académico sostenido sobre sus implicaciones epistemológicas y sociales (**[**Pickles, 1995**](https://scholar.google.com/scholar?q="Ground+truth%3A+The+social+implications+of+geographic+information+systems")**), aunque no centrado en la pérdida de capacidades cognitivas. Un precedente más próximo es el de la calculadora, cuyo uso no deterioró las destrezas básicas según los metaanálisis (**[**Ellington, 2003**](https://scholar.google.com/scholar?q="A+meta-analysis+of+the+effects+of+calculators+on+students'+achievement+and+attitude+levels")**). A diferencia de ambas, la IA generativa puede ejecutar directamente tareas de comprensión, síntesis y redacción.]**



### 2.2. Respuesta institucional

Las universidades, como instituciones, no han ofrecido hasta ahora una respuesta operativa al uso de la IA en la docencia. Existen marcos normativos y orientaciones de rango supranacional, como el Reglamento europeo de IA y la guía de la UNESCO, pero no están concebidos para la escala del aula ni de la asignatura. **[Comentario: conviene precisar la naturaleza de estos instrumentos. El documento de la UNESCO es una guía de recomendaciones, no un reglamento (**[**UNESCO, 2023**](https://scholar.google.com/scholar?q="Guidance+for+generative+AI+in+education+and+research")**). El Reglamento europeo regula sobre todo la seguridad y los riesgos de los sistemas de IA; no tiene por objeto proteger la capacidad cognitiva de los usuarios, aunque su artículo 4 exige garantizar la alfabetización en IA del personal de las organizaciones que la utilizan (**[**Reglamento (UE) 2024/1689**](http://data.europa.eu/eli/reg/2024/1689/oj)**).]**

### 2.3. Consecuencia de primer orden: la prohibición

La combinación de una tecnología que no ha sido demandada por la comunidad educativa, unas actitudes individuales heterogéneas y un marco normativo genérico conduce a que una parte relevante del profesorado opte por prohibir o restringir el uso de la IA. Esta respuesta es comprensible, dado que el profesorado carece en general de formación y de respaldo institucional para gestionar su uso. **[Comentario: no se aporta evidencia sobre la proporción de profesorado que adopta políticas prohibitivas; la afirmación debería presentarse como una observación del autor.]**

La prohibición contrasta con la amplitud del uso. En la exposición se afirmó que en torno al 90 % de la población de un país como España usa la IA a diario. **[Comentario: la cifra es incorrecta para la población general. Las encuestas sitúan el uso diario en la población general muy por debajo de ese valor. La cifra de en torno al 90 % corresponde al uso (no necesariamente diario) por parte de estudiantes universitarios: un 92 % en el Reino Unido en 2025 (**[**Freeman, 2025**](https://www.google.com/search?q=HEPI+"Student+Generative+AI+Survey+2025")**). Para el argumento de la charla, este último dato es además el más pertinente.]**

### 2.4. Consecuencia de segundo orden: el uso encubierto

Desde una perspectiva sistémica, las intervenciones sobre sistemas complejos suelen producir consecuencias no previstas. En este caso, la prohibición tendería a desplazar el uso de la IA hacia prácticas encubiertas, dada la disponibilidad de una herramienta de gran potencia. El estudiante percibe un problema que la institución no aborda, y el profesor carece de medios para identificar los trabajos elaborados con IA. **[Comentario: la hipótesis del desplazamiento hacia el uso encubierto es plausible, pero no se aporta evidencia empírica que la sustente. En cambio, la dificultad para identificar los textos generados por IA sí está bien documentada: ni el profesorado novel ni el experimentado los distingue de forma fiable (**[**Fleckenstein et al., 2024**](https://doi.org/10.1016/j.caeai.2024.100209)**), y los detectores automáticos tampoco son fiables (**[**Weber-Wulff et al., 2023**](https://doi.org/10.1007/s40979-023-00146-z)**).]**

### 2.5. Una alternativa: aprender a usar la IA en el aula

Como alternativa a la prohibición, el autor optó desde el inicio por explorar con sus estudiantes el uso de la IA como herramienta de aprendizaje. Los primeros intentos tuvieron efectos negativos no previstos; los ajustes posteriores han permitido delimitar un espacio de uso más seguro. Una limitación de este enfoque es que cada cohorte experimenta solo los errores de su curso, y no las correcciones introducidas después.

El análisis de esos errores se presenta a continuación. Se parte de la premisa de que el aprendizaje depende menos de cometer errores que de cómo se afrontan una vez cometidos. **[Comentario: respaldado, con matices. Los errores seguidos de retroalimentación correctiva favorecen el aprendizaje (**[**Metcalfe, 2017**](https://doi.org/10.1146/annurev-psych-010416-044022)**), y el entrenamiento que incorpora explícitamente la gestión de errores mejora la transferencia (**[**Keith & Frese, 2008**](https://doi.org/10.1037/0021-9010.93.1.59)**). La evidencia se refiere sobre todo al aprendizaje individual; trasladarla a la mejora de una práctica docente es una extrapolación razonable, pero no directa.]**



## 3. Experiencia docente: tres supuestos erróneos

### 3.1. Primer supuesto: lo que es útil para el profesor lo es también para el estudiante

Para el autor, la IA generativa ha transformado la forma de trabajar y, sobre todo, de aprender. Le permite iniciar con facilidad scripts de programación, preparar asignaturas nuevas y acceder con rapidez a información sobre campos que antes le resultaban poco accesibles. El autor considera este cambio de mayor alcance que la llegada de las enciclopedias digitales a finales de los años noventa.

Sobre esa base, permitió a sus estudiantes usar la IA libremente en un examen. Esperaba reflexión, cuestionamiento y elaboración de ideas nuevas. Lo observado fue distinto: los estudiantes trasladaban literalmente las preguntas a la IA, no repreguntaban, no cuestionaban la respuesta y la copiaban en el examen. El resultado fue un aprendizaje escaso. **[Comentario: la observación es coherente con estudios controlados. En un experimento con universitarios, el grupo que usó ChatGPT obtuvo mejores puntuaciones en la tarea de escritura, pero no mayor adquisición ni transferencia de conocimiento, y redujo los procesos de autorregulación; los autores lo denominan «pereza metacognitiva» (**[**Fan et al., 2025**](https://doi.org/10.1111/bjet.13544)**).]**

La explicación propuesta se basa en la diferencia entre las estructuras de conocimiento de un experto y las de un aprendiz. El experto dispone de marcos conceptuales consolidados y de una experiencia acumulada de contradicciones y revisiones, lo que le permitiría usar la IA para potenciar su aprendizaje en un ciclo de retroalimentación positiva. En el aprendiz, que aún no dispone de esos marcos, se produciría un ciclo de retroalimentación negativa: el uso de la IA al modo del experto reduciría determinadas capacidades cognitivas. En la exposición se afirmó que este efecto se ha comprobado «en multitud de ocasiones». **[Comentario: la hipótesis es plausible, pero la afirmación sobre su comprobación es excesiva. La evidencia sobre productividad apunta en sentido contrario: en atención al cliente, consultoría y escritura profesional, quienes más mejoran su rendimiento con IA son los trabajadores novatos o menos cualificados (**[**Brynjolfsson et al., 2025**](https://doi.org/10.1093/qje/qjae044)**;** [**Dell'Acqua et al., 2023**](https://doi.org/10.2139/ssrn.4573321)**;** [**Noy & Zhang, 2023**](https://doi.org/10.1126/science.adh2586)**). La forma de conciliar ambos resultados es la distinción entre rendimiento y aprendizaje (sección 3.2). En programación, la variable decisiva parece ser la competencia metacognitiva más que la experiencia: la IA favorece a los estudiantes con buenas destrezas metacognitivas y perjudica a los que tienen dificultades, que desarrollan una ilusión de competencia (**[**Prather et al., 2024**](https://scholar.google.com/scholar?q="The+widening+gap%3A+The+benefits+and+harms+of+generative+AI+for+novice+programmers")**). El efecto de reversión de la pericia ofrece un marco teórico afín: los apoyos útiles para el novato pueden ser inútiles o perjudiciales para el experto, y viceversa (**[**Kalyuga et al., 2003**](https://doi.org/10.1207/S15326985EP3801_4)**).]**

**[Comentario: las dos referencias de la diapositiva no respaldan directamente la comparación entre experto y aprendiz. Lee et al. (2025) es una encuesta a trabajadores del conocimiento que asocia la confianza en la IA con menor pensamiento crítico y la confianza en uno mismo con más; es correlacional y no compara expertos con aprendices (**[**Lee et al., 2025**](https://scholar.google.com/scholar?q="The+impact+of+generative+AI+on+critical+thinking%3A+Self-reported+reductions+in+cognitive+effort")**). Kazemitabaar et al. (2023) no encontró un efecto negativo general en principiantes: el acceso a un generador de código mejoró la realización de tareas sin empeorar el rendimiento posterior sin IA (**[**Kazemitabaar et al., 2023**](https://scholar.google.com/scholar?q="Studying+the+effect+of+AI+code+generators+on+supporting+novice+learners+in+introductory+programming")**).]**

El mecanismo invocado es la descarga cognitiva (*cognitive offloading*): al disponer de un sistema externo de gran capacidad, el usuario delega en él procesos cognitivos superiores, como la comprensión profunda, la síntesis o el pensamiento crítico, de forma no deliberada. El uso prolongado de este apoyo atrofiaría esas capacidades, del mismo modo que una muleta usada indefinidamente debilita la musculatura. **[Comentario: el concepto está bien establecido, pero se presenta de forma incompleta. La descarga cognitiva es con frecuencia una decisión estratégica, no necesariamente inconsciente, y puede ser beneficiosa, porque libera recursos para otras tareas; su coste principal documentado es una peor memoria de lo delegado (**[**Risko & Gilbert, 2016**](https://doi.org/10.1016/j.tics.2016.07.002)**). La asociación entre uso frecuente de IA, descarga cognitiva y menor pensamiento crítico se ha observado en estudios correlacionales que no prueban causalidad (**[**Gerlich, 2025**](https://doi.org/10.3390/soc15010006)**). La pérdida de destrezas por delegación sí se ha documentado en profesionales: endoscopistas habituados al apoyo de la IA detectaron menos adenomas al trabajar sin ella (**[**Budzyń et al., 2025**](https://scholar.google.com/scholar?q="Endoscopist+deskilling+risk+after+exposure+to+artificial+intelligence+in+colonoscopy")**).]**

### 3.2. Segundo supuesto: un buen resultado implica aprendizaje

El segundo supuesto erróneo, extendido en el conjunto del sistema educativo, consiste en inferir que un producto de calidad (un informe, un artículo, una gráfica) elaborado con IA refleja un aprendizaje profundo, entendido como aquel que se mantiene en el tiempo más allá de la evaluación. **[Comentario: la definición es parcial. En la literatura, el aprendizaje profundo (\*deep approach\*) se asocia sobre todo a la búsqueda de comprensión y significado, frente a la memorización reproductiva (\*surface approach\*) (**[**Marton & Säljö, 1976**](https://scholar.google.com/scholar?q="On+qualitative+differences+in+learning"+Marton+Säljö)**); la retención a largo plazo es una consecuencia, no su definición.]**

La distinción entre rendimiento (lo observable durante la práctica) y aprendizaje (lo que perdura y se transfiere) es uno de los resultados más sólidos de la psicología cognitiva ([Soderstrom & Bjork, 2015](https://doi.org/10.1177/1745691615569000)). Los estudios experimentales indican que el uso de la IA para generar productos acabados no mejora el aprendizaje o incluso lo reduce. En un experimento de campo con unos 1.000 estudiantes de secundaria, el acceso a GPT-4 sin restricciones mejoró un 48 % el rendimiento en los ejercicios de práctica, pero redujo un 17 % el rendimiento en el examen posterior sin IA respecto al grupo de control ([Bastani et al., 2025](https://doi.org/10.1073/pnas.2422633122)).

Lo que produce aprendizaje es el proceso, no solo la calidad del resultado. Ello no implica restar valor a la calidad del producto, sino advertir que los sistemas educativos tienden a centrarse en él en exceso. Este problema es anterior a la IA, que únicamente lo ha hecho más visible.

Cuando la IA se orienta al proceso, los resultados mejoran. **[Comentario: respaldado, aunque con resultados de distinta magnitud. En el estudio de Bastani et al., una versión de GPT-4 diseñada como tutor, que no ofrecía las respuestas directamente, eliminó el efecto negativo sobre el examen, aunque no lo mejoró significativamente respecto al control (**[**Bastani et al., 2025**](https://doi.org/10.1073/pnas.2422633122)**). En un ensayo controlado con estudiantes universitarios de Física, un tutor de IA diseñado según principios pedagógicos produjo ganancias de aprendizaje superiores al doble que una clase de aprendizaje activo (**[**Kestin et al., 2025**](https://scholar.google.com/scholar?q="AI+tutoring+outperforms+in-class+active+learning")**). En ambos casos se trata de herramientas configuradas específicamente, no de asistentes de uso general.]**

### 3.3. Tercer supuesto: la IA es igualmente útil para cualquier tarea

El tercer supuesto erróneo es considerar la IA como una herramienta polivalente que mejora el aprendizaje en todos los ámbitos. La experiencia del autor y la literatura indican que algunos usos lo favorecen y otros lo dificultan.

Entre los usos que tienden a favorecer el aprendizaje se encuentran los siguientes:

- **Programación.** La IA facilitaría y aceleraría el aprendizaje de cualquier lenguaje de programación. **[Comentario: la generalización es excesiva. El acceso a la IA no perjudicó el aprendizaje de principiantes en un estudio (**[**Kazemitabaar et al., 2023**](https://scholar.google.com/scholar?q="Studying+the+effect+of+AI+code+generators+on+supporting+novice+learners+in+introductory+programming")**), pero sus efectos dependen de las destrezas metacognitivas del estudiante (**[**Prather et al., 2024**](https://scholar.google.com/scholar?q="The+widening+gap%3A+The+benefits+and+harms+of+generative+AI+for+novice+programmers")**). No hay evidencia de una aceleración general para «cualquier lenguaje».]**
- **Búsqueda de información.** La búsqueda semántica aumenta la eficiencia en la localización de literatura científica, siempre que se empleen herramientas adecuadas. En la exposición se recomendaron Perplexity y Elicit y se desaconsejó ChatGPT. **[Comentario: los modelos de lenguaje sin acceso a fuentes inventan referencias con frecuencia: el 55 % de las citas de GPT-3.5 y el 18 % de las de GPT-4 eran inexistentes en un estudio (**[**Walters & Wilder, 2023**](https://doi.org/10.1038/s41598-023-41032-5)**). Sin embargo, no se dispone de evaluaciones independientes que respalden la superioridad de las herramientas recomendadas, y las versiones actuales de ChatGPT también incorporan búsqueda en fuentes. Cualquier herramienta requiere verificación sistemática de las referencias.]**
- **Explicación de conceptos.** El diálogo de tipo socrático con la IA, basado en repreguntar, favorece la comprensión. **[Comentario: respaldado cuando la herramienta está diseñada para no dar respuestas directas (**[**Kestin et al., 2025**](https://scholar.google.com/scholar?q="AI+tutoring+outperforms+in-class+active+learning")**;** [**Bastani et al., 2025**](https://doi.org/10.1073/pnas.2422633122)**).]**

Entre los usos que tienden a dificultar el aprendizaje se encuentran los siguientes:

- **Redacción.** Delegar la escritura en la IA no sería adecuado ni siquiera para personas expertas, porque conduce a la pérdida de esa capacidad. **[Comentario: la afirmación referida a expertos no está respaldada de forma general. En términos de productividad, la IA mejora la rapidez y la calidad de la escritura profesional (**[**Noy & Zhang, 2023**](https://doi.org/10.1126/science.adh2586)**). La evidencia sobre efectos cognitivos de redactar con IA es aún preliminar: un estudio con electroencefalografía encontró menor conectividad cerebral y menor sensación de autoría al escribir con ChatGPT, pero es un preprint sin revisión por pares y con una muestra pequeña (**[**Kosmyna et al., 2025**](https://arxiv.org/abs/2506.08872)**).]**
- **Resumen.** Resumir es una tarea cognitivamente exigente que no debería delegarse. **[Comentario: parcialmente respaldado. Resumir requiere procesamiento activo, pero su eficacia como técnica de estudio es limitada si el estudiante no ha sido entrenado en ella (**[**Dunlosky et al., 2013**](https://doi.org/10.1177/1529100612453266)**). Además, los resúmenes de artículos científicos generados por modelos de lenguaje tienden a generalizar en exceso las conclusiones (**[**Peters & Chin-Yee, 2025**](https://doi.org/10.1098/rsos.241776)**).]**
- **Cuestionamiento.** Contrastar la información recibida con el conocimiento propio y buscar puntos de fricción no debería delegarse en la IA; en la exposición se afirmó que este uso reduce el aprendizaje «independientemente de lo bien que usemos la IA». **[Comentario: la afirmación es demasiado absoluta y contradice la propuesta de la sección 5.1, donde la IA se usa después del esfuerzo como «contraste, espejo, adversario, corrector». Lo que la evidencia desaconseja es delegar el juicio crítico, no usar la IA como interlocutor que lo ejercite; los tutores diseñados para cuestionar al estudiante obtienen buenos resultados (**[**Kestin et al., 2025**](https://scholar.google.com/scholar?q="AI+tutoring+outperforms+in-class+active+learning")**).]**

## 4. Fundamentos cognitivos del aprendizaje profundo

La primera conclusión general es que el efecto de la IA sobre el aprendizaje no depende de su uso o no uso, sino del modo de uso. Más concretamente, depende de que ese uso se alinee con los mecanismos por los que aprende el cerebro humano, que tanto estudiantes como profesores suelen desatender. De esos mecanismos, se destacan tres condiciones.

### 4.1. Fricción

El aprendizaje requiere esfuerzo. Para que los conceptos se consoliden deben ser recuperados, contrastados con otros conceptos, relacionados y discutidos, de forma análoga al entrenamiento físico o a la práctica de un instrumento musical. Cuando la práctica cesa, lo aprendido se deteriora. En la exposición se afirmó que «si no hay esfuerzo, no hay aprendizaje». **[Comentario: la idea central está bien respaldada por la investigación sobre «dificultades deseables»: ciertas dificultades que reducen el rendimiento inmediato mejoran la retención y la transferencia (**[**Bjork & Bjork, 2011**](https://scholar.google.com/scholar?q="Making+things+hard+on+yourself%2C+but+in+a+good+way")**). También por el efecto de generación, según el cual se recuerda mejor lo que uno genera que lo que lee ya elaborado (**[**Slamecka & Graf, 1978**](https://doi.org/10.1037/0278-7393.4.6.592)**), y por el efecto de la práctica de recuperación (**[**Roediger & Karpicke, 2006**](https://doi.org/10.1111/j.1467-9280.2006.01693.x)**). Sin embargo, la formulación absoluta es incorrecta: existe aprendizaje incidental sin esfuerzo deliberado, y las dificultades solo son deseables si el estudiante puede superarlas.]**

### 4.2. Conexión con el conocimiento previo

El conocimiento nuevo no se incorpora en el vacío, sino en relación con lo que ya se sabe. Ello genera una jerarquía en el aprendizaje: la selvicultura requiere conocimientos de ecología; la ecología, de botánica; y la botánica, de edafología. Del mismo modo, la física cuántica sería inaccesible sin la física newtoniana. **[Comentario: el papel del conocimiento previo es un principio clásico (**[**Ausubel, 1968**](https://scholar.google.com/scholar?q="Educational+psychology%3A+A+cognitive+view")**). No obstante, un metaanálisis amplio muestra que el conocimiento previo predice con fuerza el conocimiento final, pero su relación con la ganancia de aprendizaje es más débil e inconsistente de lo que se suele suponer (**[**Simonsmeier et al., 2022**](https://doi.org/10.1080/00461520.2021.1939700)**). La idea de una jerarquía estricta entre disciplinas es una simplificación.]**

### 4.3. Andamiaje

El aprendizaje requiere apoyos externos provisionales, análogos a los andamios de una construcción. En la docencia adoptan la forma de una retroalimentación orientada a la mejora, de la recomendación de una lectura o de la intervención de un compañero que ya domina un concepto. El rasgo esencial del andamio es que debe retirarse: si permanece al final del proceso, sostiene el peso de la estructura y se convierte en una muleta. **[Comentario: respaldado. El concepto procede de** [**Wood et al. (1976)**](https://doi.org/10.1111/j.1469-7610.1976.tb00381.x) **y se vincula con la zona de desarrollo próximo de** [**Vygotsky (1978)**](https://scholar.google.com/scholar?q="Mind+in+society%3A+The+development+of+higher+psychological+processes")**. La retirada progresiva del apoyo (\*fading\*) se considera una característica definitoria del andamiaje (**[**van de Pol et al., 2010**](https://doi.org/10.1007/s10648-010-9127-6)**).]**

### 4.4. Implicación para la IA

La IA generativa puede vulnerar estas tres condiciones. Salvo que se le indique expresamente, no genera fricción, no tiene en cuenta la estructura de conocimientos del usuario y no actúa como un andamio que se retira: proporciona de una vez todo el conocimiento solicitado. Por tanto, un uso favorable al aprendizaje debe adaptarse a estas condiciones. **[Comentario: coherente con la evidencia. El mismo modelo de lenguaje produce efectos opuestos sobre el aprendizaje según se configure para dar respuestas o para guiar al estudiante (**[**Bastani et al., 2025**](https://doi.org/10.1073/pnas.2422633122)**).]**

## 5. Propuesta de criterios de uso: las esclusas

Un uso de la IA compatible con el aprendizaje requiere establecer límites. Para designarlos se adopta el término «esclusa», tomado del periodista Daniel Arjona: en ingeniería hidráulica, una esclusa es un recinto que regula el paso entre dos niveles, y solo permite avanzar al siguiente tramo cuando se cumplen determinadas condiciones. Aplicado al aprendizaje, el término alude a la autolimitación del uso de la IA en varias dimensiones. Las propuestas que siguen derivan de la experiencia docente del autor y del diálogo con estudiantes. **[Comentario: la fuente del término es un texto divulgativo, no revisado por pares (**[**Arjona, 2026**](https://elarjonauta.substack.com/p/el-claustro-y-la-nave-espacial-universidad-ia)**). Los criterios propuestos se apoyan en la literatura en la medida que se indica en cada caso.]**

### 5.1. Esclusa temporal

Según Arjona, «la IA puede llegar antes, durante o después del esfuerzo. Si llega antes, coloniza la fase generativa. Si llega durante, puede orientar o puede sustituir. Si llega después, funciona como contraste: espejo, adversario, corrector». De ello se deriva que la IA no debería usarse en ningún caso antes del esfuerzo propio, que su uso durante el proceso es ambivalente y que resulta más eficaz después de que el estudiante haya trabajado el problema mediante la lectura, la discusión con compañeros o la consulta al profesor. **[Comentario: el principio de «esfuerzo primero» está respaldado por la investigación sobre fracaso productivo: intentar resolver un problema antes de recibir instrucción mejora la comprensión conceptual y la transferencia (**[**Kapur, 2016**](https://doi.org/10.1080/00461520.2016.1155457)**;** [**Sinha & Kapur, 2021**](https://doi.org/10.3102/00346543211019105)**). Sin embargo, la prohibición absoluta del uso previo no lo está. Para principiantes, la instrucción guiada y los ejemplos resueltos al inicio suelen ser más eficaces que la exploración autónoma (**[**Kirschner et al., 2006**](https://doi.org/10.1207/s15326985ep4102_1)**), y el propio metaanálisis de Sinha y Kapur muestra que el efecto depende del diseño de la actividad. Sería más preciso formular el criterio como «no usar la IA para generar la respuesta antes del esfuerzo propio».]**

### 5.2. Esclusas sobre el tipo de tarea: usos desaconsejados

Se proponen tres usos desaconsejados:

1. **Creación de contenido cuando sustituye el objeto de aprendizaje.** Si una actividad persigue que el estudiante aprenda a construir una presentación con un hilo argumental, delegarla en la IA anula su finalidad. Si el objeto de aprendizaje es otro (por ejemplo, analizar las diferencias entre R y Python), el formato puede delegarse sin coste para el aprendizaje. **[Comentario: coherente con el efecto de generación (**[**Slamecka & Graf, 1978**](https://doi.org/10.1037/0278-7393.4.6.592)**) y con la distinción entre rendimiento y aprendizaje (**[**Soderstrom & Bjork, 2015**](https://doi.org/10.1177/1745691615569000)**). El criterio de identificar qué parte de la tarea constituye el objeto de aprendizaje es pertinente.]**
2. **Cuestiones personales.** Se desaconseja usar la IA para decisiones personales o como sustituto de apoyo psicológico. En la exposición se afirmó que estos sistemas «están entrenados para ganar dinero, no para ayudarnos» y que tienen una «personalidad psicopática». **[Comentario: estas dos afirmaciones carecen de base científica y la segunda es incorrecta: atribuir una personalidad clínica a un modelo de lenguaje no tiene fundamento. Sí está documentada la complacencia (\*sycophancy\*): la tendencia de estos modelos a dar la razón al usuario incluso cuando se equivoca (**[**Sharma et al., 2023**](https://scholar.google.com/scholar?q="Towards+understanding+sycophancy+in+language+models")**). La evidencia sobre el apoyo psicológico es mixta: un ensayo controlado con un chatbot terapéutico diseñado para ello mostró reducción de síntomas de depresión y ansiedad (**[**Heinz et al., 2025**](https://scholar.google.com/scholar?q="Randomized+trial+of+a+generative+AI+chatbot+for+mental+health+treatment")**), mientras que el uso intensivo de chatbots generalistas se ha asociado con más soledad y dependencia emocional (**[**Fang et al., 2025**](https://scholar.google.com/scholar?q="How+AI+and+human+behaviors+shape+psychosocial+effects+of+chatbot+use")**). No hay evidencia de que pedir sugerencias de regalos perjudique el aprendizaje o el bienestar.]**
3. **Habilidades ya adquiridas.** El uso intensivo de la IA para tareas que el usuario ya domina, como la escritura, puede llevar a la pérdida de esas habilidades. **[Comentario: respaldado por la evidencia de pérdida de destrezas en profesionales expertos tras habituarse al apoyo de la IA (**[**Budzyń et al., 2025**](https://scholar.google.com/scholar?q="Endoscopist+deskilling+risk+after+exposure+to+artificial+intelligence+in+colonoscopy")**). Este resultado matiza la idea de la sección 3.1 de que la IA es un «superpoder» para el experto.]**

### 5.3. Esclusas sobre el tipo de tarea: usos recomendados

Se proponen tres usos recomendados:

1. **Tareas mecánicas sin valor formativo**, como transcribir audio, salvo que la propia tarea sea el objeto de aprendizaje.
2. **Tareas simples**, como realizar cálculos o agregar datos en una hoja de cálculo. **[Comentario: los modelos de lenguaje pueden cometer errores aritméticos si no ejecutan código o no usan herramientas de cálculo integradas. El criterio debería incluir la verificación de los resultados.]**
3. **Aprendizaje de destrezas nuevas pero próximas.** Este es el uso más valioso: aprender lo que no se sabe, pero que está al alcance a partir de los conocimientos previos. Por ejemplo, preparar una asignatura nueva en un campo afín es abordable con ayuda de la IA; una destreza muy alejada de la propia formación no lo es, porque genera frustración y escaso aprendizaje. **[Comentario: respaldado. El criterio corresponde a la zona de desarrollo próximo (**[**Vygotsky, 1978**](https://scholar.google.com/scholar?q="Mind+in+society%3A+The+development+of+higher+psychological+processes")**) y a las condiciones de eficacia del andamiaje (**[**van de Pol et al., 2010**](https://doi.org/10.1007/s10648-010-9127-6)**). Conviene señalar que el ejemplo procede de un profesor experto; para un estudiante, el riesgo descrito en la sección 3.1 sigue presente si la IA resuelve la tarea en lugar de guiarla.]**

## 6. Conclusiones

La IA generativa no es en sí misma aliada ni enemiga del aprendizaje: su efecto depende de si su uso respeta las condiciones de fricción, conexión con el conocimiento previo y andamiaje que requiere el aprendizaje profundo. La experiencia docente analizada muestra tres supuestos erróneos: que lo útil para un experto lo es para un aprendiz, que un buen producto implica aprendizaje y que la IA es igualmente útil para cualquier tarea.

Como respuesta, se propone un sistema de esclusas que limita el uso de la IA en función del momento del proceso de aprendizaje y del tipo de tarea. Estos criterios son provisionales: la evidencia disponible procede en gran parte de estudios de corta duración, de contextos distintos al universitario o de diseños correlacionales, y requiere confirmación mediante estudios longitudinales.

## Referencias

Las referencias se han recopilado sin acceso a búsqueda bibliográfica; conviene verificar los datos antes de citarlas. Los enlaces a doi.org y arXiv son directos; los de Google Scholar buscan el título exacto. *No he leído toda esta bibliografía para preparar la charla. Solo los resúmenes de algunas. Ya tengo tarea para los próximos meses ...*

- Arjona, D. (2026). El claustro y la nave espacial. *El Arjonauta* (Substack). [Enlace](https://elarjonauta.substack.com/p/el-claustro-y-la-nave-espacial-universidad-ia)
- Ausubel, D. P. (1968). *Educational psychology: A cognitive view*. Holt, Rinehart & Winston. [Enlace](https://scholar.google.com/scholar?q="Educational+psychology%3A+A+cognitive+view")
- Bastani, H., Bastani, O., Sungu, A., Ge, H., Kabakcı, Ö. y Mariman, R. (2025). Generative AI without guardrails can harm learning: Evidence from high school mathematics. *PNAS, 122*(26), e2422633122. [Enlace](https://doi.org/10.1073/pnas.2422633122)
- Bjork, E. L. y Bjork, R. A. (2011). Making things hard on yourself, but in a good way: Creating desirable difficulties to enhance learning. En *Psychology and the real world* (pp. 56–64). Worth. [Enlace](https://scholar.google.com/scholar?q="Making+things+hard+on+yourself%2C+but+in+a+good+way")
- Brynjolfsson, E., Li, D. y Raymond, L. (2025). Generative AI at work. *The Quarterly Journal of Economics, 140*(2), 889–942. [Enlace](https://doi.org/10.1093/qje/qjae044)
- Budzyń, K. et al. (2025). Endoscopist deskilling risk after exposure to artificial intelligence in colonoscopy: A multicentre, observational study. *The Lancet Gastroenterology & Hepatology*. [Enlace](https://scholar.google.com/scholar?q="Endoscopist+deskilling+risk+after+exposure+to+artificial+intelligence+in+colonoscopy")
- Dell'Acqua, F. et al. (2023). Navigating the jagged technological frontier. *Harvard Business School Working Paper* 24-013. [Enlace](https://doi.org/10.2139/ssrn.4573321)
- Dunlosky, J., Rawson, K. A., Marsh, E. J., Nathan, M. J. y Willingham, D. T. (2013). Improving students' learning with effective learning techniques. *Psychological Science in the Public Interest, 14*(1), 4–58. [Enlace](https://doi.org/10.1177/1529100612453266)
- Ellington, A. J. (2003). A meta-analysis of the effects of calculators on students' achievement and attitude levels in precollege mathematics classes. *Journal for Research in Mathematics Education, 34*(5), 433–463. [Enlace](https://scholar.google.com/scholar?q="A+meta-analysis+of+the+effects+of+calculators+on+students'+achievement+and+attitude+levels")
- Fan, Y. et al. (2025). Beware of metacognitive laziness: Effects of generative artificial intelligence on learning motivation, processes, and performance. *British Journal of Educational Technology, 56*(2), 489–530. [Enlace](https://doi.org/10.1111/bjet.13544)
- Fang, C. M. et al. (2025). How AI and human behaviors shape psychosocial effects of chatbot use: A longitudinal randomized controlled study. Preprint, arXiv. [Enlace](https://scholar.google.com/scholar?q="How+AI+and+human+behaviors+shape+psychosocial+effects+of+chatbot+use")
- Fleckenstein, J., Meyer, J., Jansen, T., Keller, S. D., Köller, O. y Möller, J. (2024). Do teachers spot AI? Evaluating the detectability of AI-generated texts among student essays. *Computers and Education: Artificial Intelligence, 6*, 100209. [Enlace](https://doi.org/10.1016/j.caeai.2024.100209)
- Freeman, J. (2025). *Student Generative AI Survey 2025*. Higher Education Policy Institute, Policy Note 61. [Enlace](https://www.google.com/search?q=HEPI+"Student+Generative+AI+Survey+2025")
- Gerlich, M. (2025). AI tools in society: Impacts on cognitive offloading and the future of critical thinking. *Societies, 15*(1), 6. [Enlace](https://doi.org/10.3390/soc15010006)
- Heinz, M. V. et al. (2025). Randomized trial of a generative AI chatbot for mental health treatment. *NEJM AI, 2*(4). [Enlace](https://scholar.google.com/scholar?q="Randomized+trial+of+a+generative+AI+chatbot+for+mental+health+treatment")
- Kalyuga, S., Ayres, P., Chandler, P. y Sweller, J. (2003). The expertise reversal effect. *Educational Psychologist, 38*(1), 23–31. [Enlace](https://doi.org/10.1207/S15326985EP3801_4)
- Kapur, M. (2016). Examining productive failure, productive success, unproductive failure, and unproductive success in learning. *Educational Psychologist, 51*(2), 289–299. [Enlace](https://doi.org/10.1080/00461520.2016.1155457)
- Kazemitabaar, M. et al. (2023). Studying the effect of AI code generators on supporting novice learners in introductory programming. *Proceedings of CHI '23*. [Enlace](https://scholar.google.com/scholar?q="Studying+the+effect+of+AI+code+generators+on+supporting+novice+learners+in+introductory+programming")
- Keith, N. y Frese, M. (2008). Effectiveness of error management training: A meta-analysis. *Journal of Applied Psychology, 93*(1), 59–69. [Enlace](https://doi.org/10.1037/0021-9010.93.1.59)
- Kestin, G., Miller, K., Klales, A., Milbourne, T. y Ponti, G. (2025). AI tutoring outperforms in-class active learning. *Scientific Reports, 15*, 17458. [Enlace](https://scholar.google.com/scholar?q="AI+tutoring+outperforms+in-class+active+learning")
- Kirschner, P. A., Sweller, J. y Clark, R. E. (2006). Why minimal guidance during instruction does not work. *Educational Psychologist, 41*(2), 75–86. [Enlace](https://doi.org/10.1207/s15326985ep4102_1)
- Kosmyna, N. et al. (2025). Your brain on ChatGPT: Accumulation of cognitive debt when using an AI assistant for essay writing task. Preprint, arXiv:2506.08872. [Enlace](https://arxiv.org/abs/2506.08872)
- Lee, H.-P. et al. (2025). The impact of generative AI on critical thinking: Self-reported reductions in cognitive effort and confidence effects from a survey of knowledge workers. *Proceedings of CHI '25*. [Enlace](https://scholar.google.com/scholar?q="The+impact+of+generative+AI+on+critical+thinking%3A+Self-reported+reductions+in+cognitive+effort")
- Marton, F. y Säljö, R. (1976). On qualitative differences in learning: I. Outcome and process. *British Journal of Educational Psychology, 46*(1), 4–11. [Enlace](https://scholar.google.com/scholar?q="On+qualitative+differences+in+learning"+Marton+Säljö)
- Metcalfe, J. (2017). Learning from errors. *Annual Review of Psychology, 68*, 465–489. [Enlace](https://doi.org/10.1146/annurev-psych-010416-044022)
- Noy, S. y Zhang, W. (2023). Experimental evidence on the productivity effects of generative artificial intelligence. *Science, 381*(6654), 187–192. [Enlace](https://doi.org/10.1126/science.adh2586)
- Peters, U. y Chin-Yee, B. (2025). Generalization bias in large language model summarization of scientific research. *Royal Society Open Science, 12*(4), 241776. [Enlace](https://doi.org/10.1098/rsos.241776)
- Pickles, J. (Ed.). (1995). *Ground truth: The social implications of geographic information systems*. Guilford Press. [Enlace](https://scholar.google.com/scholar?q="Ground+truth%3A+The+social+implications+of+geographic+information+systems")
- Prather, J. et al. (2024). The widening gap: The benefits and harms of generative AI for novice programmers. *Proceedings of ICER '24*. [Enlace](https://scholar.google.com/scholar?q="The+widening+gap%3A+The+benefits+and+harms+of+generative+AI+for+novice+programmers")
- Reglamento (UE) 2024/1689 del Parlamento Europeo y del Consejo, de 13 de junio de 2024 (Reglamento de Inteligencia Artificial), art. 4. [Enlace](http://data.europa.eu/eli/reg/2024/1689/oj)
- Risko, E. F. y Gilbert, S. J. (2016). Cognitive offloading. *Trends in Cognitive Sciences, 20*(9), 676–688. [Enlace](https://doi.org/10.1016/j.tics.2016.07.002)
- Roediger, H. L. y Karpicke, J. D. (2006). Test-enhanced learning. *Psychological Science, 17*(3), 249–255. [Enlace](https://doi.org/10.1111/j.1467-9280.2006.01693.x)
- Sharma, M. et al. (2023). Towards understanding sycophancy in language models. Preprint, arXiv. [Enlace](https://scholar.google.com/scholar?q="Towards+understanding+sycophancy+in+language+models")
- Simonsmeier, B. A., Flaig, M., Deiglmayr, A., Schalk, L. y Schneider, M. (2022). Domain-specific prior knowledge and learning: A meta-analysis. *Educational Psychologist, 57*(1), 31–54. [Enlace](https://doi.org/10.1080/00461520.2021.1939700)
- Sinha, T. y Kapur, M. (2021). When problem solving followed by instruction works: Evidence for productive failure. *Review of Educational Research, 91*(5), 761–798. [Enlace](https://doi.org/10.3102/00346543211019105)
- Slamecka, N. J. y Graf, P. (1978). The generation effect: Delineation of a phenomenon. *Journal of Experimental Psychology: Human Learning and Memory, 4*(6), 592–604. [Enlace](https://doi.org/10.1037/0278-7393.4.6.592)
- Soderstrom, N. C. y Bjork, R. A. (2015). Learning versus performance: An integrative review. *Perspectives on Psychological Science, 10*(2), 176–199. [Enlace](https://doi.org/10.1177/1745691615569000)
- UNESCO (2023). *Guidance for generative AI in education and research*. UNESCO. [Enlace](https://scholar.google.com/scholar?q="Guidance+for+generative+AI+in+education+and+research")
- van de Pol, J., Volman, M. y Beishuizen, J. (2010). Scaffolding in teacher–student interaction: A decade of research. *Educational Psychology Review, 22*(3), 271–296. [Enlace](https://doi.org/10.1007/s10648-010-9127-6)
- Vygotsky, L. S. (1978). *Mind in society: The development of higher psychological processes*. Harvard University Press. [Enlace](https://scholar.google.com/scholar?q="Mind+in+society%3A+The+development+of+higher+psychological+processes")
- Walters, W. H. y Wilder, E. I. (2023). Fabrication and errors in the bibliographic citations generated by ChatGPT. *Scientific Reports, 13*, 14045. [Enlace](https://doi.org/10.1038/s41598-023-41032-5)
- Wang, J. y Fan, W. (2025). The effect of ChatGPT on students' learning performance, learning perception, and higher-order thinking: Insights from a meta-analysis. *Humanities and Social Sciences Communications, 12*, 621. [Enlace](https://scholar.google.com/scholar?q="The+effect+of+ChatGPT+on+students'+learning+performance%2C+learning+perception%2C+and+higher-order+thinking")
- Weber-Wulff, D. et al. (2023). Testing of detection tools for AI-generated text. *International Journal for Educational Integrity, 19*, 26. [Enlace](https://doi.org/10.1007/s40979-023-00146-z)
- Wood, D., Bruner, J. S. y Ross, G. (1976). The role of tutoring in problem solving. *Journal of Child Psychology and Psychiatry, 17*(2), 89–100. [Enlace](https://doi.org/10.1111/j.1469-7610.1976.tb00381.x)






****

[Aquí](https://github.com/aprendiendo-cosas/Conf_IA_amiga_o_enemiga_GEOFOREST/archive/refs/tags/2026_2027.zip) puedes descargar un archivo .zip que contiene este texto en formato html y todo el material que incluye.

****

<p xmlns:cc="http://creativecommons.org/ns#" >El contenido de este repositorio se puede utilizar bajo la siguiente licencia:  <a  href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1"  target="_blank" rel="license noopener noreferrer"  style="display:inline-block;">CC BY-NC-SA 4.0<img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"  alt=""><img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"  alt=""><img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"  alt=""><img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"  alt=""></a></p> 

<p>Esta licencia no aplica a enlaces a artículos, libros o imágenes no originales. Estos productos tienen su licencia correspondiente.</p>

