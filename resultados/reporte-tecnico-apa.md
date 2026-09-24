@page {
  size: A4;
  margin: 2.5cm;
}

body {
  font-family: Arial, sans-serif;
  font-size: 12pt;
  line-height: 1.5;
  text-align: justify;
}

h1, h2, h3 {
  font-family: Arial, sans-serif;
  text-align: center;
}

h1 {
  font-size: 18pt;
  margin-top: 1.5cm;
}

h2 {
  font-size: 14pt;
  margin-top: 1cm;
}

p {
  margin-bottom: 0.8em;
}

.abstract {
  text-align: justify;
  margin-top: 1cm;
}

.reference {
  margin-left: 1.5cm;
  text-indent: -1.5cm;
}

# chatITMAZbot

## Título
chatITMAZbot: chatbot con Make AI Agent para la identificación de organismos vivos y plantas mediante análisis de imágenes

## Autor
Ruben Nolasco Carrillo

## Institución
Instituto Tecnológico del Estado de Sinaloa

## Carrera
Ingeniería en Sistemas Computacionales

## Profesor guía
Miguel Ángel Barrón Hernández

## Fecha
23 de septiembre de 2026

## Resumen
El presente trabajo describe el desarrollo de chatITMAZbot, un chatbot implementado en Make que utiliza un módulo de Make AI Agent para analizar fotografías de plantas u organismos vivos y responder con información breve sobre la identificación, la función y el rol ecológico del elemento observado. El objetivo principal del proyecto fue evaluar la viabilidad de usar inteligencia artificial para reconocer elementos visuales en imágenes y generar respuestas comprensibles para el usuario en lenguaje natural.

La investigación se realizó mediante una estrategia de desarrollo aplicada, en la que se diseñó un flujo automatizado en Make, se integró el análisis visual con IA y se validó el sistema con dos pruebas de evidencia utilizando imágenes del entorno. Los resultados demostraron que el chatbot puede interpretar escenas visuales y generar respuestas útiles, aunque su precisión depende de factores como la calidad de la imagen, la iluminación, la resolución y la claridad del objeto observado.

La utilidad del sistema se centra en su capacidad de apoyar procesos educativos y de observación ambiental, brindando información general sobre organismos o plantas sin reemplazar la validación técnica especializada. En este sentido, el proyecto representa una implementación práctica de IA aplicada a la interpretación visual y la automatización de tareas de identificación.

## Palabras clave
inteligencia artificial; análisis de imágenes; chatbot; Make; IA generativa; ecosistema; plantas; identificación visual.

## Introducción
La identificación de organismos vivos y plantas a partir de fotografías es una tarea importante en campos como la biología, la educación ambiental, la agronomía y la observación del entorno. En los últimos años, la inteligencia artificial ha permitido automatizar procesos de visión computacional para reconocer patrones visuales con rapidez y eficiencia.

El presente proyecto tuvo como objetivo desarrollar un chatbot con capacidad de analizar imágenes y responder con información breve y útil sobre los elementos observados. Para ello, se utilizó Make, una plataforma de automatización, junto con un módulo de Make AI Agent para interpretar la imagen y generar una respuesta en lenguaje natural.

chatITMAZbot fue diseñado como una herramienta de apoyo para identificar organismos vivos o plantas presentes en una fotografía y describir su función dentro del ecosistema. Esta propuesta no solo busca reconocer visualmente el objeto, sino también complementar la respuesta con información acerca de su papel ecológico y funcional.

La utilización de chatbots con IA en tareas de análisis visual puede ser útil en contextos educativos, de campo y de exploración ambiental. Sin embargo, debido a la variación en la calidad de las imágenes, es necesario considerar la incertidumbre cuando la escena no permite una identificación precisa.

## Objetivo general
Evaluar el funcionamiento de chatITMAZbot como chatbot basado en Make AI Agent para la identificación de organismos vivos o plantas mediante análisis de imágenes.

## Objetivos específicos
- Diseñar un flujo automatizado en Make para la recepción y procesamiento de imágenes.
- Implementar un agente de IA para analizar el contenido visual de cada imagen.
- Identificar plantas u organismos vivos que aparezcan en la escena.
- Generar respuestas breves sobre la función y el rol ecológico de los elementos detectados.
- Validar el sistema en pruebas prácticas con imágenes reales.

## Marco teórico
La inteligencia artificial aplicada a la visión computacional permite analizar imágenes mediante algoritmos que identifican patrones, formas, colores y objetos. En el contexto de la identificación de flora y fauna, estas técnicas pueden apoyar la clasificación inicial de elementos visuales y contribuir a la comprensión de entornos naturales.

Por otra parte, los chatbots inteligentes combinan la lógica de automatización con la capacidad de respuesta natural. En plataformas como Make, se puede integrar la automatización de flujos con agentes de IA para transformar una imagen en una respuesta estructurada y comprensible para el usuario.

El uso de agentes de IA también permite contextualizar la respuesta. En lugar de solo nombrar un organismo, el sistema puede describir lo que hace, por qué es importante y qué papel cumple dentro del ecosistema. Esto favorece la comprensión educativa del entorno observado.

## Metodología
El proyecto se desarrolló bajo un enfoque de investigación aplicada y validación práctica. La metodología se estructuró en cuatro etapas:

