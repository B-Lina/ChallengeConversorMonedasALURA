<h1 align="center"> Conversor de Monedas </h1>
<h2> Descripcion del proyecto </h2>
Este proyecto es una aplicación de consola en Java que permite realizar conversiones de divisas en tiempo real. Utiliza la API de **ExchangeRate-API** para obtener las tasas de cambio más actualizadas, procesando los datos mediante la librería **Gson**.
<h2> Funcionalidades</h2>
**Consulta en Tiempo Real:** Conexión directa con la API para obtener tasas exactas.
* **Conversión Dinámica:** El usuario puede ingresar manualmente cualquier código de divisa (ej. USD, ARS, BRL, EUR).
* **Menú Interactivo:** Ciclo de ejecución continuo que permite realizar múltiples consultas sin reiniciar el programa.
* **Validación de Datos:** Manejo de excepciones para códigos de moneda no soportados o errores de conexión.
* **Soporte Multi-moneda:** Capacidad de convertir entre más de 160 divisas distintas soportadas por la API.
