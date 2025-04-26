Descripción del Dataset:

Este conjunto de datos se compone de dos colecciones de señales de latidos cardíacos derivadas de dos conjuntos de datos de clasificación de latidos cardíacos, el conjunto de datos de arritmias MIT-BIH y la base de datos de ECG de diagnóstico PTB. 

📊 MIT - BIH: Massachusetts Institute of Technology - Israel Hospital en Boston. Contiene grabaciones de electrocargiogramas (ECG) de pacientes reales, tomadas en su mayoría en entornos ambulatorios, es decir, en pacientes no hospitalizados, para detectar y estudiar arritmias (anormalidades en el ritmo cardíaco). Cada grabación dura aproximadamente 30 minutos, y cada latido está anotado manualmente por cadiólogos indicando el tipo de latido (normal, fibrilación, bloqueo, etc.)

📊 PTBDB: Son unas bases de datos creadas en Alemania por el Physikalisch-Technische Bundesanstalt. Su foco principal es diagnosticar diferentes enfermedades cardíacas, como infartos, hipertrófias, miocardiopatías, entre otras. Estos conjuntos de datos incluyen variables como la edad de los pacientes, sexo, diagnóstico médico oficial, etc. 

Resumen del dataset:

1. Conjunto de datos de arritmia (MIT-BIH)

🧪 Número de muestras: 109,446

🏷️ Número de clases: 5

'N': 0 → Latido normal

'S': 1 → Latido auricular ectópico

'V': 2 → Latido ventricular ectópico

'F': 3 → Latido de fusión

'Q': 4 → Latidos no clasificados o ruido

🔁 Frecuencia de muestreo: 125 Hz

2. Base de datos de diagnóstico de PTB

🧪 Número de muestras: 14,552

🏷️ Número de clases: 2 (probablemente: normal vs. infarto de miocardio u otra patología)

🔁 Frecuencia de muestreo: 125 Hz

3. Características comunes

🧩 Longitud fija por muestra: 188 puntos

📁 Formato: CSV (una fila = una señal de ECG; el último valor es la etiqueta/clase)

🔍 Exploración de Datos (EDA)

Ver la distribución de clases.

Visualizar algunas señales con matplotlib para ver cómo se ven las diferentes clases.

Verificar el balance/desbalance de clases.