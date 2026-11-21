# Caso 5: Puntada y la máquina compartida — Parte 2

## 1. Análisis del muestreo del trabajo

Se observaron 120 instantes por persona. Los porcentajes se obtienen dividiendo cada frecuencia entre 120.

| Persona / etapa | Trabajo | Espera de material | Consulta de información |
|---|---:|---:|---:|
| Elena (P) | 68 (56.67%) | 28 (23.33%) | 24 (20.00%) |
| Inés (S) | 94 (78.33%) | 8 (6.67%) | 18 (15.00%) |
| Hugo (F) | 47 (39.17%) | 49 (40.83%) | 24 (20.00%) |

**Interpretación.** Inés presenta la mayor proporción de trabajo observado (78.33%). Hugo concentra la mayor espera de material (40.83%), mientras que Elena también muestra una espera relevante (23.33%). Las consultas de información representan entre 15% y 20% en los tres puestos. Conviene investigar abastecimiento, ubicación y oportunidad de entrega de materiales, especialmente en F y P, y simplificar el acceso a instrucciones. El muestreo describe la distribución de instantes observados; por sí solo no demuestra causas ni justifica reducir tiempos estándar.

## 2. Revisión antropométrica y ergonómica

El asiento común mide 45 cm. La altura estimada del codo sobre el piso es asiento + codo sobre asiento:

| Persona | Codo sobre asiento | Codo sobre piso | Plano de manipulación (1–4 cm debajo del codo) |
|---|---:|---:|---:|
| Elena | 24 cm | 69 cm | 65–68 cm |
| Hugo | 28 cm | 73 cm | 69–72 cm |
| Inés | 26 cm | 71 cm | 67–70 cm |

Como referencias individuales, los puntos medios de esos rangos son aproximadamente 66.5 cm para Elena, 70.5 cm para Hugo y 68.5 cm para Inés. Una mesa fija de 70 cm no satisface por igual los tres rangos. Se recomienda una superficie regulable (64–72 cm), ajustada a la persona que ocupa el puesto, manteniendo la tarea de manipulación de papel ligeramente por debajo del codo. Las piezas de uso frecuente deben permanecer dentro del alcance cómodo informado: 36 cm para Elena, 42 cm para Hugo y 39 cm para Inés. Para una configuración común conservadora, ubicar los elementos frecuentes dentro de 36 cm, sin obligar a alcances repetidos al límite.

## 3. Análisis biomecánico con los datos disponibles

Para el objeto hipotético de 0.4 kg se usa el momento simplificado M = m × g × d, con g = 9.81 m/s².

- A 0.35 m: M = 0.4 × 9.81 × 0.35 = **1.3734 N·m**.
- A 0.20 m: M = 0.4 × 9.81 × 0.20 = **0.7848 N·m**.
- Diferencia: **0.5886 N·m**, equivalente a una reducción de **42.86%**.

Acercar el objeto reduce el momento externo estimado. Es un modelo didáctico que no incorpora postura, aceleración, geometría corporal, fuerza muscular ni duración; por tanto, no equivale a una evaluación clínica o ergonómica completa.

## 4. Rediseño propuesto del puesto y del método

1. Ajustar la altura de la mesa dentro del rango regulable para cada operador, buscando el plano de manipulación indicado.
2. Colocar kits, piezas y herramientas de uso frecuente dentro del alcance cómodo; acercar el objeto de 0.35 m a 0.20 m cuando sea viable.
3. Preparar y presentar materiales por pedido, con identificación visual clara, para reducir búsquedas y esperas.
4. Mantener la secuencia del proceso P → S → F y la restricción de una sola máquina de costura.
5. Evaluar la plantilla B para reducir preparación y la guía C para reducir costura; la elección debe basarse en la capacidad total, la inversión y la ventana disponible.

### Esquema de flujo del método

```text
Preparación (P) → Costura (S, máquina compartida) → Acabado (F) → Pedido terminado
```

### Esquema de distribución funcional

```text
[Kits y materiales dentro del alcance]
             ↓
       [P: Preparación]
             ↓
 [S: Costura + máquina única]
             ↓
        [F: Acabado]
             ↓
      [Salida / pedido]
```

## 5. Comparación de alternativas y cronograma

Estándares por pedido: A = P 3 min, S 4 min, F 2 min; B = P 1.5 min, S 4 min, F 2 min; C = P 3 min, S 3 min, F 2 min, más calibración inicial de 9 min que ocupa a la persona S y la máquina. Inversiones: A = 0 UM, B = 90 UM y C = 450 UM.

El cronograma se calcula respetando precedencias y recursos: P procesa pedidos secuencialmente; S inicia cuando el pedido y el recurso S/máquina están disponibles; F inicia cuando termina S y F está libre. La terminación exactamente en el límite de la ventana cuenta como puntual.

| Alternativa | Inversión | Pedidos terminados en 60 min (16 solicitados) | ¿Cumple 16? |
|---|---:|---:|---|
| A — Actual | 0 UM | 13 | No |
| B — Plantilla | 90 UM | 14 | No |
| C — Guía de costura | 450 UM | 16 | Sí |

Con las hipótesis del modelo, C es la única alternativa que alcanza la demanda de 16 pedidos en 60 minutos. Para 14 pedidos y una ventana de 55 minutos, C termina los 14 pedidos a los 53 minutos, por lo que cumple ese escenario.

## 6. Pruebas de conciliación de la herramienta

| Prueba | Resultado esperado / regla | Resultado del modelo |
|---|---|---|
| A, 1 pedido, H = 9 min | La igualdad con H cuenta como puntual | Termina en 9 min; 1 puntual |
| A, 2 pedidos, H = 12 min | El primer pedido termina en 9; el segundo después de H | 1 puntual; el segundo termina en 13 min |
| C, 2 pedidos, H = 17 min | El segundo pedido termina exactamente en H | 2 puntuales; último termina en 17 min |
| C, 16 pedidos, H = 60 min | Verificar capacidad objetivo | 16 puntuales; último termina en 59 min |
| A, 16 pedidos, H = 60 min | Comparar contra capacidad actual | 13 puntuales |

## 7. Recomendación

Si el objetivo prioritario es cumplir 16 pedidos dentro de 60 minutos y se acepta una inversión de 450 UM, recomendar la alternativa C, acompañada de la calibración inicial prevista y de las mejoras ergonómicas y de abastecimiento descritas. Si la inversión es una restricción, B mejora la capacidad frente a A, pero no alcanza por sí sola la demanda indicada. No debe contabilizarse el tiempo libre como ahorro salarial: el beneficio monetario adicional informado para un accesorio terminado frente a A es 7 UM por sesión, durante 30 sesiones iguales; cualquier evaluación económica debe mantener ese criterio y comparar el beneficio incremental con la inversión.

## 8. Supuestos y límites

- Se supone ritmo de 100% y suplemento de 20% para el cálculo de tiempo estándar, según el caso.
- Las asignaciones por etapa son fijas. Las combinaciones válidas son P=Elena/S=Inés/F=Hugo o P=Hugo/S=Elena/F=Inés.
- Una sola máquina de costura está disponible; la calibración de C ocupa máquina y persona S durante 9 minutos.
- El muestreo sintético no identifica causalidad.
- El análisis biomecánico utiliza únicamente masa y distancia proporcionadas y es una aproximación simplificada.
- La simulación no contempla averías, retrabajos, variación de tiempos, pausas adicionales ni reasignación dinámica.
