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