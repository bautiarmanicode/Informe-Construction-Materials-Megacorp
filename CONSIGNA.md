## Contexto

Debemos generar un informe para Construction Materials Megacorp, una empresa
multinacional de materiales de construcción, que comenzó actividades en la región
LATAM (comprendida por Argentina y países limítrofes) en el primer cuatrimestre de este
año.

## Fuentes de datos y documentación recibida

### 1. **Registro de transacciones – transactions.csv**
   ◦ id: id de la transacción – autoincremental
	◦ distributor_id: id del distribuidor
	◦ transactions: cantidad de operaciones
	◦ gross_margin: ganancia del total de las transacciones, luego de restar costos.
	◦ date: fecha del registro
	◦ taxes: impuestos adeudados sobre las ganancias
	◦ No deben existir dos transacciones idénticas con la misma fecha

BORRAR FILAS VACIAS 

### 1. Lista de distribuidores - distributors (Google Sheets)

    ◦ distributor_id: id del distribuidores
	◦ distributor: nombre de la empresa distribuidora
	◦ location_id: id de la ciudad de la distribuidora

### 1. Registro de inversiones por país: perdieron el archivo, pero se obtiene un reporte

en pdf – investments.pdf.
4. Archivo de geolocalización de ciudades – locations.SQL
	◦ id_city: id de la ciudad
	◦ id_country: id del país
	◦ city: nombre de la ciudad
	◦ longitude, latitude: coordenadas

1. Lista de países donde opera – countries.SQL
   ◦ id_country: id del país
   ◦ country: nombre del país
2. Logo de la empresa – CMM_logo.PNG
   Consignas
   Presentar un trabajo de nivel profesional, cuidando calidad de los datos, y la estética del
   diseño:
   • Aplicar la mejor estrategia para tratar los datos faltantes/duplicados.
   • Seleccionar la visualización que muestre de la manera más clara la información
   solicitada.
   Todos los archivos del trabajo (informes en Looker, Google sheets y cualquier otro) deben
   ser compartidos con el instructor con permisos de edición. Los trabajos que no cumplan
   con este requisito serán desaprobados.
   Una vez presentados los resultados, se tendrá un plazo de una semana para mejorar,
   corregir los trabajos desaprobados o que no hayan alcanzado los requisitos.
   Los plazos son inamovibles.
   Parte I: Análisis operaciones en LATAM
   Pre entrega: 26 de mayo
   Entrega final: 7 de junio
   Generar un Dashboard que muestre
3. Un panorama general:
   a) Cantidad de ciudades en las que opera
   b) Cantidad de distribuidores
   c) Total de transacciones realizadas
   d) Total de ganancia bruta
   e) Total de impuestos a pagar (3,5 % sobre la ganancia bruta)
4. Discriminados por país:
   a) Mapa de ganancias reales. ¿Qué tipo de mapa es el más apropiado? ¿Cuál es
   el que muestra la información más claramente? Datos emergentes: País y
   ganancia real. Llamamos ganancia real a la diferencia entre ganancia bruta y
   los impuestos
   b) Cantidad de transacciones
   c) Ganancias reales
5. Ganancia real por mes
6. Inversión vs Ganancias reales por país.
7. ¿Deberíamos auditar las operaciones en alguno de estos países? Fundamentar la
   respuesta
   Todos los derechos son reservados por el Programa Codo a Codo perteneciente a la
   Subsecretaría Agencia de Aprendizaje a lo largo de la vida del Ministerio de Educación del
   Gobierno de la Ciudad Autónoma de Buenos Aires. Se encuentra prohibida su venta o
   comercialización.
