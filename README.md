Definición conceptual

Decisión: Conjunto de acciones

Reuniones con clientes.

Reuniones con el equipo de trabajo.

Trabajo en la oficina (planeación y logística).

 Cada acción consiste en asignar una cantidad de tiempo a cada actividad, respetando los límites mínimos y máximos:

Reuniones con clientes: Entre 1 y 4 horas.

Reuniones con el equipo: Entre 1 y 3 horas.

Trabajo en la oficina: Entre 1 y 4 horas.

 Estados de la naturaleza (Ω): Configuraciones posibles del mundo



Reuniones con clientes:

Cierre de venta: Ocurre con una probabilidad del 30% (o 50% si el cliente es conocido).

No cierre de venta: Ocurre con una probabilidad del 70% (o 50% si el cliente es conocido).

Reuniones con el equipo de trabajo:

Reunión productiva: Ocurre con una probabilidad del 70% (Ciencia de Datos), 50% (Finanzas) o 20% (Marketing).

Reunión no productiva: Ocurre con una probabilidad del 30% (Ciencia de Datos), 50% (Finanzas) o 80% (Marketing).

Trabajo en la oficina:

Siempre productivo: No hay incertidumbre, siempre se avanza en tareas críticas.

# Información proxy (Z): Observaciones ruidosas correlacionadas con Ω


Reuniones con clientes:

Feedback del cliente: Si el cliente muestra interés o urgencia, aumenta la probabilidad de cierre de venta.

Historial de ventas: Si el cliente ha cerrado ventas antes, la probabilidad de cierre aumenta al 50%.

Reuniones con el equipo de trabajo:

Agenda de la reunión: Si la reunión está bien estructurada, es más probable que sea productiva.

Tipo de equipo: La probabilidad de productividad varía según el equipo (Ciencia de Datos: 70%, Finanzas: 50%, Marketing: 20%).

Trabajo en la oficina:
     
Siempre efectivo


# Función de Utilidad (U(ω, d))


Reuniones con clientes:

Si se cierra la venta: $10,000.

Si no se cierra la venta: -$2,000 (costo de oportunidad y tiempo perdido).

La utilidad esperada por reunión es:
     
U(clientes) =p(Cierre)×10,000+p(No cierre)×(−2,000).
 
La utilidad esperada por reunión depende del equipo:

U(equipo) = (probabilidad de que sea productiva)×5,000 + (probabilidad de que no sea productiva) ×(−1,000)=3,500−300

Trabajo en la oficina:

U(oficina) = 1,000 × horas.

# Modelo Probabilístico (p(ω) o p(ω∣Z))

Reuniones con clientes:


Si el cliente es conocido: 
p(Cierre∣conocido) = 50%


Si el cliente no es conocido: 
p(Cierre∣No conocido)=30%


Reuniones con el equipo de trabajo:

Probabilidad de que la reunión sea productiva:

Ciencia de Datos: 

p(Productiva∣Ciencia de Datos)=70%.

Finanzas: 

p(Productiva∣Finanzas)=50%.

Marketing: 

p(Productiva∣Marketing)=20%.

Trabajo en la oficina:

p(Productivo)=100%.Decisiones - CEO 



Como optimizar el tiempo de un CEO:

Objetivo: ¿Qué quiero lograr y cuál es la acción principal a decidir?

    Maximizar la utilidad del tiempo del CEO, es decir, lograr el mayor impacto posible en la empresa con el tiempo disponible (8 horas).

Contexto: ¿Dónde ocurre la decisión? ¿Qué factores externos influyen?

    El CEO de una emrpesa de tecnología dispone de 8 horas para repartir en tres actividades principales: reunions con clientes, trabajar en su oficina (planeación y logístca) y reuniones con su equipo de trabajo.

Incertidumbre: ¿Qué aspectos del mundo (o de la contraparte) no conozco con certeza y podrían afectar mi resultado?

    - Resultado de las reuniones con clientes: no se sabe si se cerrarán ventas o no.
    - Resultado de las reuniones con el equipo de trabajo: no se sabe si la junta con su equipo de trabajo será productiva o una pérdidad de tiempo.
    - Resultado del trabajo en la oficina: Aquí siempre avanzará en la planeación y logística.

Métricas de éxito: ¿Cómo valoro o cuantifico el resultado de mi acción? ¿Gano algo? ¿Pierdo algo?

    - Con los clientes se gana la mayor utilidad si se cierra la venta, pero se pierde mucha utilidad si no se cierra.
    - Con el equipo de trabajo se gana utilidad  (menos que una venta con clientes) si se logra un avance en la planeación, pero se pierde utilidad (menos que no cerrar una venta con los clientes) si no se logra nada.
    - Con el trabajo en la oficina se gana utilidad (menos que una venta con clientes y menos que un avance con el equipo de trabajo).

Información parcial (proxy): ¿Tengo datos, señales o indicios (aunque ruidosos) que puedan guiar mi decisión?

    - Reuniones con clientes:

        Probabilidad de cerrar una venta: 30% (0.3) .
        Probabilidad de cerrar una venta si ya lo conozco: 50% (0.5).

        Utilidad si se cierra la venta: $10,000.

        Utilidad si no se cierra la venta: -$2,000 (costo de oportunidad y tiempo perdido).

    - Reuniones con el equipo de trabajo:

        Probabilidad de que la reunión sea productiva con el equipo de Ciencia de datos: 70% (0.7).

         Probabilidad de que la reunión sea productiva con el equipo de Finanzas: 50% (0.5).

        Probabilidad de que la reunión sea productiva con el equipo de Marketing: 20% (0.2).

        Utilidad si es productiva: $5,000 (avances en proyectos).

        Utilidad si no es productiva: -$1,000 (tiempo perdido).

    - Trabajo en la oficina (planeación y logística):

        Utilidad fija por hora: $1,000 (siempre se avanza en tareas críticas).

    -Tiempo disponible:

        Total: 8 horas.

Recursos o restricciones: ¿Hay límites de tiempo, capacidad, dinero o credibilidad?

    Tiempo:

        Total: 8 horas.

        Límites por actividad:

            Reuniones con clientes: Mínimo 1 hora, máximo 4 horas.

            Reuniones con el equipo: Mínimo 1 hora, máximo 3 horas.

            Trabajo en la oficina: Mínimo 1 hora, máximo 4 horas.

    Capacidad:

        El CEO no puede realizar más de una actividad a la vez.

Posibles heurísticas: ¿Si no puedo modelarlo todo con precisión, qué reglas aproximadas (basadas en experiencia o datos parciales) puedo usar?

    Regla del "60-30-10":

    Dedicar 60% del tiempo a la actividad con mayor utilidad esperada.

    Dedicar 30% del tiempo a la actividad con utilidad media.

    Dedicar 10% del tiempo a la actividad con menor utilidad.


