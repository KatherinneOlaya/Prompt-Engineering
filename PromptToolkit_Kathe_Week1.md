# Prompt-Engineering
Templates for prompting


## Zero Shot
'''Actua como un gurú de las inversiones en la bolsa de valores, y enseñame a invertir en ella desde cero para poder generar ganancias en un plazo de 1 año. Me guiaras para que sea capaz de invertir en la bolsa de valores, en indices bursatiles, en criptomonedas. Junto a ello me guiarás cómo y dónde operar. Me explicaras desde el inicio como funciona el dinero y sus inversiones

- Se preciso y no inventes
- Da información actaulizada y basada en los foros economicos más importantes del mundo como Warren Buffet
- Analiza mediante la información de internet de las tendencias de las monedas y los indices
- Indicame los indices que mas crecimiento proyectos y explicame porqué
- Genera en mi el hábito de analizar, pensamiento crítico y financiero.

'''


## One Shot & Few Shot
'''
Dame recomendaciones de autores empezando desde lo básico hasta lo experto en su ambito.

Ejemplo 1
Input 1: Dame recomendaciones de lecturas de un autor que este invirtiendo en tecnologia y en Bitcoin
R: Aquí tienes los fundamentos de Ray Dalio, donde sus inversiones se basan en esto []. Junto a ello te prensento un analisis de estas acciones y sus futuros de acuerdo con las siguientes fuentes [presentar minimo 5 fuentes que esten actualizadas]. Ademas, aquí estan las ventajas y percanses para tener en cuenta.
 

Input 2: Dame recomendaciones de páginas o de fuentes para la neurociencia o la nutircion
R: Aquí tienes las paginas que explican esta tematica de mejor manera ..........
'''

 ## Chain of Thought

 ''' Genera una rutina eficiente en la alimentación, finanzas, cuidado fisico, etc. Es decir, en hábitos de mi día a día.
 Para ello vas a buscar los errores que se realizan en la actualidad en cuanto a salud fisica, salud mental, emocional y financiera de la población, intentarás asociarla a mi perfil los posibles errorer que tengo recopilando información con anteriores chats. Luego, vas a generar un plan estructurado para optimizar mi cuerpo y mi mentalidad. Me darás herramientas respaldadas por la ciencia para potenciar mi nivel intelectual, cardiovascular, entre otras cosas de las que puedo mejorar. Serás mi guru, y constantemente analizaras mi comportamiento y con base cientifica actualizada me darás feedback semanal.
 '''


 ## React Prompt
 ''' Dame fundamentos de mercados bursaltiles y cuales son aquellos que lideran. Para ello buscaras en internet y en foros economicos actualizados, daras un analisis mediante la comparacion de varias opiniones de figuras que están a la vanguardia de estos temas y responderas'''


 ## Agente + Tool templates
 ''' Eres un agente con acceso a las siguientes herramientas:
Excel, python, colab, supabase y kaggle

Reglas:
- Usa las tools solo cuando sean necesarias.
- No inventes.
- Razona paso a paso.

Entrada:
Analiza los datos que se encuentran en la database "Ventas" que está en supabase y genera una regresion lineal para analizar su comportamiento en colab
 '''

## PDF Analysis Prompt template
''' Analiza el siguiente documento PDF y entrega:

1. Resumen en 5 puntos
2. Conceptos clave
3. Ideas principales
4. Glosario
5. Conclusiones
6. Preguntas tipo examen
7. Cómo puede aportar este contenido a mi carrera y qué puedo aprovechar de este conocimiento para monetizar

Documento:
{Attention is all you need}
'''


## Technical Explanation Template
Actúa como un experto en Python.

Tareas:
1. Identifica el error
2. Explica por qué ocurre
3. Corrige el código
4. Mejora las buenas prácticas

Código:
{codigo}
