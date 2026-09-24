# Ecosistema

## Descripción
Ecosistema(chatITMAZbot) es un chatbot desarrollado en Make que utiliza un módulo de Make AI Agent para analizar fotografías de plantas u organismos vivos y responder con información breve sobre lo que identifica. El sistema busca describir qué es el elemento observado, qué función cumple y cuál es su rol dentro del ecosistema.

## Nombre del proyecto
Ecosistema(chatITMAZbot)

## Objetivo general
Desarrollar un sistema basado en inteligencia artificial para reconocer organismos vivos o plantas presentes en una imagen y ofrecer una respuesta breve, clara y útil para el usuario.

## Objetivos específicos
- Diseñar un flujo de trabajo en Make para recibir imágenes.
- Integrar un agente de IA para interpretar contenido visual.
- Identificar plantas u organismos presentes en una fotografía.
- Generar respuestas cortas sobre la función y el rol ecológico del elemento detectado.
- Evaluar el comportamiento del sistema con pruebas reales.

## Funcionamiento
El sistema realiza el siguiente flujo:

1. El usuario envía una imagen al chatbot.
2. Make recibe la imagen.
3. El módulo de Make AI Agent analiza el contenido visual.
4. El agente identifica los elementos observados.
5. El chatbot responde con información breve sobre cada organismo o planta detectada.
6. El usuario recibe la respuesta en lenguaje natural.

## Tecnologías utilizadas
- Make
- Make AI Agent
- Inteligencia artificial para análisis de imágenes
- Chatbot para interacción con el usuario

## Enlace de demostración
https://youtube.com/shorts/RY9s2PAod08?feature=share

## Evidencias de prueba
<img width="600" height="800" alt="image" src="https://github.com/user-attachments/assets/44b0130d-6f75-4202-9c45-22de57abb3e6" />


Las imágenes muestran un contexto exterior con vegetación y arquitectura, y fueron utilizadas para evaluar la capacidad del chatbot de analizar el entorno visual y responder con información útil.

## Ejemplo de respuesta del chatbot
El sistema puede responder de la siguiente manera:

- Identificación: planta o organismo observado
- Descripción breve: función o apariencia
- Rol: qué papel cumple en el ecosistema
- Observación: se indica incertidumbre si la imagen no permite una identificación precisa

## Resultados esperados
El chatbot permite identificar elementos visibles en una imagen y generar una respuesta informativa en lenguaje natural. La calidad de la respuesta dependerá principalmente de:

- calidad de la imagen
- iluminación
- resolución
- claridad del objeto o planta
- cantidad de elementos visibles en la fotografía

## Observaciones
- El sistema funciona como apoyo educativo y de observación visual.
- Debe indicar incertidumbre cuando la imagen no permita una identificación segura.
- La respuesta es útil como orientación general, pero no sustituye una validación técnica o científica.

## Reporte técnico
El reporte técnico formal, en formato APA 7 y en español, se encuentra en:

resultados/chatITMAZbot_reporte_APA.pdf

## Estructura del repositorio
```text
proyecto-ejemplo/
├── README.md
├── codigo/
│   └── .gitkeep
├── imagenes/
│   └── .gitkeep
├── video/
│   └── .gitkeep
├── resultados/
│   ├── README.md
│   └── reporte-tecnico-apa.md
└── .gitignore
```

## Datos del proyecto
- Autor: Ruben Nolasco Carrillo
- Carrera: Ingeniería en Sistemas Computacionales
- Institución: Instituto Tecnológico del Estado de Sinaloa
- Profesor: Miguel Ángel Barrón Hernández
- Fecha: 23/09/2026
- Proyecto: chatITMAZbot

## Conclusión
chatITMAZbot demuestra la viabilidad de integrar automatización con inteligencia artificial para analizar imágenes y responder con información útil sobre plantas u organismos vivos. El proyecto resulta especialmente valioso como herramienta de apoyo educativo, de observación ambiental y de exploración de aplicaciones de IA en entornos prácticos.
