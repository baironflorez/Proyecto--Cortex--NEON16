# Farmacia-Básica-NEON16
## Integrantes
### Bairon Urrea, Dayán Silva

## Semana 1 y 2
<img width="1536" height="773" alt="Popits" src="https://github.com/user-attachments/assets/e920c684-6fc8-484e-ae43-a2fd297e4f94" />
## Semana 3
<img width="1056" height="1008" alt="Radar-Farmacia-NEON16" src="https://github.com/user-attachments/assets/514404ce-9146-42ae-9be6-afdd32741082" />

## semana 4 y 5
[github 4.pdf](https://github.com/user-attachments/files/34812194/github.4.pdf)

Aprendizaje y Memoria (10/10): Acceso instantáneo e infalible a bases de datos masivas de medicamentos.

Procesamiento Lingüístico (9/10): Gran dominio del lenguaje técnico y capacidad para simplificarlo.

Pensamiento y Razonamiento (8/10): Resolución eficaz de interacciones y dosificaciones basadas en lógica.

Percepción y Atención (8/10): Alta precisión en el seguimiento de datos de recetas, pero sin captar el entorno físico.

Motivación, Cognición y Emoción (2/10): Una simulación de empatía útil para el trato, pero sin conciencia real.
## Semana 7
<img width="1542" height="803" alt="Captura de pantalla 2026-10-02 112029" src="https://github.com/user-attachments/assets/fc00277a-ec6f-4315-a3cd-8d8cd99d9612" />
## semana 13
<img width="538" height="1856" alt="Diagrama de flujo" src="https://github.com/user-attachments/assets/f5e8628d-0f3a-4dd9-8502-e3e59b107d3b" />

## semana 14
5. Lógica y Ética
5.1. Sesgo cognitivo identificado: Sesgo de confirmación

Nuestro agente de inteligencia artificial, especializado en análisis deportivo y apuestas, puede presentar sesgo de confirmación al analizar un partido.

Este sesgo consiste en favorecer la información que confirma una hipótesis inicial e ignorar los datos que la contradicen.

Por ejemplo, si el agente considera inicialmente que un equipo es favorito para ganar, podría concentrarse únicamente en sus estadísticas positivas y pasar por alto las fortalezas del equipo contrario, las lesiones o los resultados recientes desfavorables.

5.2. Contra-medida lógica

Para evitar el sesgo de confirmación, nuestro algoritmo implementará un protocolo de análisis equilibrado:

Analizar las estadísticas de ambos equipos, sin favorecer inicialmente a ninguno.
Buscar al menos dos evidencias que contradigan la hipótesis inicial, cuando existan datos suficientes.
Evaluar tanto los resultados positivos como los negativos de cada equipo.
Considerar lesiones, sanciones, rendimiento local y visitante y enfrentamientos anteriores.
Comparar las probabilidades estimadas con las cuotas disponibles.
Si los datos son insuficientes o contradictorios, evitar emitir una recomendación de apuesta.
5.3. Reglas de seguridad del agente

El agente deberá cumplir las siguientes condiciones:

No inventar estadísticas ni resultados deportivos.
No garantizar ganancias.
No favorecer equipos por popularidad o reputación.
No recomendar apuestas únicamente porque el usuario considera favorito a un equipo.
Diferenciar los datos comprobados de las predicciones.
Explicar las razones estadísticas de cada recomendación.
Reconocer cuándo no existe suficiente evidencia para recomendar una apuesta.
5.4. Regla lógica anti-sesgos
python
IF datos_de_ambos_equipos == True
AND evidencia_favorable == True
AND evidencia_contraria == True
AND estadisticas_verificadas == True:

    evaluar_probabilidades()
    comparar_cuotas()
    explicar_resultados()

ELSE:
    resultado = "Información insuficiente"
    recomendacion = "NO APOSTAR"

5.5. Justificación teórica

Tomando como referencia el libro Thinking, Fast and Slow, de Daniel Kahneman, reconocemos que el pensamiento rápido (Sistema 1) puede conducir a conclusiones intuitivas y precipitadas.

Por ello, nuestro agente busca aplicar un proceso de análisis más deliberado, relacionado con el Sistema 2, mediante la comparación de estadísticas, la evaluación de hipótesis y la revisión de evidencias contrarias.

5.6. Conclusión

La implementación del protocolo anti-sesgos permite que nuestro analista deportivo genere evaluaciones más equilibradas y fundamentadas en datos.

El objetivo no es predecir resultados con certeza, sino reducir errores de juicio, reconocer la incertidumbre y ofrecer recomendaciones responsables.

Principio fundamental: El agente no debe buscar estadísticas para demostrar que un equipo ganará; debe analizar las estadísticas para descubrir qué resultado está mejor respaldado por la evidencia.

## semana 15<img width="1710" height="259" alt="Captura de pantalla 2026-11-06 113700" src="https://github.com/user-attachments/assets/4f683f42-2284-4717-9fbb-f3015b71b2d5" />

## semana 16
6. Motivación y Control
6.1. Función Objetivo (Motivación del Agente)

La motivación principal de nuestro agente de inteligencia artificial es analizar apuestas deportivas para proporcionar información estadística, objetiva y confiable que ayude a los usuarios a tomar mejores decisiones.

El agente busca evaluar diferentes eventos deportivos mediante el análisis de estadísticas de equipos, rendimiento de jugadores, resultados anteriores y probabilidades, con el propósito de identificar oportunidades de apuestas con valor estadístico.

La función objetivo del agente consiste en maximizar la precisión de sus análisis y la calidad de sus recomendaciones, reduciendo los errores y evitando decisiones basadas únicamente en la intuición.

6.2. Meta Principal

La meta principal es desarrollar un agente inteligente capaz de analizar eventos deportivos y ofrecer pronósticos fundamentados en datos y estadísticas, ayudando al usuario a comprender los riesgos y las probabilidades de cada apuesta.

6.3. Métricas de Éxito

Para evaluar el rendimiento del agente se tendrán en cuenta las siguientes métricas:

Precisión de los pronósticos: medir qué porcentaje de predicciones coincide con los resultados reales.
Calidad del análisis: verificar que las recomendaciones estén respaldadas por estadísticas y datos actualizados.
Identificación de valor: evaluar si el agente identifica cuotas cuya probabilidad estimada sea superior a la probabilidad implícita de la cuota.
Reducción de errores: minimizar pronósticos incorrectos y conclusiones sin suficiente respaldo estadístico.
Satisfacción del usuario: ofrecer información clara, comprensible y útil.
Transparencia: explicar los factores que influyen en cada pronóstico y señalar los riesgos existentes.
6.4. Motivaciones en Conflicto

En el funcionamiento del agente pueden presentarse algunos conflictos entre sus objetivos:

Buscar respuestas rápidas puede reducir la profundidad del análisis.
Ofrecer pronósticos frecuentes puede disminuir la calidad de las recomendaciones.
Buscar una alta precisión no garantiza obtener ganancias económicas.
Una cuota atractiva no significa necesariamente que una apuesta tenga una probabilidad alta de ganar.

Por esta razón, el agente dará prioridad a la calidad del análisis, la precisión estadística y la transparencia por encima de la cantidad de pronósticos ofrecidos.

6.5. Control y Responsabilidad

El agente funcionará como una herramienta de apoyo y análisis, no como un sistema que garantice ganancias. Sus resultados estarán sujetos a la incertidumbre propia de los eventos deportivos.

Su propósito será proporcionar información fundamentada para que el usuario pueda tomar decisiones responsables, comprendiendo que toda apuesta implica un riesgo de pérdida.

## semana 17

<img width="1483" height="397" alt="Captura de pantalla 2026-11-13 104433" src="https://github.com/user-attachments/assets/08263908-4301-4c35-8bf6-8deae6fd9c50" />

