### Explicación de los Campos

- **Estaciones**: Contiene información sobre la estación de monitoreo.
  - `nombre`: Nombre de la estación.
  - `ubicacion`: Coordenadas de la estación en formato de latitud y longitud.
  - `ciudad`: Nombre de la ciudad donde se encuentra la estación.

- **Fecha**: Fecha y hora de la medición en formato ISO8601 (UTC).

- **Calidad del Aire**: Contaminantes y valores medidos.
  - `PM2.5`, `PM10`, `NO2`, `O3`, etc.: Valores medidos de diferentes contaminantes (en microgramos por metro cúbico).
  - `ICA`: Índice de Calidad del Aire (0-100), donde un valor más alto indica peor calidad del aire.

- **Condiciones Meteorológicas**: Información sobre las condiciones climáticas en el momento de la medición.
  - `temperatura`: Temperatura en grados Celsius.
  - `humedad`: Porcentaje de humedad relativa.
  - `precipitacion`: Cantidad de precipitación en milímetros.
  - `radiacion_uv`: Nivel de radiación ultravioleta.
  - `nivel_CO2`: Concentración de CO2 en partes por millón (ppm).
  - `presion_atmosferica`: Presión atmosférica en hPa.
  - `viento`: Información sobre el viento.
    - `velocidad`: Velocidad del viento en km/h.
    - `direccion`: Dirección del viento.
