Pre entrega: 26 de mayo 
Entrega final: 7 de junio
# Dashboard
### 1_Panorama general
a) Cantidad de Ciudades en las que Opera:
    - Utilizaremos el archivo de geolocalización de ciudades para contar las ciudades únicas en las que la empresa opera.
        1. Cargar el archivo `locations.SQL`.
        2. Identificar las ciudades únicas.
        3. Contar el número total de ciudades.
b) Cantidad de Distribuidores:
   - Extraeremos esta información de la lista de distribuidores.
        1. Acceder al archivo de distribuidores.
        2. Contar la cantidad de registros.
c) Total de Transacciones Realizadas:
    - Sumaremos las transacciones del registro de transacciones.
    - Pasos:
        1. Cargar el archivo `transactions.csv`.
        2. Calcular la suma de la columna “transactions”.
d) Total de Ganancia Bruta
    - Calcularemos la suma de las ganancias brutas de todas las transacciones.
        1. Utilizar la columna “gross_margin” del archivo `transactions.csv`.
        2. Calcular la suma de las ganancias brutas.
e) **Total de Impuestos a Pagar**
    - Aplicaremos el 3,5 % sobre la ganancia bruta para obtener el monto de impuestos adeudados.
    - Pasos:
        1. Multiplicar la ganancia bruta por 0,035.
## 2_ Discriminados por País:
a) **Mapa de Ganancias Reales**:
     Utilizaremos un mapa de coropletas para visualizar las ganancias reales por país.
        1. Obtener las coordenadas de los países desde el archivo `locations.SQL`.
        2. Calcular la ganancia real (ganancia bruta - impuestos) por país.
        3. Representar las ganancias en el mapa.
b) Cantidad de Transacciones
    - Calcularemos la cantidad de transacciones por país.
        1. Utilizar la columna “transactions” del archivo `transactions.csv`.
        2. Sumar las transacciones por país.
c) Ganancias Reales
    - Sumaremos las ganancias reales por país.
        1. Calcular la ganancia real por país (ganancia bruta - impuestos).
        2. Sumar las ganancias reales.
## 3_ **Ganancia Real por Mes**:
Desglosaremos las ganancias reales por mes.
    - Pasos:
        1. Utilizar la columna “date” del archivo `transactions.csv`.
        2. Agrupar las transacciones por mes.
        3. Calcular la ganancia real mensual.
## 4_**Inversión vs. Ganancias Reales por País**:
 Compararemos las inversiones con las ganancias reales por país.
    - Pasos:
        1. Obtener los datos de inversión por país (desde el reporte en PDF).
        2. Calcular la ganancia real por país.
        3. Comparar ambas métricas.
## 5_Auditoría de Operaciones:

- Evaluaremos si es necesario auditar las operaciones en alguno de los países. La respuesta se fundamentará en los datos analizados.

Recuerda compartir todos los archivos e informes con el instructor. ¡Buena suerte en tu análisis! 📊🔍