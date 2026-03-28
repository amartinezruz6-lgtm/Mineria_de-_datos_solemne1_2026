# Solemne 1: Minería de Datos 2026 📈
Este proyecto realiza un analisis sobre la evolucion temporal del valor del dolar en chile y las acciones del banco central,
asi como intenta encontrar alguna correlacion entre ambas variables.

Se elige el data set pypi.org/project/yfinance para analizar esas variables.

Hipotesis tentativa: El valor de la accion del banco de chile tiende a bajar cuando hay cambios bruscos en el precio del dolar, debido a la incertidumbre

Preguntas analiticas:
P1 = Note que en diciembre del 2025, el BCH vario mucho mas que en enero del mismo año. ¿como cambia el valor de CLP=X (dolar) en ese periodo? ¿Habra una correlacion entre ambas variables?
P2 = ¿Habra una correlacion entre las ventas de las acciones de BCH (columna volumen) y el precio del dolar?

Hallazgos:

Se observa una correlacion negativa entre las variables de -0.6645622116481087

En la evolucion temporal: PARA EL PRECIO DEL DOLAR: SE OBSERA VARIABILIDAD, PERO TENDENCIA A LA BAJA, PERO EN BCH, SE OBSERVA MAS ESTABILIDAD, PERO TENDENCIA LA ALTA

SE OBSERVA QUE DURANTE EL AÑO COMPLETO NO SUCEDIO SIEMPRE LO ESPERADO EN LA HIPOSIS INICIAL. PERO SI EN MUCHOS INTERVALOS. SE NOTA LO SIGUIENTE:
DE ENERO A MARZO DE OBSERA CAIDA EN GENERAL EN EL DOLAR Y SUBIDA EN BCH. SIN EMBARGO, ENTRE ABRIL Y MAYO, 
AUMENTARON CONJUNTAMENTE, CONTRADICIENDO LA HIPOTESIS, ASI COMMO EN E INTERVALO DE AGOSTO A SEPTIEMBRE, QUE TAMBIEN SE 
OBSERVA ESO EN ALGUNOS MOMENTOS. LUEGO,ENTRE NOVIEMBRE Y DICIEMBRE, SE VE CLARAMENTE QUE SE CUMPLE QUE EL PRECIO DEL DOLAR 
BAJA Y LAS ACCIONES DE BCH AUMENTAN. EN OTROS, SE NOTA QUE, CUANDO EL DOLAR AUMENTA, LAS ACCIONES CAEN (JULIO-AGOSTO), 
CUMPLIENDOSE LA HIPOTESIS, PERO EN EL OTRO SENTIDO.


Para ejecutar el notebook, instala las dependencias usando:
```bash
pip install -r requirements.txt