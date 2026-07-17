# ConnectaTel

Proyecto 6 - Análisis de una empresa de telecomunicaciones

## :paperclip: Introducción

Análisis realizado a ConnectaTel, empresa de telecomunicaciones con operaciones en México y Colombia.

- Se entrega un reporte para entender cómo los clientes usan realmente los servicios móviles (llamadas y mensajes).

- El objetivo de la empresa es identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.

## :bookmark: Fuentes de datos

1. **plans.csv:** los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
- Catálogo de planes con sus precios y beneficios.
3. **users_latam.csv:** información de clientes: edad, ciudad, fecha de registro, plan contratado.
- Información de cada usuario (datos personales, plan, fecha de registro, churn)
4. **usage.csv:** el detalle de uso real: llamadas (duración) y mensajes (longitud).
- Actividad generada por los usuarios: llamadas, mensajes, duración, longitud.

## :question: Preguntas del negocio 

1. ¿Qué segmentos de clientes muestran mayor o menor uso de llamadas y mensajes?
2. ¿Qué usuarios presentan valores atípicos que puedan indicar comportamientos inusuales, fraude o errores de registro?
3. ¿Cómo varía el uso según la edad y el tipo de plan contratado?
5. ¿Qué patrones pueden ayudar a diseñar mejores planes, optimizar la oferta y mejorar la satisfacción del cliente?

## :high_brightness: Objetivos de aprendizaje del proyecto

- Integrar y limpiar bases de datos provenientes de tres fuentes distintas.
- Aplicar técnicas de validación, estandarización de tipos de datos y detección de valores inconsistentes.
- Construir un perfil estadístico del uso (llamadas y mensajes) por cliente y por segmentos demográficos.
- Detectar outliers y comportamientos atípicos mediante métodos estadísticos y visuales.
- Crear segmentaciones de clientes basadas en edad, país y comportamiento de uso.
- Visualizar diferencias entre segmentos y extraer insights comerciales relevantes.
- Documentar todo el proceso en un Jupyter Notebook, junto con un README reproducible para subirlo a GitHub.

## :wrench: Herramientas de la lección

- Jupyter Notebook
- Python: pandas, numpy, seaborn, matplotlib
- Datasets del Proyecto

## :checkered_flag: Link a notebook de resultados y análisis
[Análisis de ConnectaTel](https://github.com/manuelmichoacan/ConnectaTel)  
