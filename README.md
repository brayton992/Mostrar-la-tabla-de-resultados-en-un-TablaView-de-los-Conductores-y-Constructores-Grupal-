# Mostrar-la-tabla-de-resultados-en-un-TablaView-de-los-Conductores-y-Constructores-Grupal-
La aplicación se divide en varias pantallas, comenzando con un menú principal que ofrece dos opciones: ver una tabla de resultados o un gráfico de barras con puntos totales.
# Capturas
![Imagen de WhatsApp 2024-07-25 a las 21 56 18_ff959206](https://github.com/user-attachments/assets/190fb33b-db5a-4c1b-9ff5-462c2509aaf7)
![Imagen de WhatsApp 2024-07-25 a las 21 56 18_e28d431c](https://github.com/user-attachments/assets/b31ad1ca-1201-4496-b153-62c8a631ce08)
![Imagen de WhatsApp 2024-07-25 a las 21 56 18_4f2d2f35](https://github.com/user-attachments/assets/5a8cf725-3398-4504-8e7d-02dd24a0a298)


# Componentes principales:

# Menú principal: 
Tiene dos botones, uno para ver una tabla de datos y otro para ver un gráfico de barras. El menú principal se muestra al inicio de la aplicación.

# Selector de año (ComboBox): 
Permite al usuario seleccionar un año específico para ver los resultados. Al seleccionar un año, se actualizan tanto la tabla como el gráfico de barras con los datos correspondientes.

# Vista de tabla (TableView): 
Muestra una lista de constructores con sus nombres, victorias, puntos totales y clasificación. Esta tabla se actualiza dinámicamente según el año seleccionado.

# Gráfico de barras (BarChart): 
Visualiza los puntos totales de los constructores en forma de gráfico de barras. Al igual que la tabla, se actualiza según el año seleccionado.

# Funcionamiento:

# Al seleccionar un año: 
Se consulta un repositorio para obtener los resultados de los constructores para ese año específico.
# Tabla y gráfico:
Estos se actualizan con los datos obtenidos del repositorio.
# Navegación: 
Los botones del menú permiten alternar entre la vista de la tabla y la del gráfico de barras.
# Puntos técnicos:

# TableView:
Se configura con columnas que muestran diferentes atributos de los constructores.
# BarChart:
Se configura con ejes categóricos y numéricos para representar los puntos totales por constructor.
# Actualización de datos:
Un método dedicado updateBarChart se encarga de actualizar el gráfico de barras según los datos seleccionados.
Este código demuestra cómo combinar diferentes componentes de JavaFX para crear una interfaz de usuario interactiva y dinámica, manejando eventos como la selección de año y la actualización de vistas de datos.
