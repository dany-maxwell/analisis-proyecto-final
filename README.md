# El internet muerto #
## Integrantes: ##
- Claudia Coello
- Daniel Orozco
- Gabriel Toaquiza
## Contexto ##
El internet actual ya no es lo que solia ser, actualmente los bots son un problema real en redes sociales, servidores, empresas o trafico de busquedas.

Pero como podemos identificarlos?

El siguiente estudio pretende analizar los bots en la red social Reddit, para asi, determinar su naturaleza y cuales podrian ser las consecuencias.

### Fuente https://www.kaggle.com/datasets/nudratabbas/the-dead-internet-theory-reddit-bot-vs-human

## Resultados ##

<img width="1013" height="654" alt="imagen" src="https://github.com/user-attachments/assets/c538624f-8398-4335-a011-1e51abdcff21" />

El Reprint Bot tiene el sentimiento más alto, lo que sugiere que su contenido está diseñado para parecer amigable o atractivo. Los humanos tienen el único valor negativo, lo que puede reflejar una mayor diversidad emocional o crítica en sus comentarios. Los Engagement Farmers y AI Summarizers se mantienen en un rango positivo, lo que indica que los bots tienden a evitar el lenguaje negativo. 

<img width="933" height="602" alt="imagen" src="https://github.com/user-attachments/assets/2674820c-9c36-4576-af28-b6e8663a3a30" />

Aunque los humanos son mayoría, casi la mitad del contenido con enlaces proviene de bots, lo que sugiere una estrategia automatizada para redirigir tráfico o difundir contenido. La presencia equilibrada entre los tres tipos de bots indica que el uso de enlaces no es exclusivo de un solo tipo, sino una práctica común entre automatismos. Este patrón puede ser útil para entrenar modelos de detección, ya que el uso de enlaces es una señal fuerte de automatización. 

<img width="921" height="641" alt="imagen" src="https://github.com/user-attachments/assets/3c318b26-ba57-451a-8761-f6f200166992" />

Aunque se espera que las cuentas más antiguas acumulen más karma, el gráfico muestra que no siempre es así. Hay casos atípicos de cuentas jóvenes con karma alto, lo que podría indicar: bots bien diseñados para parecer legítimos, cuentas recicladas o compradas, actividad viral o manipulada. 

## Conclusiones ##

-     A pesar de que los datos no son “reales”, estos nos permiten establecer patrones de comportamiento típicos asociados a bots y mejorar herramientas de detección. 

-    Mas allá del contexto del internet muerto, este trabajo es relevante en escenarios reales como moderación de redes sociales, prevención de la desinformación o detección de fraude. 

-    La relación entre la edad de la cuenta y el karma no es completamente lineal ni predecible. Aunque muchas cuentas jóvenes tienen karma bajo, existen excepciones que podrían representar bots sofisticados o usuarios con actividad anómala. Esto sugiere que ni la antigüedad ni el karma por sí solos son suficientes para detectar automatización, y deben analizarse en conjunto con otras variables. 

-    Los bots representan una proporción significativa del contenido que incluye enlaces, a pesar de ser minoría en cantidad total. Esto sugiere que el uso de enlaces es una estrategia clave en la actividad automatizada, ya sea para redirigir tráfico, promover contenido o simular participación legítima. El análisis de esta variable puede ser útil para detectar bots en entornos sociales como Reddit. 

-    Los bots, en especial los de tipo Reprint y Engagement Farmer, tienden a usar lenguaje más positivo que los humanos. Esto puede ser una estrategia para parecer confiables, generar interacción o evitar moderación automática. El contraste con el tono ligeramente negativo de los humanos sugiere que el análisis de sentimiento puede ser una herramienta útil para diferenciar entre actividad automatizada y orgánica. 

Weben React: https://analisis-proyecto-internet-muerto.onrender.com/
Video: https://youtu.be/grP4EP5F3Ac?si=OEE_Vt_uQAPVOs6y
Diapositivas: https://www.canva.com/design/DAG_k1dLyc4/chT-GQ_RCiQvlFfVIytr9w/edit?utm_content=DAG_k1dLyc4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