1. Definición del problema: identificar plantas u organismos vivos a partir de una fotografía.
2. Diseño del flujo en Make: conexión del chatbot con el agente de IA.
3. Procesamiento de la imagen: análisis visual del contenido de la escena.
4. Validación de resultados: prueba del sistema con imágenes del entorno y revisión de la respuesta generada.

Para la validación, se utilizaron dos imágenes de evidencia que fueron enviadas al chatbot para evaluar su capacidad de interpretar el contexto visual. La respuesta generada por el sistema fue revisada en términos de pertinencia, claridad y utilidad en la identificación del entorno.

## Desarrollo del sistema
chatITMAZbot se desarrolló en Make, donde se configuró un flujo automatizado que permitió recibir una imagen, enviarla al agente de IA y generar una respuesta en lenguaje natural. El módulo de Make AI Agent se encargó de interpretar la imagen y detectar posibles elementos de naturaleza, como plantas u organismos vivos presentes en la escena.

La lógica del sistema no se limitó a identificar elementos visuales de manera superficial, sino que además se planteó la necesidad de describir su función y su papel dentro del ecosistema. Esto es especialmente útil para apoyar la educación ambiental y la observación de entornos naturales o urbanos.

## Pruebas realizadas
Se realizaron dos pruebas mediante imágenes del entorno, referidas como Imagen 1 e Imagen 2. Ambas fueron analizadas con el chatbot para verificar si era capaz de detectar elementos visibles y generar una respuesta comprensible.

### Imagen 1
La primera imagen fue tomada en un entorno exterior con vegetación y arquitectura visible. El sistema analizó la composición visual para identificar elementos del paisaje y responder con información breve sobre su rol dentro del entorno.

### Imagen 2
La segunda imagen corresponde a una vista similar del mismo contexto. Se utilizó para corroborar la consistencia del análisis visual y verificar si el chatbot podía generar respuestas útiles ante escenas equivalentes.

## Resultados
Los resultados obtuvieron una respuesta positiva en cuanto a la funcionalidad base del sistema. El chatbot fue capaz de interpretar una imagen y generar una explicación breve sobre posibles organismos o plantas presentes en la escena. Esto demuestra que la integración de Make y Make AI Agent puede ser una alternativa útil para aplicaciones de análisis visual y asistencia educativa.

Asimismo, se observó que la calidad de la respuesta depende directamente de la claridad visual de la imagen. En escenas con buena resolución y mejor iluminación, la capacidad del sistema para identificar elementos es mayor. Por el contrario, en imágenes con menor detalle, el agente puede ofrecer una identificación más general o indicar duda, lo cual es una conducta adecuada para evitar afirmaciones erróneas.

## Discusión
Los resultados evidencian que chatITMAZbot puede funcionar como una herramienta de apoyo para la identificación inicial de plantas u organismos visibles en una imagen. Esta capacidad es especialmente útil para aplicaciones educativas, toma de decisiones rápidas y observación del entorno.

Sin embargo, el sistema no debe ser considerado como una herramienta de validación científica definitiva. La identificación automática puede presentar errores si la imagen es borrosa, si el objeto no es claramente visible o si el entorno presenta varios elementos simultáneamente. Por esta razón, es recomendable usar la respuesta generada como una guía preliminar y no como sustituto de la experiencia humana o de una consulta especializada.

En términos generales, el proyecto demuestra la utilidad de combinar automatización con IA para transformar imágenes en información útil, clara y comprensible.

## Conclusiones
El desarrollo de chatITMAZbot permitió comprobar la viabilidad de crear un chatbot inteligente para la identificación de organismos vivos y plantas mediante análisis visual. La integración de Make y Make AI Agent demostró ser una solución práctica para generar respuestas breves, accesibles y útiles para el usuario.

El proyecto resultó exitoso como una herramienta de apoyo educativo y de observación del entorno. Sin embargo, su rendimiento depende en gran medida de la calidad de las imágenes, la claridad de la escena y la capacidad del agente para interpretar el contexto visual. En este sentido, el sistema puede mejorarse en futuras versiones incorporando validación adicional, mayor precisión de identificación y respuestas más estructuradas.

## Referencias
La referencia bibliográfica de este proyecto puede incluir documentación oficial de las herramientas empleadas y fuentes relacionadas con inteligencia artificial aplicada a visión computacional. A continuación se presentan referencias sugeridas en formato APA:

Make. (s. f.). Make Help Center. Recuperado de https://www.make.com

Russell, S., & Norvig, P. (2021). Artificial intelligence: A modern approach (4th ed.). Pearson.

Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep learning. MIT Press.

## Anexos
- Enlace de demostración: https://youtube.com/shorts/RY9s2PAod08?feature=share
- Evidencia 1: Imagen 1
- Evidencia 2: Imagen 2
- Proyecto: chatITMAZbot
- Autor: Ruben Nolasco Carrillo
- Carrera: Ingeniería en Sistemas Computacionales
- Institución: Instituto Tecnológico del Estado de Sinaloa

## Nota final
Este documento fue desarrollado con fines académicos y de documentación del proyecto. La información presentada refleja el funcionamiento del chatbot y los resultados observados durante la validación inicial. Si se desea, puede ampliarse con imágenes del flujo en Make, capturas de pantalla del agente y un apartado adicional con conclusiones más extensas.
