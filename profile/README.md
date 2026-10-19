# Varicela en Colombia

Esta organización forma parte de la tesis **«Análisis espacio-temporal del impacto de la vacunación contra la Varicela en Colombia»**, desarrollada por **Diego Clemente Rojas Chingate** para optar al título de **magíster en Ciencias – Estadística de la Universidad Nacional de Colombia**.

**Estado del proyecto:** Este trabajo se encuentra en desarrollo. Los contenidos y resultados publicados pueden cambiar, y aún faltan análisis y materiales por incorporar.

El proyecto examina las notificaciones de varicela y sus tasas entre **2007 y 2025** a partir de una base que también integra población municipal, cobertura de vacunación y datos climáticos de precipitación, temperatura y humedad.

### Repositorios

- **[data-processing](https://github.com/thesis-varicella-colombia/data-processing)** reúne las fichas de las fuentes y los scripts para descargar, limpiar e integrar los datos de Sivigila (evento 831), población municipal, vacunación y clima. Su producto final es una tabla por entidad territorial y semana epidemiológica que sirve de base para el análisis. El [catálogo de datos](https://github.com/thesis-varicella-colombia/data-processing/blob/main/data/README.md) describe las variables, unidades y productos.
- **[exploratory-analysis](https://github.com/thesis-varicella-colombia/exploratory-analysis)** presenta los datos mediante gráficos de notificaciones y tasas anuales, semanales y por edad, además de un mapa municipal. Incluye los datos necesarios para la visualización y documenta su procedencia en el [README de datos](https://github.com/thesis-varicella-colombia/exploratory-analysis/blob/main/data/README.md).

### Enlaces de interés

- **[Visualización interactiva](https://thesis-varicella-colombia.github.io/exploratory-analysis/):** gráficos y mapa disponibles en el navegador, sin instalar herramientas ni descargar datos.
- [Metodología del conjunto integrado](https://github.com/thesis-varicella-colombia/data-processing/blob/main/data/processed/integration_data/README.md): estructura de la tabla final, variables y criterios de integración.
- [Procesamiento de las notificaciones de Sivigila](https://github.com/thesis-varicella-colombia/data-processing/blob/main/data/processed/sivigila/README.md): agregación de los registros por entidad territorial y semana reportada.
- [Procesamiento de las variables climáticas](https://github.com/thesis-varicella-colombia/data-processing/blob/main/data/processed/climate/README.md): convenciones temporales y métodos de agregación espacial.

### Cómo interpretar los datos

Los conteos representan **registros notificados**, no personas enfermas deduplicadas. Las semanas sin registros en la tabla no deben interpretarse automáticamente como semanas con cero casos. El año **2007** aparece en los datos y en los gráficos para revisar una discrepancia con una cifra oficial, pero se excluye del periodo analítico principal. Los detalles y las limitaciones están documentados en el [README del análisis exploratorio](https://github.com/thesis-varicella-colombia/exploratory-analysis#readme) y en el [catálogo de datos del procesamiento](https://github.com/thesis-varicella-colombia/data-processing/blob/main/data/README.md).
