# Mapa Interactivo - Datathon

Este proyecto contiene un mapa interactivo creado en **ArcGIS Online** que visualiza datos relacionados con Turismo sostenible en Medellín. El mapa interactivo permite explorar los diferentes ecoparques con los que cuenta la ciudad así, como puntos de interés, estaciones de transporte publico mas cercanas actividades, etc.

## Archivos de Datos

Los archivos necesarios para crear el mapa interactivo están disponibles en la carpeta `data`. Los archivos están comprimidos en formato `.rar` para facilitar su descarga y distribución. A continuación se describe el contenido de los archivos:

- `csv_atractivos_turisticos.zip`: contiene la información sobre los principales atractivos turisticos con los que cuenta la ciudad en formato .csv
- `geojson_pot48_2014_ciclorrutas.zip`: contiene las rutas de ciclorutas de la ciudad de Medellín en formato geojson
- `gpkg_ecoparques.zip`: contiene los ecoparques de la diudad en formato .gpkg 
- `gpkg_indice_multidimensional_c.zip`: contiene ïnformación sobre el indice de pobreza multidimensional de la ciudad de medellín en formato .gpkg 


## Instrucciones para Reproducir el Mapa

1. **Crea una cuenta en ArcGIS Online** si no tienes una. Puedes hacerlo visitando [ArcGIS Online](https://www.arcgis.com).
   
2. **Descomprime los archivos `.rar`** en la carpeta `data` para acceder a los archivos CSV y GeoJSON que contienen los datos.

3. **Inicia sesión en ArcGIS Online** y crea un nuevo mapa:
   - En el menú principal, selecciona **Crear un Mapa**.
   
4. **Importa los archivos de datos**:
   - Selecciona **Añadir capa desde archivo**.
   - Carga los archivos CSV y GeoJSON que has descomprimido.

5. **Configura las capas**:
   - Personaliza las capas agregando simbología adecuada, etiquetas y configuraciones interactivas.
   - Si es necesario, consulta la documentación oficial de ArcGIS Online para detalles sobre cómo configurar las capas de manera adecuada.

6. **Publica el mapa**:
   - Una vez que el mapa esté configurado, selecciona **Compartir** y decide si deseas hacer el mapa público o compartirlo con un grupo específico.

## Enlace al Mapa Interactivo

1. **inicia sesión en ArcGIS Online** (https://www.arcgis.com).

2. **Abrir el mapa creado** 
  - Una vez que las capas han sido agregadas al mapa junto con la simbologia y etiquetas adecuadas se procede a realizar el mapa interactivo.

3. **Hacer clic en create app** 
  - En la esquina inferior izquierda hacer clic en la opción create app y seleccionar la opcion *Instant Apps*

4. **Seleccionar plantilla o crear nueva plantilla**
  - Una vez en Instant Apps puede darle forma al mapa interactivo eligiendo una plantilla predeterminada o creando una nueva desde la interfaz que Instant Apps.

5. **Publicar mapa interactivo**
  - Cuando el mapa interactivo esté terminado se procede a dar clic en la opción guardar y publicar ubicados en la esquina inferior izquierda, una vez publicado se genera un enlace mediante el cual se puede visualizar el mapa.


## Notas

- Los archivos de datos están protegidos por [indicar tipo de licencia, si aplica].
- Si tienes alguna duda sobre cómo trabajar con ArcGIS Online, te recomendamos consultar la [documentación oficial de ArcGIS Online](https://www.esri.com/en-us/arcgis/products/arcgis-online/overview).

## Licencia

Este proyecto utiliza **ArcGIS Pro Online** bajo una licencia temporal proporcionada exclusivamente para la competición. Los datos y archivos de configuración pueden ser replicados usando cualquier otra herramienta compatible con archivos GIS, pero el uso de ArcGIS Pro Online fuera del entorno de la competición requiere una licencia válida de Esri.
